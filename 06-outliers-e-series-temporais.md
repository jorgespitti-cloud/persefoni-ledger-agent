---
title: Outliers e Séries Temporais
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Outliers e Séries Temporais

A análise deverá identificar variações relevantes, valores potencialmente atípicos, mudanças persistentes de comportamento e alterações de perfil nos dados de Escopo 1 e Escopo 2.

Um outlier deverá ser tratado como apontamento para investigação, e não como erro confirmado.

## Formação das Séries Comparáveis

Sempre que possível, a análise histórica deverá utilizar a combinação de:

- Entity;
- Location;
- Facility;
- fonte ou atividade;
- combustível ou recurso;
- unidade de medida;
- Internal Identifier.

Não deverão ser combinados em uma mesma série:

- unidades diferentes;
- fontes diferentes;
- combustíveis diferentes;
- unidades de medida diferentes;
- registros Location-Based e Market-Based como se fossem observações independentes de consumo;
- períodos com durações incompatíveis sem ajuste documentado.

## Comparações Obrigatórias

Para cada série comparável, o agente deverá confrontar o valor atual com:

1. o mês imediatamente anterior;
2. a mediana dos últimos 6 meses válidos;
3. a mediana dos últimos 12 meses válidos;
4. o mesmo mês do ano anterior, quando disponível;
5. a faixa histórica informada na Ficha Técnica, quando disponível;
6. os limites calculados pelos métodos IQR e MAD, quando houver histórico suficiente.

O agente deverá informar quando o histórico disponível for insuficiente para análise estatística confiável.

## Variação Percentual

A variação percentual deverá ser calculada por:

Variação percentual =

(Valor atual - Valor de referência) / Valor de referência x 100

Para fontes de comportamento regular, utilizar como critério inicial:

- variação acima de 30%: observar;
- variação acima de 50%: solicitar esclarecimento;
- variação acima de 100%: prioridade alta.

Os limites são critérios de triagem e não representam confirmação de erro.

Não calcular variação percentual quando o valor de referência for igual a zero.

## Método IQR

Quando houver, preferencialmente, pelo menos 8 observações comparáveis, calcular:

IQR = Q3 - Q1

Limite inferior = Q1 - 1,5 x IQR

Limite superior = Q3 + 1,5 x IQR

Classificar:

- fora de 1,5 x IQR: possível outlier;
- fora de 3 x IQR: anomalia forte.

O método não deverá ser aplicado quando o histórico for insuficiente ou quando os dados não forem comparáveis.

## Método MAD

Calcular:

MAD = mediana dos desvios absolutos em relação à mediana histórica.

Quando MAD for diferente de zero, calcular:

Modified Z-score =

0,6745 x (Valor atual - Mediana histórica) / MAD

Classificar:

- valor absoluto acima de 3,5: possível outlier;
- valor absoluto acima de 5,0: anomalia forte.

Quando MAD for igual a zero, não realizar divisão. Utilizar diferença absoluta, variação percentual e análise do padrão constante.

## Sazonalidade

Quando houver mais de um ano disponível, o agente deverá comparar o valor atual com:

- o mesmo mês do ano anterior;
- o comportamento histórico do mesmo período;
- períodos com nível operacional semelhante.

Uma variação compatível com o comportamento sazonal não deverá ser classificada automaticamente como anomalia.

## Mudança Persistente de Patamar

O agente deverá procurar alterações persistentes, mesmo quando nenhum valor isolado seja extremo.

Deverão ser sinalizados:

- três ou mais meses consecutivos acima ou abaixo do padrão anterior;
- alteração persistente superior a 20% ou 30%;
- início de uma nova fonte;
- desaparecimento de uma fonte histórica;
- mudança simultânea de consumo, unidade de medida, instalação ou identificador;
- valor constante repetido por vários períodos quando o comportamento histórico era variável.

## Fontes Intermitentes

Para fontes condicionadas à ocorrência, como:

- geradores de emergência;
- recarga de fluidos refrigerantes;
- agentes extintores;
- fornecimento por caminhão-pipa;
- destinação eventual de resíduos;
- outras atividades por ocorrência;

não deverá ser utilizada apenas a variação percentual mensal.

A análise deverá considerar:

- existência da ocorrência;
- quantidade por ocorrência;
- evidência disponível;
- capacidade do equipamento ou sistema;
- comparação com ocorrências anteriores;
- periodicidade indicada na Ficha Técnica;
- justificativa apresentada.

A ausência de ocorrência não deverá ser classificada automaticamente como lacuna ou outlier.

## Alterações de Ordem de Grandeza

O agente deverá verificar se uma variação pode ter sido causada por:

- troca entre kWh e MWh;
- troca entre litros e metros cúbicos;
- mudança de quilogramas para toneladas;
- erro de separador decimal;
- inclusão indevida de casas decimais;
- soma acumulada de períodos;
- faturamento acumulado;
- alteração do período de leitura;
- mudança no critério de rateio.

## Perguntas para Esclarecimento

Para cada variação relevante, o agente deverá formular pergunta objetiva contendo:

- unidade;
- período;
- fonte;
- valor atual;
- referência histórica;
- variação identificada;
- método que gerou o apontamento;
- possíveis causas a confirmar.

Exemplo:

> O consumo de eletricidade de setembro foi de 18.500 kWh, aproximadamente 83% acima da mediana dos seis meses anteriores, de 10.075 kWh. Houve aumento de atividade, inclusão de nova instalação, alteração no período de leitura ou faturamento acumulado?

As possíveis causas deverão ser apresentadas como hipóteses, nunca como conclusões.

## Limites de Atuação

O agente não deverá:

- alterar valores;
- excluir registros;
- substituir valores atípicos pela média ou mediana;
- considerar automaticamente um outlier como erro;
- criar justificativas;
- simular dados históricos;
- aprovar ou rejeitar o dado.

A decisão sobre aceitação, correção, justificativa ou tratamento permanecerá sob responsabilidade do Data Analyst.

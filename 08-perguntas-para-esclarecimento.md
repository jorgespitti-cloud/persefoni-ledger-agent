---
title: Perguntas para Esclarecimento
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Perguntas para Esclarecimento

Para cada lacuna, inconsistência, possível duplicidade, alteração cadastral, variação relevante ou potencial outlier, o agente deverá formular uma pergunta objetiva para apoiar a análise humana.

A pergunta deverá apresentar o contexto necessário para que o Data Analyst ou Data Collector consiga investigar o apontamento sem precisar reconstruir toda a análise.

# Conteúdo Obrigatório da Pergunta

Sempre que as informações estiverem disponíveis, a pergunta deverá indicar:

- unidade;
- período;
- template;
- fonte ou atividade;
- combustível ou recurso;
- valor atual;
- unidade de medida;
- valor ou referência histórica;
- variação identificada;
- método ou regra que gerou o apontamento;
- possíveis causas a confirmar.

# Formulação das Perguntas

O agente não deverá formular perguntas genéricas como:

> Por que o consumo aumentou?

A pergunta deverá informar os valores comparados e o motivo do apontamento.

Exemplo:

> O consumo de eletricidade de setembro foi de 18.500 kWh, aproximadamente 83% acima da mediana dos seis meses anteriores, de 10.075 kWh. Houve aumento de atividade, inclusão de nova instalação, alteração no período de leitura ou faturamento acumulado?

# Perguntas sobre Aumento de Consumo

Quando houver aumento relevante, considerar como hipóteses:

- aumento do nível de atividade;
- inclusão de nova área, instalação ou unidade consumidora;
- instalação de novo equipamento;
- aumento de dias ou horas de operação;
- abastecimento de tanque ou formação de estoque;
- faturamento acumulado;
- alteração do período de leitura;
- mudança no critério de rateio;
- mudança de unidade de medida;
- possível duplicidade;
- correção de valor anteriormente estimado.

Exemplo:

> O consumo de diesel de agosto foi de 3.600 L, aproximadamente três vezes a mediana dos seis meses anteriores, de 1.180 L. Houve utilização excepcional do gerador, abastecimento do tanque para estoque, inclusão de outra fonte ou faturamento acumulado?

# Perguntas sobre Redução de Consumo

Quando houver redução relevante, considerar como hipóteses:

- redução do nível de atividade;
- paralisação temporária;
- retirada ou manutenção de equipamento;
- redução de frota;
- mudança de combustível;
- mudança de fornecedor;
- ausência parcial de registros;
- alteração do período de leitura;
- transferência de consumo para outra unidade;
- correção de duplicidade anterior.

Exemplo:

> O consumo de gasolina de julho foi de 230 L, aproximadamente 84% abaixo da mediana histórica de 1.410 L. Houve redução da frota, paralisação de veículos, utilização de etanol ou ausência parcial de dados do fornecedor?

# Perguntas sobre Fontes Ausentes

Quando uma fonte historicamente reportada estiver ausente, perguntar se:

- a fonte deixou de existir;
- a fonte não foi utilizada no período;
- o dado ainda não foi recebido;
- houve mudança de categoria;
- houve alteração de combustível;
- o consumo passou a ser reportado por outra unidade;
- a fonte foi incluída em outro template;
- a ausência decorre de erro de consolidação.

Exemplo:

> O ledger apresenta consumo mensal de diesel do gerador entre janeiro e agosto, mas não há registro no template de setembro. O gerador deixou de existir, não foi utilizado no período ou o dado ainda não foi disponibilizado?

# Perguntas sobre Unidade de Medida

Quando houver mudança de unidade de medida, perguntar se:

- houve alteração na forma de faturamento;
- o fornecedor passou a apresentar outra unidade;
- ocorreu conversão documentada;
- o valor foi convertido corretamente;
- houve troca indevida de kWh por MWh;
- houve troca indevida de litros por metros cúbicos;
- o dado original e o convertido coexistem.

Exemplo:

> O consumo histórico de eletricidade era informado em kWh, mas o template atual apresenta MWh. A mudança decorre da forma de faturamento ou de conversão documentada? O valor informado já foi convertido corretamente?

# Perguntas sobre Escopo 2

Quando houver diferença entre Location-Based e Market-Based, perguntar sobre:

- diferença de período;
- diferença de unidade;
- ausência de registro;
- diferença de consolidação;
- instrumento contratual;
- crédito ou certificado;
- possível erro de preenchimento.

Exemplo:

> O template Location-Based apresenta 12.500 kWh e o Market-Based apresenta 9.800 kWh para a mesma unidade e período. Existe diferença de período, unidade, consolidação ou registro ausente?

Quando houver tratamento renovável:

> O template Market-Based utiliza tratamento associado à eletricidade renovável. Existe contrato, certificado, declaração do fornecedor ou aprovação corporativa que cubra a unidade e o período reportado?

# Perguntas sobre Possíveis Duplicidades

Quando forem encontrados registros semelhantes, a pergunta deverá apresentar as linhas comparadas e as diferenças identificadas.

Exemplo:

> Foram identificados dois registros de gasolina para a mesma unidade e período, ambos com 1.250 L, mas com pequenas diferenças na descrição da Facility. Os registros representam abastecimentos distintos ou possível repetição do mesmo dado?

# Perguntas sobre Estimativas

Quando o registro estiver identificado como estimado ou provisório, perguntar:

- qual critério foi utilizado;
- qual período serviu como referência;
- se houve aprovação do Data Manager;
- se o dado real já está disponível;
- se o valor provisório deve ser substituído.

Exemplo:

> O consumo de eletricidade de agosto permanece identificado como estimado com base na média histórica. O dado real já foi recebido? Caso positivo, o registro provisório deverá ser substituído antes do upload?

# Linguagem das Perguntas

As perguntas deverão:

- ser objetivas;
- apresentar os valores relevantes;
- indicar o período;
- evitar acusação de erro;
- apresentar hipóteses como possibilidades;
- permitir resposta verificável;
- evitar conclusões antecipadas;
- indicar quando uma evidência adicional é necessária.

As expressões recomendadas são:

- “Houve...?”
- “A diferença decorre de...?”
- “Existe evidência de...?”
- “O valor representa...?”
- “A fonte deixou de existir ou não houve ocorrência no período?”
- “O dado real já está disponível?”
- “Os registros representam ocorrências distintas?”

# Destinatário Sugerido

Cada pergunta deverá indicar o destinatário sugerido:

- Data Collector: esclarecimentos sobre consolidação e tratamento dos dados;
- Data Provider: informações operacionais e evidências da unidade;
- Data Analyst: revisão da classificação e dos cálculos;
- Data Manager: decisões metodológicas, exceções ou fatores de emissão.

# Prioridade

As perguntas deverão ser classificadas como:

- Crítica;
- Alta;
- Média;
- Baixa;
- Informativa.

A prioridade deverá seguir as regras estabelecidas no arquivo de classificação de criticidade.

# Formato da Saída

Apresentar as perguntas em estrutura contendo:

- ID do apontamento;
- prioridade;
- unidade;
- período;
- template;
- fonte;
- variação ou inconsistência identificada;
- pergunta sugerida;
- destinatário sugerido;
- evidência adicional requerida, quando aplicável.

# Limites de Atuação

O agente não deverá:

- responder à própria pergunta sem evidência;
- assumir que a hipótese apresentada é verdadeira;
- considerar a variação como erro confirmado;
- inventar justificativas;
- encerrar apontamentos sem avaliação humana;
- atribuir responsabilidade individual pela inconsistência.

As respostas deverão ser avaliadas pelo Data Analyst antes da aceitação, correção ou escalonamento do dado.

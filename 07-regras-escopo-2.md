---
title: Regras Específicas de Escopo 2
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Regras Específicas de Escopo 2

A análise de Escopo 2 deverá comparar os templates:

- Scope 2 - Purchased Electricity - Facility - Location-Based;
- Scope 2 - Purchased Electricity - Facility - Market-Based.

Para todas as atividades aplicáveis de Escopo 2, deverão existir registros nos dois métodos, conforme a orientação corporativa vigente.

# Correspondência entre os Templates

Para cada unidade e período, o agente deverá verificar:

- presença da unidade nos dois templates;
- correspondência entre Entity;
- correspondência entre Location;
- correspondência entre Facility;
- igualdade dos períodos de referência;
- igualdade da quantidade física de eletricidade;
- igualdade ou compatibilidade da unidade de medida;
- preenchimento dos campos obrigatórios;
- utilização do Emission Factor Set correspondente a cada método;
- existência de comentários sobre estimativas, valores provisórios ou exceções.

# Quantidade Física de Eletricidade

A quantidade física de eletricidade deverá, em princípio, ser equivalente nos templates Location-Based e Market-Based quando ambos representarem o mesmo consumo da unidade e do período.

Diferenças de quantidade deverão ser apresentadas como apontamentos para avaliação.

Para cada diferença, o agente deverá informar:

- unidade;
- período;
- quantidade Location-Based;
- quantidade Market-Based;
- unidade de medida;
- diferença absoluta;
- diferença percentual;
- possível causa a confirmar.

O agente não deverá corrigir ou igualar os valores automaticamente.

# Unidades de Medida

O agente deverá verificar possíveis diferenças entre:

- kWh;
- MWh;
- outras unidades disponíveis no template.

Quando houver diferença de unidade, o agente deverá verificar se os valores são equivalentes após conversão.

Referência:

- 1 MWh = 1.000 kWh.

Uma diferença de unidade não deverá ser tratada automaticamente como diferença de consumo.

# Emission Factor Sets

O agente deverá verificar se o Emission Factor Set é compatível com:

- o método Location-Based;
- o método Market-Based;
- o país ou região da atividade;
- o período de reporte;
- a orientação corporativa vigente.

Para operações no Brasil, a referência deverá seguir o guia corporativo vigente disponibilizado na análise.

O agente não deverá selecionar ou substituir fatores de emissão autonomamente.

# Market-Based

A existência das seguintes condições não deverá resultar automaticamente em fator de emissão igual a zero ou tratamento renovável:

- Mercado Livre de Energia;
- geração distribuída;
- créditos de energia;
- autoconsumo remoto;
- geração compartilhada;
- contrato de energia renovável;
- I-REC ou outro certificado;
- declaração do fornecedor.

O agente deverá verificar se existe indicação de:

- instrumento contratual;
- certificado;
- declaração do fornecedor;
- período coberto;
- aprovação do Group Sustainability;
- comentário ou justificativa correspondente.

A validade ou elegibilidade final do instrumento permanecerá sob responsabilidade do Data Manager e do Group Sustainability.

# Ausência de Instrumento Renovável

A ausência de instrumento renovável aprovado não elimina a necessidade de preenchimento do template Market-Based.

O agente deverá sinalizar:

- unidade presente somente no Location-Based;
- unidade presente somente no Market-Based;
- Market-Based ausente;
- Market-Based com quantidade diferente sem justificativa;
- tratamento renovável sem documentação ou comentário correspondente.

# Possíveis Duplicidades

Registros equivalentes nos templates Location-Based e Market-Based não deverão ser classificados como duplicidades, pois representam dois métodos de contabilização do mesmo consumo físico.

A confirmação de duplicidade deverá considerar registros repetidos dentro do mesmo template, método, unidade e período.

# Perguntas para Esclarecimento

Quando houver diferença entre os métodos, o agente deverá formular pergunta contextualizada.

Exemplo:

> Para a unidade informada, o template Location-Based apresenta 12.500 kWh e o Market-Based apresenta 9.800 kWh no mesmo período. Existe consumo parcialmente coberto por instrumento contratual, diferença de unidade, registro ausente ou erro de consolidação?

Quando houver tratamento renovável:

> O template Market-Based utiliza tratamento associado à eletricidade renovável. Existe contrato, certificado ou declaração aprovada que cubra a unidade e o período reportado?

# Classificação dos Apontamentos

Classificar como crítico:

- ausência de um dos templates obrigatórios;
- quantidade física significativamente diferente entre os métodos;
- possível troca entre kWh e MWh;
- unidade presente em apenas um método sem justificativa.

Classificar como alto:

- Emission Factor Set aparentemente incompatível;
- tratamento renovável sem indicação documental;
- períodos diferentes entre os métodos;
- alteração de fator sem justificativa aparente.

Classificar como médio:

- pequena diferença quantitativa;
- divergência de nomenclatura;
- comentário insuficiente;
- alteração contratual que requer confirmação.

# Limites de Atuação

O agente não deverá:

- escolher o Emission Factor Set;
- decidir sobre elegibilidade de certificados;
- aprovar tratamento renovável;
- corrigir quantidades;
- excluir registros;
- considerar Location-Based e Market-Based como duplicidade;
- presumir que Mercado Livre de Energia representa energia renovável;
- realizar upload.

Os apontamentos deverão ser avaliados pelo Data Analyst e, quando aplicável, pelo Data Manager ou Group Sustainability.

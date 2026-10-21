---
title: Formato do Relatório de Verificação
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Formato do Relatório de Verificação

O agente deverá apresentar os resultados da análise em cinco seções, mantendo linguagem objetiva e diferenciando constatações, possíveis inconsistências, hipóteses e recomendações.

# 1. Resumo Executivo

O resumo deverá apresentar:

- arquivos analisados;
- arquivos ausentes;
- período do ledger;
- período dos templates;
- quantidade de unidades identificadas;
- quantidade de registros por template;
- limitações da análise;
- quantidade de apontamentos por criticidade;
- avaliação geral da prontidão para upload.

A conclusão deverá utilizar uma das seguintes classificações:

- Pronto para upload;
- Pronto para upload com ressalvas;
- Requer correções antes do upload;
- Análise inconclusiva por insuficiência de arquivos ou informações.

A conclusão não representa aprovação formal dos dados.

# 2. Matriz de Completude

A matriz deverá ser apresentada por unidade, fonte e período.

Sempre que possível, deverá conter:

- Entity;
- Location;
- Facility;
- período;
- template;
- fonte ou atividade;
- registro esperado;
- registro encontrado;
- evidência ou comentário identificado;
- status de completude.

Utilizar os seguintes status:

- Completo;
- Completo com justificativa;
- Não aplicável à unidade;
- Não aplicável ao período;
- Pendente;
- Não avaliado por ausência de informação.

Quando a Ficha Técnica estiver disponível, ela deverá ser utilizada para definir as fontes esperadas.

Quando a Ficha Técnica não estiver disponível, a completude deverá ser avaliada principalmente pelo histórico do ledger e pela Matriz de Unidades Reportáveis.

# 3. Relatório Detalhado de Apontamentos

Cada apontamento deverá apresentar:

- ID do apontamento;
- criticidade;
- tipo de conclusão;
- unidade;
- período;
- template;
- fonte ou atividade;
- tipo de teste aplicado;
- descrição do apontamento;
- valor atual;
- valor ou referência de comparação;
- diferença absoluta;
- diferença percentual, quando aplicável;
- evidência encontrada nos arquivos;
- possível risco;
- recomendação de verificação ou tratamento.

O tipo de conclusão deverá ser identificado como:

- constatação objetiva;
- possível inconsistência;
- hipótese para investigação;
- recomendação.

Os apontamentos deverão ser ordenados por:

1. criticidade;
2. unidade;
3. período;
4. template;
5. fonte.

# 4. Perguntas para Esclarecimento

As perguntas deverão ser apresentadas em lista ou tabela contendo:

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

Os destinatários poderão ser:

- Data Provider;
- Data Collector;
- Data Analyst;
- Data Manager.

As perguntas deverão seguir as regras definidas no arquivo:

`08-perguntas-para-esclarecimento.md`

# 5. Mudanças Históricas Identificadas

O agente deverá relacionar as mudanças encontradas durante a comparação temporal.

Sempre que aplicável, deverão ser apresentados:

- entrada de nova unidade;
- encerramento ou ausência de unidade histórica;
- inclusão de nova fonte;
- desaparecimento de fonte;
- mudança de combustível;
- mudança de unidade de medida;
- mudança de Entity;
- mudança de Location;
- mudança de Facility;
- mudança de Facility Internal ID;
- mudança de Internal Identifier;
- mudança de Emission Factor Set;
- mudança de fornecedor ou contrato;
- mudança persistente de patamar;
- estimativa ainda não substituída;
- outra alteração relevante.

Para cada mudança, informar:

- unidade;
- período inicial;
- período da alteração;
- condição anterior;
- condição atual;
- possível impacto;
- necessidade de confirmação.

# Apresentação dos Resultados

O relatório deverá:

- utilizar títulos claros;
- apresentar os valores com suas unidades de medida;
- identificar os períodos comparados;
- evitar conclusões sem evidência;
- evitar repetição do mesmo apontamento em várias seções;
- relacionar cada pergunta ao respectivo ID do apontamento;
- informar quando uma análise não puder ser concluída;
- registrar as limitações dos arquivos fornecidos.

# Prontidão para Upload

Utilizar:

## Pronto para upload

Quando não houver apontamentos críticos ou altos pendentes e os dados estiverem completos para o escopo analisado.

## Pronto para upload com ressalvas

Quando houver apenas apontamentos médios, baixos ou informativos que não impeçam tecnicamente o upload, sujeitos à avaliação do Data Analyst.

## Requer correções antes do upload

Quando houver apontamentos críticos, altos ou lacunas que possam comprometer a completude, a consistência ou a confiabilidade dos dados.

## Análise inconclusiva

Quando os arquivos ou informações fornecidos não forem suficientes para avaliar adequadamente a prontidão para upload.

# Limites da Conclusão

O agente não deverá:

- aprovar formalmente os dados;
- declarar conformidade legal;
- substituir a decisão do Data Analyst;
- substituir a aprovação do Data Manager;
- realizar upload;
- alterar os arquivos analisados;
- declarar um dado incorreto sem evidência suficiente.

A avaliação de prontidão constitui recomendação técnica complementar e deverá ser confirmada pelo Data Analyst.

---
title: Arquivos e Campos da Análise
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Arquivos Obrigatórios

Antes de iniciar a análise, o agente deverá solicitar:

1. ledger atualizado da Persefoni;
2. Scope 1 - Mobile Combustion;
3. Scope 1 - Stationary Combustion - Facility;
4. Scope 1 - Stationary Combustion;
5. Scope 2 - Purchased Electricity - Facility - Location-Based;
6. Scope 2 - Purchased Electricity - Facility - Market-Based.

# Arquivos Recomendados

Quando disponíveis, também deverão ser fornecidos:

- Ficha Técnica das Unidades;
- Matriz de Unidades Reportáveis;
- relação de estimativas e exceções;
- relação de valores provisórios;
- guia corporativo vigente da Persefoni.

# Verificação Inicial

Antes da análise, o agente deverá informar:

- arquivos recebidos;
- arquivos ausentes;
- período abrangido pelo ledger;
- período dos templates;
- quantidade de registros em cada arquivo;
- quantidade de unidades identificadas;
- limitações causadas pela ausência de dados ou arquivos.

O agente não deverá presumir ou completar informações ausentes.

# Campos Principais

Sempre que estiverem disponíveis, deverão ser utilizados:

- Entity;
- Location;
- Facility;
- Facility Internal ID;
- Activity Start Date;
- Activity End Date;
- template;
- fonte ou atividade;
- combustível;
- quantidade;
- unidade de medida;
- Internal Identifier;
- Emission Factor Set;
- Comments.

# Chave Analítica

Sempre que possível, os registros deverão ser comparados pela combinação:

- Entity;
- Location;
- Facility;
- período de referência;
- template;
- fonte ou atividade;
- combustível ou recurso;
- unidade de medida;
- Internal Identifier.

O agente não deverá identificar duplicidades somente com base na igualdade do valor numérico.

# Ausência de Arquivos

Se algum arquivo obrigatório estiver ausente, o agente deverá:

1. identificar o arquivo ausente;
2. explicar quais análises serão prejudicadas;
3. realizar somente as verificações possíveis;
4. não simular o conteúdo ausente.

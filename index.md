---
layout: default
title: Verificação Persefoni
---

# Verificação Complementar de Ledger e Templates Persefoni

Esta biblioteca contém a metodologia vigente para verificação complementar dos templates de Escopo 1 e Escopo 2 antes do upload na Persefoni.

## Finalidade

A metodologia orienta a análise complementar de:

- completude temporal e por unidade;
- consistência cadastral e quantitativa;
- possíveis duplicidades;
- alterações históricas;
- variações relevantes e potenciais outliers;
- correspondência entre Location-Based e Market-Based;
- perguntas para esclarecimento;
- classificação dos apontamentos;
- prontidão dos templates para upload.

## Documentos Metodológicos

1. [Governança e Limites](01-governanca-e-limites.html)
2. [Arquivos e Campos](02-arquivos-e-campos.html)
3. [Regras de Completude](03-completude.html)
4. [Regras de Consistência](04-consistencia.html)
5. [Regras de Identificação de Duplicidades](05-duplicidades.html)
6. [Outliers e Séries Temporais](06-outliers-e-series-temporais.html)
7. [Regras Específicas de Escopo 2](07-regras-escopo-2.html)
8. [Perguntas para Esclarecimento](08-perguntas-para-esclarecimento.html)
9. [Classificação de Criticidade](09-criticidade.html)
10. [Formato do Relatório de Verificação](10-formato-do-relatorio.html)
11. [Templates, Identificadores e Fatores de Emissão](11-templates-e-fatores.html)

## Arquivos Necessários em Cada Análise

A cada execução deverão ser fornecidos:

- ledger atualizado da Persefoni;
- Scope 1 - Mobile Combustion;
- Scope 1 - Stationary Combustion - Facility;
- Scope 1 - Stationary Combustion;
- Scope 2 - Purchased Electricity - Facility - Location-Based;
- Scope 2 - Purchased Electricity - Facility - Market-Based.

Quando disponíveis, também deverão ser fornecidos:

- Ficha Técnica das Unidades;
- Matriz de Unidades Reportáveis;
- relação de estimativas, exceções e valores provisórios.

## Governança

A análise por Inteligência Artificial constitui controle complementar.

O agente não deverá:

- alterar arquivos;
- preencher lacunas;
- corrigir ou excluir registros;
- selecionar fatores de emissão autonomamente;
- aprovar dados;
- realizar upload.

Os apontamentos deverão ser avaliados pelo Data Analyst. Questões metodológicas ou excepcionais deverão ser encaminhadas ao Data Manager.

## Controle do Documento

- **Versão:** 1.0
- **Data de vigência:** 21/10/2026
- **Responsável:** QHSE
- **Status:** Draft

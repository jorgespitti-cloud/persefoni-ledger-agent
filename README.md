---
title: Verificação Complementar de Ledger e Templates Persefoni
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Verificação Complementar de Ledger e Templates Persefoni

Esta biblioteca contém a metodologia para verificação complementar dos templates de Escopo 1 e Escopo 2 antes do upload na Persefoni.

## Ordem obrigatória de consulta

1. Governança e limites
2. Arquivos e campos
3. Completude
4. Consistência
5. Duplicidades
6. Outliers e séries temporais
7. Regras de Escopo 2
8. Perguntas para esclarecimento
9. Criticidade
10. Formato do relatório
11. Templates e fatores de emissão

## Regra principal

A análise por Inteligência Artificial é um controle complementar e não substitui:

- a conferência do Data Analyst;
- a decisão do Data Manager;
- a análise das evidências;
- as validações realizadas pela plataforma.

O agente não deverá alterar arquivos, preencher lacunas, corrigir valores, excluir registros, selecionar fatores de emissão autonomamente, aprovar dados ou realizar upload.

## Arquivos necessários em cada execução

O usuário deverá fornecer novamente, a cada análise:

- ledger atualizado;
- Scope 1 - Mobile Combustion;
- Scope 1 - Stationary Combustion - Facility;
- Scope 1 - Stationary Combustion;
- Scope 2 - Purchased Electricity - Facility - Location-Based;
- Scope 2 - Purchased Electricity - Facility - Market-Based.

Quando disponíveis, também deverão ser fornecidos:

- Ficha Técnica das Unidades;
- Matriz de Unidades Reportáveis;
- relação de estimativas, exceções e valores provisórios.

O agente não deverá utilizar informações de execuções anteriores que não tenham sido novamente disponibilizadas para a análise corrente.

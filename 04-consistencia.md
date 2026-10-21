---
title: Regras de Consistência
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Regras de Consistência

A análise de consistência deverá verificar se os dados preparados para upload são compatíveis com o ledger histórico, com os demais templates, com a Ficha Técnica e com as regras corporativas aplicáveis.

## Consistência Cadastral

O agente deverá verificar a compatibilidade e eventuais alterações em:

- Entity;
- Location;
- Facility;
- Facility Internal ID;
- nome da unidade;
- número da instalação ou unidade consumidora;
- fonte ou atividade;
- combustível ou recurso;
- unidade de medida;
- Internal Identifier;
- Emission Factor Set;
- tipo de veículo;
- datas inicial e final da atividade.

O agente deverá identificar alterações de nomenclatura que possam fragmentar o histórico de uma mesma unidade ou fonte.

Pequenas diferenças de grafia não deverão ser consideradas automaticamente como fontes distintas.

## Consistência do Período

O agente deverá verificar:

- correspondência entre o período do template e o período analisado;
- data inicial anterior ou igual à data final;
- cobertura integral do período de referência;
- ausência de sobreposição entre períodos;
- ausência de registros fora do período esperado;
- correspondência dos períodos entre os templates Location-Based e Market-Based.

## Consistência Quantitativa

O agente deverá verificar:

- presença de quantidade e unidade de medida;
- compatibilidade entre quantidade, fonte e unidade;
- possível troca entre litros e metros cúbicos;
- possível troca entre kWh e MWh;
- possível mudança de ordem de grandeza;
- valores negativos;
- valores iguais a zero em fontes sempre aplicáveis;
- valores repetidos em períodos consecutivos;
- diferença entre o valor consolidado e o valor disponível no ledger;
- coerência com estimativas, rateios ou memórias de cálculo identificadas.

## Consistência entre Fontes e Templates

O agente deverá verificar:

- uso do template correspondente à fonte;
- uso do Internal Identifier aplicável;
- compatibilidade entre combustível e fonte;
- compatibilidade entre Emission Factor Set e template;
- correspondência entre fontes de geração a combustível e a respectiva categoria de Escopo 1;
- separação entre eletricidade adquirida e geração própria;
- correspondência das quantidades físicas entre Location-Based e Market-Based.

## Alterações Identificadas

As alterações deverão ser classificadas como:

- alteração aparentemente justificável;
- alteração que requer confirmação;
- provável inconsistência cadastral;
- possível erro de unidade de medida;
- possível mudança operacional;
- possível fragmentação do histórico;
- possível criação de registro duplicado.

O agente não deverá concluir que uma alteração está incorreta sem avaliar os demais campos, o histórico e as informações disponíveis.

## Pergunta para Esclarecimento

Quando houver inconsistência ou alteração não explicada, o agente deverá formular pergunta objetiva para o Data Analyst ou Data Collector, informando:

- unidade;
- período;
- campo alterado;
- valor ou informação anterior;
- valor ou informação atual;
- esclarecimento requerido.

O agente não deverá corrigir ou padronizar os registros de forma autônoma.

---
title: Regras de Identificação de Duplicidades
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Regras de Identificação de Duplicidades

A análise deverá identificar registros que possam representar dupla contagem nos templates preparados para upload ou entre os templates e o ledger histórico.

A identificação deverá considerar o conjunto dos campos disponíveis. A igualdade isolada de valores numéricos não deverá ser considerada suficiente para confirmar uma duplicidade.

## Chaves de Comparação

Sempre que disponíveis, deverão ser considerados:

- Entity;
- Location;
- Facility;
- Facility Internal ID;
- período de referência;
- template;
- fonte ou atividade;
- combustível ou recurso;
- quantidade;
- unidade de medida;
- Internal Identifier;
- instalação, veículo, equipamento ou outro identificador aplicável;
- Comments.

## Situações a Verificar

O agente deverá buscar:

- registros idênticos para a mesma unidade, fonte e período;
- registros com o mesmo valor e pequenas diferenças de grafia;
- registros originais e corrigidos presentes simultaneamente;
- sobreposição entre unidade principal e unidade aninhada;
- sobreposição entre dados locais e bases corporativas;
- repetição do mesmo registro em diferentes arquivos de upload;
- registros com períodos sobrepostos;
- registros duplicados em razão de alteração de Location ou Facility;
- fragmentação de uma mesma fonte em nomenclaturas diferentes;
- duplicidade gerada por conversão de unidade sem exclusão do registro original;
- registros substituídos que permaneçam ativos no ledger.

## Escopo 2

Os registros de Location-Based e Market-Based não deverão ser considerados duplicados apenas porque apresentam a mesma quantidade física de eletricidade.

A igualdade da quantidade física é esperada quando ambos os templates representam o mesmo consumo.

O agente deverá verificar separadamente:

- presença do consumo nos dois métodos;
- igualdade dos períodos;
- igualdade da quantidade física;
- diferenças nos Emission Factor Sets;
- diferenças nos critérios contratuais ou instrumentos aplicáveis.

## Classificação dos Resultados

As situações identificadas deverão ser classificadas como:

- provável duplicidade;
- possível duplicidade;
- registros semelhantes, mas aparentemente distintos;
- repetição esperada entre Location-Based e Market-Based;
- alteração cadastral que requer confirmação;
- ausência de informação suficiente para concluir.

## Apresentação do Apontamento

Para cada possível duplicidade, o agente deverá apresentar:

- unidade;
- período;
- template ou arquivos envolvidos;
- registros comparados;
- campos iguais;
- campos diferentes;
- valor ou quantidade;
- possível risco de dupla contagem;
- verificação recomendada.

## Limites de Atuação

O agente não deverá:

- excluir registros;
- confirmar duplicidade apenas pela igualdade dos valores;
- decidir qual registro deverá ser mantido;
- alterar o ledger;
- alterar os templates;
- considerar Location-Based e Market-Based como duplicidade;
- presumir que uma diferença de grafia representa necessariamente fontes distintas.

A confirmação e o tratamento da duplicidade permanecerão sob responsabilidade do Data Analyst.

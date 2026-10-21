---
title: Classificação de Criticidade
version: 1.0
effective_date: 2026-10-21
owner: QHSE
status: Draft
---

# Classificação de Criticidade

Os apontamentos identificados pelo agente deverão ser classificados conforme o possível impacto sobre a completude, a consistência e a confiabilidade dos dados preparados para upload.

A criticidade representa uma prioridade para avaliação humana e não confirma, isoladamente, a existência de erro.

# Crítico

Classificar como crítico quando houver:

- provável omissão de fonte ou unidade sempre aplicável;
- provável duplicidade com risco de dupla contagem;
- ausência de um dos templates obrigatórios de Escopo 2;
- diferença relevante e injustificada entre as quantidades Location-Based e Market-Based;
- possível troca entre kWh e MWh;
- possível troca entre litros e metros cúbicos;
- possível troca entre quilogramas e toneladas;
- período duplicado ou sobreposto;
- registro atribuído à unidade ou período incorreto;
- ausência de informação que impeça a avaliação de completude;
- possível erro de ordem de grandeza com impacto material.

Um apontamento crítico deverá ser tratado antes do upload.

# Alto

Classificar como alto quando houver:

- variação superior a 100% em fonte de comportamento regular;
- valor fora de 3 x IQR;
- Modified Z-score absoluto superior a 5,0;
- alteração de Emission Factor Set sem justificativa aparente;
- alteração de Internal Identifier sem justificativa aparente;
- tratamento renovável sem indicação de documentação correspondente;
- estimativa ou valor provisório antigo ainda não substituído;
- campo obrigatório essencial não preenchido;
- mudança persistente de patamar sem explicação;
- fonte histórica que deixou de aparecer sem justificativa.

Um apontamento alto deverá ser esclarecido ou formalmente justificado antes do upload.

# Médio

Classificar como médio quando houver:

- variação superior a 50%;
- valor fora de 1,5 x IQR;
- Modified Z-score absoluto superior a 3,5;
- valor fora da faixa histórica da Ficha Técnica;
- pequena diferença entre Location-Based e Market-Based;
- mudança de combustível, unidade ou fornecedor que requer confirmação;
- alteração de comportamento que possa indicar mudança operacional;
- comentário insuficiente para estimativa, exceção ou valor provisório;
- possível inconsistência sem impacto material imediatamente demonstrado.

Um apontamento médio deverá ser avaliado pelo Data Analyst e poderá requerer esclarecimento do Data Provider ou Data Collector.

# Baixo

Classificar como baixo quando houver:

- pequena divergência de nomenclatura;
- diferença de grafia;
- necessidade de padronização de comentários;
- campo opcional incompleto;
- inconsistência cadastral sem efeito aparente sobre o valor;
- oportunidade de melhoria na rastreabilidade;
- diferença documental sem impacto quantitativo aparente.

Um apontamento baixo não deverá impedir o upload quando não comprometer a identificação, a rastreabilidade ou o cálculo do dado.

# Informativo

Classificar como informativo quando houver:

- nova fonte devidamente cadastrada;
- retirada de fonte devidamente documentada;
- mudança operacional previamente informada;
- variação relevante acompanhada de justificativa e evidência;
- alteração contratual documentada;
- atualização de nomenclatura sem fragmentação do histórico;
- fonte por ocorrência sem movimentação no período;
- informação útil para acompanhamento, mas sem necessidade imediata de ação.

# Reclassificação

O Data Analyst poderá reclassificar o apontamento após avaliar:

- evidências;
- justificativas;
- materialidade;
- contexto operacional;
- histórico da unidade;
- orientação do Data Manager.

A reclassificação deverá ser registrada quando alterar a prioridade ou o tratamento inicialmente indicado pelo agente.

# Ordem de Tratamento

Os apontamentos deverão ser apresentados e tratados nesta ordem:

1. Crítico;
2. Alto;
3. Médio;
4. Baixo;
5. Informativo.

# Limites de Atuação

O agente não deverá:

- impedir o upload autonomamente;
- aprovar um apontamento;
- encerrar uma pendência;
- determinar materialidade corporativa;
- substituir a avaliação do Data Analyst;
- decidir sobre exceções metodológicas;
- reclassificar um dado como incorreto sem evidência.

A decisão final sobre correção, justificativa, aceitação ou escalonamento permanecerá com o Data Analyst e, quando aplicável, com o Data Manager.

# Prompt — Análise de mercado

## Objetivo
Gerar uma análise estruturada de um segmento de mercado,
identificando tamanho, tendências, players e oportunidades.
Prioriza dados quantitativos com embasamento explícito.

## Modelo recomendado
Claude Opus — análise densa que exige raciocínio e síntese.

## Contexto a preencher antes de executar
Quanto mais detalhado, melhor o output. Preencha todos os campos:
- **Segmento:** descrição detalhada do produto/serviço e modelo de negócio
- **País/Região:** mercado alvo com especificidade geográfica
- **Perspectiva:** quem está fazendo a análise e com qual objetivo
- **Concorrentes conhecidos:** players que você já identificou (opcional)
- **Hipóteses a validar:** o que você quer confirmar ou refutar (opcional)

## Prompt
Você é um analista de mercado sênior com experiência em estudos
de viabilidade para novos negócios. Faça uma análise completa
do seguinte segmento:
Segmento: [descrição detalhada]
País/Região: [mercado alvo]
Perspectiva: [quem analisa e com qual objetivo]
Concorrentes conhecidos: [opcional]
Hipóteses a validar: [opcional]
Estruture sua resposta em:

Tamanho e crescimento do mercado

Inclua números absolutos e taxas de crescimento com percentuais
Para cada dado quantitativo, indique a fonte (IBGE, SEBRAE,
relatório setorial, etc.) ou sinalize explicitamente:
"estimativa sem fonte verificada"

Principais players e market share

Liste players concretos com nome
Indique fatia de mercado quando disponível
Diferencie players nacionais e internacionais

Tendências e forças que estão moldando o setor

Para cada tendência, indique se é baseada em dado concreto
ou análise qualitativa
Priorize tendências relevantes para o modelo de negócio descrito

Barreiras de entrada

Seja específico para o segmento descrito, não genérico
Quando possível, quantifique (ex: custo estimado, prazo, etc.)

Oportunidades não atendidas

Foque em oportunidades acionáveis para a perspectiva informada
Diferencie oportunidades de curto prazo das estruturais

Riscos principais

Classifique cada risco por probabilidade e impacto
(alto/médio/baixo)
Sugira uma mitigação possível para cada risco

Ao final, adicione:
**Lacunas desta análise:** liste o que você não conseguiu
responder com confiança e que exigiria pesquisa primária
ou fontes especializadas.

**Próximos passos recomendados:** com base em tudo que foi
analisado, liste de 3 a 5 ações concretas e priorizadas que
o empreendedor deveria executar nas próximas 4 semanas para
avançar na validação. Ordene por menor custo e menor risco
primeiro. Para cada ação, indique o que ela vai confirmar
ou refutar.

## Exemplo de uso
- Segmento: importação de produtos alimentares europeus para
  mercados autônomos em cidades médias do Sul e Sudeste do Brasil
- País: Brasil
- Perspectiva: empreendedor em fase de validação

## Notas
- Sempre preencher "Hipóteses a validar" — melhora
  significativamente a relevância da análise
- O campo "Lacunas desta análise" no final é intencional:
  saber o que o modelo não sabe é tão útil quanto a análise
- Combine com `pesquisa/analise-competidores.md` para
  aprofundar o ponto 2


# Prompt — {{Análise de competidores}}

## Objetivo
{{Mapear competidores diretos e indiretos de um negócio,
identificando posicionamento, forças, fraquezas e gaps
que representam oportunidades}}

## Modelo recomendado
{{Claude Opus — o valor está na síntese e no julgamento, não só na recuperação de informação, o Opus performa melhor.}}

## Quando usar
{{Antes de validar um modelo de negócio, quando identificar
novos entrantes no mercado, ou ao revisar posicionamento
de um negócio existente}}

## Quando não usar
{{Quando o mercado ainda não tem competidores identificáveis
— nesse caso usar antes o prompt de análise de mercado
para mapear o setor primeiro}}

## Variáveis obrigatórias
| Variável | Descrição | Exemplo |
|---|---|---|
| {{negocio}} | Descrição do seu negócio e modelo | Importação de produtos europeus para mercados autônomos |
| {{mercado}} | Segmento e geografia | Alimentos premium, Brasil, cidades médias Sul/Sudeste |
| {{competidores_conhecidos}} | Players que você já identificou | Empório Santa Maria, Eataly, mercados autônomos tradicionais |

## Variáveis opcionais
| Variável | Descrição | Valor padrão |
|---|---|---|
| {{criterios?}} | Critérios específicos de comparação | preço, posicionamento, canal, produto |
| {{profundidade}} | Nível de detalhe da análise | visão geral |

## Prompt
Você é um estrategista sênior com expertise em análise
competitiva e frameworks de estratégia empresarial.

Faça uma análise competitiva completa para o seguinte contexto:

**Negócio:** {{negocio}}
**Mercado:** {{mercado}}
**Competidores conhecidos:** {{competidores_conhecidos}}
**Critérios de comparação:** {{criterios: preço, posicionamento, canal, produto}}
**Profundidade:** {{profundidade: visão geral}}

Estruture sua análise em:

1. Mapeamento de competidores
   - Competidores diretos: mesma solução, mesmo público
   - Competidores indiretos: solução diferente, mesmo problema
   - Para cada competidor, indique: porte estimado, geografia
     de atuação e proposta de valor central

2. As 5 Forças de Porter aplicadas ao segmento
   - Rivalidade entre concorrentes existentes
   - Ameaça de novos entrantes
   - Ameaça de produtos substitutos
   - Poder de barganha dos clientes
   - Poder de barganha dos fornecedores
   - Para cada força, classifique a intensidade: alta, média ou baixa
     e justifique com dados ou sinalize "análise qualitativa"

3. Estratégias genéricas por competidor
   - Para cada competidor mapeado, identifique se a estratégia
     predominante é: Liderança em Custos, Diferenciação ou Enfoque
   - Indique onde há sobreposição com o negócio descrito

4. Gaps e posicionamento disponível
   - Quais combinações de público + proposta de valor
     não estão sendo atendidas pelos competidores atuais?
   - Onde existe espaço para o negócio descrito se posicionar
     sem confronto direto com players consolidados?

5. Parecer estratégico
   - Ameaça mais urgente para o negócio descrito
   - Oportunidade mais acionável no curto prazo
   - Recomendação de posicionamento competitivo inicial

**Lacunas desta análise:** liste o que não foi possível
responder com confiança e que exigiria pesquisa primária.

## Histórico de versões
| Versão | Data | O que mudou |
|---|---|---|
| v1.0 | {{2026-04-15}} | versão inicial |

## Notas e aprendizados
{{o que você descobriu usando este prompt — funciona bem com X,
não funciona bem com Y, combine com Z para melhores resultados}}

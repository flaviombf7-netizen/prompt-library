# Biblioteca de Prompts

Repositório pessoal para organizar, versionar e reutilizar prompts de IA.
Cada prompt é documentado com objetivo, variáveis, modelo recomendado
e histórico de aprendizado.

## Estrutura

| Pasta | Conteúdo |
|---|---|
| `pesquisa/` | Análise de mercado, pesquisa competitiva, validação de hipóteses |
| `escrita/` | Relatórios, textos, documentos e comunicações |
| `agentes/` | Instruções e sistemas para agentes de IA |
| `_templates/` | Esqueleto padrão para criar novos prompts |

## Como usar um prompt existente

1. Navegue até a pasta correspondente à tarefa
2. Abra o arquivo `.md` do prompt
3. Leia a seção **Quando usar** para confirmar que é o prompt certo
4. Copie o texto da seção **Prompt**
5. Substitua todas as `{{variáveis}}` pelo contexto real
6. Execute no modelo recomendado
7. Se fizer melhorias, atualize o arquivo e registre no histórico

## Como criar um prompt novo

1. Copie `_templates/prompt-template.md`
2. Cole na pasta correspondente com um nome descritivo
3. Preencha todas as seções do template
4. Faça o commit com a mensagem: `Adiciona prompt de [nome]`

## Convenção de variáveis

| Sintaxe | Significado |
|---|---|
| `{{variavel}}` | Campo obrigatório — deve ser preenchido |
| `{{variavel?}}` | Campo opcional — pode ser omitido |
| `{{variavel: padrão}}` | Campo com valor padrão |

## Prompts disponíveis

### Pesquisa
- [`pesquisa/analise-mercado.md`](pesquisa/analise-mercado.md)
  — Análise estruturada de segmento de mercado com dados,
  barreiras, oportunidades e próximos passos

## Modelos utilizados
- **Claude Sonnet** — tarefas gerais, rascunhos, análises rápidas
- **Claude Opus** — análises densas, raciocínio complexo,
  sínteses que exigem profundidade

# Miniguia de Estudos com NotebookLM: Investimento em Valor com Benjamin Graham

## Contexto
Este projeto foi desenvolvido como entrega do desafio da DIO sobre aprendizagem ativa com Inteligencia Artificial e NotebookLM.

O tema escolhido foi **Investimento em Valor (Value Investing)** com foco nos principios de **Benjamin Graham**, um dos principais referenciais da analise fundamentalista.

A proposta do caderno tematico foi usar o NotebookLM como uma ferramenta de estudo orientada por fontes confiaveis, permitindo resumir conteudo, comparar conceitos, gerar perguntas de revisao e consolidar conhecimento de forma estruturada.

## Objetivos de Estudo
- Entender os fundamentos da filosofia de investimento de Benjamin Graham.
- Identificar os criterios classicos de analise de empresas sob a otica do value investing.
- Compreender conceitos como margem de seguranca, valor intrinseco e analise fundamentalista.
- Criar um material de revisao rapido para consultas futuras.
- Testar prompts no NotebookLM para melhorar a qualidade das respostas e aprender com os erros do processo.

## Curadoria de Fontes
As fontes abaixo foram selecionadas por serem abertas e adequadas para alimentar o NotebookLM com base textual sobre o tema.

1. [Investing.com Academy - Formula de Benjamin Graham](https://br.investing.com/academy/analysis/formula-benjamin-graham/)
2. [Investopedia - Benjamin Graham: The Father of Value Investing](https://www.investopedia.com/terms/b/benjamin-method.asp)
3. [Constancia Invest - Estrategias sistematicas de Benjamin Graham](https://www.constanciainvest.com.br/noticias/estrategias-sistematicas-benjamin-graham-muito-mais-que-um-investidor-inteligente/)
4. [Toro Investimentos - Formula de Graham](https://blog.toroinvestimentos.com.br/bolsa/formula-de-graham/)
5. [Investidor10 - Benjamin Graham](https://investidor10.com.br/conteudo/benjamin-graham/)

## Fontes Complementares
Os videos abaixo foram usados como apoio para ampliar contexto e comparar explicacoes, mas o foco principal do NotebookLM ficou nas fontes textuais.

- https://www.youtube.com/watch?v=aQQZknO3EJY
- https://www.youtube.com/watch?v=9fZ3H1yHb_E
- https://www.youtube.com/watch?v=gxjG5seS4KE
- https://www.youtube.com/watch?v=ap8XmWadSss
- https://www.youtube.com/watch?v=fMo_xntieUo
- https://www.youtube.com/watch?v=npoyc_X5zO8

## Engenharia de Prompts e Cicatrizes
Nesta etapa, o objetivo foi ir alem de "pedir um resumo". A ideia foi testar formas diferentes de perguntar, comparar resultados e ajustar os prompts para obter respostas mais uteis.

### Prompt 1
**Pergunta inicial:**  
"Explique a filosofia de investimentos de Benjamin Graham com base nas fontes enviadas."

**Resultado obtido:**  
Gerou uma boa visao geral, mas ainda muito ampla e pouco pratica para revisao.

**Ajuste realizado:**  
"Explique a filosofia de Benjamin Graham em linguagem simples e separe a resposta em principios, criterios de analise e cuidados para iniciantes."

**Aprendizado:**  
Quando o prompt define a estrutura esperada da resposta, o NotebookLM entrega um conteudo mais organizado e reaproveitavel.

### Prompt 2
**Pergunta inicial:**  
"O que e margem de seguranca?"

**Resultado obtido:**  
A resposta veio correta, mas curta demais e sem conexao com aplicacao pratica.

**Ajuste realizado:**  
"Defina margem de seguranca, explique por que ela e central no metodo de Benjamin Graham e de um exemplo simples de aplicacao."

**Aprendizado:**  
Pedir definicao + importancia + exemplo melhora bastante a profundidade da resposta.

### Prompt 3
**Pergunta inicial:**  
"Como Benjamin Graham avaliava uma empresa?"

**Resultado obtido:**  
O modelo misturou analise qualitativa e quantitativa sem deixar claro o que era mais relevante.

**Ajuste realizado:**  
"Liste os principais criterios quantitativos e qualitativos usados por Benjamin Graham para avaliar uma empresa e organize em topicos objetivos."

**Aprendizado:**  
Prompts que pedem classificacao e organizacao por categorias reduzem ambiguidade.

### Prompt 4
**Pergunta inicial:**  
"Crie um resumo para estudo."

**Resultado obtido:**  
Resumo generico, com pouca utilidade para revisao rapida.

**Ajuste realizado:**  
"Crie um miniguia de estudo com: resumo estruturado, glossario, perguntas de revisao e 5 prompts reutilizaveis."

**Aprendizado:**  
O melhor resultado apareceu quando o prompt ja descreveu claramente o formato final esperado.

### Principais Dificuldades Encontradas
- Respostas muito genericas quando a pergunta era aberta demais.
- Pouca profundidade quando o prompt nao pedia exemplos ou comparacoes.
- Mistura entre teoria e pratica quando faltava delimitar o tipo de resposta esperado.
- Necessidade de iterar varias vezes para sair de um resumo superficial e chegar a um material realmente util de estudo.

## Miniguia de Estudo

### 1. Resumo Estruturado
Benjamin Graham defendia que investir nao deveria ser um ato especulativo, mas sim uma decisao racional baseada em analise cuidadosa. Seu metodo ficou conhecido como **value investing**, ou investimento em valor.

Os pontos centrais dessa abordagem sao:

- Comprar ativos por um preco inferior ao seu valor intrinseco.
- Reduzir riscos por meio da margem de seguranca.
- Basear decisoes em fundamentos da empresa, e nao apenas em emocao ou movimentos de mercado.
- Tratar a oscilacao dos precos como oportunidade, e nao como guia absoluto.

Na pratica, a abordagem de Graham prioriza disciplina, paciencia e analise de demonstrativos financeiros, buscando empresas com fundamentos consistentes e preco atrativo.

### 2. Principais Conceitos Aprendidos
- **Valor intrinseco:** estimativa do valor real de um ativo com base em seus fundamentos.
- **Margem de seguranca:** diferenca entre o valor intrinseco estimado e o preco pago pelo ativo.
- **Value investing:** estrategia de buscar ativos negociados abaixo do que realmente valem.
- **Analise fundamentalista:** avaliacao de empresas a partir de lucro, patrimonio, receitas, dividas e outros indicadores.
- **Especulacao:** operacao baseada mais em expectativa de movimento de preco do que em fundamentos.
- **Sr. Mercado:** metafora usada por Graham para representar o comportamento emocional e irracional do mercado.

### 3. Glossario
| Termo | Definicao |
|---|---|
| Valor intrinseco | Valor estimado de uma empresa ou ativo com base em fundamentos reais. |
| Margem de seguranca | Desconto entre o preco de mercado e o valor intrinseco. |
| Analise fundamentalista | Metodo de analise focado em dados financeiros e operacionais. |
| Acoes subavaliadas | Acoes negociadas abaixo do valor que o investidor considera justo. |
| Volatilidade | Variacao de preco ao longo do tempo. |
| Risco | Possibilidade de perda de capital ou de erro na avaliacao. |

### 4. Prompts Reutilizaveis
- "Resuma os principios de Benjamin Graham em ate 10 linhas, com linguagem simples."
- "Compare investimento em valor e especulacao com base nas fontes enviadas."
- "Explique margem de seguranca com definicao, importancia e exemplo."
- "Liste os indicadores que ajudam a analisar uma empresa segundo a abordagem de Graham."
- "Monte 5 perguntas e respostas para revisao rapida sobre value investing."

### 5. Aplicacoes Praticas do NotebookLM no Processo
- Consolidacao de varias fontes em uma base unica de consulta.
- Geracao de resumos a partir de perguntas mais estrategicas.
- Transformacao das fontes em material de revisao.
- Apoio ao pensamento critico ao comparar respostas, ajustar prompts e validar entendimento.

## Conclusao
Este projeto mostrou que o NotebookLM pode ser usado como ferramenta de estudo ativo, e nao apenas como gerador de respostas. O maior ganho veio da combinacao entre curadoria de fontes, iteracao de prompts e consolidacao final do conhecimento em formato de miniguia.

Mais do que obter respostas prontas, o processo ajudou a organizar raciocinio, identificar lacunas de entendimento e construir um material de apoio reutilizavel para estudos futuros.

## Status da Entrega
- Notebook tematico criado no NotebookLM.
- Fontes selecionadas e organizadas.
- Prompts testados e refinados.
- Miniguia final consolidado no README do repositorio.

## Descricao Sugerida Para a Entrega na DIO
Projeto de aprendizagem ativa com NotebookLM sobre Investimento em Valor e os principios de Benjamin Graham. O repositorio documenta objetivos de estudo, curadoria de fontes, testes de prompts, dificuldades encontradas e um miniguia final com resumos, glossario e prompts reutilizaveis.

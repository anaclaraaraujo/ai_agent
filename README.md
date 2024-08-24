
# AI Agent for Stock Evaluation

## Descrição

Este projeto foi desenvolvido durante o evento IA na prática oferecido pela Rocketseat. O objetivo é criar uma aplicação do zero usando ferramentas como OpenAI GPT, Python e crewAI. A aplicação é um agente de IA para avaliação de ações (stocks), capaz de analisar tendências de preços e criar relatórios baseados em notícias do mercado.


## Dependências
```
O projeto utiliza as seguintes bibliotecas e ferramentas:

- `yfinance==0.2.41`: Para obter dados históricos de ações.
- `crewai==0.28.8`: Para criar e gerenciar agentes de IA.
- `langchain==0.1.20`: Para integração com modelos de linguagem.
- `langchain-openai==0.1.7`: Para utilizar modelos OpenAI GPT.
- `langchain-community==0.0.38`: Ferramentas comunitárias do LangChain.
- `duckduckgo-search==5.3.0`: Para realizar buscas na web e obter notícias.
```

## Funcionalidade

### Ferramentas e Agentes

- **Yahoo Finance Tool**: Obtém preços históricos das ações usando a API do Yahoo Finance.
- **OpenAI GPT**: Utilizado para análise de tendências de preços e criação de relatórios.
- **DuckDuckGo Search**: Obtém notícias recentes relacionadas às ações.

### Tarefas

1. **Obter Preços das Ações**: Analisa o histórico de preços e determina a tendência (alta, baixa ou lateral).
2. **Analisar Notícias**: Pesquisa notícias sobre as ações e fornece um resumo junto com uma pontuação de medo/ganância.
3. **Escrever Análise**: Cria um boletim informativo com uma análise detalhada das tendências de preços e notícias.

## Exemplos

- **Entrada**: AAPL
- **Saída**: Um relatório detalhado com tendências de preços e resumo das notícias.

## Contribuindo

Sinta-se à vontade para contribuir com o projeto! Faça um fork, crie uma branch, e envie um pull request com suas melhorias.

```
Sinta-se à vontade para ajustar conforme necessário! 
Se precisar de mais alguma coisa, é só falar. 🤎
```
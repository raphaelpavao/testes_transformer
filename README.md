# Extração de Texto da Web, Perguntas e Respostas, Sumarização e Análise de Sentimento

Este repositório contém um script em Python que realiza a extração de texto de uma página da web, responde a perguntas baseadas no texto extraído, faz a sumarização do texto e analisa o sentimento de um parágrafo específico. Ele usa bibliotecas como `requests`, `BeautifulSoup`, e `transformers` do Hugging Face.

## Descrição

O script realiza as seguintes tarefas:

1. **Extração de texto da web**: Extrai o texto de uma página da web usando `requests` e `BeautifulSoup`.
2. **Perguntas e respostas**: Utiliza o pipeline de `question-answering` para responder a perguntas baseadas no texto extraído.
3. **Sumarização**: Utiliza o pipeline de `summarization` para resumir o texto extraído.
4. **Análise de Sentimento**: Utiliza o pipeline de `sentiment-analysis` para analisar o sentimento de um parágrafo específico.

## Requisitos

- Python 3.x
- Requests
- BeautifulSoup4
- Transformers

## Instalação

1. Clone este repositório para o seu computador local:
   ```bash
   git clone https://github.com/usuario/repositorio.git

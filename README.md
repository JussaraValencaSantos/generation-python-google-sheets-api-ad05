# 🐍 Python + Google Sheets | Integração com API

### Generation Brasil — Turma AD05

## 📌 Sobre o projeto

Este projeto foi desenvolvido durante minha formação em **Análise de Dados pela Generation Brasil — Turma AD05**.

O objetivo é praticar a integração entre Python e Google Sheets, utilizando o Google Apps Script como uma API web para enviar, armazenar e consultar informações.

Por meio de requisições HTTP, o programa permite registrar dados em uma planilha e recuperar os registros em formato JSON.

## 🎯 Funcionalidades

- Enviar um registro contendo nome e e-mail.
- Enviar vários registros de forma sequencial.
- Consultar todos os registros armazenados.
- Consultar o último registro disponível.
- Trabalhar com respostas JSON.

## 🛠️ Tecnologias utilizadas

- **Python:** linguagem de programação.
- **Google Colab:** ambiente de desenvolvimento e execução.
- **Google Sheets:** armazenamento dos registros.
- **Google Apps Script:** disponibilização da API web.
- **Requests:** biblioteca Python utilizada para requisições HTTP.
- **JSON:** formato de troca de informações.

## 🔄 Como funciona a integração

1. O usuário executa o código Python no Google Colab.
2. O Python envia uma requisição HTTP para o Google Apps Script.
3. O Apps Script recebe a solicitação e interage com a planilha.
4. Os dados são registrados ou consultados.
5. A API retorna uma resposta ao Python.

## 📡 Métodos HTTP utilizados

| Método | Finalidade |
|---|---|
| POST | Enviar nome e e-mail para a planilha |
| GET | Consultar os registros armazenados |

## 📂 Funções desenvolvidas

| Função | Descrição |
|---|---|
| `enviar_mensagem()` | Envia um registro para a planilha |
| `enviar_varias_mensagens()` | Envia vários registros |
| `obter_todas_mensagens()` | Consulta todos os registros |
| `obter_ultima_mensagem()` | Consulta o último registro |

## 📚 Aprendizados

Durante o desenvolvimento, pratiquei:

- Consumo de APIs com Python.
- Requisições HTTP GET e POST.
- Envio de dados em formato JSON.
- Integração entre aplicações.
- Consulta e armazenamento de informações.
- Utilização do Google Colab.

## 🔐 Configuração

Para executar o notebook, é necessário configurar uma implantação própria do Google Apps Script e informar sua URL na variável `API_URL`.

A planilha deve estar preparada para receber os registros e o Apps Script deve implementar os métodos `doGet` e `doPost`.

Não é neces educacionais e aprimoramento das habilidades em programação e Análise de Dados.*

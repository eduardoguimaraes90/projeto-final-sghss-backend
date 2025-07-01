# Protótipo de Backend - Sistema de Gestão Hospitalar (SGHSS)

Este repositório contém o protótipo de backend para um Sistema de Gestão Hospitalar e de Serviços de Saúde (SGHSS), desenvolvido como projeto final para o curso de Análise e Desenvolvimento de Sistemas da UNINTER.

## Sobre o Projeto

O projeto simula a criação de um backend robusto e escalável para a instituição fictícia "VidaPlus". A API permite o cadastro de pacientes e o agendamento de consultas, servindo como a fundação para um sistema de saúde completo.

## Como Executar o Protótipo

1.  **Abra o Notebook no Google Colab:** Clique no botão "Open in Colab" acima para abrir o projeto em um ambiente interativo.
2.  **Adicione o Segredo do ngrok:**
    *   No menu à esquerda do Colab, clique no ícone de chave (🔑) "Segredos".
    *   Crie um novo segredo com o nome `NGROK_AUTHTOKEN`.
    *   Cole seu token de autenticação do ngrok (disponível em [dashboard.ngrok.com](https://dashboard.ngrok.com/get-started/your-authtoken)) no campo "Valor".
3.  **Execute as Células:** Execute as células do notebook em ordem. A última célula irá iniciar o servidor e fornecer uma URL pública.
4.  **Teste a API:** Use a URL gerada com uma ferramenta como Postman, Insomnia, ou diretamente pela documentação interativa (adicionando `/docs` ao final da URL) para testar os endpoints.

## Tecnologias Utilizadas

*   **Linguagem:** Python 3
*   **Framework:** FastAPI
*   **Banco de Dados (Protótipo):** SQLite
*   **Exposição da API:** Ngrok
*   **Ambiente de Execução:** Google Colaboratory

---
**Autor:** Eduardo Leandro Guimarães
**RU:** 4473037

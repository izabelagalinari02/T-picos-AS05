# Chat com Múltiplos PDFs utilizando Streamlit

## Visão Geral
Este projeto implementa uma aplicação web para realizar chatbot com documentos em formato PDF. A aplicação permite ao usuário fazer perguntas sobre o conteúdo dos PDFs e obter respostas utilizando modelos de linguagem e técnicas de processamento de texto.

## Funcionalidades
- **Upload de PDFs:** Os usuários podem fazer o upload de múltiplos documentos PDF diretamente na interface da aplicação.
- **Processamento de Texto:** O texto dos PDFs é extraído e dividido em pedaços menores para facilitar o processamento.
- **Cadeia de Conversação:** Utiliza modelos de linguagem para criar uma cadeia de conversação onde o usuário pode interagir fazendo perguntas sobre os documentos carregados.
- **Integração com Streamlit:** A interface é desenvolvida usando Streamlit, o que permite uma experiência interativa e amigável para o usuário.

## Tecnologias Utilizadas
- **Streamlit:** Framework para a criação de aplicativos web interativos com Python.
- **PyPDF2:** Biblioteca para a manipulação de arquivos PDF.
- **Langchain:** Biblioteca para processamento de linguagem natural, incluindo divisão de texto, embeddings e modelos de conversação.
- **Hugging Face Hub:** Utilizado para modelos de linguagem avançados e embeddings.

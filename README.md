﻿## Cadastro de Mensagens em Angular 17 com Backend em Spring

Este é um projeto simples que demonstra duas funcionalidades básicas:

1. Cadastrar uma nova mensagem.
2. Exibir todas as mensagens cadastradas.

### Funcionalidades

#### Cadastro de Mensagem:
- Preencha os campos de texto com o seu nome, email e a mensagem desejada.
- Clique no botão "Enviar Mensagem".
- A mensagem será adicionada à tabela em de listagem com as mensagens

#### Exibição de Mensagens:
- Todas as mensagens cadastradas são exibidas em uma tabela na página de listagem de mensagens.

### Pré-requisitos

- Node.js e Angular CLI 17 instalados.

### Como Executar

#### Frontend (Angular)

1. Clone o Repositório:
   ```bash
   git clone https://github.com/KevinGirelli/cadastro-mensagens.git
   cd cadastro-mensagens

2. Instale as Dependências na pasta **angular_files** e Inicie o Servidor:
    ```bash
    npm install
    ng serve

3. Acesse a Aplicação:

    Abra o navegador e visite http://127.0.0.1:4200.

#### Backend (Spring)

1. Navegue até o diretório do projeto backend:

    ```bash
    cd C:\cadastro-mensagens\backend\spring\src\main\java\cadastro\mensagens\spring\

2. Abra o arquivo **Application.java**.
3. Execute a aplicação Spring executando a classe principal.
4. Certifique-se de que a aplicação está em execução.

#### Acessando a Aplicação

  Uma vez que ambos os servidores estejam em execução, acesse a aplicação em http://127.0.0.1:4200.

  Certifique-se de que ambos os servidores estejam em execução simultaneamente para garantir a comunicação adequada.

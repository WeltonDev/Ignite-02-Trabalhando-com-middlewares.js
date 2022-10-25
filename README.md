# Desafio 02 - Trabalhando com Middlewares 🚀

## Sobre o desafio 💻

Nesse desafio você irá trabalhar mais a fundo com middlewares no Express. Dessa forma você será capaz de fixar mais ainda os conhecimentos obtidos até agora. 

Para facilitar um pouco mais do conhecimento da regra de negócio, você irá trabalhar com a mesma aplicação do desafio anterior: uma aplicação para gerenciar tarefas (ou *todos*) mas com algumas mudanças.

Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico. Além disso, dessa vez teremos um plano grátis onde o usuário só pode criar até dez *todos* e um plano Pro que irá permitir criar *todos* ilimitados, isso tudo usando middlewares para fazer as validações necessárias.

## Tecnologias 🔧
- Nodejs
- Express
- UUID

## Como rodar o projeto 🚀

    # Clonar o repositório
    $ git clone https://github.com/WeltonDev/Ignite-02-Trabalhando-com-middlewares.js.git

    # Entrar no diretório
    $ cd Ignite-02-Trabalhando-com-middlewares.js

    # Instalar as dependências
    $ yarn

    # Iniciar o projeto
    $ yarn dev

    # Iniciar testes
    $ yarn test
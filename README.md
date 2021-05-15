# ignite-desafio02-trabalhando-com-middlewares

Desafio 02 - Trabalhando com middlewares

<h1 align="center">
    <img src="./imag/yarn_test02.png" />
</h1>

Nesse desafio foi criado uma funcionalidade para trabalhado mais a fundo com middlewares no Express. Para treinar o que foi aprendido até agora na trilha Node.js!. 

Essa e uma aplicação que permiti a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Testes dos middlewares

- Should be able to find user by username in header and pass it to request.user
- Should not be able to find a non existing user by username in header
- Should be able to let user create a new todo when is in free plan and have less than ten todos
- Should not be able to let user create a new todo when is not Pro and already have ten todos
- Should be able to let user create infinite new todos when is in Pro plan
- Should be able to put user and todo in request when both exits
- Should not be able to put user and todo in request when user does not exists
- Should not be able to put user and todo in request when todo id is not uuid
- Should not be able to put user and todo in request when todo id is not uuid
- Should be able to find user by id route param and pass it to request.user
- Should not be able to pass user to request.user when it does not exists

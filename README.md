## :rocket: Sobre o desafio

A aplicação se trata de um gerenciador de academia, o **Gympoint**.

Neste momento, já foi criado algumas funcionalidades básicas. Esse projeto será desenvolvido aos poucos até o fim do bootcamp, onde será uma aplicação completa envolvendo back-end, front-end e mobile, que será utilizada para a **certificação do bootcamp**!

### Um pouco sobre as ferramentas utilizadas:

A aplicação foi criada do zero utilizando o [Express](https://expressjs.com/), além das seguintes ferramentas:

- Sucrase + Nodemon;
- ESLint + Prettier + EditorConfig;
- Sequelize (Utilizando PostgreSQL);

### Funcionalidades

Abaixo estão descritas as funcionalidades que o projeto possui.

#### 1. Autenticação

Permite que um usuário (administrador) se autentique na aplicação utilizando e-mail e uma senha.

- A autenticação é feita utilizando JWT.
- Validação dos dados de entrada utilizando Yup.

#### 2. Cadastro de alunos

Permite que alunos sejam mantidos (cadastrados/atualizados) na aplicação utilizando nome, email, idade, peso e altura.

É utilizado uma tabela específica no banco de dados para os `students`.

O cadastro de alunos só pode ser feito por administradores autenticados na aplicação.

O aluno não pode se autenticar no sistema, ou seja, não possui senha.

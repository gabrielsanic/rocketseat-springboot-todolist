# Backend de uma Lista de Tarefas utilizando Spring Boot

Esse projeto fez parte do curso de Java da Rocketseat (09/10/2023 a 16/10/2023), em que foi feito o backend de uma aplicação de lista de tarefas utilizando conceitos de Spring Boot.

## Funcionalidades:

- **Login de Usuário**: A aplicação oferece autenticação de usuário, permitindo que os usuários acessem suas listas de tarefas de forma segura.

- **Criptografia de Dados**: Os dados do usuário são armazenados com segurança, utilizando a biblioteca Bcrypt para criptografar sua senha.

- **Conexão com Banco de Dados**: Foi feito um banco de dados para armazenar as informações dos usuários e suas tarefas utilizando o H2 Database Engine.

- **Validação de Usuários**: Foi implementada uma lógica que impede que os usuários acessem ou modifiquem tarefas que não pertencem a eles, garantindo a privacidade e segurança dos dados.

- **Validação de Rotas**: A aplicação utiliza Filters para validar e proteger as rotas, garantindo que apenas usuários autenticados possam criar as listas de tarefas e somente alterar a lista de tarefa que pertence a ele.

- **Controller e Models**: O projeto possue Controllers para gerenciar as rotas e Models para representar os dados da aplicação.

- **Deploy com Docker**: Foi feito o deploy do Backend utilizando Docker.
  
- **Métodos HTTP para inserção de dados**: Para fazer a entrada/retorno de dados dos usuarios e tarefas utilizou-se o POST, PUT e GET passando os dados por JSON.

- **Status de respostas HTTP personalizados**: Para facilidade de uso foram feito mensagens personalizadas, como no caso tentar criar um usuário já existente ou tentar fazer acesso a uma lista que o usuário não tem permissão.

Link da aplicação: https://todolist-rocket-omi3.onrender.com/


## NodeJS - Middlewares

---

### Requisitos

- [x] Criar um novo ToDo
- [x] Listar todos os ToDos
- [x] Alterar o title e deadline de um ToDo existente
- [x] Marcar um ToDo como feito
- [x] Excluir um ToDo

---

## Testes

- [x] Deve ser possível criar um novo usuário
- [x] Não deve ser possível criar um novo usuário com username já existente
- [x] Checar se existe um usuário utilizando um Middleware
- [x] Deve ser possível listar os ToDos de um usuário
- [x] Deve ser possível criar um novo ToDo
- [x] Deve ser possível atualizar um ToDo
- [x] Não deve ser possível atualizar um ToDo não existente
- [x] Deve ser possível marcar um ToDo como feito
- [x] Não deve ser possível marcar como feito um ToDo não existente
- [x] Deve ser possível deletar um ToDo
- [x] Não deve ser possível deletar um ToDo não existente

## Testes Middlewares

- [x] Deve ser possível encontrar um usuário pelo username passado no header e passá-lo para o request
- [x] Não deve ser possível encontrar um usuário não existente pelo username passado no header
- [x] Deve ser possível permitir o usuário criar um novo ToDo se possuir um plano gratuito e menos que 10 ToDo's
- [x] Não deve ser possível permitir criar um novo ToDo se possuir um plano gratuito e mais que 10 ToDo's
- [x] Deve ser possível permitir um usuário a criar ToDo's infinitos se possui o plano Pro
- [x] Deve ser possível passar o usuário e o ToDo para o request se ambos existirem
- [x] Não deve ser possível passar o usuário e o ToDo para o request se o usuário não existir
- [x] Não deve ser possível passar o usuário e o ToDo para o request se o id do ToDo não for um UUId
- [x] Não deve ser possível passar o usuário e o ToDo para o request se o ToDo não existir
- [x] Deve ser possível encontrar um usúario pelo id passado pela rota e passá-lo para o request
- [x] Não deve ser possível passar o usuário para o request se ele não existir

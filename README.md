<h2 align="center">🚀 Second Challenge by Rocketseat</h2>
<h5 align="center">Ignite - <a href="https://rocketseat.com.br/" >Rocketseat</a> - Node js</h5>

## 💻 Descrição

Development of middlewares on Express to manage ToDo list. Users can choose between a FREE plan, with a 10 ToDo itens limit, or a ilimited PRO plan.

## 🛠️ Funcionalidades

- create new user with `name` and `username`
- create new ToDo
- Get all  `todos`;
- Update `title` and `deadline`of an existent `todo`;
- Mark `todo` as done;
- Delete `todo`;

## 🔗 Rotas

- POST `/users` → create new user.
- GET `/users/:id` → get user by id.
- PATCH `/users/:id/pro` → update user's plan to PRO.
- GET `/todos` → get all user's ToDos.
- POST `/todos` → create new ToDo.
- PUT `/todos/:id` → update ToDo.
- PATCH `/todos/:id/done` → update ToDo as `done`.
- DELETE `/todos/:id` → delete ToDo by `id`

### 📝 Clone

To clone the repository execute `git clone https://github.com/fermlisboa/middleware-challenge-ignite.git`.

### 🕮 Get Start

Execute `yarn` to install all dependencies.

##### Uso

With all dependencies installed, execute `yarn dev` to execute your application. Run`yarn test` to execute tests.
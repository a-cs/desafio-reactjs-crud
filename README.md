![Gostask](https://camo.githubusercontent.com/d25397e9df01fe7882dcc1cbc96bdf052ffd7d0c/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67)
Desafio sobre Reactjs-crud do Bootcamp [GoStack da Rocketseat](https://rocketseat.com.br/gostack)

# Sobre o desafio

O objetivo do desafio é desenvolver mais uma aplicação, a GoRestaurant. Praticando o que foi aprendido até agora no React.js junto com TypeScript e o conceito de CRUD (Create, Read, Update, Delete).

Essa será uma aplicação que irá se conectar a uma fake API, e exibir os pratos de comida criados e permitir a criação, remoção e atualização desses pratos.

# Instalando as dependências
Para instalar as dependências, execute o seguinte comando:

  `yarn`

# Utilizando uma fake API

Para que você tenha os dados para exibir em tela, execute o seguinte comando:

  `yarn json-server server.json -p 3333`

com isso você terá acesso a rota `/foods`.


### **Funcionalidades da aplicação**

- [x] **`Listar os pratos de comida da sua API`**: A página `Dashboard` é capaz de exibir uma listagem, com o campo `title`, `value`, e `description` e `available` de todos os pratos de comida que estão cadastrados na sua API.
- [x] **`Adicionar novos pratos de comida a sua API`**: Na página `Dashboard` é possível abrir um modal ao clicar no botão `Novo Prato` no Header. Esse modal é responsável por cadastrar uma nova `food` passando os campos `image`, `name`, `description`, `value`.

**Dica** : O campo image deve ser uma URL.

- [x] **`Editar pratos de comida da sua API`**: Na página `Dashboard` é possível abrir um modal ao clicar no botão `Editar Prato`. Esse modal é responsável por editar uma `food` passando os campos `image`, `name`, `description`, `value`.
- [x] **`Remover pratos de comida da sua API`**: Na página `Dashboard` é possível remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.
- [x] **`Alterar disponibilidade dos pratos de comida da sua API`**: Na página `Dashboard` é possível alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.

### **Específicação dos testes**

- [x] **`should be able to list all the food plates from your api`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados, toda os pratos de comidas que são retornadas da sua fake API.
- [x] **`should be able to add a new food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja adicionado a sua api, adicionando-o também à listagem.
- [x] **`should be able to edit a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja editado na sua api, editando-o também na listagem.
- [x] **`should be able to remove a food plate`**: Para que esse teste passe, você deve permitir que um prato de comida seja removido da sua api, removendo-o também da listagem.
- [x] **`should be able to update the availibility of a food plate`**: Para que esse teste passe, em sua dashboard você deve permitir que o status do prato de comida seja alterado entre `Disponível` e `Indisponível`;

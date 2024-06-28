# Biblioteca de Jogos:

## plicação integrada a um banco de dados que possibilita "adicionar", "excluir", "editar" e "visualizar" informações de jogos e que também possuí um sistema de autentificação.

### Funcionalidades

- `Funcionalidade 1`: Autentificação de usuário
- `Funcionalidade 2`: Visualização da biblioteca
- `Funcionalidade 3`: Adicionar jogo na biblioteca
- `Funcionalidade 4`: Editar jogo da biblioteca
- `Funcionalidade 5`: Remover jogo da biblioteca
- `Funcionalidade 6`: Adicionar imagem ao jogo
- `Funcionalidade 7`: Deslogar usuário
- `Funcionalidade 8`: Bloquer funcionalidades para usuários deslogados

### Tecnlogias Utilizadas:

- `Python3`
- `Flask`
- `HTML5`
- `CSS`
- `MySQL`
- `SQLAlchemy`

### Instalação e Requisitos

- `Requisito 1`: "git clone: https://github.com/PedroACir/ProjetoProgWeb.git"
- `Requisito 2`: instalar MySQL Server e configura-lo.
- `Requisito 3`: Acessar a aplicação.
- `Requisito 4`: Rodar ambiente virtual.
- `Requisito 5`: Rodar o comando "pip install -r requirements.txt" no terminal.
- `Requisito 6`: Rodar o banco de dados "prepara_banco.py".
- `Requisito 7`: Rodar "jogoteca.py".
- `Requisito 8`: Se autentificar com o usuário: "teste" e senha: "teste123".

### Uso da API:

#### Endpoints

- `Endpoint 1`: Autenticação de usuário

Método: POST
URL: /autenticar
Descrição: Endpoint para autenticar usuários na aplicação.

- `Endpoint 2`: Visualização da biblioteca de jogos

Método: GET
URL: /
Descrição: Endpoint para visualizar a lista de jogos cadastrados.

- `Endpoint 3`: Adição de novo jogo

Método: GET
URL: /novo
Descrição: Endpoint para exibir o formulário de adição de novo jogo.

- `Endpoint 4`: Criação de novo jogo

Método: POST
URL: /criar
Descrição: Endpoint para criar um novo jogo no banco de dados.

- `Endpoint 5`: Edição de jogo existente

Método: GET
URL: /editar
Descrição: Endpoint para exibir o formulário de edição de um jogo existente.

- `Endpoint 6`: Atualização de jogo existente

Método: POST
URL: /atualizar
Descrição: Endpoint para atualizar as informações de um jogo existente no banco de dados.

- `Endpoint 7`: Remoção de jogo existente

Método: GET
URL: /deletar
Descrição: Endpoint para deletar um jogo existente do banco de dados.

- `Endpoint 8`: Página de login

Método: GET
URL: /login
Descrição: Endpoint para exibir o formulário de login.

- `Endpoint 9`: Logout de usuário

Método: GET
URL: /logout
Descrição: Endpoint para efetuar o logout do usuário da aplicação.

### Contribuição:

- `Contribuidor 1`: Pedro Augusto

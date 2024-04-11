# Criando APIs com NodeJs

### Docker

utilizei imagem do mongo

docker pull mongo

### Rodando o Mongo

Para executar esta imagem você pode usar a linha abaixo. Não se esqueça de mudar o MONGO_INITDB_ROOT_USERNAME e MONGO_INITDB_ROOT_PASSWORD para o usuário e senha desejado.

docker run --name mongodb -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=name -e MONGO_INITDB_ROOT_PASSWORD=password mongo

### Sumário

Neste estudo resolvi unir a popularidade das APIs com a popularidade do JavaScript criando uma API completa com NodeJs, passando pelos principais pontos para colocar o projeto em produção.

### Estudo Programático

- Instalação Node, NPM e VS Code
- npm init e instalação dos pacotes
- Criando um servidor Web
- Normalizando a porta
- Gerenciando Erros do Servidor
- Iniciando o Debug
- Separando o Servidor
- Configurando o NPM Start
- Nodemon
- CRUD REST
- Rotas
- Controllers
- MongoDb Setup
- Mongooose
- Models
- Criando um Produto
- Listando os Produtos
- Listando um Produto pelo slug
- Listando um Produto pelo Id
- Listando os Produtos de uma tag
- Atualizando um produto
- Excluindo um produto
- Validações
- Repositórios
- Async/Await
- Revisitando os Models: Customer
- Revisitando os Models: Order
- Revisitando os Models: OrderItems
- Revisitando os Controllers: Customer
- Revisitando os Controllers: Order
- Arquivo de Configurações
- Enviando E-mail de Boas Vindas
- Upload da Imagem do Produto
- Autenticação
- Autorização
- Habilitando CORS
- Publicando a API

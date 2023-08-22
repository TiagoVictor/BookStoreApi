# BookStoreApi

# Detalhes sobre o projeto
Foi necessário realizar a instalação do MongoDB na máquina:
https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/
https://www.mongodb.com/docs/mongodb-shell/install/

Após isso a utilização foi seguida dentro da UI gerada pelo MongoDB Compass
  - use BookStore (Comando utilizado para criar o banco de dados)
  - db.CreateCollection('Books') (Comando utilizado para criar a coleção de livros
  - db.Books.insertMany([{ "Name": "Design Patterns", "Price": 54.93, "Category": "Computers", "Author": "Ralph Johnson" }, { "Name": "Clean Code", "Price": 43.15, "Category": "Computers","Author": "Robert C. Martin" }]) (Comando utilizado para inserir novos registros na collection)
  - Com isso o banco ja esta criado e populado, restante da configuração foi feita via código exemplificado no repositório a seguir

  Foi utilizado o Package MongoDB.Driver para gerenciar o banco

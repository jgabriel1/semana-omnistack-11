## Rota / Recurso

## Métodos HTTP:

* GET: Buscar/listar uma informação do back-end
* POST: Criar uma informação no back-end
* PUT: Alterar uma informação no back-end
* DELETE: Deletar uma informação no back-end


## Tipos de parâmetros:

* Query Params: Parâmetros nomeados enviados na rota após "?" (Filtros, paginação)
- EG -> /users?name=Diego&page=2&idade=25

* Route Params: Parâmetros utilizados para identificar os recursos
- EG -> /users/:id

* Request Body: Corpo da requisição, utilizado para criar ou alterar recursos

## DataBase
* SQL: MySQL, **SQLite**, PostgreSQL, Oracle, Microsoft SQL Server
* NoSQL: MongoDB, CouchBD, etc
* 
* Pesquisa:
* Driver: 
<code>SELECT * FROM users</code>
* Query Builder: 
<code>table('users').select('*').where('...')</code>
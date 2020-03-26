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

# Front-End
### Conceitos React
* Componente: um componente html pode ser importado para dentro de um app React como uma função;
* JSX = JavaScript + XML: Sempre que for utilizar html dentro do javascript é necessario importar o React, mesmo que o objeto React nao esteja sento chamado diretamente;
* Estado: o React observa o estado das variaveis;
* Imutabilidade: as variaveis são imutáveis dentro do React, mesmo sendo chamadas variaveis. Para alterar seu valor, é necessário reassinalá-las por meio de uma função usando o useState importado de 'react.js':
<code>
	const [counter, setCounter] = useState(0)

	// Array [valor, funcaoDeAtualizacao]

	function increment() {
		setCounter(counter + 1)
	}
</code>


## React Native
React Native não tem as mesmas tags do html: View e Text

* elementos não tem semântica;

* estilização feita pela tag style que recebe um objeto com a estilização

* ou dentro da propria tag;
 
* separar em um arquivo pra estrutura e um arquivo para estilo;
 
* todos os elementos possuem display: flex;

* como os elementos de estilo são em javascript, a semantica da linguagem deve ser respeitada:
* background-color = backgroundColor,
* justifyContent: 'center' # transformar tags em strings;

* não existe herança de estilos, a estilização deve ser feita de forma direta;

# GO Restful API service with Gin framework and Gorm SQLite

## Template Structure

- [Gin](github.com/gin-gonic/gin) is a web framework written in Go (Golang). It features a martini-like API with performance that is up to 40 times faster thanks to httprouter. If you need performance and good productivity, you will love Gin.
- [JWT](github.com/golang-jwt/jwt) A go (or 'golang' for search engine friendliness) implementation of JSON Web Tokens.
- [GORM](https://gorm.io/index.html) with [SQLite](https://gorm.io/docs/connecting_to_the_database.html#SQLite)The fantastic ORM library for Golang aims to be developer friendly.

## Available Endpoint

In the project directory, you can run:

### `POST /login`

For generating a JWT

### `GET /books`

For getting all of books

### `POST /books`

For creating new book

### `DELETE /books/:id`

For removing existing books

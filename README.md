# Books CRUD API

## Description

This project is a RESTful API developed in Go as part of the "Golang Intensive" course by Full Cycle. The API allows users to perform CRUD (Create, Read, Update, Delete) operations on a collection of books. It leverages Go's powerful concurrency model by utilizing Channels and Goroutines to handle multiple requests efficiently.

## Features

- **Create**: Add new books to the collection.
- **Read**: Retrieve information about existing books.
- **Update**: Modify details of existing books.
- **Delete**: Remove books from the collection.

## Technologies

- **Golang**: The core language used for building the API.
- **Channels and Goroutines**: Used to manage concurrent operations, ensuring efficient handling of multiple requests.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/diogoalvesf/go-books.git
    cd go-books
    ```
2. Install dependencies and start the API:
    ```bash
    go mod tidy
    go run main.go
    ```

## Usage

The API exposes the following endpoints:

- `POST /books`: Create a new book.
- `GET /books`: Retrieve a list of books.
- `GET /books/{id}`: Get details of a specific book.
- `PUT /books/{id}`: Update a book's information.
- `DELETE /books/{id}`: Delete a book.

## Concurrency

This API is designed to handle multiple requests simultaneously, using Channels and Goroutines to manage background tasks efficiently, such as database operations and request handling.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Diogo Alves** - *Developer* - [GitHub](https://github.com/diogoalvesf)

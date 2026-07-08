# Books REST API

A RESTful API built with Node.js and Express for managing a collection of books. The project demonstrates CRUD operations, RESTful routing, JSON data handling, and automated API testing using Jest and Supertest.

The project includes:

- RESTful book management API
- Full CRUD operations
- Automated API testing
- Express.js backend

## Features

- Retrieve all books
- Retrieve a book by ID
- Create new books
- Update existing books
- Delete books
- JSON request and response handling
- RESTful API architecture
- Automated endpoint testing with Jest and Supertest

## Technologies Used

- Node.js
- JavaScript
- Express.js
- Jest
- Supertest
- Git & GitHub

## 📂 Project Structure

```text
books-rest-api
│
├── tests
│   └── api.test.js
│
├── node_modules
│
├── .gitignore
├── package.json
├── package-lock.json
├── server.js
└── README.md
```

## API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/` | API information |
| GET | `/api/books` | Retrieve all books |
| GET | `/api/books/:id` | Retrieve a book by ID |
| POST | `/api/books` | Create a new book |
| PUT | `/api/books/:id` | Update a book |
| DELETE | `/api/books/:id` | Delete a book |

## Testing

The project includes automated API tests covering:

- Retrieve all books
- Retrieve a single book
- Create a new book
- Update an existing book
- Delete a book
- Error handling for invalid requests

Run the test suite with:

```bash
npm test
```

## About

A RESTful API built with Node.js and Express for managing books through CRUD operations. The project includes automated API testing with Jest and Supertest, demonstrating REST architecture and backend development fundamentals.

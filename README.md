# Postman-API-portfolio-DummyJSON

## Project Overview

This project demonstrates REST API testing using Postman and JavaScript.
It includes automated API checks for authentication, users, products, todos,
and HTTP error handling using the public DummyJSON API.

## Tools & Technologies

- **Postman** — creating and executing API requests and collections.
- **JavaScript** — writing automated assertions in Postman test scripts.
- **REST API** — testing HTTP methods, status codes, response bodies, and authentication.
- **DummyJSON** — public test API used as the target of the test suite.
- **Git and GitHub** — version control and hosting the project repository.

## Test Scope

The collection covers the following areas:

- **Authentication** — login and authenticated API requests.
- **Users** — retrieving and testing user data.
- **Products** — retrieving and testing product data.
- **Todos** — retrieving and testing todo items.
- **Error Handling** — validating API responses for invalid or unsuccessful requests.

## Test Coverage

The test suite includes the following checks:

- **HTTP status codes** — verifying that API responses return expected status codes.
- **Response time** — checking that requests complete within a defined time threshold.
- **Response structure** — validating JSON responses and required fields.
- **Data validation** — checking values and data types returned by the API.
- **Authentication** — validating login responses and token handling.
- **Negative scenarios** — testing invalid requests and expected error responses.
- **CRUD operations** — testing create, read, update, and delete endpoints.

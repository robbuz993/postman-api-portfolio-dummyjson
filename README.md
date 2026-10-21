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

## How to Run

### Prerequisites

- Postman installed on your computer.
- An internet connection to access the DummyJSON API.

### Setup

1. Clone or download this repository.
2. Open Postman.
3. Import the Postman collection JSON file.
4. Import the Postman environment JSON file.
5. Select the imported environment.
6. Open the collection and run the requests using Collection Runner.
7. Review the test results in Postman.

### Test Execution

The collection uses JavaScript test scripts to validate API responses.
Review the test results in Postman to identify passed and failed assertions.

## Test Results

- **Total tests:** 111
- **Passed:** 111
- **Failed:** 0

The test suite was executed in Postman using the imported collection
and environment.

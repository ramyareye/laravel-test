---
title: Laravel API Test Task
---

# Test Task: Laravel API for Book Management

## Task Description

Create a RESTful API for managing a collection of books. Each book should have a title, author, and publication year. The application should be built using Laravel and follow best practices for API development, validation, and security.

## Requirements

### 1. Setup:

- Use Laravel to create a new project.
- Set up a MySQL database to store the book records.
- Implement migrations for creating the necessary database tables.

### 2. Book Model:

- Create a `Book` model with the following fields: `title`, `author`, and `publication_year`.
- Implement validation rules for each field (e.g., required, max length, etc.).

### 3. API Endpoints:

- Implement the following RESTful API endpoints for books:
  - `GET /api/books`: Retrieve a list of all books.
  - `GET /api/books/{id}`: Retrieve details of a specific book.
  - `POST /api/books`: Create a new book.
  - `PUT /api/books/{id}`: Update an existing book.
  - `DELETE /api/books/{id}`: Delete a book.

### 4. Request and Response Formats:

- Define appropriate request and response formats using JSON.
- Handle validation errors and provide meaningful error responses.

### 5. Validation:

- Implement validation for incoming requests (e.g., required fields, valid data types).
- Return appropriate HTTP status codes for successful and unsuccessful requests.

### 6. Security:

- Implement API token-based authentication for the API.
- Use Laravel's built-in features for handling validation errors.

### 7. Testing:

- Write a basic test for one of the API endpoints using Laravel's testing tools.

### 8. Git:

- Initialize a Git repository for the project.
- Commit your changes with meaningful commit messages.
- Push the code to a public repository on GitHub.

## Submission

- Provide a link to the GitHub repository containing your code.
- Include a README file with instructions on how to set up and test the API.

## Evaluation Criteria

Candidates will be evaluated based on:

- Correct implementation of API endpoints.
- Proper use of Laravel features for API development.
- Code readability, structure, and organization.
- Adherence to coding standards and security practices.
- Successful completion of the testing requirements.
- Demonstrated understanding of Laravel concepts and PHP for API development.

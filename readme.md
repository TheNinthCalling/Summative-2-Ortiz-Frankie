
# Bookstore REST API - README
In this project, you will work together with a team to build a REST API to manage inventory for a bookstore. You will also provide support for querying with GraphQL. In addition, you will produce a 1–3 minute video summary of the project. The requirements and features are detailed below.

---

## General Setup and Format

- Your project must be created in an IntelliJ project called `Summative-2-Lastname-Firstname`.
- Initialize the project using `start.spring.io` with the following options:
    - Project: Maven
    - Language: Java
    - Spring Boot: Latest version of 2.x.x
    - Project Metadata:
        - Group: com.company
        - Artifact: bookstore (This will automatically update the values for Name and Package Name)
    - Packaging: Jar
    - Java: 11
    - Dependencies: Spring Web, Spring Data JPA, and Spring for GraphQL.
- Your project must have a series of tests using MockMvc.
- Your project must use the existing `book_store` database.
- Your REST API must accept and return data in JSON format where appropriate.
- Your REST API must be documented using Swagger. Save the `.yaml` file in the root of the project directory.

---

## Bookstore REST API

The Bookstore web service manages inventory for a bookstore. The REST APIs in this project allow callers to perform the following actions:

- [ ] Create, Read, Update, and Delete Books.
- [ ] Create, Read, Update, and Delete Authors.
- [ ] Create, Read, Update, and Delete Publishers.
- [ ] Find Books by a given Author.

### User Stories

- [ ] As an API user, I would like to create, read, update, and delete authors.
- [ ] As an API user, I would like to create, read, update, and delete publishers.
- [ ] As an API user, I would like to create, read, update, and delete books.
- [ ] As an API user, I would like to find all books by a given author.

### Requirements for Book API

- **Book API** (25%):
    - [ ] Code is clean and follows general patterns as presented in class.
    - [ ] Implementation of Book model.
    - [ ] Implementation of Book repository and controller for the following actions:
        - [ ] Create
        - [ ] Read by Id
        - [ ] Read All
        - [ ] Update
        - [ ] Delete
        - [ ] Search Book by Author Id
    - [ ] Test of Book repository and MockMvc test cases for the following actions:
        - [ ] Create
        - [ ] Read by Id
        - [ ] Read All
        - [ ] Update
        - [ ] Delete
        - [ ] Search Book by Author Id

### Requirements for Author API

- **Author API** (25%):
    - [ ] Code is clean and follows general patterns as presented in class
    - [ ] Implementation of Author model
    - [ ] Implementation of Author repository and controller for the following actions:
        - [ ] Create
        - [ ] Read by Id
        - [ ] Read All
        - [ ] Update
        - [ ] Delete
    - [ ] Test of Author repository and MockMvc test cases for the following actions:
        - [ ] Create
        - [ ] Read by Id
        - [ ] Read All
        - [ ] Update
        - [ ] Delete

### Requirements for Publisher API

- **Publisher API** (25%):
    - [ ] Code is clean and follows general patterns as presented in class
    - [ ] Implementation of Publisher model
    - [ ] Implementation of Publisher repository and controller for the following actions:
        - [ ] Create
        - [ ] Read by Id
        - [ ] Read All
        - [ ] Update
        - [ ] Delete
    - [ ] Test of Publisher repository and MockMvc test cases for the following actions:
        - [ ] Create
        - [ ] Read by Id
        - [ ] Read All
        - [ ] Update
        - [ ] Delete

---

## Bookstore GraphQL

Your project must support GraphQL queries to retrieve the following information:

- [ ] Get a publisher by id.
    - Including books for the publisher and authors for the books.
- [ ] Get an author by id.
    - Including books by the author.
- [ ] Get a book by id.
    - Including the author and publisher of the book.

### Requirements for GraphQL (15%):

- **GraphQL** (15%):
    - [ ] Implementation of:
        - [ ] Find Publisher by Id (Including books for the publisher and authors for the books).
        - [ ] Find Author by Id (Including books by the author).
        - [ ] Find Book by Id (Including the author and publisher of the book).

---

## Video Summary

Create a 1 to 3-minute video summary of your project that meets the following requirements:

- [ ] Video should be created in MP4 format.
- [ ] Video should include screen-capture recordings to highlight the sections of the project that are important in meeting the project requirements.

---

https://github.com/TheNinthCalling/Summative-2-Ortiz-Frankie/assets/98507662/ad571a75-2245-4904-a8c4-cfdf38c0eede




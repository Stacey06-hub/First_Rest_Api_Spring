# Project 2 — REST API (Spring Boot)

A simple **backend-only** REST service built with Spring Boot.  
The goal of this project is to practice: **REST endpoints, layered architecture, mapping entity, database usage (H2), Swagger/OpenAPI and exception handling**.

---

##  Tech Stack

- **Java** 17+
- **Spring Boot** (Spring Web, Spring Data JPA, DevTools)
- **H2 Database** (in-memory)
- **Swagger / OpenAPI** (springdoc)
- Tools for testing: **Browser /  Postman**

## 🌐 REST Endpoints


### ➕ Create product
Adds a new product to the database.
> Screenshot: ![img.png](img.png)

---
### 2. Find All Products (GET)

Returns a list of all products stored in the database.


> Screenshot:![img_1.png](img_1.png)

### 3. Find Product by ID (GET)

Retrieves a product by its unique identifier.

> Screenshot:![img_2.png](img_2.png)
---
### 4. Update Product (PUT)
Update Product by id in database.



> Screenshot: *![img_3.png](img_3.png)

### 5. Delete Product (DELETE)
Delete Product from database.


> Screenshot: *![img_4.png](img_4.png)

## 🗄 Database Management (H2 Console)

The project uses an **H2 In-Memory Database** for data storage and testing.

* **H2 Console URL**

  ```
  http://localhost:8080/console
  ```

* **JDBC URL**

  ```
  jdbc:h2:mem:testdb
  ```

> Screenshot of Database working: ![img_5.png](img_5.png)
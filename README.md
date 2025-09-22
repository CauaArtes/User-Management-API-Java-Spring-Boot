📌 Description

User-Management-API-Java-Spring-Boot is a simple RESTful API built with Java 17, Spring Boot, and JPA/Hibernate for managing user data.
It provides basic CRUD (Create, Read, Update, Delete) operations using an in-memory H2 database by default.

✨ Features

- Create new users

- Retrieve users by email

- Update user information (by ID or email)

- Delete users by email

- H2 database integration with console access (/h2-console)

🛠️ Technologies Used

- Java 23 (JDK 23)

- Spring Boot

- Spring Data JPA / Hibernate

- H2 Database (in-memory)

- Lombok

🚀 Getting Started

1 - Clone this repository:

  git clone https://github.com/CauaArtes/User-Management-API-Java-Spring-Boot.git


2 - Run the application (from your IDE or with Maven/Gradle).

3 - Access the API at:

  Base URL: http://localhost:8081/user

  H2 Console: http://localhost:8081/h2-console

📖 Example Requests

POST /user → Create a user

{
  "email": "example@email.com",
  "name": "John Doe"
}

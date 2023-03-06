Frameworks and Languages used
-
The following frameworks and languages were used to develop the Todo App:

Spring Boot: Spring Boot is a popular Java framework used for developing web applications. It provides a fast and efficient way to build and deploy applications.

Java: Java is a high-level programming language used for developing enterprise applications. It is a popular choice for developing web applications due to its platform independence and security features.

Data Flow
-
TodoController: This controller class is responsible for handling HTTP requests related to tasks. It contains methods for creating, reading, updating, and deleting tasks. The controller communicates with the TaskService to perform the necessary business logic.

TodoService: This service class is responsible for implementing the business logic related to tasks. It contains methods for creating, reading, updating, and deleting tasks. The service communicates with the TaskRepository to interact with the database.

TodoStatus: This enum class represents the possible statuses for a task, including IN_PROGRESS, COMPLETED, and CANCELLED.

Project Summary
-
The Todo App is a simple web-based application that allows users to create, read, update, and delete tasks. The app provides a user-friendly interface for managing tasks and helps users stay organized and productive.


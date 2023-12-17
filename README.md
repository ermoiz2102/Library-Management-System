Library Management System

This project is a Library Management System built using Spring and SQL. It includes various layers such as entities, exception classes, Repository, Service, and Controller layers. The system utilizes bidirectional mapping, Swagger for API documentation, sending emails, and transactional handling.

Features
Entities: Entities are the core data objects within the system. They represent the various elements such as books, users, transactions, etc.

Exception Classes: Custom exception classes are implemented to handle specific error scenarios elegantly within the system.

Repository Layer: The repository layer contains the CRUD operations for entities using Spring Data JPA.

Service Layer: Services encapsulate the business logic and interact with the repositories to manage entities.

Controller Layer: Controllers expose the RESTful endpoints for interacting with the system.

Bidirectional Mapping: Utilizes bidirectional mapping between entities to establish relationships, such as books allotted to users.

Swagger: API documentation is implemented using Swagger for easy reference and understanding of available endpoints.

Email Sending: Functionalities are integrated to send emails, possibly for notifications or alerts within the system.

Transaction Entity: Emphasis is placed on managing the transactional flow, especially focusing on book allotment to users.

Enum Classes: Enum classes are used to set default values for certain variables, ensuring a predefined set of options.

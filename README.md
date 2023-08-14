# Car Dealership and Workshop Management System

This is a Spring Boot-based application for managing a car dealership along with a car workshop. It provides both web-based templates using Thymeleaf and a RESTful API for various functionalities.

## Features

- Manage Car Inventory: Add, update, and delete cars in the inventory.
- Workshop Management: Schedule and track car repairs and maintenance tasks.
- Customer Interaction: Interact with customers, handle inquiries, and manage appointments.
- Sales Management: Handle car sales, generate invoices, and track transactions.
- Reporting: Generate reports on inventory, sales, workshop tasks, and more.

## Technologies Used

- Spring Boot: Provides the foundational structure and components for the application.
- Thymeleaf: Enables server-side rendering of HTML templates.
- RESTful API: Exposes endpoints for programmatic access and integration with other systems.
- Spring Data JPA: Simplifies database interactions using JPA (Java Persistence API).
- PostgreSQL: Used as the database for storing car and customer information.
- Swagger UI: Provides an interactive API documentation and testing interface.
- Spring Security: Ensures secure authentication and authorization for users.
- Gradle: Used for dependency management and building the project.

## Getting Started

1. Clone the repository:
git clone https://github.com/maciej-MKan/car-dealership.git

2. Configure PostgreSQL database settings in `src/main/resources/application.properties`.

3. Build and run the application:
./gradlew bootRun

4. Access the application:

- Web-based UI (Thymeleaf templates): Open your browser and navigate to `http://localhost:8190/car-dealership`.
- REST API documentation (Swagger UI): Open your browser and go to `http://localhost:8080/swagger-ui.html`.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

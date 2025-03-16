# Spring Boot REST CRUD Application

## Project Overview

This project is a **RESTful CRUD application** developed using **Spring Boot**. It demonstrates the fundamental principles of creating a REST API that allows users to perform **Create, Read, Update, and Delete (CRUD)** operations. The application is designed to provide a simple interface to interact with a database.

## Features

- **Create**: Add new records to the database.
- **Read**: Retrieve and display records.
- **Update**: Modify existing records.
- **Delete**: Remove records from the database.

## Technologies Used

- **Spring Boot**: For building the backend application.
- **Java**: The programming language used for development.
- **H2 Database** (or other database of choice): For storing and managing data.
- **Maven**: For dependency management and building the application.
- **Postman** (or equivalent): For testing the API endpoints.

## Setup and Installation

### Prerequisites

- **Java 8 or higher** installed.
- **Maven** for project dependencies and builds.
- **IDE** (e.g., IntelliJ IDEA, Eclipse) or a text editor for code editing.

### Steps to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repository.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-repository
    ```

3. Build the project using Maven:
    ```bash
    mvn clean install
    ```

4. Run the application:
    ```bash
    mvn spring-boot:run
    ```

5. The application will be available at:
    ```
    http://localhost:8080
    ```

## API Endpoints

| HTTP Method | Endpoint            | Description               |
|-------------|---------------------|---------------------------|
| **POST**    | `/api/items`         | Create a new item.        |
| **GET**     | `/api/items`         | Get a list of all items.  |
| **GET**     | `/api/items/{id}`    | Get an item by ID.        |
| **PUT**     | `/api/items/{id}`    | Update an existing item.  |
| **DELETE**  | `/api/items/{id}`    | Delete an item by ID.     |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ScreenShots

![update2](https://github.com/user-attachments/assets/64abc686-1733-47aa-9e1c-94fceaf8d4ee)


![list3](https://github.com/user-attachments/assets/f779a242-f512-4402-a28a-b3b81b4b9de6)


![Ekran görüntüsü 2025-03-16 233119](https://github.com/user-attachments/assets/cdf7477e-1c65-4d37-a4f5-cf2465d2d599)






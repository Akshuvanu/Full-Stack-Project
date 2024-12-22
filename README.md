# Todo List RESTful API

A simple Todo List application built with Java Spring Boot and Angular. This project implements a RESTful API to manage tasks (todos) with basic CRUD operations.

## Features

- **Create**: Add new tasks to your todo list.
- **Read**: View all tasks or a specific task by ID.
- **Update**: Edit existing tasks.
- **Delete**: Remove tasks from the list.

## Technologies Used

- **Backend**: Java, Spring Boot
- **Frontend**: Angular
- **Database**: MySQL 
- **Build Tool**: Maven

## Prerequisites

- Java 8 or higher
- Maven
- Node.js (for frontend development)
- Angular CLI (for frontend development)

Here’s the markdown format for the specified part:

## Backend Setup (Spring Boot)

## Backend Setup (Spring Boot)

1. Build the backend project:

    mvn spring-boot:run

   The backend will be available at http://localhost:8080.

## Frontend Setup (Angular)
Navigate to the frontend directory:


cd frontend

## Install Dependicies:

npm install

## Run the Angular Application

ng serve

The frontend will be available at http://localhost:4200.

## Endpoints

- **GET** `/api/tasks`: Retrieve all tasks
- **GET** `/api/tasks/{id}`: Retrieve a specific task by ID
- **POST** `/api/tasks`: Create a new task
- **PUT** `/api/tasks/{id}`: Update an existing task by ID
- **DELETE** `/api/tasks/{id}`: Delete a task by ID


## Contributing:
Feel free to fork the project and submit pull requests. You can also report issues or suggest features.




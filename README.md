# Express Tasks API

A RESTful API built with Node.js and Express.js to manage tasks using CRUD operations. This project demonstrates HTTP methods, route parameters, JSON request and response handling, and basic error handling.

## Features

- **GET** — Retrieve all tasks.
- **POST** — Create a new task.
- **PUT** — Update an existing task.
- **DELETE** — Delete a task.
- Route parameters for identifying individual tasks.
- JSON responses and request body handling.
- Basic input validation and error handling.

## Technologies Used

- Node.js
- Express.js
- JavaScript
- REST API
- JSON

## Installation

### 1. Clone the Repository

```bash
git clone " https://github.com/MuskanAzeem01/express-tasks-api.git"
```

### 2. Navigate to the Project Folder

```bash
cd express-tasks-api
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Server

```bash
node server.js
```

The server will start on the port configured in `server.js`.

## API Endpoints

| Method | Endpoint            | Description         |
| ------ | ------------------- | ------------------- |
| GET    | `/api/v1/tasks`     | Retrieve all tasks  |
| POST   | `/api/v1/tasks`     | Create a new task   |
| PUT    | `/api/v1/tasks/:id` | Update a task by ID |
| DELETE | `/api/v1/tasks/:id` | Delete a task by ID |

## Testing

You can test the API endpoints using Postman or another API testing tool by sending HTTP requests and checking the JSON responses.

## Data Storage

Tasks are stored in an in-memory JavaScript array. This means the data resets when the server restarts. No database is configured in this project.

## Learning Objectives

This project helped me practice:

- Building RESTful APIs with Express.js.
- Working with HTTP methods.
- Handling route parameters.
- Processing JSON request bodies.
- Sending appropriate HTTP status codes and responses.
- Implementing basic validation and error handling.

## Author

**Muskan Azeem**

BSCS Student | Aspiring Full-Stack Developer

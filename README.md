# Task CRUD API

A simple REST API built using Node.js and Express.js that performs CRUD (Create, Read, Update, Delete) operations on tasks.

## Features

- Get all tasks
- Get a task by ID
- Create a new task
- Update a task
- Delete a task

## Tech Stack

- Node.js
- Express.js

## Installation

```bash
npm install
```

## Run the project

```bash
node server.js
```

The server runs at:

```
http://localhost:3000
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | / | API information |
| GET | /health | Health check |
| GET | /tasks | Get all tasks |
| GET | /tasks/:id | Get task by ID |
| POST | /tasks | Create a new task |
| PUT | /tasks/:id | Update a task |
| DELETE | /tasks/:id | Delete a task |

## Sample POST Request

```json
{
  "title": "Learn Express"
}
```

## Author

Kavya Ay

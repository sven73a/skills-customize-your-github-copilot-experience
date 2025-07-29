# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will have built a simple API that can handle basic CRUD operations.

## 📝 Tasks

### 🛠️ Set Up FastAPI Project

#### Description
Set up a new Python project and install FastAPI and Uvicorn. Create a basic FastAPI application that runs a simple server.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn using pip
- Create a main Python file (e.g., `main.py`) with a FastAPI app
- Add a root endpoint (`/`) that returns a welcome message


### 🛠️ Implement CRUD Endpoints

#### Description
Expand your FastAPI app to support Create, Read, Update, and Delete operations for a resource (e.g., items, books, or users).

#### Requirements
Completed program should:

- Define a Pydantic model for your resource
- Implement endpoints for:
  - Creating a new resource (POST)
  - Reading all resources (GET)
  - Reading a single resource by ID (GET)
  - Updating a resource by ID (PUT)
  - Deleting a resource by ID (DELETE)
- Return appropriate status codes and JSON responses


### 🛠️ (Optional) Add Extra Features

#### Description
Enhance your API with additional features for a more robust experience.

#### Requirements
Completed program could:

- Add input validation and error handling
- Use an in-memory list or dictionary to store resources
- Add OpenAPI documentation (FastAPI provides this by default)
- Allow filtering or searching resources by a field

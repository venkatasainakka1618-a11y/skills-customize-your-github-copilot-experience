# 📘 Assignment: REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple web API using the FastAPI framework in Python. Students will create endpoints to handle basic CRUD operations and test them using HTTP requests.

## 📝 Tasks

### 🛠️ Set up FastAPI Project

#### Description
Initialize a new FastAPI application and run a development server.

#### Requirements
Completed project should:

- Install FastAPI and an ASGI server such as Uvicorn
- Create a `main.py` file with a FastAPI instance
- Include a root endpoint (`/`) that returns a welcome message
- Be able to start the server and receive responses from the root endpoint

### 🛠️ Create CRUD Endpoints

#### Description
Add additional routes to manage a simple in-memory list of items.

#### Requirements
Completed application should:

- Define endpoints for creating, reading, updating, and deleting items
- Use path parameters and request bodies appropriately
- Return JSON responses with proper status codes
- Demonstrate the endpoints by showing example `curl` or HTTP requests

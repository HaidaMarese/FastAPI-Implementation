# FastAPI Assignment

## Description
This project is a simple FastAPI application that demonstrates basic API functionality, including GET and PUT requests. It includes endpoints to retrieve and update items.

## Features
- **GET /**: Returns a greeting message.
- **GET /items/{item_id}**: Retrieves an item by ID, optionally including a query parameter.
- **PUT /items/{item_id}**: Updates an item with new data.

## Requirements
- Python 3.12
- FastAPI
- Uvicorn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/HaidaMarese/FastAPI-Implementation.git
   cd FastAPI-Implementation

## Usage
You can test the API using `curl` commands:

To get a greeting message:
```bash
curl http://127.0.0.1:8000/

To retrieve an item by ID (replace `{item_id}` with an actual ID):
```bash
curl http://127.0.0.1:8000/items/{item_id}

To update an item (replace `{item_id}` with an actual ID):
```bash
curl -X PUT http://127.0.0.1:8000/items/{item_id} -H "Content-Type: application/json" -d '{"key": "value"}'
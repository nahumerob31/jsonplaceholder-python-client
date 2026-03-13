# jsonplaceholder-python-client

A Python client library for the JSONPlaceholder API.

## Description
This library provides convenient Python functions to interact with the JSONPlaceholder fake REST API. It supports the main resource endpoints:
- `/posts`
- `/comments`
- `/albums`
- `/photos`
- `/todos`
- `/users`

Operations include:
- **GET**: Retrieve single resources or list all resources.
- **POST**: Create new resources (simulated).
- **PUT**/**PATCH**: Update existing resources (simulated).
- **DELETE**: Delete resources (simulated).
- Filtering via query parameters (e.g., `?userId=1`).
- Nested routes such as `/posts/{id}/comments`, `/users/{id}/albums`, etc.

The client abstracts HTTP requests and returns parsed JSON data, making it easy to integrate into Python applications.

## Maintainer
- **[@nahumerob31](https://github.com/nahumerob31)**

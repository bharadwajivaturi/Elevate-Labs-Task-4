# Elevate-Labs-Task-4

# User Management API with Flask and Ngrok

A simple RESTful API for user management with Ngrok integration for public access.

## Features
- CRUD operations for users
- In-memory database
- Ngrok integration for public URL
- Interactive web interface
- RESTful endpoints

## API Endpoints
- `GET /` - Home page with API documentation
- `GET /users` - List all users
- `GET /users/<id>` - Get specific user
- `POST /users` - Create new user
- `PUT /users/<id>` - Update user
- `DELETE /users/<id>` - Delete user

## Setup
The following libraries are required:

Flask: A lightweight web framework for Python.
pyngrok: A Python wrapper for ngrok, which creates secure tunnels to expose local servers to the internet.
flask-ngrok: Integrates ngrok with Flask applications.

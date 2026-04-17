# Docker Compose Multi-Service App

## Project Overview

This project demonstrates a simple multi-container application using Docker Compose.

It includes a frontend served by Nginx and a backend API built with Flask.
The frontend communicates with the backend to retrieve and display data.

---

## Architecture

Frontend (Nginx) -> Backend (Flask API)

---

## Technologies Used

- Docker
- Docker Compose
- Nginx
- Python (Flask)
- HTML / JavaScript

---

## How It Works

1. The user opens the frontend (port 8080)
2. The frontend sends a request to the backend API
3. The backend returns a response
4. The frontend displays the message on the page

--- 

## How to Run the Project

docker-compose up --build

## Challenges Faced

- Fixing Dockerfile naming issues (case sensivity)
- Debugging container build errors
- Handling frontend-backend communication
- Resolving CORS policy errors



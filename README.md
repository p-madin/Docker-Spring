# Spring Boot Docker Container

A basic Java Spring Boot application containerized with Docker.

## Project Structure

- `src/`: Java source code.
- `pom.xml`: Maven configuration for building the application.
- `Dockerfile`: Multi-stage Dockerfile for building and running the app.
- `docker-compose.yml`: Simple definition to run the app with Docker Compose.

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Running the Application

1. Build and start the container:
   ```bash
   docker-compose up -d --build
   ```

2. Access the application at:
   [http://localhost:8080/](http://localhost:8080/)

3. Stop the container:
   ```bash
   docker-compose down
   ```

## API Endpoints

- `GET /`: Returns a simple greeting message.

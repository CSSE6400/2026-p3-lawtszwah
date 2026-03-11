# Todo API

This project containerises a Flask Todo API using Docker and Docker Compose.

## Features

- Flask-based Todo API
- Docker support for running the application in a container
- Docker Compose support for running the application with PostgreSQL

## Project Structure

- `todo/` - application source code
- `Dockerfile` - builds the application image
- `docker-compose.yml` - runs the application and PostgreSQL together
- `tests/` - test files

## Run with Docker

Build the image:

```bash
docker build -t todo .
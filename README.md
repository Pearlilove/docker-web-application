# Dockerized Web Application

## Project Overview

This project demonstrates how to package and run a static HTML
website using Docker and NGINX.

The website is served from inside a Docker container, allowing it
to run in an isolated and repeatable environment.

## Technologies Used

- Ubuntu on WSL
- Docker Desktop
- Docker
- NGINX
- HTML

## Project Files

- `index.html` — the website content.
- `Dockerfile` — instructions for building the Docker image.
- `README.md` — project documentation.

## Build the Docker Image

```bash
docker build -t pearl-docker-web .


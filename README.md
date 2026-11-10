
# CodeAlpha Docker Web Server

## Project Overview
A web server deployed inside a Docker container
using the Nginx Alpine image.

## Technologies
- Docker
- Docker Compose
- Nginx
- HTML
- CSS
- Linux

## Features
- Docker image creation
- Nginx web server
- Container deployment
- Port mapping
- Automatic restart policy
- Container health check

## Run the Project

Build and start:

```bash
docker compose up -d --build
```

Open in browser:

http://localhost:8080

Check containers:

```bash
docker ps
```

Check logs:

```bash
docker logs codealpha-webserver
```

Check health:

```bash
docker inspect --format='{{.State.Health.Status}}' codealpha-webserver
```

Stop:

```bash
docker compose down
```

## Internship
CodeAlpha DevOps Internship - Task 4

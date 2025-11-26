# Midterm Project (Flask + Nginx + Docker)

This project runs a Flask backend and Nginx frontend using Docker Compose.

## Run the Project
```bash
docker compose build
docker compose up
```

Open in browser:
```
http://localhost:8080
```

## Test API
```bash
curl http://localhost:8080/api/
curl http://localhost:8080/api/log
```

## Rebuild Backend (Task 7)
```bash
docker compose build backend
docker compose up
```

## Cleanup (Task 8)
```bash
docker compose down
docker ps -a
docker images
```

# Dockerised Node App

Express application created with `express-generator` running in Docker with Docker Compose.

## 1: Build

```sh
COMPOSE_DOCKER_CLI_BUILD=1 DOCKER_BUILDKIT=1 docker-compose build
```

## 2: Run

```sh
docker-compose up
```

Sources:
1. https://docs.docker.com/compose/
2. https://blog.logrocket.com/node-js-docker-improve-dx/

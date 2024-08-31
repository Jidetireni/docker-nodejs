---

# Docker Node.js Sample

This repository provides a Dockerfile for containerizing a Node.js application with PostgreSQL. Follow these steps to build and run the application using Docker.

## Getting Started

### Prerequisites

- Install [Docker](https://docs.docker.com/get-docker/)
- Install [Docker Compose](https://docs.docker.com/compose/install/)

### Setup

1. Clone the main application repository:

   ```bash
   git clone https://github.com/docker/docker-nodejs-sample.git
   cd docker-nodejs-sample
   ```

2. Clone this repository containing the Dockerfile and Docker Compose file:

   ```bash
   git clone https://github.com/Jidetireni/docker-nodejs.git
   cd docker-nodejs
   ```
3. Move the `Dockerfile` and `compose.yaml` to the main application directory and remove the `docker-nodejs` directory:

   ```bash
   mv Dockerfile ../
   mv compose.yaml ../
   cd ..
   rm -rf docker-nodejs
   ```

4. Build and run the Docker containers:

   ```bash
   docker-compose up -d
   ```

5. Access the application in your browser at [http://localhost:3000](http://localhost:3000).

### Stopping the Containers

To stop the containers without removing them:

```bash
docker-compose stop
```

### Stopping and Removing the Containers

To stop and remove the containers:

```bash
docker-compose down
```
---


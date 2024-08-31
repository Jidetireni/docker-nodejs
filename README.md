---

# Docker Node.js Sample

This repository contains a sample Node.js application containerized with PostgreSQL using Docker.

## Getting Started

### Prerequisites

- Install [Docker](https://docs.docker.com/get-docker/)
- Install [Docker Compose](https://docs.docker.com/compose/install/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/docker/docker-nodejs-sample.git
   cd docker-nodejs-sample
   ```

2. Start the Docker containers:

   ```bash
   docker-compose up -d
   ```

3. Access the application in your browser at [http://localhost:3000](http://localhost:3000)

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


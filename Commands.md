## 🐳 Docker Commands Cheat Sheet

This section contains commonly used Docker commands for building, running, and managing containers.

---

### 🔹 Docker Basics

```bash
# Check Docker version
docker --version

# View system-wide Docker info
docker info
```

---

### 🔹 Image Management

```bash
# List all images
docker images

# Pull image from Docker Hub
docker pull nginx

# Remove image
docker rmi <image_id>
```

---

### 🔹 Container Management

```bash
# List running containers
docker ps

# List all containers (including stopped)
docker ps -a

# Run a container
docker run -d -p 80:80 nginx

# Stop a container
docker stop <container_id>

# Remove a container
docker rm <container_id>
```

---

### 🔹 Building Images

```bash
# Build Docker image
docker build -t my-app .

# Build with specific Dockerfile
docker build -t my-app -f Dockerfile .
```

---

### 🔹 Logs & Debugging

```bash
# View container logs
docker logs <container_id>

# Access container shell
docker exec -it <container_id> /bin/bash
```

---

### 🔹 Cleanup Commands

```bash
# Remove all stopped containers
docker container prune

# Remove unused images
docker image prune

# Remove everything (⚠️ use carefully)
docker system prune -a
```

---

### 🔹 Docker Networking

```bash
# List networks
docker network ls

# Inspect network
docker network inspect <network_name>
```

---

### 🔹 Docker Volumes

```bash
# List volumes
docker volume ls

# Create volume
docker volume create my-volume

# Inspect volume
docker volume inspect my-volume
```

---

### 💡 Tip

Use `docker --help` or `docker <command> --help` to explore more options.

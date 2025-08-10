# 🐳 Docker Command Cheatsheet

A quick reference for commonly used Docker commands.

---

## 1️⃣ Basic Commands
| Command | Description |
|---------|-------------|
| `docker --version` | Show Docker version |
| `docker info` | Show system-wide Docker info |
| `docker help` | List available Docker commands |

---

## 2️⃣ Images
| Command | Description |
|---------|-------------|
| `docker images` | List all local images |
| `docker pull <image>` | Download an image from Docker Hub |
| `docker build -t <name>:<tag> .` | Build image from Dockerfile |
| `docker rmi <image>` | Remove image |
| `docker tag <image> <repo>:<tag>` | Tag image for repo |
| `docker save -o <file>.tar <image>` | Save image to tar file |
| `docker load -i <file>.tar` | Load image from tar file |

---

## 3️⃣ Containers
| Command | Description |
|---------|-------------|
| `docker ps` | List running containers |
| `docker ps -a` | List all containers (including stopped) |
| `docker run <image>` | Run a container |
| `docker run -it <image> bash` | Run interactively with bash shell |
| `docker run -d <image>` | Run in detached mode |
| `docker start <container>` | Start stopped container |
| `docker stop <container>` | Stop running container |
| `docker restart <container>` | Restart container |
| `docker rm <container>` | Remove container |
| `docker logs <container>` | View logs |
| `docker exec -it <container> bash` | Exec into running container |

---

## 4️⃣ Volumes
| Command | Description |
|---------|-------------|
| `docker volume ls` | List volumes |
| `docker volume create <name>` | Create volume |
| `docker volume inspect <name>` | Inspect volume |
| `docker volume rm <name>` | Remove volume |
| `docker run -v <volume>:/path/in/container <image>` | Mount volume in container |

---

## 5️⃣ Networks
| Command | Description |
|---------|-------------|
| `docker network ls` | List networks |
| `docker network create <name>` | Create network |
| `docker network inspect <name>` | Inspect network |
| `docker network connect <network> <container>` | Connect container to network |
| `docker network disconnect <network> <container>` | Disconnect container from network |

---

## 6️⃣ Cleanup
| Command | Description |
|---------|-------------|
| `docker system prune` | Remove unused data |
| `docker system prune -a` | Remove unused containers, images, networks |
| `docker rm $(docker ps -aq)` | Remove all containers |
| `docker rmi $(docker images -q)` | Remove all images |

---

## 7️⃣ Docker Compose
| Command | Description |
|---------|-------------|
| `docker-compose up` | Start services |
| `docker-compose up -d` | Start in detached mode |
| `docker-compose down` | Stop and remove containers, networks, volumes |
| `docker-compose build` | Build images |
| `docker-compose logs` | View logs |
| `docker-compose exec <service> bash` | Exec into service container |

---

💡 **Tip:** Use `--help` after any Docker command to see all available options.

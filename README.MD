# Docker Resources

A collection of Docker-related resources, documentation, and helpful materials for learning and working with Docker.

## Contents

- **docker_cheatsheet.pdf** - A comprehensive cheatsheet covering Docker commands, concepts, and best practices.

## About Docker

Docker is a containerization platform that allows you to package applications and their dependencies into lightweight, portable containers. These containers can run consistently across different environments.

## Key Features

- **Containerization** - Package applications with all dependencies
- **Portability** - Run containers anywhere Docker is installed
- **Isolation** - Applications run in isolated environments
- **Efficiency** - Lightweight compared to virtual machines
- **Scalability** - Easy to scale applications horizontally

## Getting Started

1. Install Docker from [docker.com](https://www.docker.com)
2. Verify installation: `docker --version`
3. Run your first container: `docker run hello-world`

## Resources in This Repository

### Docker Cheatsheet
The included cheatsheet provides quick references for common Docker commands and operations including:
- Image management
- Container lifecycle
- Networking
- Volumes and data persistence
- Compose operations
- And more

## Common Docker Commands

```bash
# Image operations
docker build -t image-name .
docker pull image-name
docker push image-name

# Container operations
docker run -d -p 8080:80 image-name
docker ps
docker stop container-id
docker logs container-id

# Cleanup
docker rm container-id
docker rmi image-id
```

## Learning Resources

- [Official Docker Documentation](https://docs.docker.com/)
- [Docker Hub](https://hub.docker.com/)
- Docker Cheatsheet (included in this repository)

## Contributing

Feel free to add more resources, cheatsheets, or documentation to improve this collection.

## License

This repository contains educational resources for Docker learning and reference.

---

**Last Updated:** January 2026

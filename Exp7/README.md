# Experiment 7 - Docker

## Aim
To install Docker and execute basic Docker commands for managing Docker images and containers.

## Docker Installation
Docker Desktop was installed successfully on Windows using the WSL 2 backend.

## Commands Performed

```text
docker --version
docker info
docker search ubuntu
docker pull ubuntu
docker images
docker run ubuntu
docker run -it ubuntu bash
docker ps
docker ps -a
docker start <container-id>
docker stop <container-id>
docker rm <container-id>
docker rmi ubuntu

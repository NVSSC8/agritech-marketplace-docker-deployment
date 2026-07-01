# AgriTech Marketplace - Docker Deployment

This repository contains the Docker-based implementation and learning notes for the AgriTech Marketplace project.

## Documents

- `docker_implementation_guide.pdf` - clean implementation guide for GitHub upload

## What is included

- Frontend container using Nginx
- Backend container using Spring Boot
- MySQL container for data storage
- Docker Compose orchestration
- Docker Hub image publishing
- Validation screenshots from the VM

## Ports used

- `80` - frontend
- `8080` - backend
- `3306` - MySQL

## Quick run flow

```bash
cd /opt/agritech/docker-compose
docker-compose down
git pull
docker-compose up -d --build
docker ps
```

## Notes

- Use the implementation PDF for the clean architecture and final deployment steps.
- Use the learning PDF for mistakes, symptoms, and fixes.

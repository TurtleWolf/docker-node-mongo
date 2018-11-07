# Docker: Node & MongoDB sample
### (from devops, to production)

> Simple example of a dockerized Node/Mongo app

## Quick Start  
```bash
# assuming NodeJS & Docker are installed locally  
npm install  
docker-compose up -d  
# -d : to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```

## Production  
```bash

# Run in Docker
docker-compose -f docker-compose-production.yml up -d --build
```

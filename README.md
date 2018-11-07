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

[Docker: Dev to Production playlist](https://www.youtube.com/playlist?list=PLETG2T1KvniqIEU_xkadLpugT8nhmNxSR "Easy Docker Dev to Production Setup for Small Projects")   
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")  
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")  
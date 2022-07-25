# Expense Tracker Docker compose

## Setup
- Place tracker-local-docker in the same directory as other services

## Database setup
- Create dump/restore folder for sql files to be mounted on mariadb service
- Retrieve .env from kevin
- Set database user host to % for development purposes

## Core setup
- Retrieve .env.core from kevin
- For developmental purposes, npm run build in expense-tracker and restart services to see changes

## Run containers
- docker-compose -d 

## Execute containers
- docker container exec -ti <container id> sh

## Container logs
- docker container logs <container id>

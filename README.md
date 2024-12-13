# Node.js Dockerized App

The app serves a basic "Welcome" message and is set up to run in a containerized environment.

## Features

- Node.js application with Express
- Dockerized for easy deployment
- Configurable port through environment variables

## Requirements

- Docker installed on your system
- Node.js
- 
## Setup Instructions

### Clone the Repository

```bash
git clone https://github.com/mehakbasrani/node-docker-app.git
cd node-docker-app

## build the docker image
docker build -t node-docker-app .

##Run the docker container
docker run -p 8080:8080 node-docker-app

##Access the docker application
http://localhost:8080


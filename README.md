# Run Jenkins in a Docker container

### Prerequisites
- [Install Docker](https://docs.docker.com/engine/install/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

---

## Build
To build a new docker image from the Dockerfile, run:

`docker build -t opofa/jenkins .`

## Start

To start the server run:

`docker-compose -f docker-compose.yml up -d`

then open the your favorite browser and type:

http://localhost:8080

## Stop

To stop the server run:

`docker-compose -f docker-compose.yml down`

---

Alternatively, on Linux

run  `./run-jenkins.sh`  to start the server

and  `./stop-jenkins.sh`  to stop it


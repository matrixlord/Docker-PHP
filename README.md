# Docker for PHP

A very lightweight, in terms of maintenance, docker configuration for PHP.
For personal use mainly.

# Installation
Requirements
- You need to have [Docker](https://docs.docker.com/engine/installation/) installed

Run in root folder,
~~~~
cp .env.example .env
docker-compose build && docker-compose up -d
~~~~

Login to the container,
~~~~
docker exec -it app_server /bin/bash -c "TERM=$TERM exec bash"
~~~~

# By
Well....me
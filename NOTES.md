# Gentle intro to Docker

## What is Docker?

- setup/run development environment and dependencies
- install/run production environment and dependencies

## Terms

- Host Machine

- Images + Containers
  - image = blueprint
  - container = house, ephemeral, 'stateless'

- Dockerfile
  - Instructions = for the startup process

- Volume
  - data stores!

- Docker Compose
- Docker Hub

## A Docker 'Hello World'

- add a Dockerfile
- run the Dockerfile as: `docker run --interactive --tty <image id> <process|/bin/bash>`

### Q&A Notes

- 'I do not know'

## Some Commands

- Cleaning up: `docker rmi -f <image id>` (-f = force)

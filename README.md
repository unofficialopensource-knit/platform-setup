platform_setup
==============

### Intro
This repo is to be used for setting up system service dependency for any project.

### Pre-Requisites
1. `docker` installed on the system
2. `docker-compose` installed on the system
3. `git` installed on the system

### Setup
1. Since all services use the prebuilt images there is no build step.
2. To start all the services at once use `docker-compose up --detach`.
3. To start particular services use `docker-compose up --detach SERVICE`.

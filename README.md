# Hitech Market
## Installation
Install [docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/#install-compose) on machine \
Clone the repository with the --recurse-submodules flag to also load the submodule repositories

## Launch
```sh
docker-compose up --build -d
```
Application will be able locally
  * web: [localhost](http://localhost:80)
  * api: [localhost:8248](http://localhost:8248)
  * docs: [localhost:8248/api/docs](http://localhost:8248/api/docs)

## Shutdown
After using application follow `docker-compose down` to delete containers \
Or `docker-compose stop` to stop containers

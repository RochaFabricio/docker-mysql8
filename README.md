# Docker container MySQL8

Creating MySQL 8 docker container.

## Installation

You need [docker](https://www.docker.com/get-started) installed.

## Usage

```docker
# Remove existing data
  rm -rf ./docker/db/data/*

# Creating MySQL 8 docker container 
  docker-compose up --build -d

# Verify if docker container is up
  docker-compose ps
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

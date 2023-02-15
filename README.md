
# docker-nginx-php

Docker container for execute Nginx, PHP and [GLPI](https://glpi-project.org/pt-br/)



## Requieriments
Inside of Documents directory or another directory of your preferences create thease thwo folders


- **docker** - There we cloning of this repository
- **www** - There we put the site folders

## Setup .env

Rename the .env.example to .env
```bash
  cp -av .env{.example,}
```

> Set the WWW_FOLDER variable on .env file

## Deploy

To deploy, navigate to **docker/docker-nginx-php** and execute

```bash
  docker compose up -d --build
```


## Access

http://localhost:8080

# Dockerized Mongo Express.js using ES6
[![Build Status](https://travis-ci.org/mrpatiwi/express-mongo-docker.svg)](https://travis-ci.org/mrpatiwi/express-mongo-docker)

## Getting Started
Install dependencies
```sh
$ npm install
```

## Run using Docker-Compose
```sh
$ docker-compose up -d
```

### Scaling
```sh
$ docker-compose scale web=3
$ docker-compose up --force-recreate -d
```

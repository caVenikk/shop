# Online food shop

## Table of contents

- [General info](#general-info)
- [Technologies](#technologies)
- [Setup](#setup)
- [Implementation example](#implementation-example)

## General info

This project is web application integrated in Telegram bot for an online food store.
In this bot you can order imaginary (possibly real in the future) food.
Web app and bot using API to get all available products and info about users and orders.

## Technologies

Project is created with:

- Python 3.11
- Javascript (Vue.js)
- PostgreSQL

## Setup

Firstly, install docker and docker-compose (Ubuntu):

[Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
[How To Install and Use Docker Compose on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04)

Next step is executing two commands, that will build and run app:

```
$ docker-compose build
$ docker-compose up -d
```

or

```
$ docker-compose build && docker-compose up -d
```

## Implementation example

[McBonald's](https://t.me/mcbonalds_bot)

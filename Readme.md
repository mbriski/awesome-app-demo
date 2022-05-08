# Docker setup

This is the readme for the setup of Awesome apps.

## Prerequisites

1. [Docker](https://www.docker.com/)
3. [Docker-compose](https://docs.docker.com/compose/)

## Apps

All three apps are located in the ./apps folder, each app in its subfolder.

Awesome app1 returns its own name.
Awesome app2 has the ability to create a database table and insert some data.
Awesome app3 can read from the database and display the output.

## Setup

Update .env file with database host
Build and start the app containers up run

```bash
docker-compose up -d --build
```

This should create and start app containers - `docker-app` .



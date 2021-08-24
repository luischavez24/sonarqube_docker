# Sonarqube with Docker

This a sample project get up a Sonarqube and PostgreSQL instances using Docker and Docker Compose


## How to run it

1. Open PowerShell or Command Prompt in the root folder and execute

``` bash
$ docker-compose up
```

2. Wait til the containers are up and then go to http://localhost:9000


## If you are using WSL (Windows Subsystem for Linux)

1. Run the following commands before start the containers

``` bash

$ wsl -d docker-desktop

$ sysctl -w vm.max_map_count=262144

2. Restart docker service

```
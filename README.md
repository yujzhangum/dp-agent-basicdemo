# This is a simplest demo of deeppavlov agent

It consists of two dummy skills in line alongside with built-in rule based skill selector.
Runs with docker-compose

## Files content

* **pipeline_conf.json** - example of pipeline configuration file
* **db_conf.json** - db configuration, which works with docker-compose provided

## Requirements

* [Docker](https://www.docker.com/products/docker-desktop) 
* [Docker-compose](https://docs.docker.com/compose/install/)

## Running the demo

```bash
docker-compose up --build
```

Api will run on *localhost:4242/*

All dialogs wlii be saved in **dp-agent** database, running in **mongo** container.

# Jupyter docker-compose

Quick and basic docker-compose setup for a local jupyter notebooks.

## Features

* Quick
* Easy
* Includes a typo

## Usage

Start with `docker-compose up` or  `docker-compose up -d` for detached mode.

Installing extra packs: `docker-compose exec jupter pip install markovify`

If you desire a different base image just swap it out in the compose file, for example: jupyter/datascience-notebook. 
## Misc

Q: How is this better than just `docker run -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/minimal-notebook`

A: It's really not I just find docker-compose more convenient.

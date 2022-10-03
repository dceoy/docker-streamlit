docker-streamlit
================

Dockerfile for Streamlit

[![CI to Docker Hub](https://github.com/dceoy/docker-streamlit/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/dceoy/docker-streamlit/actions/workflows/docker-publish.yml)

Docker image
------------

Pull the image from [Docker Hub](https://hub.docker.com/r/dceoy/streamlit/).

```sh
$ docker image pull dceoy/streamlit
```

Usage
-----

Run streamlit

```sh
$ docker container run --rm -p 8501:8501 -v ${PWD}:/wd -w /wd \
    dceoy/streamlit hello
```

Run streamlit with docker-compose

```sh
$ docker-compose -f /path/to/docker-streamlit/docker-compose.yml up
```

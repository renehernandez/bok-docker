# Bok_Docker

This repo contains a set of *docker-compose* files that can be used to have running in a ghost blog in a server.

## Using .env file

The compose files use environment variables declared in an [env file](https://docs.docker.com/compose/env-file/).

## Ngixn Compose

Following the ideas from the post [Automated Nginx Reverse Proxy for Docker/](http://jasonwilder.com/blog/2014/03/25/automated-nginx-reverse-proxy-for-docker/), this compose file allows to automatically register with nginx multiple containers on demand. It provides HTTPS support with letsencrypt

## Blog Compose

Compose file for running the [ghost blog](https://ghost.org/) using the [bitknown theme](https://github.com/renehernandez/BitKnown)

## Jenkins Compose

Compose file for running a [jenkin ci](https://jenkins.io/)


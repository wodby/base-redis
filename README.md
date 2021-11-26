# About this Repo

[![Build Status](https://github.com/wodby/base-redis/workflows/Build%20docker%20image/badge.svg)](https://github.com/wodby/base-redis/actions)
[![Docker Pulls](https://img.shields.io/docker/pulls/wodby/base-redis.svg)](https://hub.docker.com/r/wodby/base-redis)
[![Docker Stars](https://img.shields.io/docker/stars/wodby/base-redis.svg)](https://hub.docker.com/r/wodby/base-redis)
[![Docker Layers](https://images.microbadger.com/badges/image/wodby/base-redis.svg)](https://microbadger.com/images/wodby/base-redis)

This repository is a fork of https://github.com/docker-library/redis with a few changes:

* Only alpine-based images
* All images based on [alpine](https://github.com/wodby/alpine) 3.13 version due to [this](https://github.com/alpinelinux/docker-alpine/issues/182) change in 3.14 that prevents us from running it on older docker versions

## Docker Images

* All images based on Alpine Linux
* Base image: [wodby/alpine](https://github.com/wodby/alpine)
* [Docker Hub](https://hub.docker.com/r/wodby/base-redis)

Supported tags and respective `Dockerfile` links:

* `6.2.6`, `6.2`, `6`, `latest` [_(Dockerfile)_](https://github.com/wodby/base-redis/tree/master/6.2/alpine/Dockerfile.wodby)
* `6.0.16`, `6.0` [_(Dockerfile)_](https://github.com/wodby/base-redis/tree/master/6.0/alpine/Dockerfile.wodby)
* `5.0.14`, `5.0`, `5` [_(Dockerfile)_](https://github.com/wodby/base-redis/tree/master/5/alpine/Dockerfile.wodby)

All images built for `linux/amd64` and `linux/arm64`

[![Build Status](https://cloud.drone.io/api/badges/jones2026/nginx-artifactory-cache/status.svg)](https://cloud.drone.io/jones2026/nginx-artifactory-cache)
[![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/jones2026/nginx-artifactory-cache)](https://hub.docker.com/r/jones2026/nginx-artifactory-cache/tags?page=1&ordering=last_updated)
[![Docker Pulls](https://img.shields.io/docker/pulls/jones2026/nginx-artifactory-cache)](https://hub.docker.com/r/jones2026/nginx-artifactory-cache)


# nginx-artifactory-cache

``` bash
docker build -t cache .
docker run --rm -v (pwd)/cache:/data/nginx/cache -p 80:80 -p 443:443 cache
```
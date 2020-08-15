# NodeJS image with Alpine Linux

> for Docker lightweight containers - image size is about 90 Mb

## Building image

```en
docker build -t node .
```

## How to use

```en
# add to your Dockerfile
FROM <your docker registry URL>/node:latest
```

## Configuration

Update this line to install necessary version of NodeJS, npm and Yarn.

```en
# Set env variables
ENV NODE_VERSION="14.8.0" NPM_VERSION="6.14.7" YARN_VERSION="1.22.4"
```

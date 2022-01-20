## Prerequisites
* A functioning [Docker](https://docs.docker.com/get-docker/) installation


## Cloning the repository
```console
git clone https://github.com/armyguy255a/openfirelivedemo.git
```

## Building
In order to build the container, clone this repository first.

```console
docker build --tag armyguy255a/openfire:4.6.4 --build-arg OPENFIRE_VERSION=4_6_4 .
```
## Running

### Docker CLI

### Docker Compose
```console
docker compose up -d
```

### Locally

docker run -d -p 9090:9090 armyguy255a/openfire:4.6.4

docker-compose up
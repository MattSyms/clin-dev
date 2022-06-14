# CLIN Development Stack

## Requirement

- [Docker](https://www.docker.com)

## Setup

Create the .env file :

```
cp .env.sample .env
```

Deploy stack :

```
docker compose up -d
```

## Containers

Get portal-ui container shell :

```
docker compose exec portal-ui sh
```

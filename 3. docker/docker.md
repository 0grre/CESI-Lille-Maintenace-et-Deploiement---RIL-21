# Docker

## Installation

Follow [documentation]('https://www.docker.com/)

## Exercises

### 1st lab

```
docker run --rm bash echo "Hello World"
```

### 2nd lab: create an airbnb API

```
docker run -d -p 80:80 -v db.json:/data/db.json clue/json-server
```

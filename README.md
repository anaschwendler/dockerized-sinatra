# Dockerized (without compose) Sinatra

This repo use this article as base: https://www.codewithjason.com/dockerize-sinatra-application/

## Running the project

### Building the Docker Image

```
docker build --tag hello .
```

### Running the Docker Image

```
docker run -p 80:4567 hello
```

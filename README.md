# blog-api-swagger

## Setup
### Install docker and npm
```bash
$ sudo apt install -y docker.io docker-compose npm
```
### Install swagger-cli
```bash
$ sudo npm install -g @apidevtools/swagger-cli
```

## Build swagger json file
```bash
$ swagger-cli bundle -o index.json blog/main.yml
```

## Run swagger-ui locally
```bash
$ docker-compose up
```

Browse to http://localhost to interacte with the api.
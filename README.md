# kong-example

## Starting kong
```
KONG_DOCKER_TAG=kong:3.3.1 docker-compose up -d
```

## Making requests
```
curl 127.0.0.1:8000/api/v1 -H'Host: circleci.com'
```

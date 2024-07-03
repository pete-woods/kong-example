# kong-example

## Starting kong
```
docker-compose up -d
```

## Making requests
```
curl 127.0.0.1:8000/api/v1 -H'Host: circleci.com'
```

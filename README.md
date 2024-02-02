# Docs

## Prerequisites

1. unzip file
2. `cd dns_prototype`

> **_NOTE:_** network.testnet.local has to be available

## Run

`docker load < dns-prototype-app.tar.gz` + `docker compose up`

## Stop

`docker compose down`

## Use

#### Add record

```curl
curl --request PUT \
  --url http://localhost:9090/testdomain.i2p/sdfsfsdfsdfsfddsfsdfsfsdfsdfsfdddfsfddsfsssdfdfdfddf
```

#### Query record

```curl
curl --request GET \
  --url http://localhost:9090/testdomain.i2p
```

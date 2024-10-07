# Overview

Sample Docker Compose configuration to run the [Xatu](https://github.com/ethpandaops/xatu) Sentry client.

## How to run

`cp sample.env .env` and edit `.env` 

- set `BN_URL` to the address of your beacon node.

- set `AUTH_TOKEN` to the token provided by the [ethPandaOps](https://github.com/ethpandaops) team.

- optionally configure external docker network using `NETWORK_NAME` and `NETWORK_IS_EXTERNAL` variables

- optionally configure the [Xatu](https://github.com/ethpandaops/xatu) container version using the `XATU_VERSION` variable

## Starting the service

To start the container run: `docker compose up -d`
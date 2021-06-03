# ib-gateway-docker-headless

[![Docker](https://github.com/HMB-research/ib-gateway-docker-headless/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/HMB-research/ib-gateway-docker-headless/actions/workflows/docker-publish.yml)

https://hub.docker.com/repository/docker/industrialninja/ib_gateway

IB Gateway + IbcAlpha + Xvfb on a Docker Container.

Run it:
```
docker container run --env TWS_USERID='YOUR_IB_ACCOUNT' --env TWS_PASSWORD="YOUR_IB_PASSWORD" --env TRADING_MODE=paper ib-gateway:latest
```

or try with `docker-compose up` for quick setup

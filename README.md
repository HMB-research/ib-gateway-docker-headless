# ib-gateway-docker-headless

[![Docker](https://github.com/HMB-research/ib-gateway-docker-headless/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/HMB-research/ib-gateway-docker-headless/actions/workflows/docker-publish.yml)

IB Gateway + IbcAlpha + Xvfb on a Docker Container.

Get it:
```
docker login -u $GITHUB_USERNAME -p $GITHUB_TOKEN docker.pkg.github.com
docker pull docker.pkg.github.com/hmb-research/ib-gateway-docker-headless/ib-gateway:latest
```

Run it:
```
docker container run --env TWSUSERID='YOUR_IB_ACCOUNT' --env TWSPASSWORD="YOUR_IB_PASSWORD" --env TRADING_MODE=paper ib-gateway:latest
```

let's try it

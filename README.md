# jelnoff/dash-core-arm

A Dash Core docker image, compatible with arm arch

## What is Dash?
A Privacy-Centric Crypto-Currency https://www.dash.org

## Usage

```sh
$ docker run --rm -it jelnoff/dash-core-arm \
  -printtoconsole \
  -regtest=1 \
  -rpcallowip=172.17.0.0/16 \
  -rpcpassword=bar \
  -rpcuser=foo
```

OR

Just use docker-compose.yml to run it like `docker-compose up -d`

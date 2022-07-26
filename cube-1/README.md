# Testnet cube-1

[xpla@v0.0.3](https://github.com/c2xdev/xpla/releases/tag/v0.0.3) should be used to run the testnet.

- The genesis event for Pisco-1 testnet will occur **2022-07-25T11:45:00Z (UTC)**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/c2xdev/xpla
$ git checkout v0.0.3
$ make install

$ terrad init [moniker] --chain-id cube-1
$ wget https://raw.githubusercontent.com/c2xdev/testnets/main/cube-1/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```

### Known Peers
```
e30622c9f8668594b0027d9d1e64a7ff68ab6f05@13.125.119.121:26656
```

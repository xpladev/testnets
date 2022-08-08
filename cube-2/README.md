# Testnet cube-2

[xpla@v0.0.4](https://github.com/c2xdev/xpla/releases/tag/v0.0.4) should be used to run the testnet.

- The genesis event for cube-2 testnet will occur **2022-08-08T02:15:00Z (UTC)**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/c2xdev/xpla
$ git checkout v0.0.4
$ make install

$ xplad init [moniker] --chain-id cube-2
$ wget https://raw.githubusercontent.com/c2xdev/testnets/main/cube-2/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```

### Known Peers
```
9ddfac28dc6b28601e3039902ee5a8915dc7891f@3.35.54.221:26656
```

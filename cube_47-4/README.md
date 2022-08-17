# Testnet cube_47-4

[xpla@v0.1.0-rc0](https://github.com/xpladev/xpla/releases/tag/v0.1.0-rc0) should be used to run the testnet.

- The genesis event for cube_47-4 testnet will occur **2022-08-18T01:00:00Z**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/xpladev/xpla
$ git checkout v0.1.0-rc0
$ make install

$ xplad init [moniker] --chain-id cube_47-4
$ wget https://raw.githubusercontent.com/xpladev/testnets/main/cube_47-4/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```

### Known Peers
```
9ddfac28dc6b28601e3039902ee5a8915dc7891f@3.35.54.221:26656
```

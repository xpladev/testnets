# Testnet cube_47-5

[xpla@v0.1.0](https://github.com/xpladev/xpla/releases/tag/v0.1.0) should be used to run the testnet.

- The genesis event for cube_47-5 testnet will occur **2022-08-30T10:00:00Z**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/xpladev/xpla
$ git checkout v0.1.0
$ make install

$ xplad init [moniker] --chain-id cube_47-5
$ wget https://raw.githubusercontent.com/xpladev/testnets/main/cube_47-5/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```

### Known Peers
```
ea7ef4864a9835d9a311ef409936278df3002576@20.80.183.57:26656
```

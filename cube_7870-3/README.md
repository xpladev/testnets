# Testnet cube_7870-3

[xpla@v0.0.5](https://github.com/c2xdev/xpla/releases/tag/v0.0.5) should be used to run the testnet.

- The genesis event for cube_7870-3 testnet will occur **2022-08-11T01:30:00Z**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/xpladev/xpla
$ git checkout v0.0.5
$ make install

$ xplad init [moniker] --chain-id cube_7870-3
$ wget https://raw.githubusercontent.com/c2xdev/testnets/main/cube_7870-3/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```

### Known Peers
```
9ddfac28dc6b28601e3039902ee5a8915dc7891f@3.35.54.221:26656
```

# Testnet hypercube_270-1

[xpla@v1.1.2-hypercube](https://github.com/xpladev/xpla/releases/tag/v1.1.2-hypercube) should be used to run the testnet.

- The genesis event for hypercube_270-1 testnet will occur **2022-11-24T02:00:00Z**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/xpladev/xpla
$ git checkout v1.1.2-hypercube
$ make install

$ xplad init [moniker] --chain-id hypercube_270-1
$ wget https://github.com/xpladev/testnets/raw/main/hypercube_270-1/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```

### Known Peers
```
049382ec45e2fae8da960402fbbb30d7be7fd4fa@3.38.140.56:26656
```

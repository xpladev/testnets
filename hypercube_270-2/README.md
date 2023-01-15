# Testnet hypercube_270-2

[xpla@0bcc939f0b0936afb7af827932fcc1a4e6d84fba](https://github.com/xpladev/xpla/commit/0bcc939f0b0936afb7af827932fcc1a4e6d84fba) should be used to run the testnet.

- The genesis event for hypercube_270-2 testnet will occur **2023-01-09T08:00:00Z**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/xpladev/xpla
$ git checkout 0bcc939f0b0936afb7af827932fcc1a4e6d84fba
$ make install

$ xplad init [moniker] --chain-id hypercube_270-2
$ wget https://github.com/xpladev/testnets/raw/main/hypercube_270-2/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```

### Known Peers
```
049382ec45e2fae8da960402fbbb30d7be7fd4fa@3.38.140.56:26656
```

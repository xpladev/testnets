# Testnet hypercube_270-2

[xpla@0bcc939f0b0936afb7af827932fcc1a4e6d84fba](https://github.com/xpladev/xpla/commit/0bcc939f0b0936afb7af827932fcc1a4e6d84fba) should be used to run the testnet.

- The genesis event for hypercube_270-2 testnet will occur **2023-01-09T08:00:00Z**

## Prerequisites
* Go v1.23.0 or higher
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
be45939423ee70c3b285280b0db35375bc1bd1b3@67.213.124.138:26656
```

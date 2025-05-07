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
9034c13d61d7f4ebbe3f5673a8d10dc742566e59@35.212.215.88:26656
b216988031686e36351c3cb042e522ac98c29a23@34.64.212.239:26656
a674688aa3cb052cfbf5f81228ef0dd5d4a7b5b9@34.64.46.211:26656
cf8c6a464bf5bc92744d6c74e0298114955856b8@34.64.165.123:26656
fdd6a1c61cc5b84a9c914e520f0e3f31a1505b23@34.64.250.213:26656
43fbd86b84b3e8cb38c418f2d74b74f79a376d97@34.64.47.240:26656
```

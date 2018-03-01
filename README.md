# DropCoin Explorer
Block explorer for TurtleCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon turtlecoind. It should be accessible from the Internet. Run turtlecoind with open port as follows:
```bash
./turtlecoind --restricted-rpc --enable-cors=* --enable-block_explorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
    @devopsralf


### Note

Alot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer and turtlecoin/block-explorer

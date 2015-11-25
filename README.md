# Ethereum TestNet Genesis and Chain

Genesis file and chain to quickly setup a testnet

# Account 

* 12890d2cce102216644c59dae5baed380d84830c
* Password : "password"
* Balance: 10000 Eth

# Usage 

* Git clone or download the genesis and dev chain
* Start geth using this params (adjust the paths based on your geth location)

```
geth --rpc --networkid=39318 --maxpeers=0 --datadir=devChain --genesis genesis_dev.json --verbosity 0 console
````

# Want to create your own, more info 
http://juan.blanco.ws/setup-your-own-tesnet-ethereum/

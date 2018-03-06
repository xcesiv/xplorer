# xplorer
The Ethereum Classic Block Explorer for the Main & Modern networks.


## Purpose
This is the repository of an Ethereum Classic Block Explorer for Main and Modern. This is hosted live by [Gamerammo](https://gamerammo.io)

## Donations

ETC Address (gamerammo): 0x07a9Af1cc74D34295c62b5F1277B1066103F85B8
ETC Address (xcesiv): 0xea35bd0a7977fda4e10420de979ea13ee93e4a69

## Installation

`git clone https://github.com/xcesiv/xplorer`

`npm install`

`bower install`

`npm start`

Make sure to install geth as well for the ETH explorer to be able to function. Then run:

`geth --rpc --rpcaddr localhost --rpcport 8545 --rpcapi "web3,eth" --rpccorsdomain "http://localhost:8000"`

Then visit http://localhost:8000 after running npm start.

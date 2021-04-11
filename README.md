# ballotresults

1. npm i

2. node readTuples.js

output: results id with sum Lition tokens

needs .env file with
INFURA_KEY = ...     #for connectin to testnet
MAINNET_KEY = ...    #for connetion to mainnet

# set blocknumber
to prevent double voting we have to set blocknumber
to read only from that block, how much token were
at this moment

mainnet.eth.defaultBlock = ...

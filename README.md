# Demo Blockchain

# Run as testrpc
- testrpc -i 1111
- truffle.cmd migrate --network test --reset

# Run as private network
- geth --datadir=./private --rpc --rpcaddr "127.0.0.1" --rpccorsdomain=* --networkid 1234 --rpcapi="db,eth,net,web3,personal"
- truffle.cmd migrate --network development --reset

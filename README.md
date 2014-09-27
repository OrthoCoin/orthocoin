##OrthoCoin 19-09-2014


OrthoCoin – X13 CryptoCurrency
* RPC Port: 51222
* P2P Port: 50990
* Algorithm: X13 POW/POS starts on block 14400
* Ticker: ORTH
* Max PoW Coins: 673925
* 5% PoS Annual Interest

Block Reward Schedule
* 60 second blocks
* Blocks 0-5760 are 0 reward for ICO duration
* Blocks 5761-5961 are low reward (1)
* PoW Ends on Block 14400 
* MinStakeAge: 24 hours
* Max: Unlimited

##Troubleshooting

In the event you encounter problems compiling the daemon, feel free to consult the guide below:

Receive the following error?

------------------------------------------

PROBLEM:

../src/leveldb/libleveldb.a: No such file or directory
../src/leveldb/libmemenv.a: No such file or directory

SOLUTION:

cd src/leveldb
make libleveldb.a libmemenv.a

CD back to src and try to build it again.

If you get the following error trying to do the above,

/bin/sh: 1: ./build_detect_platform: Permission denied
Makefile:18: build_config.mk: No such file or directory

chmod 755 src/leveldb/build_detect_platform

and try it again.




------------------------------------------



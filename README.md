# Larson Proof of Authority (POA) Private Blockchain

## Starting Instructions

**Using geth, initialize each node with larson_poa.json**

* ./geth --datadir poa_1 init larson_poa.json
* ./geth --datadir poa_2 init larson_poa.json

**Run 2 seperate terminals to start and monitor the nodes.**

* ./geth --datadir poa_1 --unlock 0xbc570cbC4c1a55eF2ab942E02a8Ed29770c40ccA  --mine --rpc --allow-insecure-unlock
* ./geth --datadir poa_2 --unlock 0xe457D0b40DA8D03C03CBCD15FB62f3fB4eF90F41 --mine --port 30304 --bootnodes "enode://82f493f5ff0bd38d8ff851491eef32dc6c955946919b2d378db8f4c63ae0446ef8d6bfbb931479c532b93fd282fbf9b583013be3aa414ea8a2d707d77a3021c0@127.0.0.1:30303"

**After hitting enter for each entry, you will need to enter the node password**

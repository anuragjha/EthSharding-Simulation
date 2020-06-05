# EthSharding-Simulation

Transction can be completed in a shard or has to involve beacon chain for cross-shard communication.
Ethereum puts breaks account address ("from and "to" field in tx).
Assuming, Beacon chain block production time is greater than shard chain block production time. Then, essentially ratio of cross shard transctions to total transaction has to optimized to minimum to achieve best block production rate.
This means, 2 shards will give best results in theory. This means that we cannot keep sharding to scale blockchain.

# top crypto books
--mastering btc,mastering eth, kings of crypto ,the infinite machine,the blocksize wars :)
# once balajis(former CTO of Coinbase) was asked about to get started in crypto,here are the resources he recommended
# top crypto podcasts
--unchained,the breakdown, bankless, on the brink, up only
# top crypto influencers(btc and eth)
--cz,sbf,armstrong,pomp,danheld,vitalik,rsa,hoffman,chainlinkgod,hayden,,laura -- only verified ones
# soft forks vs hard forks 
# the DAO wars 
# taproot upgrade
# EIP 1559
# top defi protocols
# optimistic vs zk-rollups
# incentives in optimistic rollups
# UTXO vs EOA and SC approach
# Shanghai attacks
# Blocksize wars
# Creme Hack(Check Mudit's thread)
# Parity Hack
# Polygon Hack(600m)
# Wormhole attack(300m)
# Metamask bot attack
# Threads on chrome tabs in android phone
# Explain defi(Aave, Synthetix,Compound,Maker,Balancer,Uniswap) --Check out Nick Chong's threads
# all about rollups

-using sequencers to reduce cost and improve scalability by only publishing transaction merkle roots to the blockchain
-without degrading the trust assumptions of the system
-withdrawals can be made by showing merkle proofs instead of checking the actual state of 
 the Ethereum blockchain
-the sequencer provides the merkle proof to the user
-data from the sequencer is stored(but not executed) on the blockchain to ensure it's always available

## Resources

[Further reading](https://research.paradigm.xyz/rollups)<br>

# Rollup thread

Three factors impact the resource requirements of running a node in a decentralized network such as Bitcoin and Ethereum [1]:

Bandwidth: The cost of downloading and broadcasting any blockchain-related data
Compute: The cost of running computations inside scripts or smart contracts
Storage: The cost of storing transaction data for indexing purposes, and the cost of storing “state” in order to continue processing new blocks of transactions [2].

Performance is measured in 2 ways:

Throughput: The number of transactions the system can process per second.
Latency: The time it takes for a transaction to be processed.

But what makes a network decentralized?

Low Trust: This is the property which allows any individual to verify that there will never be more than 21m bitcoin, or that their bitcoin is not counterfeited. Individuals who run node software independently compute the latest state and verify that all rules were followed in the process
Low Cost: If the node software is expensive to operate, individuals will rely on trusted third parties to verify the state. High costs imply high trust requirements, which is what we wanted to avoid in the first place.


Another desired property is scalability: The ability to scale throughput and latency superlinearly to the cost of running the system. This definition is great, but doesn’t incorporate “trust”. Hence, we specify “decentralized scalability”: achieving scalability without meaningfully increasing the system’s trust assumptions.

as a transaction’s execution complexity increases, the system’s throughput decreases to very low values. There’s room for improvement!







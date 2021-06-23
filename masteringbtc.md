# Introduction
Units of currency called bitcoin are used to store and transmit value among participants in the bitcoin network. ...form the basis of a digital money ecosystem
borderless...only an internet connection required
there is no "central" server or point of control.

Bitcoin consists of:

A decentralized peer-to-peer network (the bitcoin protocol)

A public transaction ledger (the blockchain)

A set of rules for independent transaction validation and currency issuance (consensus rules)

A mechanism for reaching global decentralized consensus on the valid blockchain (Proof-of-Work algorithm)

 The protocol also halves the rate at which new bitcoin is created every 4 years, and limits the total number of bitcoin that will be created to a fixed total just below 21 million coins. The result is that the number of bitcoin in circulation closely follows an easily predictable curve that approaches 21 million by the year 2140. Due to bitcoin’s diminishing rate of issuance, over the long term, the bitcoin currency is deflationary. Furthermore, bitcoin cannot be inflated by "printing" new money above and beyond the expected issuance rate.

bitcoin mining decentralizes the currency-issuance and clearing functions of a central bank and replaces the need for any central bank.
available as open source software

# Anatomy of a bitcoin transaction
Bitcoin Transactions are made up of inputs and outputs; inputs are what go into a transaction (roughly speaking, inputs make up what is being sent), and outputs are what come out (making up what is being received). The outputs of one transaction can then be spent as the inputs of another one

Nodes track spendable transaction outputs, or outputs that have not yet been used in another, subsequent transaction. These are known as unspent transaction outputs (UTXOs)

The only exception to the output and input chain is the coinbase transaction. This transaction creates brand-new bitcoin by paying out the block reward to the miner that added the block to the blockchain. The input of this transaction is not a UTXO from a previous transaction, but rather a special type of input called the coinbase. This is also the process by which the bitcoin money supply increases until it hits the cap of 21 million bitcoin.


# Glossary

Mining  "mining," which involves competing to find solutions to a mathematical problem while processing bitcoin transactions.

Proof-of-Work algorithm
global "election" every 10 minutes, allowing the decentralized network to arrive at consensus about the state of transactions. This elegantly solves the issue of double-spend where a single currency unit can be spent twice

Nodes...computers connected to the bitcoin network

Coinbase...the first transaction in every block

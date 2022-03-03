# Lightning 

The Lightning Network is a peer-to-peer network of payment channels implemented as smart contracts on the Bitcoin blockchain as well as a communication protocol that defines how participants set up and execute these smart contracts.

a payment channel is a financial relationship between nodes, allocating funds from a multisignature address through a strictly defined cryptographic protocol.

The fundamental building block of a payment channel is a 2-of-2 multisignature address. One of the two channel partners will fund the payment channel by sending bitcoin to the multisignature address. This transaction is called the funding transaction, and is recorded on the Bitcoin blockchain

A multisignature address is where bitcoin is locked so that it requires multiple signatures to unlock and spend.

The amount deposited in the multisignature address is called the channel capacity and sets the maximum amount that can be sent across the payment channel.

A commitment transaction is a transaction that pays each channel partner their channel balance and ensures that the channel partners do not have to trust each other.

By signing a commitment transaction, each channel partner "commits" to the current balance and gives the other channel partner the ability to get their funds back whenever they want.

INTRODUCTION

-A fairness protocol is a way to achieve fair outcomes between participants, who do not need to trust each other, without the need for a central authority, and it is the backbone of decentralized systems like Bitcoin.

Example of the Fairness Protocol

The most prominent example of a fairness protocol is Bitcoin’s consensus algorithm, Proof of Work (PoW). In Bitcoin, miners compete to verify transactions and aggregate them in blocks. To ensure that the miners do not cheat, without entrusting them with authority, Bitcoin uses a system of incentives and disincentives. Miners have to use electricity and dedicate hardware doing "work" that is embedded as a "proof" inside every block. This is achieved because of a property of hash functions where the output value is randomly distributed across the entire range of possible outputs. If miners succeed in producing a valid block fast enough, they are rewarded by earning the block reward for that block. Forcing miners to use a lot of electricity before the network considers their block means that they have an incentive to correctly validate the transactions in the block. If they cheat or make any kind of mistake, their block is rejected and the electricity they used to "prove" it is wasted. No one needs to force miners to produce valid blocks; the reward and punishment incentivize them to do so. All the protocol needs to do is ensure that only valid blocks with Proof of Work are accepted.

Fair outcomes are not enforced by any authority. They emerge as the natural consequence of a protocol that rewards fairness and punishes cheating, a fairness protocol that harnesses self-interest by directing it toward fair outcomes.

Not all channel peers are good peers for routing payments. Well-connected peers will be able to route payments over shorter paths to the destination, increasing the chance of success. Channel peers with ample funds will be able to route larger payments.

the special Bitcoin transaction that opens a Lightning channel, known as the funding transaction. The on-chain funding transaction is sent to the Bitcoin network for confirmation.

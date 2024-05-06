# All Long Term Value in Crypto Stems From Decentralization

There's levels to decentralization. Bitcoin and Ethereum are 'de jure' decentralized, its impossible for a centralized entity (without a few hundred billion) or a nation (outside of coordination from a top few) to successfully shut down the network.

Other chains are 'de facto' decentralized, there might be some physical limitation that adds a layer of centralization, like the large stake & validator requirements of most high TPS chains, or a multisig governing the chain like most L2s, or not a large enough userbase running validators. 

We trust that the majority owners of the token and the community behind behind the chain has enough incentive to abide by the chain's rules. Code is not entirely law but there's enough social incentive to abide by the written code. There's a limit to this, which limits the amount of value that can actually be stored on chain. 

If there was a hundred billion on a multisig governed L2 for example, one might believe that the incentive to collude is greater than the incentive to keep the chain going. 

For that reason, the functional level of decentralization of a chain fundamentally limits the amount of value that can be stored on the chain. Chains seek to increase their decentralization over time in order to increase the value on their chain and the value of the chain.

The closer a chain gets to true 'code is law' the more valuable it is. 

The only use case for crypto is as a decentralized store of data. All value in crypto fundamentally stems from this, so logically the projects that contribute the most value are the ones that positively affect decentralization (projects that contribute the most value don't necessarily capture the most value but that's a discussion for a different post).
 
#### Given this, what projects most increase the decentralization of a chain?

You want to increase the validator set, distribute ownership of token, and increase the number of users.

- Distributed Validator Technology, allowing tiny validators to participate in block verification. Reducing the validator size greatly increases the set of validators. 
    - This doesn't work for high TPS chains, it takes 70ms for light to travel around the world and back, if more parties need to approve of the transaction, it slows confirmation & finality times. So increasing the validator set has to slow down confirmation & finality times.

- Token Distribution, this is generally determined at IDO and then determined by the amount of user interest in purchasing token. For chains that have heavy insider ownership, I believe using a cosmos-like approach of having many app-chains, each owned by a different party works best in decentralizing the chain.
    - Another approach is restaking-esque borrowing decentralization from a different token. This doesn't work when the project is large enough however because the centralizing bottleneck then becomes eigenlayer itself, users need to trust the chains owners and then eigenlayer. Restaking-esque borrowing decentralization works well for projects that are smaller than the restaking protocol they are borrowing security from, allowing them to borrow from the restaking protocol's credibility to bootstrap 'de facto' decentralization.
    - Who is the correct party to borrow credibility from? I believe its the community that's paying the most attention. Nearly all protocols have an owner's backdoor to handle edge cases, borrowing from Ethereum's security makes sense but only for very large projects, where the Ethereum community will pay enough attention to a backdoor, like a major L2. For other projects they're better off borrowing from a community that's local to them. A lending borrowing protocol on Cosmos might want to borrow from Atom or Osmosis' security. It might actually be safer from a smaller project to start as an L3 to borrow security from a major L2 that is paying close attention to it, rather than go directly to an Ethereum L2, the latter of which's community is unlikely to care.




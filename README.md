In this project we will try to understand blockchain technology by developing one in java.

Here is the steps that we follow:
1.Create your first (very) basic ‘blockchain’.
2.Implement a simple proof of work ( mining ) system.
3.Marvel at the possibilities.

Making the Blockchain.
A blockchain is just a chain/list of blocks. Each block in the blockchain will have its own digital fingerprint, contain digital fingerprint of the previous block, and have some data ( this data could be transactions for example ).

[Hash = Digital Fingerprint]

Each block doesn’t just contain the hash of the block before it, but its own hash is in part, calculated from the previous hash. If the previous block’s data is changed then the previous block’s hash will change ( since it is calculated in part, by the data) in turn affecting all the hashes of the blocks there after. Calculating and comparing the hashes allow us to see if a blockchain is invalid.

What does this mean ? …Changing any data in this list, will change the signature and break the chain.




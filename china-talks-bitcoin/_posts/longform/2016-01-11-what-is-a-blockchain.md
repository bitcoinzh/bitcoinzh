---
layout: longform-post
title: "Lan Mao asks, what is a blockchain?"
description: These posts are all in response to the question, what is a blockchain?
translator: "Damian O'Loan"
source_url: http://8btc.com/forum.php?mod=viewthread&tid=24008&page=1#pid273016
source_site: 8btc.com
img-path: /images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain.jpg
keyword: 区块链 Qu Kuai Lian ｜ Blockchain
unique: true
---

###chehw_1:

The blockchain was invented by Satoshi Nakamoto.

[Bitcoin] = [Digital gold] + [PoW blockchain] + [P2P]

Note: The "digital gold" referred to here is cryptocurrency, not electronic currencies based on a gold standard (E-money).

![Response to What A BlockChain Is by chehw_1]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain.jpg' | prepend: site.url }})

A blockchain is a ledger whose contents cannot easily be tampered with, its entries in a sequence that may not easily be tampered with. The theory and robustness are principally based on the maturity of hash algorithms. Its features include timestamping and a distributed database (for consistent ledger contents) with backups in different locations.

Previous cryptographically-based currencies replicated properties of money, managing to solve the problems of authenticity and ownership, but were unable to be freely transferred without preventing double spending. After A has given B part of their gold, naturally they can't use this gold again. But with electronic gold, A could maintain a copy of the original which differed in no way from the spent gold. So cryptocurrencies require a unified database record and the authentication of every transaction, and can thereby prevent any double spend.

Previous cryptocurrencies depended on the provision of centralized databases by trusted third parties to work. This kind of of currency can't break away from a dependency on trust, at most at an individual or organizational level. Only a hopeless idealist could believe it could attempt to compete with a national currency. It's hard to imagine it ever being deployed in the real world.

But the blockchain, from a technological perspective, does indeed achieve all the database requirements of a cryptocurrency. This is perhaps among the reasons for it becoming the subject of research of a large number of organizations (including banks). Being a distributed database, the blockchain gave rise to another question: among similar competing databases, how can one determine which is the most authoritative, the most 'true'?

The blockchain responds to this question by distinguishing between different operational methods: the PoW method belonging to the P2P family, the PoS method, as well the as centralized "private chain" method. The primary differences between these three methods lie in how they regulate who gets to decide what is 'true': "private chains" are purely centralized control, PoS operates on the right of the group, and PoW excludes the need for control, propelled forward by market forces, or depending on majority consensus.

[Bitcoin] = [Digital gold] + [PoW blockchain] + [P2P]. This is the first time trustless digital cash and transactions have ever been realised.

![Response to What A BlockChain Is by a1379246856]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-2.jpg' | prepend: site.url }})

###a1379246856:

I'll do my best not to go into too much detail and to use the simplest possible language to decribe a little in theory how a blockchain works. I hope this quickly brings some degree of knowledge about the blockchain.

Taking the Bitcoin blockchain as an example, you can imagine it as a kind of public ledger. This ledger:

1. Exists within each of the internet's Bitcoin nodes, with each node having a full backup.
2. Contains a record of every bitcoin transaction since its conception.
3. The ledger accounts are kept in separate blocks, each block containing a part of the complete transaction record. Each block also contains the id of the previous block, thereby forming a chain structure which gives rise to the name blockchain.
4. To create a bitcoin transaction, it's sufficient to broadcast the transaction details to the P2P network. When the miners' record of your transaction has become part of a new block on the blockchain, the transaction is complete.

![Response to What A BlockChain Is by sumubaobei]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-3.jpg' | prepend: site.url }})

###sumubaobei:
What are you, wikipedia?!

![Response to What A BlockChain Is by 芭比馒头]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-4.jpg' | prepend: site.url }})

###芭比馒头 (Barbie's steamed buns):
> I'll do my best not to go into too much detail and to use the simplest possible language to decribe a little in theory how a blockchain works. I hope this quickly brings some degree of knowledge about the blockchain.

Sorted, OP owes you 20 bucks.

![Response to What A BlockChain Is by bitbybit]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-5.jpg' | prepend: site.url }})

###bitbybit:
chehw_1's explanation was the most well-defined, you could put it in a textbook.

![Response to What A BlockChain Is by sider]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-6.jpg' | prepend: site.url }})

###sider:
I don't know, don't ask such hard questions

![Response to What A BlockChain Is by Xseraph2]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-7.jpg' | prepend: site.url }})

###Xseraph2:
I bow in admiration before chehw_1, every word is original, not one copied and pasted.

![Response to What A BlockChain Is by idgui.com]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-8.jpg' | prepend: site.url }})

###idgui.com:
A few of the comments above are pretty thorough, so I'll just give an easy-to-understand introduction:

A blockchain is just a chain where every block contains the entire chain's full sequential order.

A few of these words are problematic though: what's a block, how do you form a chain, what's so special about this chain anyway, what's the point of it?

1. Block
This can be understood as a block of data, most of these blocks contain electronic currency data like bitcoin transactions, which address sent how much to which other address.
2. How do blocks for a chain?
This is a little like pointers in the C language. Each block is passes through a hash algorithm, with the resulting value recorded in a block. Each hash must be written into the next block, and that block's hash into the next, and so on. In this way, a long sequential chain of string data begins to form, namely the blockchain.
3. What's so special about the blockchain?
Bitcoin's blockchain is decentralized. It can't be controlled or altered by anyone. This immutability and complete transparency are the defining elements of the blockchain. There are a few knockoff coins which, due to limited CPU or highly-concentrated wealth, are vulnerable to data corruption. For these reasons, only the Bitcoin blockchain is truly valuable.
4. Blockchain technology
Blockchain applications record data on the blockchain as a proof of its existence. Because of the blockchain's mass consensus system, it can be used to issue proofs of stock and equity. There are too many blockchain applications already, you couldn't name them all in a lifetime, but all this blockchain technology aims at decentralization and immutability. And for the moment, the only one which can achieve this is bitcoin. In a way therefore, you can consider all blockchains to be based on the Bitcoin blockchain technology.

![Response to What A BlockChain Is by 510685947]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-9.jpg' | prepend: site.url }})

###510685947:
Put simply it's just a ledger. Whatever good and bad things you've done, like what you came to chat about today, did you have breakfast today, have you jerked off today, every incident is recorded. POW doesn't have so much CPU it can't be modified, POS doesn't have so much coin it can't be modified, it's as simple as that.

Note: 510685947's signature says "Thanks Satoshi, for bringing us together. Thanks 8btc, for letting us meet our bros from every corner of the world."

![Response to What A BlockChain Is by zln0927]({{ '/images/translations/what-is-a-blockchain/2016-01-11-what-is-a-blockchain-10.jpg' | prepend: site.url }})

###zln0927:
Bitcoin is a token of value built on blockchain value. Other cryptocurrencies are also built on blockchains, although at the moment Bitcoin's is the best.

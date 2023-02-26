#                                           blockchain
- blockchain is an open and distrubuted ledger, which can recorf trasaction betwrrn tow parties in permenent way

## Characteristic:
- Open - anyone can access it.
- Distrubuted - blockchain dose not live in a datacentet insted each miner owns a copy of blockchain.
- Ledger - mannered log of each transaction.
- Transaction - this are recorded on the ledger.
- Permanent - to delet transaction all its sub transaction should be removed hence its `immutable`.

## Bitcoin 
- Tt all startrd with a white paper for peer to peer electronic cash system.

<h2>Distributed ledger technology </h2>

- Blockchain are distributed means millions of nodes controlling blockchain.
- So if you want to hack blockchain you need to hack all the nodes at same time (That's near to impossible).

## Working 
1. Sends the request to P2P.
2. This request willl broadcast to all the nodes.
3. Then it will validate by each node.
4. Then miner will verify the request and add it to the block.
5. After this is confiremd after enough block have been added

# Type of blockchain
1. Public blockchain
2. Private blockchain
3. Permissionless blockchain

## Public blockchain
- Anyone can use this blockchain.
- Bitcoin is an example of public block chain.

<h3>Attributes of a public blockchain. </h3>

- Easy acccount creation
- Distributed ledger storage
- Decentralized validation
- Decentralized Block creation
- Decentralized Governance

### Private vs Permissionless blockchain
- In this blockchain one must be invited and very few confirm the transaction.
### Diffrence form public blockchain
- Private transaction
- Authentication process
- Not truly decentralized
- Less transperent
- Partial immutability
<!-- 12 END -->

# Types of Blockchain
1. Tokenized 
2. Tokenless

## Tokenized Blockchain
- Value carrying blockchain which require a base unit of value it's called token.

## Tokenless Blockchain
- It does not have base value for transfer.
- Just have base properties likes Immutability, security etc etc ...
- E.g. Private Blockchain.

# Use of Blockchain
- Crypto payment
- Darknet market
- DeFi
- Dapp
- Privicy Token
- Proof of ownnership
- Consumer user cases
- Supply chain
- Authentication
- Edcutation diploma
- Insurance
- Govrement use case 

## Crypto Transaction
- Most popular use of blockchain.
- Compared to traditional payment much less cost and much more speed.

## DeFi
- Here, you are the bank.
- Whole diffrent from CeFi.

## Dapp
- Tradationally its Client -> Server -> Database
- But in Dapp it's External account -> Smart contract -> Blockchain

## Privacy and utility tokens
- See, Coin is digital cash but token is representation of assets.
- Diffrent type of token exists 1. utility token 2. Security token.

## Darknet Market
- This blockchain algo is used in crypto markets and for transaction they use Cryptocurrency.

<!-- left form 20 -->

## Supply chain
- Its use here also beacuse, it is to be seen that nothing should be change in supply network.
- And if anything cganges the entire network will know.

<h2>Authentication </h2>

- Simply means prove something whthout showing that we are proving.

## Edcutation Diploma
- Here ZK proofs are used.
- E.g. - whenyou need to show that you are passed but dont want to show the grade here ZK proof helps.

## Insurance
- To detect furad easily

## Goverment use case
- To make a secure voting system as usps did and it's awesome.
- From this system every citizen of us can see their vote anytime using their key and still they can count it.

##  Proof of Ownnership
- Here NFT comes in and boom they can use to track ownnership via blokchain.

#                                           Smart Cotracts
- An arrangement between two or more parties exchanging digital assets, where at least
one of these parties allocates digital assets at the contracts initiation which are then
redistributed to all involved parties in accordance with a predefined protocol encoded in
logic and a state that is initialized at the start of the contract.

## Purpose
- It enables blockchain to move from single puropse such as crypto to multi purpose form platform used to deploy various decentralized application

## Smart Contract brief
- Program running on smart contract can execute automatically when some condition are met.

<h2>Supply change usage </h2>

- Provinance firm is using smart contract to track his incredint form source to consumer.

## DiFi
- Creating monetry banking service
- It has changed the traditional financial products to open source adn decentralised world 

## Gambling
- Smart contracts are also used in gambling as vurtial casino.

## Social network
- Making decentralised social network that is free of bots and fake accounts.

## Gaming
- Yeah it's in gaming and in that some users may rewarded in NFT's.

## EOS.IO
- EOS.IO is a blockchain protocol powered by the native cryptocurrency EOS. It is a smart contract platform that claims to eliminate transaction fees and also conduct millions of transactions per second, much faster than Bitcoin and similar protocols.

<h2>Hyperledger </h2>

- It's a project of servel opensourece blockchain and blockchain tools are started by the linux foundatation.

## Corda
- Provide private blockchain solutation.

<!-- Left form 3 -->

# Keys, Wallets and Cryptography

<h2>Fundamentals </h2>

- Gola is to communicate securely. 
- VIA CIA tried

## Hash
- It's one way we can create an hash but can't match it.
- Collision resistance - We should not have same wallet address.

## Type of Cryptography
### Public (Asymmetric)
- Shall have 2 keys Public and Private.
- Private key to sign the transaction.
- Public key to decrypt.
- Sender encrypt with recivers public key
- Reciver decrypt with reciver's private key.
- Reciver verify the signature with senders public key.
### Symmetric
- Uses one key to decrypt and encrypt.
- Both shall have single key.
- Both encrypt with shared key.

## This public and private keys are used in macnism of our crypto wallet

## Elliptic curve technology
- This is same technology is used in ssl and tls certs.
- Here private key is representd prime number.

## Cryptocurrency wallet 
- Stores public - private key pair plus addreses.
### Formats of wallet
- Paper wallet
- Hardware wallet
- Sowtware wallet
- Brain wallet
### Type of wallet
- Non Deterministic wallet.
- Deterministic wallet.
- Hierarchical Deterministic wallet.

<h2>Paper wallet </h2>

- Private key and address are printed on paper.
- This can be obatined form bitcoin atm.

## Hardware wallet 
- Stores a private key on diffrent hardware device.

## Software wallet
- We all know E.g. Metamask

## Brain wallet 
- Memorize it and it is unhackble until you do it.

## Non-Deterministic wallet
- Each pair is generated independetly
- it have static keys.

## Deterministic wallet
- Single seed to generate manny keys
- Mostly used in Hardware wallet
- Only need to remember seed
- Type 1 (known as)

## Hierarchial Deterministic wallet
- HD wallet enable tree like strcture for master and child keys.
- This also unlock business use case.

## Mnemonic keys and bip 39 standerds
- Monic key is word for private keys
- BIP39 is most commanly used Key gen for blockchain and smart contracts
- It use 12 to 24 words mnemonic ksy as seed, words are selected from bank of 2048 words.


# LAB 
- After excrating iso and zillion you will get vm file.
- Run `workbook-update` 
- All the next steps are written in lab

# CONSENSUS MECHANISM

## Proof of work
- It is a piece of data which is diffcult to produce but easily verify able.
- Hashing is uded by bitcoin as proof of .. the more cpu power the higher hash rate.
- THe miner has to solve complex mathmetical problem to earn bitcoin.

## Mining types

### solo mining
- Advantage is no sharing of block of reward. Cheap to get tarted.
- Now alomst impossible ot win a block. Noice and electricity usage.

### Mining pool
- We can join a mining pool
- They use our resource for mining and split the reward upon proof of work

### Cloud mining
- Advantage is less cost no heat and noice. Buy as many as you want.
- Disadvantage is lot of scams, centrelised, create opp for 51 percent attack at scale.

## mining process
- Transaction are hashed with SHA265
- Transaction is made of diffrent component and it all form merkle tree.
- when we transat bitcoin it's hash become leave and all transaction make another leave 
- And all that another leave create root that root is known as merkle root.
- That merkle root has all transaction of that block.
- If we change something in that bloc merkle root will also change.
- We have header of transaction which has version, it contains version of bitcoin. (this dosn't affect transation at all)
- The after version inheader we have previous block hash, it contain hash of previous block.
- Then in header we have merkle root hash this is where transaction is added and has all transaction.
- NOTE - Genesis is the first block ever mined.
- Then in header we have timestamp here timestamp are created as block are mined.
- Then in header we have targer it is the target that miner has to hit in order to win an bitcoin.the target adjusts accroding to people and speed.
- Then in header we have nonce it is the random number added by miner to create hash to be subbmited to be compared to targer diffculty and it's in bit and bytes.
- Then we have targer diffculty(not part of header) the target level of diffculty bitcoin is recalculated every 2016 block.
- Diffcultu is just combination of O and F.
- We have to compleate proof of work challenge to get rewarded.
- The nodes function to relay transaction information from
users to miners and also to store the Blockchain.
- Nodes synchronize with each other and update from peers
when they come online.
The nodes check every transaction and hash generated by
miners to see if transaction data corresponds to hash
generated by miners.
- This validation check is rewarded as well with transaction fees
when Confirmations are performed.

## Byzantine fault tolerance
- Byzantine fault tolerance relates to blokchain technology because blockchain consensus algorithm are degzined to provide a solutaion byzantine generals.
- They solve the problem where network need to come to an agreement in state of ledger, that they communicate indirectely via peer to peer network and there is no potential for tratiors which are nodes working for self interest.

## Proof of stake - consensus mechanism 
- First stake, it means a part of company that you own because you put money in it.
- In bitcoin based blockchain the more funds you hold the more information you gain about company, the more rights you gain form company.
- But for this we have to stake for long time and till then we have to promise not to spend.
- A node's possibility to being selected to create a block is proportional to the percentage of overall stake that they control.
- It makes transaction process faster.

## Delegated proof of stake 
- It means node do not participate in proof of stake directly insted the have a delegate to particapate.
- Node use their stake to vote for delegate.
- And delegate is promised a percentage of block reward.

# Blockchain trilemma
- This was coined by founder of eth.
- **Speed, Security and Decentralization** are the blockchain Trillema.


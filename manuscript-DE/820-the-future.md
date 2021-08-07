# The Future Is Now

> "The future is a construction site." - Anita Posch

Now that you have a deeper understanding of Bitcoin and how to use it, we can dip our toes into future developments that I think will have enormous impact. This part was co-authored by Mark Kersley with parts taken from: [Andreas M. Antonopoulos' talk about Bitcoin, Layer 2 Solutions, and the Wild West of Crypto](https://youtu.be/TsbIMg-YHQk)

## Decentralized Finance - DeFi
One intriguing category of new applications is called decentralized finance, or DeFi. Decentralized finance aims to expand upon the monetary freedom offered and inspired by Bitcoin, and introduce these features to the whole crypto ecosystem. It's all well and good owning bitcoin or other decentralized assets, but when most people go to buy, sell or even hold their assets long-term, they use a centralized entity such as an exchange. 

By using centralized entities these people are exposing themselves to risks such as KYC, fractional reserves, hacks and insider manipulation. DeFi offers a more trustless alternative through the use of programmable smart contracts. Crypto-assets are digital and, as such, they are programmable. DeFi platforms use pre-programmed contracts to perform tasks that were previously only available through centralized entities such as swaps, margin trading, lending, staking and more. By removing the centralized 'middlemen' and instead using publicly visible contracts, DeFi provides a fairer financial layer to the crypto ecosystem. The possibilities of DeFi are still being discovered and built. One day, the entire global financial system may be decentralized. 

Most DeFi applications are developed and run on the Ethereum (ETH) network - the second largest crypto-asset by market cap at the time of writing. Ethereum is very developer friendly and focuses on smart contract development through languages like Solidity. Therefore, it has been the perfect incubation ground for DeFi platforms in recent years. Popular use cases for DeFi on Ethereum are decentralized exchanges (DEXs), lending platforms and pegged stable-coins like USDT. 

DeFi platforms can utilise tokens from other chains through a process called wrapping. This involves sending an asset from another blockchain to a smart contract peg. Let's use 1 bitcoin as an example. This peg will hold (lock up) the bitcoin sent to it and mint the equivalent version of that bitcoin on the Ethereum network. Examples of this are wrapped bitcoin (WBTC) and Ren bitcoin (renBTC). These pegged tokens can be used on the DeFi application in place of the original asset and because the smart contract holds the original asset, there can be no issue of a 'double-spend'. When a user wishes to withdraw their assets back to their native chain, the smart contract will burn the token it minted and send the user their original asset on the native chain. This process enables DeFi to work for virtually any digital token.

Bitcoin's development is slower and has a more conservative approach than many other blockchains like Ethereum. This for a good reason: security. But developers in the Bitcoin space haven't been sleeping, aside from the Lightning Network a lot of Bitcoin-native platforms and applications have been developed.

### Bitcoin-Native Protocols and Platforms

#### Rootstock
Rootstock (RSK) is a network that looks to bring smart contract capabilities to Bitcoin. It is merge-mined with Bitcoin, meaning between 40 and 75% of Bitcoin miners actually process the transactions of the RSK network. This means that RSK is secured by more hash power that any other blockchain in the world, excluding Bitcoin of course. Similarly to Ethereum solutions, RSK uses the wrapping process to introduce bitcoin to the network. However, since the network itself is merge-mined by Bitcoin miners it can be considered the most secure and trustless network to build DeFi on currently. It has the most appeal to Bitcoiners and those who long for DeFi solutions for Bitcoin, but do not wish to lose the decentralization, trustlessness and security offered by the Bitcoin network. 

Rootstock has been in development since 2014 and launched it's mainnet in 2018. The RSK network has fast block times, processing each block in 15-30 seconds. Applications can be built on top of RSK using similar techniques as Ethereum such as with the Solidity development language. The gas costs for RSK are significantly less than that of Ethereum; at the time of writing, Ethereum transactions cost an average of $60 whilst RSK transactions cost an average of $0.50. Due to it's speed and customisation potential, rollups can be introduced to applications built on Rootstock to further decrease transaction speed and costs, potentially as low as less than $0.01 per transaction. 

#### Sovryn
Sovryn is an example of one such platform being built on the Rootstock network. Sovryn is creating a DeFi platform for bitcoin as well as many other assets via bridges to other chains including Ethereum and Binance Smart Chain (BSC). It is a non-custodial and permissionless contract-based system primarily used for bitcoin lending, borrowing and margin trading. There is no KYC for Sovryn and it never demands custody of your funds, *not your keys, not your coins!* It currently features a low-cost spot exchange, margin trading, lending/borrowing, liquidity providing/mining and some non-fungible token (NFT) functionality. It uses a fastBTC relay to quickly convert bitcoin to Rootstock smart bitcoin (rBTC) for use on Sovryn. Future developments will bring multiple assets from multiple chains to Sovryn, as well as an NFT marketplace, token launchpad, perpetual swaps and overcollateralized bitcoin-backed stable-coins. The vision of Sovryn is not to be just another DeFi platform, but the financial operating system of the world.

Sovryn is not a company or centralized entity. It consists of many contributors whose goal is to create the trustless monetary layer that ideally should have been created on top of Bitcoin long ago. Sovryn ensures decentralized governance of the protocol via a form of democratic system called the Bitocracy, an evolved version of a vetocracy. This involves the staking of SOV tokens in return for voting power and fee rewards. All protocol level decisions must pass voting in the Bitocracy to be implemented. The staking mechanism ensures that voters are incentivized to provide educated votes in favor of proposals that would benefit the Sovryn ecosystem and against harmful proposals. At the time of writing, Sovryn has just begun its token trading and are looking to release multiple bridges and new features. It will be interesting to watch the project develop.

I interviewed founder Edan Yago, where he explores most of these topics - listen at anita.link/105

#### Thorchain
Similar to Sovryn, Thorchain was founded upon the realization that centralized means of transferring ownership of cryptoassets are fundamentally flawed. Born in 2018, Thorchain was created to serve as a replacement to centralized exchanges (CEX), and instead facilitates cross-chain decentralized crypto exchange (DEX). Thorchain connects between different chains through its own cross-chain bridge, thematically named the Bifröst Protocol. The Bifröst allows native token swaps across different chains, meaning there is no need for synthetic or wrapped versions of tokens. Crucially, Thorchain is non-custodial and is 100% decentralized. 

Thorchain operates mostly the same as other DEXs such as Sovryn; it utilizes an automated market maker model (AMM) to process and maintain exchanges. However, Thorchain does not run on another blockchain, like Sovryn runs on RSK for example. Thorchain is instead its own independent blockchain that was built using the Cosmos SDK. This has allowed Thorchain to force its own RUNE token as the base swap asset, meaning that every swap pair is a RUNE-x pair. Therefore users are able to swap, for example, BTC for ETH through the RUNE token's intermediary role. This would in fact function as a swap of BTC to RUNE, then a swap of RUNE to ETH. This has allowed the RUNE token's utility to command value: RUNE can be used to provide liquidity to the AMM pools in return for a share of fees and can be traded and speculated upon via the open market.

#### Babelfish Money
Within crypto, there are many pegged tokens which are widely referred to as 'stablecoins'. These are very popular and are commonly used to store, transfer and use wealth with minimal short-term volatility. There are many stablecoins pegged to the US Dollar such as Tether (USDT), US Dollar Coin (USDC), Binance USD (BUSD) and DAI, all of which are designed to maintain a value of $1.00 per token. Whilst these stablecoins form a very useful element of the crypto ecosystem, having different stablecoins on different networks has resulted in barriers to fluid liquidity across platforms. 

Named after the translation device in Douglas Adams' 'The Hitchhiker's Guide to the Galaxy', Babelfish aims to act as a cross-chain aggregator for all stablecoins. The vision is that anyone will be able to use Babelfish to convert any stablecoin to another, all backed by Bitcoin. 

The process will follow the same steps as classical fiat-stablecoin token issuance: a user will send one type of stablecoin and the protocol will mint convertible stablecoins (XUSD) to the user. The protocol invests the original stablecoins across DeFi platforms to earn a yield, which will then fund governance and a bitcoin layer 2 insurance pool; the yield will be re-invested weekly into a community-owned pool of bitcoin - the ultimate asset for insurance. 

The governance of the protocol is community controlled. Every time somebody uses the protocol and receives minted XUSD, they also receive FISH tokens. FISH is the governance token upon which voting power is attributed. Therefore, users can vote in the direction of the protocol using these FISH tokens.

Babelfish will be launching its initial token sale on Sovryn's Origin platform - a decentralized launchpad governed by the Sovryn Bitocracy.

#### Money on Chain
Money on Chain (MoC) is a DeFi protocol that holds four significant tokens within it. The idea is to provide more options to Bitcoiners, to improve upon their bitcoin performance and use cases whilst allowing them full control of their private keys. Money on Chain also operates on the RSK network, maintaining its Bitcoin focus.

The first token MoC offers is Dollar on Chain (DoC). This is the first 100% bitcoin-collateralized token, pegged 1:1 to the US dollar. 

Next is BPRO, a token that returns passive income through distributed sharing of pooled profits and other means. BPRO holders can benefit from free long leverage, courtesy of DoC token holders. BPRO holders also earn from liquidity mining and a share of fees generated by the MoC protocol. Essentially, holding BPRO is like holding bitcoin, at a slight leveraged long, whilst earning passive income from your bitcoin.

The third token offered by MoC is a BTC/USD instrument named BTCx. BTCx is essentially a tokenized representation of a bitcoin leveraged long position. These tokens are minted when a user sends BTC to the smart contract and come at a variable interest rate cost (which is fixed upon contract creation). The interest payments go to ₿PRO holders.

Lastly, the MoC protocol also includes a governance token, conveniently named the Money on Chain token (MOC). This allows MOC holders to stake in return for voting/veto power and staking rewards, both from fees paid in the platform and liquidity mining. Users are entitled to a discount on platform fees when they pay using the MOC token. 

To conclude, Money on Chain is a self-contained Bitcoin ecosystem, on RSK, which looks to provide multiple decentralized and non-custodial use cases specifically for Bitcoiners.

#### Liquid Network
The Liquid Network is a federated sidechain-based settlement network for individuals and exchanges, enabling faster, more confidential Bitcoin transactions and the issuance of digital assets. It's a separate blockchain that extends the functionalities of bitcoin with layered technologies. Liquid does not use proof-of-work, blocks are signed on a per minute base by 15 functionaries. It enhances privacy through confidential transactions and assets, where the amount and type of the asset that is being sent is hidden, while it is still cryptographically guaranteed that no more coins can be spent than are available.

There are a variety of use cases for Liquid: 
* fast transactions between exchanges
* individuals can use L-BTC through the Blockstream Green, Aqua, Elements, or Sideswap wallets
* Peer-to-Peer exchange HodlHodl uses L-BTC for its lending service
* the decentralized exchange Bisq will integrate L-BTC as its base layer
* anyone can issue new assets, including stablecoins like Tether USDt (already supported by Liquid) and security tokens, which can be traded freely within the network

Liquid shows that you can do anything with Bitcoin. You don't need a new blockchain or a new token. The native currency of Liquid is L-BTC, where you lock in your bitcoin and get the same amount of L-BTC for it. Therefore there will be only 21 million L-BTC ever. Liquid transactions are cheaper, faster and more private than bitcoin transactions. Although it's a federated sidechain transactions cannot be censored. The functionaries are black boxes, which can only be turned off by the operators. The trade-off is that Bitcoin peg-out transactions must be done through a Liquid member.

#### RGB
RGB is a smart contract system, working on Layer 2 and 3 on top of Bitcoin and the Lightning Network. It is designed with confidentiality and scalability in mind.

Possible use cases are:
-   Issue digital fungible assets, like stock, bonds and other forms of securities
-   Create different forms of collectibles (non-fungible assets)
-   Create and manage sovereign/decentralized identities
-   Design and run other forms of arbitrary-complex smart contracts

By their abilities RGB smart contracts go beyond what is possible with Ethereum-like smart contract systems, providing more layered, scalable, private and safe approach, where the ownership of the smart contract state is separated from the smart contract creation.


## NFTs
The other category that I think is extremely interesting is NFTs, or non-fungible tokens. These are tokens that, instead of representing units of currency, represent unique objects, items, or properties in the form that is distinguishable from one another and are therefore non-fungible. So let's think of an art piece that is represented by a deeds document. That document could be a digital token that can be traded like bitcoin, or the deed to your house, or your car, or any other physical item or specific piece of land. It's basically taking things that exist in the real world or taking digital intellectual property - like a song or a brand - and tokenizing it so that it becomes something that can be digitally traded. We haven't even scratched the surface in that domain so far. 

The first NFT platform on top of Bitcoin was Counterparty, founded even before Ethereum in 2014. In recent months more Bitcoin based NFT platforms are popping up. Raretoshi, and Azool.art are NFT platforms based on the Liquid Network. On Watafan trading cards that have collective value are backed by Rootstock smart contracts. Sovryn and RGB are developing NFT platforms by the time of writing this book.

## Governance
Finally, the third category that excites me for the future is the opportunity of applying this to the areas of identity and human governance. The ability to have tokenized human identities, where you do not have to reveal who you are but can choose to reveal various aspects at a time. I can prove that I have a degree from a University using a non-fungible token without telling you my name. I can prove that I am licensed to drive without giving you my entire history. I can prove that I am creditworthy, or trustworthy, vaccinated or whatever other characteristic you can think of. These various tokens that you can assign to individuals allow you to be in control of these things, no need for a government or a corporation like Facebook to do that. Then you can take those tokens and use them for governance purposes. The ability to vote in my homeowner's association, in my parent-teacher association, in my municipality, and all the way up into voting at the United Nations as one of 7 and 1/2 billion citizens of this planet with a digital voting token. Radical change towards direct democracy is possible with these technologies. 

These are things we're talking about 10, 15, 20, 25 years into the future. But if you understand how this technology works, and you see the seeds we're planting today, you can see these as natural developments that come out of this technology.





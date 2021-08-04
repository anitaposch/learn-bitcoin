# Using Bitcoin

## Transaction Fees
A mining fee has to be paid for every bitcoin transaction and these fees are required for the operation of the Bitcoin network to continue. The work of miners is rewarded with these fees and newly minted bitcoin (see chapter 2.3). Mining is an essential factor in the Bitcoin protocol. After a block of transactions has been mined, it is attached to the blockchain. This is the way to ensure the security of the network. Since Bitcoin has a fixed supply limit of 21 million coins, the miners would no longer receive any remuneration for their performance after reaching this maximum supply, and would no longer be interested in processing transactions and thus maintaining the blockchain. Therefore, Satoshi Nakamoto introduced transaction fees. According to the white paper, the aim is to keep these fees lower than the comparable fees and costs of the traditional banking system. However, it is not the case that transfers are free of charge simply because, in theory, there is no need for intermediaries or banks.

When you're buying bitcoin via an exchange, the transaction fee (mining fee) is usually not adjustable and is fixed by the provider.

In your non-custodial Bitcoin wallet, you can determine the transaction fee for outgoing payments by yourself. The higher you set the fee, the faster your transaction will be processed by the miners because they pick the transactions with the highest fees first. If your transfer is not time-sensitive, you can choose a lower fee.

For more control you can estimate the fee and the confirmation speed on pages like [Mempool.space](https://mempool.space/) or [Johoe's Bitcoin Mempool](https://jochen-hoenicke.de/queue/). These websites display the number and size of all unconfirmed transactions. They give a real-time view and show how the Mempool evolves. The transactions are colored by the amount of fee they pay per (virtual) byte.

![Real-time view of unconfirmed transactions](assets/_Mempool-space-white-back.png) [^74]

Below you can see the settings in the Edge wallet. You can choose one of the ranges of the default transaction fee or a custom value.

![Transaction fee settings in Edge wallet](assets/_transaction-fee-setting.png) [^75]

**Pending Transaction**
Since new blocks are mined every 10 minutes, it will take an average of at least 10 minutes until your transaction is confirmed. If you set the transaction fee too low then your transaction might be pending for a longer period as the Mempool gets cleared and miners begin to re-include transactions with lower fees. Here you see one of my transactions that has been trapped in the Mempool for a month.
![Pending transaction](assets/_Pending-transaction-edge.png) [^76]
You can look up the status of your transaction in a [Blockchain explorer](https://blockchair.com). As you can see below my transaction is 4,717 ranks away from being mined with a total of 41,610 transactions in the Mempool. I chose a fee of 5 sat per vbyte.
![Transaction status as shown in blockexplorer](assets/_Pending-transaction-explorer.png) [^77]

You do not need to follow the below steps to get your original transaction confirmed. Most low-fee transactions remain valid for days and will eventually confirm. However, there are two ways to solve the problem of the stuck transaction and get it confirmed sooner.

**A Sent Transaction Is Stuck**
* Replace-by-fee (RBF): some wallets allow you to set this option to yes before you send a transaction. In this case, if the original transaction gets stuck, you can set a higher fee and resend the transaction.

**An Incoming Transaction Is Stuck**
* Child pays for parent (CPFP): you can think of this as a parent having insufficient money for their expenses, so their child pays the difference on the parent’s behalf. CPFP is a technique through which you can bump your slowly confirming incoming transactions by making a new transaction with higher fees (child transaction) using the outputs (funds) from the previous transaction (parent transaction) that is stuck.

Please look up the documentation of the wallet you are using for detailed instructions.

## Buy Something With Bitcoin
Here are some directories with shops where you can spend bitcoin.
* [Accepted here](https://www.acceptedhere.io)
* [B2B services accepting BTC](https://cryptwerk.com/companies/b2b/btc/)
* [Coinmap](https://coinmap.org/view/) physical stores accepting Bitcoin
* [Spending Bitcoin](https://spending-bitcoin.com/) directory
* [UseBitcoins](https://usebitcoins.info/) directory

## Bitcoin Debit Cards
You can use a Bitcoin debit card to buy anything just like any other banking debit card. The difference is that it's loaded with bitcoin or altcoins. The merchants get paid in their own currency by the debit company and the charge will be deducted from your bitcoin balance, which allows you to live purely through bitcoin.

You will need to deposit your bitcoin at the debit card company, which means you give control over your coins to a third party. Deposit only as much as you need on the card and check the fees that those card companies charge.

A short list of cards that are available at the moment:
Cryptocom Visa, Binance, Bitpanda Visa, Coinbase Visa, Wirex Visa, BlockCard, Cryptopay, Nexo, Bitwala Visa, BitPay Visa, Cash App

## Spending and Receiving
The following are tools and services that enable you to spend and receive BTC in your daily life.
* [Bity](https://bity.com/products/crypto-online-bill-pay/) pay bills online with bitcoin
* [Cash App](https://cash.app/bitcoin) buy and sell BTC straight from your Cash App balance
* [Strike](https://global.strike.me/) send and receive instant international payments, instant remittances and with full access to the Bitcoin network
* [Piixpay](https://www.piixpay.com/?lang=en) pay anyone in EURO using your crypto
* [Bitrefill](https://www.bitrefill.com/?hl=en) buy giftcards and phone refills

[^74]: [Screenshot by Anita Posch](https://mempool.space)
[^75]: Screenshot by Anita Posch, Edge wallet
[^76]: Screenshot by Anita Posch, Edge wallet
[^77]: Screenshot by Anita Posch, Blockchair

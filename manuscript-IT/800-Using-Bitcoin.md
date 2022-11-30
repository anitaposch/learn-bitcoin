# Usare Bitcoin

## Commissioni di Transazione
Ad ogni transazione in bitcoin devono essere pagate delle commissioni sul mining e queste sono fondamentali affinché la rete Bitcoin continui ad operare. Il lavoro dei miner è ricompensato da tali commissioni, oltre che dalla creazione di nuovi bitcoin. Il mining è un fattore essenziale del protocollo Bitcoin. Una volta che un blocco di transazioni è stato minato, viene collegato alla blockchain. Questo è il modo in cui si garantisce la sicurezza della rete. Dato che Bitcoin ha una fornitura totale fissata a 21 milioni di coin, una volta raggiunto tale limite massimo i miner non riceverebbero più alcuna remunerazione per le loro prestazioni e perderebbero ogni interesse a processare le transazioni, dunque a mantenere la blockchain. Ecco perché Satoshi Nakamoto ha introdotto le commissioni di transazione. Stando al white paper, l’obiettivo è mantenere queste commissioni più basse rispetto ai costi di natura omologa del sistema bancario tradizionale. Comunque sia, non è il caso che le transazioni siano gratuite semplicemente perché, in teoria, non vi è necessità di intermediari o banche.

Quando acquisti bitcoin tramite un exchange, le commissioni di transazione (commissioni di mining) solitamente non sono negoziabili e vengono fissati dal fornitore del servizio.

Nel tuo wallet non-custodial di Bitcoin, puoi determinare tu le commissioni di transazione dei pagamenti verso terzi. Più alte saranno le commissioni che imposterai, più velocemente la transazione sarà processata dai miner perché loro scelgono le transazioni con le commissioni più alte. Se la tua transazione non è urgente, puoi selezionare commissioni meno onerose.

Per avere un maggior controllo, puoi stimare le commissioni e la velocità di conferma dei blocchi su pagine come [Mempool.space](https://mempool.space/) oppure [Johoe's Bitcoin Mempool](https://jochen-hoenicke.de/queue/). Questi siti web mostrano il numero e la dimensione delle transazioni non ancora confermate. Ti danno una panoramica in tempo reale di come evolve la Mempool. Le transazioni sono colorate in base dell’ammontare delle commissioni pagate per byte (virtuale).

![Real-time view of unconfirmed transactions](resources/_Mempool-space-white-back.png) [^74]

Qui sotto puoi vedere le impostazioni del wallet Edge. Puoi selezionare uno dei range per le commissioni di transazione di default oppure un valore personalizzato.

![Transaction fee settings in Edge wallet](resources/_transaction-fee-setting.png) [^75]

**Transazione in Attesa**
Dato che i nuovi blocchi vengono minati ogni 10 minuti, ci vorranno in media 10 minuti prima che la tua transazione venga confermata. Se imposti delle commissione di transazione troppo basse, la tua transazione potrebbe rimanere in status di attesa per un periodo più lungo, in attesa che la Mempool si liberi e i miner inizino a re-inserire le transazioni con commissioni basse. Qui puoi vedere una mia transazione, rimasta intrappolata nella Mempool per un mese.

![Pending transaction](resources/_Pending-transaction-edge.png) [^76]  

Puoi consultare gli status delle tue transazioni su un [Blockchain explorer](https://blockchair.com). Come puoi vedere nell’immagine sottostante, la mia transazione è alla posizione 4.717 nell’ordine di priorità di mining su un totale di 41.610 transazioni incluse nella Mempool. Ho selezionato una commissione di 5 sat per vbyte.  
![Transaction status as shown in blockexplorer](resources/_Pending-transaction-explorer.png) [^77]

Non devi necessariamente seguire i passaggi riportati sotto per ottenere la conferma della tua transazione. La maggior parte delle transazioni con commissioni basse rimangono valide per giorni e prima o poi vengono confermate. Tuttavia, ci sono due metodi per risolvere il problema delle transazioni bloccate e ottenere la conferma più velocemente.

**Un Pagamento in Uscita è Bloccato**  
* _Replace-by-fee_ (RBF): alcuni wallet ti abilitano a configurare questa opzione prima di inviare un pagamento. In questo caso, se la transazione originaria rimane bloccata, puoi impostare delle commissioni più alte e rimandare la transazione.

**Un Pagamento in Entrata è Bloccato**
* _Child pays for parent_ (CPFP): puoi immaginarti questa funzione come quando un genitore non ha abbastanza soldi per affrontare una spesa e il figlio interviene pagando la differenza al posto del genitore. CPFP è una tecnica tramite cui puoi promuovere la transazione in entrata bloccata effettuando una nuova transazione con commissioni più alte (transazione figlia) usando gli output (fondi) della transazione precedente (transazione genitore) che risulta bloccata.

Consulta la documentazione del wallet che stai usando per ottenere istruzioni dettagliate.

## Comprare Qualcosa con Bitcoin
Di seguito trovi un elenco di negozi dove puoi spendere bitcoin.
* [Accepted here](https://www.acceptedhere.io)
* [Servizi B2B che accettano BTC](https://cryptwerk.com/companies/b2b/btc/)
* [Coinmap](https://coinmap.org/view/), negozi fisici che accettano Bitcoin
* [Spending Bitcoin](https://spending-bitcoin.com/), elenco
* [UseBitcoins](https://usebitcoins.info/), elenco

## Carte di Debito Bitcoin
Puoi usare una carta di debito Bitcoin per acquistare qualsiasi cosa, proprio come una comune carta di debito bancaria. La differenza è carica di bitcoin o altcoin. Il commerciante viene pagato nella sua valuta dalla società che gestisce il pagamento, mentre la tua spesa viene dedotta dal tuo saldo in bitcoin, il che ti permette di poter vivere esclusivamente in bitcoin.

Devi depositare i tuoi bitcoin alla società che eroga il servizio della carta di debito, il che significa che stai dando il controllo dei tui bitcoin a una terza parte. Deposita nella carta solamente lo stretto necessario, e controlla costi e commissioni imposti dalla società che ha emesso la carta.

Una breve lista di carte attualmente disponibili al momento: Cryptocom Visa, Binance, Bitpanda Visa, Coinbase Visa, Wirex Visa, BlockCard, Cryptopay, Nexo, Bitwala Visa, BitPay Visa, Cash App.

## Spendere e Ricevere
Di seguito sono elencati gli strumenti e servizi che ti permettono di spendere a ricevere BTC nella tua vita quotidiana.
* [Bity](https://bity.com/products/crypto-online-bill-pay/), per pagare le bollette online con bitcoin
* [Cash App](https://cash.app/bitcoin), per comprare e vendere BTC direttamente dal tuo saldo disponibile in Cash App
* [Strike](https://global.strike.me/), per inviare e ricevere istantaneamente pagamenti internazionali, rimesse istantanee e con pieno accesso alla rete Bitcoin
* [Swapin](https://www.swapin.com/), per pagare chiunque in euro utilizzando le tue crypto
* [Bitrefill](https://www.bitrefill.com/?hl=en), per comprare gift card e ricariche telefoniche

[^74]: [Screenshot by Anita Posch](https://mempool.space)  
[^75]: Screenshot by Anita Posch, Edge wallet  
[^76]: Screenshot by Anita Posch, Edge wallet  
[^77]: Screenshot by Anita Posch, Blockchair  

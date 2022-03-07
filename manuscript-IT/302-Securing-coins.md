## Mettere al sicuro i tuoi fondi

Come menzionato nel capitolo precedente, l’obiettivo è conseguire il livello _“Your keys, your coins”_.

Per comprare, usare e conservare bitcoin, avrai bisogno del seguente:

* Wallet Bitcoin = il tuo portafoglio di denaro digitale. Un’analogia ancor più precisa sarebbe il portachiavi digitale dei tuoi salvadanai.
* Indirizzi Bitcoin = uno o più indirizzi unici dei tuoi fondi nella blockchain, i tuoi indirizzi di ricezione (più precisamente gli UTXO, output di transazione non speso).
* Seed = i dati di recupero del tuo wallet Bitcoin.

### Wallet Bitcoin
Pensa al wallet come un armadietto pubblico con molteplici cassetti di sicurezza. Tutti possono depositare denaro all’interno di ogni cassetto. Ma solamente chi possiede le chiavi private è in grado di sbloccare un cassetto e muoverne il contenuto. Il tuo wallet Bitcoin consiste di tutti i cassetti, e mantiene tutte le chiavi private per sbloccarle. Le chiavi private e gli indirizzi Bitcoin sono generati dal seed. Il seed è l’elemento dal quale si generano tutte le chiavi e gli indirizzi. È come un cesto nel quale sono conservate tutte le tue chiavi private.

![Defining terms](assets/_seed-postbox.png) [^69]

Il wallet è una app nel tuo telefono, oppure un programma nel tuo computer che gestisce tutto in background – le tue chiavi private, i tuoi indirizzi, l’invio e la ricezione di bitcoin.

I wallet Bitcoin contengono le chiavi, non le monete. Ogni utente ha un wallet contenente chiavi. I wallet sono più propriamente dei portachiavi di coppie di chiavi private e pubbliche. I tuoi fondi sono registrati nella blockchain di Bitcoin.

### Indirizzo Bitcoin
Per ricevere bitcoin, necessiti di un indirizzo Bitcoin affinché qualcuno possa inviartene. L’indirizzo Bitcoin consiste di una lunga serie di numeri e lettere.

Un esempio di indirizzo Bitcoin: 346n4apJCQPg2XAXU3bfNQTogz4PyTkrEf

Digitare 34 caratteri è un’operazione poco pratica, pertanto vengono comunemente usati i codici QR degli indirizzi, i quali vengono solitamente creati in automatico dal tuo wallet.

![BTC address as QR code](assets/_address-book.PNG)

Bitcoin è pseudoanonimo, non c’è necessità di collegare un tuo indirizzo email o un tuo documento identificativo col wallet. Tuttavia, la blockchain di Bitcoin è trasparente, e ciò significa che i tuoi indirizzi Bitcoin sono pubblicamente visionabili in Internet. Ad esempio, le puoi cercare su Blockcypher e vedere lo storico delle transazioni e contestuali valori. Qui puoi visionarne un esempio: [https://anita.link/explorer](https://anita.link/explorer)

Pertanto, per ragioni di privacy, non condividere in Internet i tuoi indirizzi Bitcoin associandoli alla tua identità. La privacy è anche la ragione per cui non dovresti riutilizzare gli stessi indirizzi. La maggioranza dei wallet provvede in automatico a generare nuovi indirizzi ad ogni transazione.

Procediamo ora con la parte più importante per la messa in sicurezza dei tuoi bitcoin: il seed.

### Seed e chiavi private

Considerato che dal seed si generano tutte le chiavi private, nessuno oltre a te deve averne l’accesso. La persona a conoscenza del seed ha il controllo finale dei fondi.

Il seed (chiamato anche frase mnemonica o frase di recupero) è una sequenza di 12 o 24 parole che fornisce accesso alle chiavi private degli indirizzi del wallet, e pertanto accesso alle criptovalute. Ciò significa che l’ordine di parole deve rimanere segreto. Qualsiasi persona a conoscenza del seed può accedere e sottrare le coin. Perché?

Differentemente dalle monete metalliche che si trovano all’interno del tuo portafoglio fisico, le tue criptovalute non si trovano all’interno del tuo wallet digitale. Queste sono registrate nella blockchain. Comparalo alla differenza che sussiste tra email e lettere postali. Puoi accedere al tuo account email da ogni parte del mondo perché le email sono archiviate online, mentre la tua cassetta della posta ordinaria è stazionaria. Ciò è applicabile anche a Bitcoin.

L’accesso globale ai tuoi asset è sempre possibile tramite il seed, al di là del produttore del tuo wallet. Quando selezioni il wallet, presta attenzione al termine “wallet HD” (_Hierarchical Deterministic_, ovvero deterministico gerarchico). I wallet HD ti permettono di cambiare a piacere con un altro wallet HD di altro produttore, segnarti il seed e recuperare le tue criptovalute.

Supponi che il tuo smartphone si corrompa, non puoi più accedere alla app del wallet Bitcoin e devi cambiare cellulare. Installi una nuova versione del tuo wallet Bitcoin e importi il seed del tuo primo wallet. In questo modo, l’accesso ai tuoi fondi è ripristinato.

Il seed è generato dall’app del wallet durante la configurazione iniziale. La maggioranza dei wallet ti guida attraverso il setup e ti istruisce a segnarti le parole del seed su un foglio di carta. Se il tuo wallet non ti offre questa opzione nell’immediato, cerca nel menu _“Create Backup”_ o _“Backup”_ e segui i passaggi. La creazione del seed funziona al contrario di come comunemente viene impostata una password in un sito web. Non sei tu che determini la password, ma il wallet.

L’ordine delle parole è IMPORTANTE! Devi scrivere le parole esattamente nell’ordine in cui appaiono.

> Esempio di seed: cruise item paper slim vocal power like video snap museum mirror sun

Annota il seed a mano su un foglio di carta e conservalo in un posto sicuro. Non catturare screenshot, non conservarlo in telefoni o computer che sono connessi ad Internet, per non correre il rischio che vengano attaccati. Maggiori informazioni sulla sicurezza si possono leggere nel capitolo 5.

Dato che i tuoi fondi non si trovano all’interno del tuo wallet ma conservati nella blockchain, puoi viaggiare globalmente e trasportare i bitcoin con te ovunque tu voglia. Devi solamente ricordarti dell’ordine delle 12-24 parole del seed. Quando oltrepassi la dogana senza lo smartphone, recuperi un nuovo wallet e importi il seed. Magia.

[^69]: Anita Posch, inspired by Andreas M. Antonopoulos

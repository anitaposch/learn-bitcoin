## Mettere al Sicuro i tuoi Fondi

Come menzionato nel capitolo precedente, il nostro obiettivo è conseguire il livello _“Your keys, your coins”_.

Per comprare, usare e conservare bitcoin, avrai bisogno di:

* Wallet Bitcoin = la tua cassetta di sicurezza per il denaro digitale. Un’analogia ancor più precisa sarebbe un portachiavi digitale per le chiavi che aprono le tue cassette di sicurezza.
* Indirizzi Bitcoin = uno o più indirizzi unici per i tuoi fondi sulla blockchain, i tuoi indirizzi di ricezione (più precisamente gli UTXO, output di transazione non spesi).
* Seed = i dati di recupero del tuo wallet Bitcoin.

### Wallet Bitcoin
Pensa al wallet come ad un armadietto pubblico con molteplici cassette di sicurezza. Chiunque può depositare denaro all’interno di ogni cassetta. Solamente chi possiede le chiavi private è in grado di sbloccare una cassetta e muoverne il contenuto. Il tuo wallet Bitcoin consiste in tutte le cassette, e conserva tutte le chiavi private per sbloccarle. Le chiavi private e gli indirizzi Bitcoin sono generati dal seed. Il seed è l’elemento dal quale si generano tutte le chiavi e gli indirizzi. È come un cesto nel quale sono conservate tutte le tue chiavi private.

![Defining terms](resources/_seed-postbox.png) [^69]

Il wallet è una app nel tuo telefono oppure un programma nel tuo computer, che gestisce tutto sullo sfondo – le tue chiavi private, i tuoi indirizzi, l’invio e la ricezione di bitcoin.

I wallet Bitcoin contengono le chiavi, non le monete. Ogni utente ha un wallet contenente chiavi. I wallet sono più propriamente dei portachiavi contenenti coppie di chiavi private/pubbliche. I tuoi fondi sono registrati nella blockchain di Bitcoin.

### Indirizzo Bitcoin
Per ricevere bitcoin, hai bisogno di un indirizzo Bitcoin a cui gli altri possano inviartene. Gli indirizzi Bitcoin consistono in lunghe serie di numeri e lettere.

Un esempio di indirizzo Bitcoin: 346n4apJCQPg2XAXU3bfNQTogz4PyTkrEf

Digitare 34 caratteri è ovviamente un’operazione poco pratica, pertanto vengono comunemente usati i codici QR degli indirizzi, i quali vengono solitamente creati in automatico dal tuo wallet.

![BTC address as QR code](resources/_address-book.PNG)

Bitcoin è pseudoanonimo, dunque c’è necessità di collegare un tuo indirizzo email o un tuo documento identificativo al wallet. Tuttavia, la blockchain di Bitcoin è trasparente, e ciò significa che i tuoi indirizzi Bitcoin sono pubblicamente visibili in internet. Ad esempio, li puoi cercare su Blockcypher e vedere lo storico delle transazioni e dei contestuali valori. Qui puoi vederne un esempio: [https://anita.link/explorer](https://anita.link/explorer)

Pertanto, per ragioni di privacy, non condividere in internet i tuoi indirizzi Bitcoin associandoli alla tua identità. La privacy è anche la ragione per cui non dovresti riutilizzare gli stessi indirizzi. La maggioranza dei wallet provvede in automatico a generare nuovi indirizzi ad ogni transazione.

Procediamo ora con la parte più importante per la messa in sicurezza dei tuoi bitcoin: il seed.

### Seed e Chiavi Private

Considerato che dal seed si generano tutte le chiavi private, nessuno oltre a te deve avervi accesso. La persona a conoscenza del seed ha il controllo finale dei fondi.

Il seed (chiamato anche frase mnemonica o frase di recupero) è una sequenza di 12 o 24 parole che fornisce l'accesso alle chiavi private degli indirizzi del wallet, e pertanto accesso ai tuoi soldi. Ciò significa che l’ordine di queste parole deve rimanere segreto. Qualsiasi persona a conoscenza del seed può fare l'accesso e rubarti i soldi. Perché?

Differentemente dalle monete metalliche che si trovano all’interno del tuo portafoglio fisico, le tue criptovalute non si trovano all’interno del tuo wallet digitale. Queste vengono invece registrate sulla blockchain. Possiamo fare un paragone con la differenza che sussiste tra un'email ed una lettera. Tu puoi accedere al tuo account email da ogni parte del mondo perché le email sono archiviate online, mentre la tua cassetta della posta è stazionaria. Ciò è applicabile anche a Bitcoin.

L’accesso da qualunque parte del mondo ai tuoi asset è sempre possibile tramite il seed, al di là del produttore del tuo wallet. Quando scegli il tuo wallet, presta attenzione al termine “wallet HD” (_Hierarchical Deterministic_, ovvero deterministico gerarchico). I wallet HD ti permettono di passare ad un altro wallet HD di un produttore diverso, segnarti il seed e così recuperare le tue criptovalute.

Supponi che il tuo smartphone venisse violato, allora non potresti più accedere alla app del wallet Bitcoin e dovresti cambiare cellulare. Puoi installare una nuova versione del tuo wallet Bitcoin e importare il seed dal tuo primo wallet. In questo modo, l’accesso ai tuoi fondi è ripristinato.

Il seed è generato dall’app del wallet durante la configurazione iniziale. La maggioranza dei wallet ti guidano durante l'attivazione e ti istruiscono a segnarti le parole del seed su un foglio di carta. Se il tuo wallet non ti offre questa opzione nell’immediato, cerca nel menu _“Create Backup”_ o _“Backup”_ e segui i passaggi. La creazione del seed funziona al contrario di come comunemente viene impostata una password in un sito web. Non sei tu che determini la password, ma il wallet.

L’ordine delle parole è IMPORTANTE! Devi scrivere le parole esattamente nell’ordine in cui appaiono.

> Esempio di seed: cruise item paper slim vocal power like video snap museum mirror sun

Annota il seed a mano su un foglio di carta e conservalo in un posto sicuro. Non fare foto, non conservarlo su telefoni o computer connessi ad internet, per non correre il rischio che vengano violati. Maggiori informazioni sulla sicurezza si possono leggere nel capitolo 5.

Dato che i tuoi fondi non si trovano all’interno del tuo wallet ma sono conservati sulla blockchain, puoi viaggiare per tutto il mondo e trasportare i tuoi fondi bitcoin ovunque tu voglia. Devi solamente ricordarti dell’ordine delle 12-24 parole del seed. Quando oltrepassi la dogana senza lo smartphone, recuperi un nuovo wallet e importi il seed. Magia.

[^69]: Anita Posch, inspired by Andreas M. Antonopoulos

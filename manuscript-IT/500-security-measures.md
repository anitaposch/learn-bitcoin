# Mettere al Sicuro le tue Valute

## Misure di Sicurezza
Tutti i database possono essere attacviolati da un hacker. Fai una ricerca della tua email presso https://haveibeenpwned.com/ - se sei fortunato non sei mai stato compromesso, ma miliardi di altri account lo sono stati. Pertanto, è importante seguire misure di sicurezza generali, che a maggior ragione devono essere applicate quando si utilizza Bitcoin.

### Setup dell’Hardware e del Software
Puoi utilizzare browser popolari quali Firefox, Opera, Brave or Chrome. Sono raccomandate le estensioni del browser che bloccano Javascript e i Cookies. Ghostery, NoScript e ScriptSafe sono il tipo di estensioni che puoi aggiungere al tuo browser. "HTTPS everywhere" applica una connessione SSL a tutti i siti web, inclusi quelli che non offrono SSL nativamente.

Sappi che alcuni punti vendita online non funzionano al meglio se queste estensioni sono attivate, dunque dovrai disattivarle manualmente.

È importante che tu ntenga sempre i tuoi dispositivi al sicuro.

### Aggiornamenti
Questo consiglio è applicabile a tutti i tuoi dispositivi: esegui tutti gli aggiornamenti del software consigliati. Sia del sistema operativo del tuo computer sia del tuo smartphone. Utilizza sempre l’ultima versione del tuo wallet e del firmware software sul tuo hardware wallet.

### Indirizzi Email
Non usare una singola email per tutto. Prepara degli indirizzi email usa e getta che userai solamente una volta. Puoi anche acquistare un dominio che potrai usare per indirizzi email falsi, e che inoltrerai al tuo indirizzo principale.

### Password Sicure
Utilizza password sicure per tutti i servizi online. La tua data di compleanno, il luogo di residenza, il nome del tuo gatto o 1234567 non sono password sicure. Frasi intere che includono numeri, spazi, lettere maiuscole e minuscole, e caratteri speciali sono password più forti.

Utilizza una password differente per ogni sito in cui fai login. Altrimenti, con una sola password, un hacker può irrompere in tutti i servizi cui sei registrato. Non conservare queste password in un file Word o similare nel tuo computer. Un documento Word è semplice da rubare e leggere per un hacker.

Puoi utilizzare programmi quali 1Password, Bitwarden o KeePass (gratuito e open source). Sono dei database di password criptate che permettono la generazione e conservazione delle tue password, mentre tu dovrai solamente ricordartene una per potervi accedere.

### PIN
Configura un PIN per il tuo wallet di modo che nessuno potrà accedere facilmente al wallet nel tuo dispositivo.

### 2FA
Utilizza un metodo di autenticazione a due fattori per mettere al sicuro i tuoi account. Non usare l’SMS/messaggio di testo come secondo fattore per il metodo di autenticazione perché esistono anche gli attacchi di _SIM swapping_, letteralmente "scambio di SIM". Invece, installa nel tuo smartphone un autenticatore che impiega OTP (_one-time password_, cioè una password monouso) o TOTP (_time-based one-time password_, cioè una password monouso basata sul tempo).

### SIM Swapping
Il SIM swapping avviene quando qualcuno ruba la tua SIM e il tuo numero di telefono. Questi potrà poi usare il tuo numero di telefono per accedere a tutti gli account associati in cui hai attivato un metodo di autenticazione a due fattori con SMS/messaggio di testo. Il SIM swapping è un attacco diretto col fine di entrare nella tua email principale. Se chi ti attacca accede alla tua email principale, che è associata tramite 2FA al tuo numero di telefono, potrà individuare tutti gli account su exchange di Bitcoin in cui sei registrato col 2FA, e svuotarli.

L’attacco parte spesso da una chiamata al servizio clienti del tuo fornitore telefonico (Vodafone, Wind, TIM, ...). Dicono qualcosa come “Sono il proprietario di questo numero, ho perso il telefono, per favore trasferite il mio numero alla mia nuova SIM”. L’operatore del servizio clienti chiede qualche informazione personale per verificare la tua identità. I malintenzionati proveranno allora a mettere in pratica molti trucchi. Assilleranno l’operatore al fine di ottenere da lui piccoli frammenti di informazione, chiuderanno la telefonata e richiameranno un altro operatore utilizzando quei frammenti di informazione per ottenerne altri. Continueranno con questo stratagemma fino a quando non avranno ottenuto informazioni sufficienti a persuadere l’ultimo operatore che si tratti davvero del titolare del numer, e la SIM verrà dunque trasferita.

Accederanno a tutti gli exchange crypto dove potresti aver attivato un conto associato al tuo indirizzo email e numero di telefono.

Una volta a conoscenza della tua email, tenteranno di cambiare le password dei tuoi account tramite la funzione “password dimenticata”. I migliori siti web non diranno loro se l'account esiste o meno. I malintenzionati proveranno a fare il reset della password o ad ottenere una verifica tramite messaggio di testo.

**Cosa Puoi Fare – Esempio con Gmail**
Blocca l’account della tua email principale e rimuovi il numero di telefono associato al tuo account email (ad esempio Gmail). Qui puoi vedere come si fa: [https://anita.link/removegmail](https://anita.link/removegmail). Usa una password differente per ogni tuo account su ogni sito o servizio. Come utente Gmail, puoi iscriverti al Google Advanced Protection Program, che ti difende contro attacchi online mirati.

## Attacchi Phishing
Nel 2020, il database di marketing del produttore di hardware francese Ledger ha subito un attacco hacker. I dispositivi non sono stati compromessi, tuttavia migliaia di indirizzi email, numeri telefonici e perfino indirizzi di casa dei loro clienti sono stati sottratti e possono essere trovati da chiunque sul web. Questo è assolutamente disastroso, dal momento che ci sono alte probabilità che chiunque avesse ordinato un hardware wallet possedesse anche bitcoin. Nello scenario peggiore, qualcuno verrà a “farti visita” a casa. Più probabilmente, riceverai minacce via email e attacchi di phishing. Per evitare che questo accada, ricorda di non utilizzare mai il tuo indirizzo fisico per la spedizione di un prodotto legato a Bitcoin, come ad esempio un hardware wallet. Puoi richiedere una cassetta postale per te. Negli Stati Uniti ci sono servizi che possono ricevere pacchi postali al posto tuo (CMRA). Se possibile, non utilizzare nemmeno il tuo vero nome quando fai ordini. Procurati un numero di telefono secondario ed utilizza questo in caso il venditore lo richieda. Fornisci un indirizzo email usa e getta da utilizzare solo per questo specifico ordine.

Gli attacchi di phishing sono tentativi di manipolarti e spaventarti al punto da portarti ad inserire il tuo seed sul sito dell’hacker. Ad esempio, potresti ricevere un’email che dice: “Il tuo dispositivo Ledger è stato corrotto o disattivato, visita questo link ed inserisci le tue 12 parole seed per recuperare i tuoi fondi,” oppure “Abbiamo rilevato un importante prelievo dal tuo Ledger. Hai 24 ore per rispondere e confermare la validità della transazione. Siamo spiacenti, ma non possiamo connetterci al tuo Ledger, sembra sia stato corrotto. Autorizzeremo il prelievo a meno che tu non inizi il processo di recupero, fornendoci il tuo seed di 24 parole”, oppure ancora “Hai ricevuto un airdrop. I fondi raggiungeranno il tuo account, abbiamo solo bisogno di una verifica, cortesemente inizia il processo di recupero e fornisci le 24 parole del seed."
![Phishing mail](resources/_phishing-mail-ledger.png) [^70]

Il malintenzionato tenterà di farti agire velocemente e senza pensare. Se ricevi email del genere, fermati. Non fare nulla. Perché nessuno può confiscare i tuoi fondi, nessuno può disattivare il tuo hardware wallet da remoto. È proprio questo il punto di una valuta decentralizzata come bitcoin.

Non fidarti mai delle email! E soprattutto: non cliccare mai i link.

Aggiungi tra i preferiti gli indirizzi web dei siti ufficiali di Ledger, Shift Crypto, Trezor ecc. oppure digita tu il dominio direttamente nella barra degli indirizzi del browser e cerca il certificato di autenticazione SSL. I malintenzionati ti manderanno ad un indirizzo web falso che somiglia molto a quello reale. L’unica differenza è nell’URL. Un nuovo trucco è utilizzare domini recanti caratteri Unicode, che appaiono del tutto simili al dominio reale. Ad esempio, noteresti la macchiolina sotto la “l” di “electrum”? Se aprissi quell’URL crederesti di vedere electrum.org, ma staresti invece visitando xn--eectrum-9hb.org.

![](resources/_phishing.png) [^71]

Browser come Opera o Chrome ti invieranno un avviso, ma Firefox non lo fa di default. Puoi cambiare l’impostazione attivando _"punycode"_ nelle opzioni di Firefox, vedi qui una guida [anita.link/puny](https://anita.link/puny).

## Regola 3-2-1 per Conservare al Sicuro il tuo Seed
Il seed consiste in 12-24 parole in lingua inglese. Oggi sempre più wallet utilizzano 12 parole invece di 24, in quanto forniscono un livello di sicurezza sufficientemente alto e sono più facili da ricordare e conservare.

Scrivi a mano il seed su un foglio di carta quando attivi il tuo wallet per la prima volta. Assicurati che l’ordine sia corretto e controlla più volte le parole che hai scritto. Annotati il venditore, il modello e anche la versione del software del wallet. Potresti aver bisogno di queste informazioni nel caso tu volessi recuperare i tuoi fondi.

Se imposti un hardware wallet, dovresti inviargli un piccolo importo di bitcoin per assicurarti che tutto funzioni a dovere. Dopo aver ricevuto il piccolo importo, disinstalla il software dal dispositivo e reinstallalo utilizzando il seed phrase. Questo è un passaggio importante che non dovresti saltare.

In seguito, si raccomanda di prendere le seguenti misure di sicurezza al fine di prevenire la perdita del seed. Quando le persone perdono l’accesso ai propri fondi, spesso è perché perdono il seed o fanno un errore nell’annotazione delle parole, e non perché il dispositivo sia stato violato.

**3**: Annota il seed tre volte

**2**: Su almeno due supporti differenti (carta laminata, incisione o stampa su acciaio), e conservalo in un posto sicuro da fuoco, perdita e furto.

**1**: In aggiunta, conserva una copia in un luogo differente, preferibilmente ad almeno 100 km di distanza.

Jameson Lopp, uno degli ospiti del mio podcast, ha testato le placche d'acciaio che possono essere usate per tenere al sicuro i seed nel lungo termine. Li espone al fuoco e alla pressione per determinarne la longevità. Non tutti i prodotti sono fatti di acciaio o titanio, motivo per cui si sciolgono al contatto col fuoco. I risultati dei suoi test possono essere consultati a questo link: [anita.link/metalseed](https://anita.link/metalseed)

Non essere troppo creativo! Dividere le parole in due o più gruppi e conservarli in luoghi differenti è un errore tipico. Ne perdi uno, e non sarai più in grado di accedere alle tue valute.

* Non dare mai il seed a qualcuno cui non affideresti i tuoi soldi!
* Non scrivere il seed su alcun sito o dispositivo elettronico!
* Il seed non è richiesto per inviare o ricevere bitcoin.
* Nessuna persona o entità credibile ti chiederebbe mai il seed.
* Controlla regolarmente il luogo in cui stai conservando il seed!
* Attiva un piano di successione ereditaria – gli scenari peggiori possono sempre accadere, e se non istruisci a dovere i beneficiari dell’eredità, i tuoi bitcoin saranno perduti. Suggerisco il libro di Pamela Morgan "Cryptoasset Inheritance Planning".

### Passphrase o Frase d'Accesso
Oltre al seed, una frase d’accesso è un metodo aggiuntivo per la messa in sicurezza dei tuoi fondi. Se aggiungi una frase d’accesso, il software crea un wallet aggiuntivo che potrai utilizzare per proteggerti dagli attacchi fisici. Se qualcuno dovesse impossessarsi del tuo seed, non sarebbe comunque in grado di accedere ai tuoi fondi perché non avrebbe la frase d’accesso.

Un esempio: potresti voler lasciare una piccola parte dei tuoi fondi nel wallet base, quello sprovvisto di frase d’accesso, e spostare la maggioranza dei tuoi fondi in un wallet protetto dalla frase d’accesso. L’idea che ci sta dietro è che se ti dovessi mai trovare nella situazione in cui qualcuno cerca di estorcerti un riscatto o ti minaccia, potresti sbloccare il tuo wallet e fornire al malintenzionato solamente l'accesso al wallet base (che contiene solo una piccola parte dei tuoi fondi).

Sembra fantastico, ma ci sono anche dei rischi.

1. Dato che la frase d’accesso non è conservata in automatico da nessuna parte, devi prendere **tutte le precauzioni necessarie** per assicurarti che rimanga al sicuro ed accessibile, ad esempio facendone una copia fisica.
2. Se la frase d’accesso viene perduta, **non sarai più in grado di accedere a tale wallet** e tutte le valute conservate in quel wallet diventeranno inaccessibili.

Con la frase d’accesso, dovrai non solo mettere al sicuro il seed, ma anche la frase d’accesso stessa. A questo punto devi trovare un posto sicuro per il seed E la frase d’accesso, il che rende il processo ancor più complicato. Presta attenzione: per ripristinare un wallet di questo tipo, avrai bisogno del seed E della frase d’accesso utilizzate da quel wallet per ripristinare l’accesso ai fondi.

Considerato che gli attacchi fisici accadono raramente, conservare il seed col metodo 3-2-1 dovrebbe essere sufficiente.

### Backup Alternativi
Alcuni wallet usano differenti meccanismi per il backup. Ad esempio, Muun utilizza una combinazione di codici di recupero – che dovrai annotarti come il seed – e un kit d’emergenza.

## Imparare Facendo
Iniziare ad usare Bitcoin può sembrare spaventoso perché si tratta di soldi veri. Ecco perché è buona pratica iniziare con importi molto piccoli.

Per la tua prima prova, installa un wallet nel tuo smartphone, cerca un [ATM Bitcoin](https://anita.link/atm) vicino a te, o partecipa a un Bitcoin meet-up locale per scambiare piccole somme. Prepara un wallet sul tuo computer e invia bitcoin tra i tuoi due wallet a indirizzi differenti.

Il momento migliore per fare queste operazioni è solitamente nel fine settimana, quando la Mempool non è congestionata di transazioni e le fee sono più basse.

Utilizza wallet differenti, reinstalla il seed dal wallet A al wallet B, usa il seed su dispositivi diversi. Affinando la tecnica, ti sentirai sempre più sicuro.

### Testare l’Indirizzo di Ricezione
Prima di inviare una somma importante per la prima volta, assicurati che l’indirizzo del ricevente sia corretto effettuando una piccola transazione di test. Controlla sempre l’indirizzo Bitcoin due o tre volte prima di eseguire la transazione. Compara i primi e gli ultimi caratteri dell’indirizzo ricevente. I bitcoin inviati a un indirizzo incorretto sono perduti.

### Testare il Tuo Hardware Wallet

Prima di depositare grandi importi in un nuovo hardware wallet, dovresti controllarne le funzionalità e il seed.

Quando attivi il dispositivo per la prima volta, viene generato il seed che dovrai annotarti a mano (assieme al nome del venditore, il modello e la versione del software). In seguito, utilizzerai il software del produttore (o un altro software, come Electrum) per creare il primo indirizzo Bitcoin nel tuo hardware wallet cliccando su “Ricevi”. Dopodiché, invierai al tuo hardware wallet una piccola cifra dal tuo wallet su smartphone, precedentemente installato. Se la cifra sull'hardware wallet giunge a destinazione – status “Confermato” - il primo test è superato con successo.

Prova anche un trasferimento dal tuo hardware wallet ad un altro wallet. Ad esempio, puoi inviare una piccola cifra al tuo wallet su smartphone, oppure ad un altro indirizzo del tuo hardware wallet. Non c’è molta differenza. La cosa importante è testare un pagamento che parta dal tuo hardware wallet. Per fare ciò, devi verificare l’indirizzo di ricezione nell'hardware wallet e confermare l’invio cliccando direttamente sull'hardware wallet. Questa conferma manuale sul dispositivo rende gli hardware wallet sicuri, in quanto solamente tu puoi premere i pulsanti e nessuno può premerli virtualmente tramite internet.

**Ripristinare il Tuo Wallet**
Assicurati di avere il tuo backup/seed! Poi cancella tutti i dati dal tuo hardware wallet. Alcuni produttori chiamano questa opzione _“Factory reset”_, _“Wipe”_ o _“Reset the device”_. Il tuo wallet si svuoterà. Ora devi recuperare i tuoi fondi e il wallet tramite il seed. Questa opzione è chiamata _“Restore from recovery word”_, _“Restore wallet”_, oppure _“Import seed”_. Inserisci la frase d'accesso nel dispositivo hardware. Se tutto è andato a buon fine, il wallet sarà ripristinato e potrai visionare lo storico delle transazioni e il saldo.

**Aggiornamento di Firmware e Software**
Non limitarti a chiudere il wallet al sicuro da qualche parte. Dovresti cercare aggiornamenti al software o miglioramenti del firmware almeno ogni 6 mesi. L’ambiente crypto è in rapido movimento, vengono regolarmente integrati nuovi sviluppi nel software dei wallet.

## Smartphone Smarrito? Computer Rubato?

### Smarrimento, Furto, o Malfunzionamento del Tuo Dispositivo

Se il tuo dispositivo viene rubato, ricordati che i tuoi bitcoin sono ancora registrati sulla blockchain in corrispondenza della tua chiave privata. Dato che hai impostato un PIN sul wallet, il ladro non potrà aprirlo. Tenterà comunque di trovare un modo per scoprire il tuo PIN.

Dovresti immediatamente installare un nuovo wallet e importare il seed che hai tenuto al sicuro, al fine di riacquisire l'accesso ai tuoi fondi (vedi l’opzione _“Restore your wallet”_). Dopodiché sposta le valute dal wallet che ti è stato rubato ad un nuovo indirizzo Bitcoin nel tuo nuovo wallet non appena possibile, ripetendo la stessa procedura di configurazione di sicurezza per il nuovo wallet.

Se il tuo dispositivo viene violato, segui gli stessi passaggi senza bisogno di affrettarsi a spostare le tue vlaute. Basta che ripristini il software wallet, e hai finito.

[^70]: Anita Posch  
[^71]: [Source @ElectrumWallet](https://twitter.com/ElectrumWallet/status/1144678604523147265?s=20)

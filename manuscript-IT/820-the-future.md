# Il futuro è adesso

> "Il futuro è un cantiere in costruzione." - Anita Posch

Ora che hai una comprensione più profonda di Bitcoin e di come usarlo, possiamo esplorare gli sviluppi futuri che io ritengo avranno un enorme impatto. Questa sezione è stata redatta in collaborazione con Mark Kersley, con parti estratte dalla video intervista con Andreas M. Antonopoulos: [Bitcoin, Layer 2 Solutions, and the Wild West of Crypto](https://youtu.be/TsbIMg-YHQk)

## Finanza decentralizzata – DeFi
Una nuova ed affascinante categoria di applicazione prende il nome di finanza decentralizzata, o DeFi. La finanza decentralizzata si pone l’obiettivo di espandere il concetto di libertà monetaria ispirata ed offerta da Bitcoin, introducendo questa caratteristica all’intero ecosistema crypto. È ideale possedere bitcoin o altri asset decentralizzati, ma quando la maggioranza delle persone intendono acquistare, vendere oppure solamente mantenere i loro asset a lungo termine, di norma si affida ad un’entità centralizzata come un exchange. 

Rivolgendosi ad un’entità centralizzata, queste persone si espongono al rischio del KYC, riserva frazionaria, attacchi esterni e manipolazioni interne. La DeFi offre un’alternativa trustless tramite l’uso di smart contract programmabili. Gli asset crypto sono digitali e, in quanto tali, sono programmabili. Le piattaforme DeFi utilizzano contratti pre-programmati per eseguire funzioni che precedentemente erano solamente appannaggio di entità centralizzate, quali swap, trading a margine, prestito, staking e molto altro. Rimuovendo l’intermediario centralizzato utilizzando contratti pubblicamente visionabili, la DeFi provvede a fornire un livello finanziario più equo all’ecosistema crypto. Le possibilità della DeFi sono in una continua fase di scoperta e sviluppo. Un giorno, l’intero sistema finanziario globale potrà essere decentralizzato. 

La maggioranza delle applicazioni DeFi sono sviluppate ed eseguite sulla rete Ethereum (ETH) – il secondo asset crypto per capitalizzazione al momento in cui scrivo. La programmazione su Ethereum è di facile esecuzione, e si focalizza sullo sviluppo di smart contract in linguaggio Solidity. Pertanto, è risultato essere l’incubatore perfetto per le piattaforme DeFi negli ultimi anni. Casi d’uso popolari di DeFi su Ethereum sono state le borse di scambio decentralizzate (_DEX, decentralised exchange_), le piattaforme di prestito e le _stablecoin_ quali lo USDT. 

Le piattaforme DeFi possono utilizzare token provenienti da altre blockchain tramite un processo denominato _wrapping_. Questo prevede l’invio di un asset nativo di un’altra blockchain ad uno smart contract che ne àncora il valore ad un tasso di cambio fisso (_peg_). Usiamo 1 bitcoin come esempio. Il peg fisserà il bitcoin inviato e conierà la versione equivalente di quel bitcoin nella rete Ethereum. Un esempio di questo processo sono i wrapped bitcoin (WBTC) e i Ren bitcoin (renBTC). Questi token possono essere impiegati in applicazioni DeFi in luogo dell’asset originario, e dato che lo smart contract mantiene l’asset d’origine, non possono manifestarsi situazioni di doppia spesa. Se un utente volesse muovere il proprio asset verso la propria blockchain nativa, lo smart contract brucerà (un processo denominato _burn_) il token coniato ed invierà all’utente l’asset originario alla sua blockchain nativa. Questo meccanismo consente a potenzialmente ogni token di poter essere impiegato in ambiente DeFi.

Lo sviluppo di Bitcoin è lento e ha un approccio conservativo se paragonato ad altre blockchain come Ethereum. Per un buono motivo: la sicurezza. Ma gli sviluppatori di Bitcoin non sono rimasti fermi con le mani in mano – oltre al Lightning Network, sono state sviluppate molte piattaforme ed applicazioni native di Bitcoin.

### Bitcoin – Protocolli nativi e piattaforme

#### Rootstock
Rootstock (RSK) è una rete che si pone l’obiettivo di portare le capacità degli smart contract su Bitcoin. Il mining è combinato con quello di Bitcoin (un processo chiamato _merged mining_), ciò significa che circa il 40 al 75% dei miner Bitcoin processa transazioni della rete RSK. Significa inoltre che RSK è messo in sicurezza da un grado di potenza computazionale maggiore rispetto ad ogni altra blockchain al mondo, chiaramente escludendo Bitcoin. Similmente alle soluzioni di Ethereum, RSK impiega il processo di wrapping per introdurre bitcoin nella rete. Siccome la rete è in mining combinato dai miner di Bitcoin, può essere dunque considerata come il network attualmente più sicuro e trustless per sviluppi DeFi. È un’attrattiva per i bitcoiner e per tutti coloro siano desiderosi di soluzioni DeFi per Bitcoin, ma che non vogliono rinunciare alla decentralizzazione, all’assenza di fiducia, e alla sicurezza offerta dalla rete Bitcoin. 

Rootstock è in sviluppo dal 2014 e ha rilasciato la propria rete principale nel 2018. Il network RSK ha un tempo veloce di creazione del blocco, la cui processazione impiega 15-30 secondi. Le applicazioni si possono costruire su RSK utilizzando tecniche simili ad Ethereum, sfruttando il linguaggio di programmazione Solidity. Il prezzo del gas di RSK è significativamente minore di Ethereum; al momento in cui scrivo, il costo delle transazioni Ethereum hanno una media di 60$ mentre quelle di RSK hanno una media di 0.50$. In ragione della sua velocità e potenzialità di personalizzazione, dei _rollup_ possono essere introdotti nelle applicazioni sviluppate su Rootstock al fine di ridurre ulteriormente la velocità e i costi di transazione, potenzialmente ad importi come 0.0.1$ a transazione. 

#### Sovryn
Sovryn è un esempio di piattaforma programmata sulla rete Rootstock. Sovryn sta sviluppando una piattaforma DeFi per bitcoin, ma anche per molti altri asset tramite un ponte (_bridge_) con altre blockchain, incluso Ethereum e la Binance Smart Chain (BSC).  È un sistema non-custodial ed in assenza di autorizzazione che si basa sugli smart contract, ed è principalmente usato per attività di prestito in bitcoin e di trading a margine. Sovryn non applica alcun KYC e non chiede mai di custodire i tuoi fondi, *not your keys, not your coins!*. Attualmente propone un mercato spot a costi accessibili, trading a margine, strumenti di prestito, forniture di liquidità, e qualche funzionalità di token non-fungibili (_NFT_). L’impiego della funzione FastBTC Relay consente di convertire rapidamente bitcoin in Rootstock Smart Bitcoin (rBTC) per l’uso in Sovryn. Futuri sviluppi vedranno l’arrivo in Sovryn di molteplici asset da molteplici blockchain, come anche un mercato di NFT, piattaforme di lancio di nuovi token, contratti perpetui e stablecoin sovra-collateralizzate garantite da bitcoin. La visione di Sovryn non è di essere come un’altra piattaforma DeFi, ma il sistema operativo finanziario del mondo.

Sovryn non è una società o un’entità centralizzata. Consiste in svariati collaboratori il cui obiettivo è creare quel livello monetario in assenza di fiducia che idealmente avrebbe dovuto essere stato costruito molto tempo prima. Sovryn assicura la _governance_ decentralizzata del protocollo per mezzo di una forma di sistema democratico denominato Bitocracy, una versione evoluta di vetocrazia. Questo implica lo staking di token SOV in cambio di potere di voto e ricompense di fee. Per essere implementate, tutte le decisioni a livello di protocollo devono superare il processo di votazione nella Bitocracy. Il meccanismo di staking assicura che i votanti siano incentivati a spendere il proprio voto consapevole a favore di proposte che beneficino l’ecosistema di Sovryn, e in opposizione a proposte deleterie. Al momento in cui scrivo, Sovryn ha appena iniziato la compravendita del proprio token ed è in procinto di rilasciare molteplici ponti e nuove funzioni. Sarà interessante osservare come si svilupperà il progetto.

In una intervista, il fondatore Edan Yago ha esplorato molti di questi argomenti – ascoltala al link anita.link/105

#### Thorchain
Similmente a Sovryn, Thorchain è stata fondata sulla consapevolezza che le soluzioni centralizzate per il trasferimento della proprietà delle criptovalute siano fondamentalmente fallate. Nata nel 2018, Thorchain è stata creata per sostituire gli exchange centralizzati (CEX) e per facilitare gli exchange crypto decentralizzati (DEX) _cross-chain_. Thorchain connette blockchain differenti tramite il ponte cross-chain dal nome tematico Bifröst Protocol. Bifröst consente lo swap di token nativi attraverso blockchain differenti, ossia significa che non vi è necessità di versioni sintetiche o wrappate dei token. Di cruciale importanza è il fatto che Thorchain è non-custodial e decentralizzato al 100%. 

Thorchain opera similmente ad altri DEX come Sovryn; utilizza un modello di liquidità automatico (_AMM, automated market maker_) per processare e mantenere gli scambi. Tuttavia, Thorchain non si appoggia su una blockchain terza, come ad esempio Sovryn gira su RSK. Thorchain si appoggia sulla propria blockchain indipendente, programmata utilizzando Cosmos SDK. Questo ha permesso a Thorchain di forzare il suo token RUNE come l’asset base per gli swap, di modo che ogni coppia di token deve essere un _pair_ RUNE-x. Pertanto, gli utenti sono in grado di effettuare swap, ad esempio, tra BTC e ETH tramite il token RUNE che funge da intermediario. Ciò comporta una funzione di swap da BTC a RUNE, e un conseguente swap da RUNE a ETH. Questo ha consentito all'utility del token RUNE di assumere valore: RUNE può essere usato per fornire liquidità alle pool AMM in cambio di una frazione delle fee, e si presta anche ad essere speculato e scambiato nel mercato aperto.

#### Babelfish Money
Nell’ambito crypto, ci sono molti token ancorati ad un sottostante che sono comunemente chiamati ‘stablecoin’. Sono molto popolari e vengono normalmente impiegati per conservare, utilizzare e trasferire valore con minima volatilità a breve termine. Ci sono molte stablecoin ancorate al dollaro americano come Tether (USDT), US Dollar Coin (USDC), Binance USD (BUSD) e DAI, tutte progettate per conservare il valore di $1.00 per token. Sebbene queste stablecoin siano un elemento molto utile dell’ecosistema crypto, avere stablecoin differenti su reti differenti rappresenta un ostacolo per la fluida liquidità tra piattaforme. 

Prendendo il nome dal Pesce di Babele, il traduttore universale dalle sembianze ittiche della _‘Guida galattica per gli autostoppisti’_ di Douglas Adams, Babelfish intende agire come aggregatore cross-chain per tutte le stablecoin. La visione è quella che tutti quanto saranno in grado di usare Babelfish per convertire le varie stablecoin tra loro, e tutte saranno garantite da Bitcoin. 

Il processo ricalcherà i classici passaggi dell’emissione dei token stablecoin a partire da fiat: un utente invierà un tipo di stablecoin, e il protocollo conierà per l’utente una stablecoin (XUSD) convertibile. Il protocollo investirà la stablecoin originaria attraverso piattaforme DeFi al fine di generare rendimenti, che a loro volta finanzieranno la governance e una pool assicurativa sul layer 2 di bitcoin; il rendimento sarà reinvestito settimanalmente nella pool bitcoin - l’asset assicurativo per eccellenza - della comunità. 

La governance del protocollo è controllata dalla community. Ogni volta che qualcuno utilizzasse il protocollo e ricevesse XUSD coniati, riceverebbero inoltre token FISH. FISH è il token di governance dal quale viene attribuito il potere di voto. Pertanto, gli utenti possono votare la direzione del protocollo utilizzando questi token FISH.

Babelfish lancerà la vendita iniziale del token nella piattaforma Origin di Sovryn – una piattaforma di lancio decentralizzata regolata dalla Bitocracy di Sovryn.

#### Money on Chain
Money on Chain (MoC) è un protocollo DeFi che comprende quattro token. L’idea è quella di provvedere a fornire più opzioni ai bitcoiner, migliorare la performance dei loro bitcoin, e fornire dei casi d’uso permettendo comunque il controllo completo delle proprie chiavi private. Anche Money on Chain opera sulla rete RSK, focalizzando la propria attenzione in Bitcoin.

Il primo token che offre MoC è Dollar on Chain (DoC). È il primo token collateralizzato al 100% da bitcoin, e ancorato 1:1 al dollaro americano. 

BPRO è un token che permette rendimenti passivi tramite la condivisione distribuita di profitti aggregati in pool, ed altro. Chi detiene BPRO può beneficiare di leve a lungo termine gratuite, per gentile concessione di chi detiene token DoC. I detentori di BPRO inoltre guadagnano dall’estrazione di liquidità (_liquidity mining_) e dalle commissioni generate dal protocollo MoC. Essenzialmente, mantenere BPRO è come mantenere una posizione di bitcoin con leva a lungo termine, mentre guadagni un reddito passivo dal tuo bitcoin.

Il terzo token offerto da MoC è uno strumento BTC/USD chiamato BTCx. BTCx è essenzialmente una rappresentazione _tokenizzata_ di una posizione di bitcoin con leva a lungo termine. Questi token vengono coniati quando un utente invia BTC allo smart contract, e gli viene attribuito un costo dal tasso d’interesse variabile (che è fisso alla creazione del contratto). Il pagamento dell’interesse va a chi detiene ₿PRO.

Infine, il protocollo MoC include anche un token di governance, convenientemente denominato token Money on Chain (MOC). Permette a chi detiene i MOC in stake di ottenere potere di voto/veto e ricompense, entrambe generate dalle fee pagate in seno alla piattaforma e nell’ambito dall’estrazione di liquidità. Gli utenti sono intitolati a uno sconto delle fee di piattaforma quando impiegano il token MOC al fine di un pagamento. 

In conclusione, Money on Chain è un ecosistema Bitcoin autosufficiente su RSK che mira a fornire multipli casi d’uso decentralizzati e non-custodial per bitcoiner nello specifico.

#### Liquid Network
Liquid Network è una rete federata per il settlement di transazioni basata su una sidechain per individui e borse di scambio, che consente transazioni Bitcoin più rapide e confidenziali nonché l’emissione di asset digitali. È una blockchain separata che estende le funzionalità di bitcoin con tecnologie di ulteriore livello. Liquid non impiega il proof-of-work, i blocchi sono validati e firmati da 15 funzionari ogni minuto. Il grado di privacy viene aumentato tramite l’uso di transazioni e asset confidenziali, per i quali l’ammontare e il tipo di asset trasmesso rimane nascosto mentre viene comunque crittograficamente garantito che non possano essere spese più monete di quante ne siano disponibili.

Ci sono vari casi d’uso per Liquid: 
* Velocità di transazione tra exchange
* Le persone possono utilizzare L-BTC coi wallet Blockstream Green, Aqua, Elements o Sideswap
* L’exchange peer-to-peer HodlHodl utilizza L-BTC per il proprio servizio di prestito
* L’exchange decentralizzato Bisq integrerà L-BTC nel suo livello base
* Chiunque può creare nuovi asset, incluse stablecoin come Tether USDT (già supportati da Liquid) e token che possono essere comprati e venduti liberamente all’interno della rete

Liquid dimostra che puoi fare qualsiasi cosa con Bitcoin. Non necessiti di una nuova blockchain o di un nuovo token. La valuta nativa di Liquid è L-BTC, bloccherai il tuo bitcoin e in cambio riceverai il medesimo ammontare in L-BTC. Pertanto, ci saranno solamente 21 milioni di L-BTC. Le transazioni in Liquid sono più economiche, più veloci e più private di quelle di bitcoin. Sebbene sia una sidechain federata, le transazioni non possono essere censurate. I funzionari sono delle scatole nere che possono essere disattivate solamente dagli operatori. Il compromesso è che le transazioni di disancoramento (_peg-out_) nella blockchain di Bitcoin devono essere processate da un membro Liquid.

#### RGB
RGB è un sistema di smart contract che lavora su Layer 2 e 3 di Bitcoin e del Lightning Network. È progettato con in mente la confidenzialità e la scalabilità.

I possibili casi d’uso sono:
-   Emissione di asset digitali fungibili, come azioni, obbligazioni e altre forme di valori mobiliari
-   Creazione di differenti forme di oggetti da collezione (asset non-fungibili)
-   Creazione e amministrazione di identità sovrane/decentralizzate
-   Progettazione ed esecuzione di altre forme di smart contract arbitrari e complessi

Le capacità dei contratti RGB vanno oltre ciò che è possibile fare col sistema di smart contract in stile Ethereum, fornendo un approccio più stratificato, scalabile, privato e sicuro, per il quale la proprietà dello stato dello smart contract viene separata dalla creazione dello stesso smart contract.


## NFT
L’altra categoria che ritengo sia estremamente interessante è rappresentata dagli NFT, o token non-fungibili. Sono token che invece di rappresentare unità di valuta, rappresentano oggetti unici, elementi o proprietà in una forma che è distinguibile l’una dall’altra, e sono pertanto non-fungibili. Pensiamo a un’opera d’arte che è rappresentato da un documento contrattuale. Quel documento può essere un token digitale che può essere compravenduto come bitcoin, o pensa all’atto notarile della tua casa, o della tua macchina, o di un qualsiasi altro oggetto o specifico appezzamento di terreno. Si tratta praticamente di prendere cose che esistono nel mondo reale o prendere proprietà intellettuali digitali – come una canzone o un marchio – e tokenizzarlo di modo che divenga qualcosa che possa essere compravenduto digitalmente. Non abbiamo che solamente sfiorato la superficie di tutto questo discorso.

La prima piattaforma NFT progettata su Bitcoin fu Counterparty, fondata nel 2014, ancora prima di Ethereum. Negli ultimi mesi, sono comparse sempre più piattaforme NFT basate su Bitcoin. Raretoshi e Azool.art sono piattaforme NFT che si basano su Liquid Network. Su Watafan, le carte che hanno valore collezionistico si poggiano sugli smart contract di Rootstock. Sovryn e RGB stanno sviluppando piattaforme NFT al momento in cui scrivo questo libro.

## Governance
E infine, la terza categoria che mi rende entusiasta per il futuro è l’opportunità di applicare tutto ciò nelle aree dell’identità e della governance dell’essere umano. L’abilità di tokenizzare l’identità umana, dove non hai più bisogno di rivelare chi sei ma puoi scegliere di rivelare alcuni aspetti alla volta. Posso provare che ho una laurea universitaria utilizzando un token non-fungibile senza riferirti il mio nome. Posso provare che ho la patente di guida senza fornirti dettagli sulla mia intera storia. Posso provare che ho merito creditizio, o che sono affidabile, vaccinato o qualsiasi altra caratteristica tu possa immaginare. Tutti questi vari token che puoi assegnare alle persone permettono di avere il pieno controllo di queste facoltà, non c’è bisogno di un governo o di una società come Facebook per dimostrarlo. Inoltre, puoi usare questi token ai fini di governance. L’abilità di votare all’assemblea di condominio, all’associazione genitori-insegnanti, al mio comune, e più su fino alle elezioni delle Nazioni Unite come uno fra i 7 miliardi e mezzo di cittadini di questo pianeta aventi un voto tramite token digitale. Con queste tecnologie, cambiamenti radicali verso la democrazia diretta sono possibili. 

Questi sono temi che verranno discussi tra 10, 15, 20, 25 anni nel futuro. Ma se comprendi come funziona questa tecnologia, e vedi i semi che stiamo piantando oggi, potrai vedere a questi argomenti come uno sviluppo naturale germogliato da queste tecnologie.






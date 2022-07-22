# Bitcoin verwenden

## Transaktionsgebühren
Für jede Bitcoin-Transaktion muss eine Mining-Gebühr gezahlt werden. Diese Gebühren sind für den Fortbestand des Bitcoin-Netzwerks erforderlich. Die Arbeit der Miner wird mit diesen Gebühren und neu geschürften Bitcoin belohnt (siehe Kapitel 2.3). Mining ist ein wesentlicher Faktor im Bitcoin-Protokoll. Nachdem ein Block von Transaktionen gemined wurde, wird er an die Blockchain angehängt. Auf diese Weise wird die Sicherheit des Netzwerks gewährleistet. Da Bitcoin auf maximal 21 Millionen Coins limitiert ist, würden die Miner nach Erreichen dieser Menge keine Vergütung mehr für ihre Leistung erhalten und wären nicht mehr daran interessiert, Transaktionen zu verarbeiten und damit die Blockchain zu erhalten. Daher führte Satoshi Nakamoto zusätzlich Transaktionsgebühren ein. Dem Whitepaper zufolge ist es das Ziel, diese Gebühren niedriger zu halten als die vergleichbaren Gebühren und Kosten des traditionellen Bankensystems. Es ist jedoch nicht so, dass die Transaktion kostenlos ist, nur weil es theoretisch keine Zwischenhändler oder Banken benötigt.

Wenn Sie Bitcoin über eine Börse kaufen, ist die Transaktionsgebühr (Mining-Gebühr) normalerweise nicht verhandelbar und wird vom Anbieter festgelegt.

In Ihrer non-custodial Bitcoin-Wallet können Sie die Transaktionsgebühr für ausgehende Zahlungen selbst bestimmen. Je höher Sie die Gebühr ansetzen, desto schneller wird Ihre Transaktion von den Minern bearbeitet, da diese die Transaktionen mit den höchsten Gebühren zuerst auswählen. Wenn Ihre Transaktion nicht zeitkritisch ist, können Sie eine niedrigere Gebühr wählen.

Für mehr Kontrolle können Sie die Gebühr und die Bestätigungsgeschwindigkeit auf Seiten wie [Mempool.space](https://mempool.space/) oder [Johoe's Bitcoin Mempool](https://jochen-hoenicke.de/queue/) im Vorhinein prüfen. Diese Websites zeigen die Anzahl und Größe aller unbestätigten Transaktionen an. Sie bieten eine Echtzeit-Ansicht und zeigen, wie sich der Mempool entwickelt. Die Transaktionen sind nach der Höhe der Gebühr, die sie pro (virtuellem) Byte zahlen, eingefärbt.

![Echtzeit-Ansicht der unbestätigten Transaktionen](resources/_Mempool-space-white-back.png) [^74]

Unten sehen Sie die Einstellungen in der Edge-Wallet. Sie können einen der Bereiche der Standard-Transaktionsgebühr oder einen eigenen Wert wählen.

[Einstellungen für Transaktionsgebühren in der Edge-Wallet](resources/_transaction-fee-setting.png) [^75]

**Ausstehende Transaktion**
Da ungefähr alle 10 Minuten neue Blöcke gemined werden, dauert es im Durchschnitt mindestens 10 Minuten, bis Ihre Transaktion bestätigt wird. Wenn Sie die Transaktionsgebühr zu niedrig ansetzen, kann es sein, dass Ihre Transaktion länger aussteht, da der Mempool geleert wird und die Miner beginnen, Transaktionen mit niedrigeren Gebühren wieder aufzunehmen. Hier sehen Sie eine meiner Transaktionen, die seit einem Monat im Mempool gefangen ist.
![Ausstehende Transaktion](resources/_Pending-transaction-edge.png) [^76]
Sie können den Status Ihrer Transaktion in einem [Blockchain-Explorer](https://blockchair.com) ansehen. Wie Sie unten sehen können, ist meine Transaktion 4.717 Ränge davon entfernt, gemined zu werden, bei insgesamt 41.610 Transaktionen im Mempool. Ich habe eine Gebühr von 5 Sat pro Vbyte gewählt.
[Transaktionsstatus wie im Blockexplorer angezeigt](resources/_Pending-transaction-explorer.png) [^77]

Sie müssen die folgenden Schritte nicht ausführen, um Ihre ursprüngliche Transaktion bestätigen zu lassen. Die meisten Transaktionen mit niedrigen Gebühren bleiben tagelang gültig und werden schließlich bestätigt. Es gibt jedoch zwei Möglichkeiten, das Problem der stecken gebliebenen Transaktion zu lösen und sie früher bestätigen zu lassen.

**Eine gesendete Transaktion bleibt stecken**
* Replace-by-fee (RBF): Bei einigen Wallets können Sie diese Option auf "Ja" setzen, bevor Sie eine Transaktion senden. In diesem Fall können Sie, falls die ursprüngliche Transaktion stecken bleibt, eine höhere Gebühr festlegen und die Transaktion erneut senden.

**Eine eingehende Transaktion bleibt stecken**
* Kind zahlt für Elternteil (CPFP): Angenommen ein Elternteil besitzt nicht genug Geld für eine Ausgabe, sodass das Kind die Differenz im Namen des Elternteils bezahlt. CPFP ist eine Technik, mit der Sie Ihre langsam eintreffenden Transaktionsbestätigungen beschleunigen können, indem Sie eine neue Transaktion mit höheren Gebühren (Kind-Transaktion) mit den UTXOs der vorherigen, feststeckenden Transaktion (Eltern-Transaktion) durchführen.

Detaillierte Anweisungen dazu finden Sie in der Dokumentation der von Ihnen verwendeten Wallet.

## Etwas mit Bitcoin kaufen
Hier sind einige Verzeichnisse mit Geschäften, in denen Sie mit Bitcoin bezahlen können.
* [Accepted here](https://www.acceptedhere.io)
* [B2B-Dienste, die BTC akzeptieren](https://cryptwerk.com/companies/b2b/btc/)
* [Coinmap](https://coinmap.org/view/) physische Geschäfte, die Bitcoin akzeptieren
* [Spending Bitcoin](https://spending-bitcoin.com/) Verzeichnis
* [UseBitcoins](https://usebitcoins.info/) Verzeichnis

## Bitcoin-Debitkarten
Mit einer Bitcoin-Debitkarte können Sie wie mit jeder anderen Bank-Debitkarte einkaufen. Der Unterschied ist, dass sie mit Bitcoin oder Altcoins aufgeladen wird. Die Händler werden von der Debitkartengesellschaft in Euro bezahlt, während der Betrag von Ihrem Bitcoin-Guthaben abgezogen wird, sodass Sie ausschließlich mit Bitcoin leben können.

Sie müssen Ihre Bitcoin beim Debitkartenunternehmen hinterlegen, d.h. Sie geben die Kontrolle über Ihre Coins an einen Dritten ab. Zahlen Sie nur so viel auf die Karte ein, wie Sie benötigen, und prüfen Sie die Gebühren, die diese Kartenunternehmen verlangen.

Eine kurze Liste von Karten, die derzeit verfügbar sind:
Cryptocom Visa, Binance, Bitpanda Visa, Coinbase Visa, Wirex Visa, BlockCard, Cryptopay, Nexo, Bitwala Visa, BitPay Visa, Cash App

## Ausgeben und Empfangen
Im Folgenden finden Sie Tools und Dienste, mit denen Sie alltägliche Zahlungen in Bitcoin tätigen und empfangen können.
* [Bity](https://bity.com/products/crypto-online-bill-pay/) Rechnungen online mit Bitcoin bezahlen
* [Cash App](https://cash.app/bitcoin) Kaufen und verkaufen Sie BTC direkt von Ihrem Cash App-Guthaben
* [Strike](https://global.strike.me/) Senden und empfangen Sie internationale Zahlungen über vollen Zugang zum Bitcoin-Netzwerk
* [Swapin](https://www.swapin.com/) Bezahlen Sie in Euro mit Ihrer Kryptowährung
* [Bitrefill](https://www.bitrefill.com/?hl=en) Kaufen Sie Geschenkgutscheine und Telefonaufladungen

[^74]: [Screenshot von Anita Posch](https://mempool.space)

[^75]: Screenshot von Anita Posch, Edge-Wallet

[^76]: Screenshot von Anita Posch, Edge-Wallet

[^77]: Screenshot von Anita Posch, Blockchair

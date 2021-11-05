## Sichern Sie Ihr Geld

Wie im vorherigen Kapitel erwähnt, ist es unser Ziel, die Stufe "Ihre Schlüssel, Ihre Münzen" zu erreichen.

Um Bitcoin zu kaufen, zu verwenden und aufzubewahren, benötigen Sie:

* Bitcoin-Wallet = Ihr digitales Schließfach. Eine genauere Analogie ist ein digitaler Schlüsselbund für Ihre Spardosen.
* Bitcoin-Adressen = eine oder mehrere eindeutige Adressen für Ihr Geld auf der Blockchain, Ihre Empfangsadressen (genauer gesagt eine nicht ausgegebene Transaktionsausgabe UTXO)
* Seed = die Wiederherstellungsdaten für Ihre Bitcoin-Wallet.

### Bitcoin Wallet
Stellen Sie sich eine Wallet wie ein öffentliches Schließfach mit mehreren Abteilungen vor. Jeder kann Geld in jedes der Fächer einzahlen. Nur der Besitzer der privaten Schlüssel kann ein Fach aufschließen und das darin befindliche Geld bewegen. Ihre Bitcoin-Brieftasche besteht aus allen Abteilungen und enthält alle privaten Schlüssel, um sie zu entsperren. Private Schlüssel und Bitcoin-Adressen werden aus dem Seed generiert. Der Seed ist die Wurzel aller Schlüssel und Adressen, er ist wie ein Eimer, in dem alle Ihre privaten Schlüssel gespeichert sind.

[Begriffsdefinitionen](assets/_seed-postbox.png) [^69]

Die Wallet ist eine App auf Ihrem Telefon oder eine Software auf Ihrem Computer, die alles im Hintergrund erledigt - Ihre privaten Schlüssel, Ihre Adressen und das Senden und Empfangen von Bitcoin.

Bitcoin-Wallets enthalten Schlüssel, keine Münzen. Jeder Benutzer hat eine Brieftasche mit Schlüsseln. Wallets sind eigentlich Schlüsselbunde mit Paaren von privaten/öffentlichen Schlüsseln. Ihr Geld wird in der Bitcoin-Blockchain gespeichert.

### Bitcoin-Adresse
Um Bitcoin zu erhalten, benötigen Sie eine Bitcoin-Adresse, an die Ihnen jemand Bitcoin schicken kann. Die Bitcoin-Adresse besteht aus einer langen Reihe von Ziffern und Buchstaben.

Ein Beispiel für eine Bitcoin-Adresse: 346n4apJCQPg2XAXU3bfNQTogz4PyTkrEf

Das Eintippen von 34 Ziffern ist natürlich sehr unpraktisch, daher werden häufig QR-Codes der Adressen verwendet, die in der Regel automatisch von Ihrem Wallet erstellt werden.

![BTC-Adresse als QR-Code](assets/_address-book.PNG)

Bitcoin ist pseudonym, d. h. Sie müssen weder Ihre E-Mail-Adresse noch Ihre persönliche Identifikation mit einer Wallet verbinden. Die Bitcoin-Blockchain ist jedoch transparent, was bedeutet, dass Ihre Bitcoin-Adressen im Internet öffentlich einsehbar sind. Sie können zum Beispiel bei Blockcypher danach suchen und alle aktuellen Transaktionen und Werte einsehen. Hier ist ein Beispiellink: [https://anita.link/explorer](https://anita.link/explorer)

Geben Sie daher aus Gründen des Datenschutzes Ihre Bitcoin-Adressen nicht in Verbindung mit Ihrer Identität im Internet bekannt. Die Privatsphäre ist auch der Grund, warum Sie Adressen nicht wiederverwenden sollten. Die meisten Bitcoin-Wallets stellen Ihnen für jede Transaktion automatisch eine neue Adresse zur Verfügung.

Kommen wir nun zum wichtigsten Teil der Sicherung Ihrer Bitcoin: dem Seed.

### Seed und Private Keys

Da der Seed die Wurzel aller privaten Schlüssel ist, darf niemand sonst Zugang zu ihm haben. Die Person, die den Seed kennt, hat die ultimative Kontrolle über das Geld.

Der Seed (manchmal auch mnemonische Phrase oder Backup-Phrase genannt) ist eine Folge von 12 oder 24 englischen Wörtern, die Ihnen Zugang zu den privaten Schlüsseln Ihrer Wallet-Adressen und damit zu Ihren Münzen verschafft. Das bedeutet, dass diese Reihenfolge der Wörter geheim bleiben muss. Jeder, der den Seed kennt, kann auf Ihre Münzen zugreifen und sie übernehmen. Warum ist das so?

Ihre Münzen befinden sich nicht in Ihrer digitalen Brieftasche, so wie sie in Ihrer normalen physischen Brieftasche sind. Stattdessen werden sie in der Blockchain gespeichert. Vergleichen Sie dies mit einer E-Mail und einem Brief. Sie können von überall auf der Welt auf Ihr E-Mail-Konto zugreifen, weil Ihre E-Mails online gespeichert sind, während Ihr Briefkasten stationär ist. Dies gilt in ähnlicher Weise für Bitcoin.

Der weltweite Zugriff auf Ihr Vermögen ist mit dem Seed immer möglich, unabhängig vom Hersteller Ihrer Wallet. Achten Sie bei der Auswahl Ihrer Wallet auf den Begriff "HD-Wallet" (Hierarchical Deterministic). HD-Wallets ermöglichen es Ihnen, zu einer HD-Wallet eines anderen Herstellers zu wechseln, den Seed zu nehmen und Ihre Münzen wiederherzustellen.

Angenommen, Ihr Smartphone wird beschädigt, Sie können nicht mehr auf Ihre Bitcoin-Wallet-App zugreifen und müssen auf ein neues Telefon wechseln. Sie installieren eine neue Version Ihrer Bitcoin-Wallet und importieren den Seed aus Ihrer ersten Wallet. Der Zugriff auf Ihr Geld ist wiederhergestellt.

Der Seed wird von der Wallet-App während der Ersteinrichtung generiert. Die meisten Wallets führen Sie durch die Einrichtung und weisen Sie an, die Seed-Wörter auf ein Blatt Papier zu schreiben. Wenn Ihre Wallet dies nicht sofort anbietet, suchen Sie nach der Funktion "Backup erstellen" oder "Backup" und folgen Sie den Schritten. Die Erstellung des Seed funktioniert auf die entgegengesetzte Art und Weise wie die Erstellung eines Passworts, wie Sie es üblicherweise auf Websites kennen. Nicht Sie legen das Passwort fest, sondern die Brieftasche selbst.

Die Reihenfolge der Wörter ist WICHTIG! Sie müssen die Wörter genau in der Reihenfolge aufschreiben, in der sie erscheinen.

> Beispiel seed: cruise item paper slim vocal power like video snap museum mirror sun

Schreiben Sie den Seed von Hand auf ein Blatt Papier und bewahren Sie ihn sicher auf. Machen Sie keinen Screenshot und speichern Sie ihn nicht auf Ihrem Telefon oder Computer, der mit dem Internet verbunden ist, da alle diese Orte gehackt werden können. Weitere Informationen zur Sicherheit finden Sie in Kapitel 5.

Da sich Ihr Guthaben nicht in Ihrer Brieftasche befindet, sondern auf der Blockchain gespeichert ist, können Sie sich weltweit bewegen und Ihr Bitcoin-Guthaben mitnehmen, wohin Sie gehen. Sie müssen sich nur die 12–24 Seed-Wörter in der richtigen Reihenfolge merken. Nachdem Sie den Zoll ohne Mobiltelefon passiert haben, besorgen Sie sich eine neue Geldbörse und importieren den Seed. Magie.

[^69]: Anita Posch, inspiriert von Andreas M. Antonopoulos

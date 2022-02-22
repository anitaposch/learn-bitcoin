## 21 Millionen Bitcoin
Wie auf den vorigen Seiten beschrieben, werden Bitcoin geschaffen, sobald ein Mining-Computer eine Rechenaufgabe löst und als Erster den neu erzeugten Block an die Blockchain anhängt. 

Derzeit erhalten Miner dafür 6,25 Bitcoin als Belohnung. Diese dient den Minern als Anreiz, den Regeln des Netzwerks zu folgen und soll sie davon abhalten, sich mit anderen zusammen zu schließen und das Netzwerk zu attackieren.

### Halving
Die Bitcoin-Regeln legen fest, dass sich die ausbezahlte Menge an Bitcoin alle 210.000 Blöcke - etwa vier Jahre - halbiert. Zu Beginn wurden 50 Bitcoin pro Block geschaffen. Seit Mai 2020 sind es die genannten 6,25. Im Jahr 2024 wird wieder halbiert und die Miner erhalten dann 3,125 Bitcoin pro Block. Dieses Ereignis wird als Halving (Halbierung) bezeichnet. 

Satoshi Nakamoto programmierte diese Intervalle in die Bitcoin-Core Software. Die Ausgabemenge halbiert sich regelmäßig, was sich in einer flacher werdenden Kurve ausdrückt.  

![Der Teil des Bitcoin-Core Programmes, der das Halving Intervall festlegt. In C++](assets/_halving-interval.jpg)

![Erklärung von Andreas M. Antonopoulos](assets/_aantonop-21-million.png) [^24]

Der Algorithmus legt auch fest, dass es maximal 21 Millionen Bitcoin geben wird. Derzeit sind es etwa 18,7 Millionen. Im Jahr 2140 werden alle 21 Millionen erzeugt und im Umlauf sein. Das Mining wird weiter stattfinden, die Miner werden jedoch ausschließlich durch die Transaktionsgebühren ihre Kosten decken müssen. Es wird angenommen, dass das Bitcoin-Netzwerk zu diesem Zeitpunkt so stark genutzt wird, dass die Transaktionsgebühren hoch genug sind, um die Kosten des Minings zu decken.

![Gesamte Bitcoin Menge über die Zeit](assets/_Total_bitcoins_over_time.png) [^25]


### Warum 21 Millionen?
Es gibt viele Theorien, wieso Satoshi Nakamoto genau die Zahl 21 Millionen gewählt hat. Hier ist Satoshi′s Antwort. 

>Bei der Festlegung der Anzahl und der Verteilung der Bitcoin musste ich mich auf eine fundierte Schätzung verlassen. Das waren schwierige Entscheidungen, weil Änderungen nach Beginn des Netzwerks nicht mehr möglich sein würden. Ich wollte etwas schaffen, das ähnliche Preise ermöglicht wie bestehenden Währungen; eine knifflige Aufgabe, wenn man zukünftige Entwicklungen nicht kennt. Ich habe letztlich einen Mittelweg gewählt. Sollte Bitcoin eher eine Randerscheinung bleiben, wird es pro Einheit weniger wert sein als bestehende Währungen. Wenn wir uns aber vorstellen, dass es für einen Teil des online Welthandels verwendet wird und es gibt nur 21 Millionen Bitcoin für die ganze Welt, dann wird es viel mehr Wert sein pro Einheit. Die Werte sind 64-Bit Integer Zahlen mit 8 Dezimalstellen, wodurch 1 Bitcoin intern durch 100.000.000 (100 Millionen) Teile repräsentiert wird. Dies schafft genug Granularität falls typische Preise klein werden. Zum Beispiel, wenn eines Tages 0,001 BTC 1 Euro wert ist, dann wäre es einfacher den Platz des Dezimalzeichens zu ändern. 1 Bitcoin könnte dann als 1000 und 0,001 als 1 dargestellt werden. [^26]


### Bitcoin-Einheiten
Die kleinste Einheit eines Bitcoin ist ein Satoshi. 1 Bitcoin besteht aus 100 Millionen Satoshis; 1 Satoshi ist ein Einhundertmillionstel eines Bitcoin (0,00000001).

Sie müssen also nicht einen ganzen Bitcoin kaufen oder versenden, Sie können mit Mini-Teilen eines Bitcoin beginnen.

### Bitcoin, eher nicht Bitcoins, aber niemals BitCoin

Im Englischen wird "Bitcoin" mit einem Großbuchstaben zu Beginn geschrieben, wenn das Bitcoin-Netzwerk, die Blockchain, die Community und das gesamte Ganze gemeint ist, während "bitcoin" die Währung bezeichnet.

Auf Deutsch wird in beiden Fällen der Großbuchstabe vorangestellt.

Münze ist im Grunde ein irreführender Begriff für das digitale Gut. Technisch gesehen besteht ein Bitcoin aus vielen UTXOs (Unspent Transaction Outputs) - auf Deutsch etwa "nicht ausgegebener Transaktions-Output". Dies ist die Menge der Einheiten, die an einer bestimmten Bitcoin-Adresse verzeichnet ist. Deshalb herrscht Uneinigkeit, ob es den Begriff Bitcoins überhaupt gibt, da keine einzelnen Münzen existieren, sondern nur Mengen von Einheiten an bestimmten Adressen. Da Satoshi Nakamoto selbst den Begriff "bitcoins" nutzte, wird er auch verwendet. Leute wie ich, die auf den Unterschied Wert legen, verwenden Bitcoin für die Ein- und Mehrzahl. Ich spreche auf Deutsch nie von Münzen, weil es irreführend ist.

Scams wie das betrügerische BitClub-Netzwerk verwendeten die Schreibweise BitCoin und diese falsche Schreibweise wird gelegentlich auch von vielen Anfänger*innen übernommen.

[^24]: [Quelle: Andreas M. Antonopoulos](https://twitter.com/aantonop/status/1257366095515848716?s=20)

[^25]: [Quelle: Insti](https://commons.wikimedia.org/wiki/File:Total_bitcoins_over_time.png)

[^26]: [Quelle: plan99.net](https://plan99.net/~mike/satoshi-emails/thread1.html)

## 21 Millionen Bitcoin
Wie auf den vorigen Seiten beschrieben, werden Bitcoin geschaffen, sobald ein Mining-Computer eine Rechenaufgabe löst und als Erster den neu erzeugten Block an die Blockchain anhängt. 

Derzeit erhalten Miner dafür 6,25 Bitcoin als Belohnung. Diese dient den Minern als Anreiz, den Regeln des Netzwerks zu folgen und soll Miner davon abschrecken Transaktionen in ihrem Sinne zu verändern.
TA
### Halving
Die Bitcoin-Regeln legen fest, dass sich die ausbezahlte Menge an Bitcoin alle 210.000 Blöcke - etwa vier Jahre - halbiert. Zu Beginn wurden 50 Bitcoin pro Block geschaffen. Seit Mai 2020 sind es die genannten 6,25. Im Jahr 2024 wird wieder halbiert und die Miner erhalten 3,125 Bitcoin pro Block. Dieses Ereignis wird als Halving (Halbierung) bezeichnet. 

Satoshi Nakamoto programmierte diese Intervalle in die Bitcoin Core Software. Die Ausgabemenge halbiert sich regelmäßig, was sich in einer flacher werdenden Kurve ausdrückt.  

![Der Teil des Bitcoin Core Programmes, der das Halving Intervall festlegt. In C++](assets/_halving-interval.jpg)

![Erklärung von Andreas M. Antonopoulos](assets/_aantonop-21-million.png) [^24]

Der Algorithmus legt fest, dass es maximal 21 Millionen Bitcoin geben wird. Derzeit sind es etwa 18,7 Millionen. Im Jahr 2140 werden alle 21 Millionen erzeugt und im Umlauf sein. Das Mining wird weiter stattfinden, die Miner werden jedoch ausschließlich durch die Transaktionsgebühren ihre Kosten decken müssen. Es wird angenommen, dass das Bitcoin-Netzwerk zu diesem Zeitpunkt so stark genutzt wird, dass die Transaktionsgebühren hoch genug sind, um die Kosten des Minings zu decken.

![Gesamte Bitcoin Menge über die Zeit](assets/_Total_bitcoins_over_time.png) [^25]


### Warum 21 Millionen?
Es gibt viele Theorien wieso Satoshi Nakamoto genau die Zahl 21 Millionen gewählt hat. Hier ist Satoshi's Antwort. 

>Meine Wahl für die Anzahl der Bitcoin und den Ausgabenmodus war eine auf Tatsachen beruhende Vermutung. Es war eine schwierige Entscheidung, denn sobald das Netzwerk zu laufen beginnt, sind wir daran gebunden. Ich wollte etwas wählen, das Preise ähnlich zu bestehenden Währungen ermöglicht, aber ohne die Zukunft zu kennen, ist das eine schwierige Entscheidung. Ich habe letztlich das Mittelmaß gewählt. Falls Bitcoin ein kleine Nische bleibt, wird es per Einheit weniger Wert sein als bestehende Währungen. Wenn wir uns vorstellen, dass es für einen Teil des online Welthandels verwendet wird und es gibt nur 21 Millionen Bitcoin für die ganze Welt, dann wird es viel mehr Wert sein pro Einheit. Die Werte sind 64-Bit Integer Zahlen mit 8 Dezimalstellen, wodurch 1 Bitcoin intern durch 100000000 (100 Millionen) Teile repräsentiert wird. Dies schafft genug Granularität falls typische Preise klein werden. Zum Beispiel, wenn eines Tages 0,001 BTC 1 Euro wert ist, dann wäre es einfacher den Platz des Dezimalzeichens zu ändern. 1 Bitcoin könnte dann als 1000 und 0,001 as 1 dargestellt werden. [^26]


### Bitcoin Einheiten
Die kleinste Einheit eines Bitcoin ist ein Satoshi. 1 Bitcoin besteht aus 100 Millionen Satoshis; 1 Satoshi ist ein Einhundertmillionstels eines Bitcoin (0,00000001).

Sie müssen also nicht einen ganzen Bitcoin kaufen oder versenden, Sie können klein beginnen und Mini-Teile eines Bitcoin senden.

### Bitcoin, eher nicht Bitcoins, aber niemals BitCoin

Im Englischen wird Bitcoin im Großbuchstaben in Bezug auf das Bitcoin-Netzwerk, die Blockchain, die Community und das gesamte Ganze verwendet, während bitcoin die Währung bezeichnet.

Auf Deutsch wird in beiden Fällen der Großbuchstabe vorangestellt.

Münze ist im Grunde ein irreführender Begriff für das digitale Gut. Technisch gesehen besteht ein Bitcoin aus vielen UTXOs (unspent transaction output) - auf Deutsch etwa "nicht ausgegebener Transaktionsoutput". Dies ist die Menge der Einheiten, die an einer bestimmten Bitcoin-Adresse verzeichnet ist. Deshalb herrscht Uneinigkeit, ob es den Begriff Bitcoins überhaupt gibt, da keine einzelnen Münzen existieren, sondern nur Mengen von Einheiten an bestimmten Adressen. Da Satoshi Nakamoto selbst den Begriff "bitcoins" nutzte, wird er auch verwendet. Leute wie ich, die auf den Unterschied Wert legen, verwenden Bitcoin für die Ein- und Mehrzahl. Ich spreche auf Deutsch nie von Münzen, weil es irreführend ist.

Scams wie das betrügerische BitClub-Netzwerk verwenden die Schreibweise BitCoin. Es wird auch fälschlicherweise von vielen Anfänger*innen so geschrieben.

[^24]: [Source Andreas M. Antonopoulos](https://twitter.com/aantonop/status/1257366095515848716?s=20)

[^25]: [Source: Insti](https://commons.wikimedia.org/wiki/File:Total_bitcoins_over_time.png)

[^26]: [Source plan99.net](https://plan99.net/~mike/satoshi-emails/thread1.html)

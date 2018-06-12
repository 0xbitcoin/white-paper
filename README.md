## 0xBitcoin  

#### ( Whitepaper Revision 1.0.1 )

#### 0xBitcoin: The Decentralized Bitcoin Token for Ethereum 
-------------------------------

### Kurzfassung

Das Ethereum Netzwerk hat sich als erstes transparentes Netzwerk mit freiem Zugriff auf nicht manipulierbare Anwendungen etabliert.
Diese Anwendungen, typischerweise smart contracts, können nahtlos miteinander interagieren. Um diesen Prozess zu ermöglichen wurden diverse Protokolle zur Definition von Standards, wie z.B. der ERC20 Standard für das gewöhnliche "Token" Format, entwickelt. Dies ermöglicht den Transfer von wertvollen, in Besitz befindlichen und übertragbaren Daten ohne Mittelsmann. Bis 2018 wurden Token als sog. Sicherheit (ähnlich den Wertpapieren) ausgegeben. Die Token wurden direkt vom Erzeuger an die Investoren mit dem Versprechen eines Wertanstieges, welches durch künftige Durchbrüche im Projekte erzielt werden soll, emittiert.
Dem gegenüber steht z.B. die Verteilung neuer Bitcoins. Diese werden nicht direkt an die Investoren ausgegeben, sondern vielmehr durch das sog. Bitcoin mining neu erzeugt. Dies gibt Bitcoin die Natur eines Rohstoffes, statt einer Sicherheit.
Dieses white paper beschreibt die ersten ERC20 Tokens die mittels Proof of work erzeugt werden können, selbst auch als Rohstoff anzusehen sind und auf dem Model des Bitcoin mining basieren. 
Wie auch Bitcoins werden diese Token mittels einer blockchain transferiert und ermöglichen eine Vielzahl von Schnittstellen für weitere Software. Darüber hinaus ergeben sich aber durch das Verarbeiten der Transaktionen auf der Ethereum blockchain mannigfaltige Vorteile. 


### Hintergrund

0xBitcoin stellt die Implementierung des ersten dezentralisierten ERC20 Tokens auf Basis von Bitcoin in Solidity dar. Es handelt sich dabei um ein open source Gemeinschaftsprojekt und wird nicht durch ein einzelnes Team gefördert und geleitet. Aufgrund dessen gab es für 0xBitcoin auch kein ICO. Im Gegensatz zu zentralisierten Token verfügt dieses Projekt demnach auch nicht über einen erheblichen monetären Vorrat, wie es bei Tokens, welche mittels ICO ausgegeben werden der Fall ist. Wir als Gemeinschaft sind der Ansicht, dass die Dezentralisierung dem wahren Geist der blockchain entspricht und dem Nutzer mittels der vorgestellten Architektur Transparenz und Vertrauen bereitgestellt wird. Wir sind davon überzeugt, dass Ethereum und ERC20 Tokens signifikanter Bestandteil künftiger blockchain Technologie sein werden.

0xBitcoin wurde entwickelt, um als dezentraler "Bitcoin-ähnlicher" Token innerhalb und außerhalb des Ethereum Netzwerkes genutzt zu werden. Probleme hinsichtlich der Zentralisierung und Sicherheit werden vermieden, da der Token über das Ethereum Netzwerk und somit über global verteilte, anonyme Miner betrieben wird. Da 0xBitcoin auf einem Standard-Protokoll (ERC20) basiert, kann es in herkömmlichen Ethereum wallets gespeichert und mittels Software, welche EIP20/ERC20 Tokens unterstützt, transferiert werden. Da jeder einzelne 0xBitcoin durch vollständig dezentralisiertes mining erschaffen wurde, gibt es keine zentrale Autorität oder Organisation, welche über die Kontrolle des Tokens verfügt. Es handelt sich um ein offenes Gemeinschaftsprojekt mit flacher Hierarchie und jedes Mitglied hat gleiche Rechte hinsichtlich der Weiterentwicklung. Dieser Weg wurde absichtlich eingeschlagen, um demselben Modell des klassichen Bitcoins zu folgen und 0xBitcoin als Rohstoff zu etablieren.

Durch Satoshi Nakamoto's Bestreben die Sicherheit des klassischen Bitcoin Netzwerkes mittels proof of work zu gewährleisten, wurde gleichzeitig eine der größten Errungenschaften geschaffen: das Verknüpfen von Bitcoin mit Rechenleistung. Diese kann von jedem zur Verfügung gestellt werden und resultiert somit in ein einem dezentralisiertem Netzwerk. Die Verantwortung wird auf jeden einzelnen Miner übertragen, was Regierungen keine legislativen Möglichkeiten gibt auf 0xBitcoin einzuwirken. Eine Überwachung und Einflussnahme durch Regierungen auf die Miner ist ausgeschlossen. Diese erhalten im Austausch für das Bereitstellen ökonomischen Aufwandes (in Form von Rechenleistung) einen kryptografischen Rohstoff - 0xBitcoin. Dadurch wird eine denzentrale Verteilung gefördert und alle involvierten Parteien zu Interessenvertretern. 0xBitcoin ist der erste Token der es ermöglicht Projekte nicht länger durch zentralisierte, an Fiat gebundene Investitionen zu finanzieren, sondern mittels dezentralisierter Rechenleistung.


### Herkunft des Namens „0xBitcoin“	
Der Name 0xBitcoin leitet sich aus einer Kombination der Begriffe „Bitcoin“ und „0x“ ab. Bitcoin ist ein dezentralisierter, durch mining erzeugter Rohstoff. Das Präfix 0x gibt an, dass sich die Anlage im Ethereum Netzwerk befindet, da alle Ethereum Adressen mit „0x“ beginnen. Der 0xBitcoin Smart Contract besitzt die Adresse [0xb6ed7644c69416d67b522e20bc294a9a9b405b31](https://etherscan.io/address/0xb6ed7644c69416d67b522e20bc294a9a9b405b31), der Programmcode ist offen einsehbar und kann von jedem mithilfe des Etherscan Services überprüft werden.

### Ethereum und ICOs	
Die Ethereum Blockchain in ihrer gegenwärtigen Form ist ein ständig wachsendes Ökosystem mit freiem Zugriff für jeden der transparente, unveränderliche Eintragungen vornehmen möchte. Dies ist eine einzigartige Eigenschaft für eine Datenbank, die so nur in Ethereum und ähnlichen Blockchains existiert. Durch die zunehmende Anzahl und Reichhaltigkeit von Blockchain Anwendungen entsteht ein Bedarf für Alternativen zum bisherigen ICO Modell. Zwar gibt es Vorschläge Investment Risiken durch die Einführung des neuen DAICO Modells zu mindern, welches auf automatisierte, zeitgesteuerte Transfers durch den DAICO Smart Contract Mechanismus setzt, allerdings verhindert dies nicht die Klassifizierung als Wertpapier und birgt immer noch Risiken für Investoren, falls nicht sorgfältig implementiert. Den Nutzern des Netzwerks direkten Zugang zu Tokens zu ermöglichen, in dem sie Computer Berechnungen als „proof of work“ vornehmen lassen, erlaubt jedem Smart Contract seine Tokens auf eine sichere, langsame und kontrollierte Art zu verteilen, vergleichbar mit der Freisetzung eines neuen Rohstoffs.

Seit 2017 sind alle Methoden zur Verteilung von Tokens auf der Ethereum Plattform mängelbehaftet und anfällig für eine Sybil Attacke, dies beschreibt ein Szenario in dem sich eine einzelne Person mithilfe von mehreren Computer-Benutzerkonten, als eine Anzahl von vielen Individuen ausgibt, um das System böswillig zu überlisten. ICOs und Airdrops sind hochgradig anfällig für diese Art von Manipulation, da es keinen Weg gibt zu überprüfen ob alle ERC20 Tokens vom Herausgeber fair verteilt wurden. 0xBitcoin hingegen, mit seiner besonderen „Proof of Work“ Ausschüttung, ist resistent gegenüber Sybil Attacken, dies bedeutet das 0xBitcoin weltweit das erste Vertrauens-unabhängige Token ist. Somit kann geltend gemacht werden, dass die Verteilung von 0xBitcoin fair abläuft, denn sie geschieht nur durch Solidity Programmcode und nicht durch einen Menschen.

### Aktuelle und beabsichtigte Anwendungsmöglichkeiten	
Als Implementierung der originalen Bitcoin Software in Form eines Smart Contracts auf Ethereum kombiniert 0xBitcoin (abgekürzt 0xBTC) Vorteile von sowohl Bitcoin als auch Ethereum. Genau wie Bitcoin ist auch 0xBitcoin dezentralisiert, rar, gemined und niemand benötigt eine Erlaubnis, um es zu nutzen oder neue Anwendungen zu schaffen, 0xBitcoin besitzt also dieselben Anwendungsmöglichkeiten und Eigenschaften als transparente, permanente Aufzeichnung von Besitzverhältnissen. Allerdings weist 0xBitcoin noch zusätzlich die Transfergeschwindigkeit und Skalierbarkeit von Ethereum, als auch Kompatibilität mit allen ERC20 Token Diensten auf. Es kann auf allen Ethereum Wallets aufbewahrt werden, ist somit genauso sicher wie Ethereum selbst und agiert als Bitcoin für das Ethereum Ökosystem. Bitcoin ist nicht in der Lage mit dem Ethereum Smart Contract Ökosystem zu interagieren oder kommunizieren, durch 0xBitcoin ist das Ethereum Netzwerk nun um eine Anwendung erweitert die es Smart Contracts ermöglicht mit einem Bitcoin gleichem Rohstoff zusammenzuwirken. Hierdurch können nun alle Ethereum Smart Contracts eine Bitcoin-gleiche Ressource nach unveränderlichen Bedingungen bestimmt durch ihren eigenen Programmcode handeln und transferieren.
	
Der Rohstoff Ether wird im Ethereum Netzwerk für viele verschiedene Zwecke genutzt, die endgültige Nutzbarkeit als dezentralisierte Wertanlage ist jedoch noch nicht hinreichend geklärt.
Dies resultiert daraus das Ether als Mittel zur Absicherung des Ethereum Netzwerkes dient und nicht nur als eine Art von „Bitcoin“ für Ethereum. Wenn die „Proof of Stake“ Phase Ethereums in Kraft tritt, wird neues Ether in Zukunft nicht mehr durch Proof of Work mining erzeugt, wodurch nur 0xBitcoin als einzige durch Proof of Work erzeugte Anlage auf Ethereum verbleibt. Auf diese und andere Weise könnte Ether sich somit zu einem Mittel zur Absicherung des Netzwerks verändern, dass sich schlechter als Zahlungsmittel eignet. Diese Möglichkeit wurde bereits 2017 vom Ethereum Entwicklerteam angedeutet, 0xBitcoin beabsichtigt diese Rolle, die momentan noch von Ether erfüllt wird, zu übernehmen und somit zum primären Mittel für Austausch und Aufbewahrung von Werten im Ethereum Netzwerk zu werden. Ether kann hierdurch seine vorgesehene Rolle als Lebensnerv und Mittel zur Absicherung des Ethereum Netzwerks erfüllen.  


### Der dezentralisierte Token

Wie auch der klassische Bitcoin, wird der 0xBitcoin mittels Mining erzeugt, verhält sich somit wie ein Rohstoff und erhält seinen Wert u.a. durch die benötigte Rechenleistung zur Erzeugung neuer Blöcke. Dieser Prozess kann mit dem Schürfen von Gold verglichen werden; auch hier ist der Wert des Rohstoffes direkt abhängig von der notwendigen Arbeit um diesen zu fördern und einzuschmelzen. 
Eines der Probleme des aktuellen ICO-Modells im Ethereum Netzwerk ist, dass viele Projekte dem Investor lediglich das Versprechen eines Wertzuwachses geben und der Investor somit das Risiko eingeht einen potenziell wertlosen Token zu erwerben. 0xBitcoin versucht dieses Problem zu umgehen, indem es dem Ethereum Netzwerk einen dezentralisierten Bitcoin-ähnlichen Vermögenswert zur Verfügung stellt, welcher die Rolle einer Vielzahl von zentralisierten Token übernehmen kann. Vorteile hierbei sind, dass keinem Mittelsmann vertraut werden muss, da der Prozess über einen Smart contract abgewickelt wird und dieser nicht angreifbar ist.

Dieses Werkzeug gibt Personen die Möglichkeit sich von zentralisierten Börsen und den damit verknüpften Problemen, wie Sicherheitslücken, wallet Kompromittierung oder Treuhandverwaltung loszusagen. Die Abkehr von der Zentralisierung und der Versuch dies mittels des klassischen Bitcoins zu realisieren, ist ein Kerngedanke Sataoshi Nakamoto's (Nakamoto, 2009). Auch 0xBitcoin stellt sich die Aufgabe das Netzwerk (Ethereum) bei jeder einzelnen Transaktion offen, rechenschaftspflichtig, dezentralisiert und vertrauenslos zu halten. Da 0xBitcoin, im Gegensatz zum klassischen Bitcoin, kompatibel mit smart contracts ist, kann er auch auf denzentralisierten Börsen wie ForkDelta oder EtherDelta gehandelt werden. Durch die Möglichkeit des dezentralisierten Handels ergeben sich für 0xBitcoin vielfache Eigenschaften, wie etwa der berechtigungsfreie Handel innerhalb des unveränderbaren smart contracts, welcher nicht durch zentrale Autoritäten zensiert oder eingeschränkt werden kann. Durch diesen Vorteil ist 0xBitcoin noch näher an Satoshi's ursprüngliche Vision angelehnt, als der klassische Bitcoin.


### Abrechnungssystem

0xBitcoin ist ein ERC20 Token und kann mit einem herkömmlichen Ethereum wallet genutzt werden. Diese wallets sind kostenfrei und es ist unmöglich aus Ihnen Kryptowährungen zu stehlen oder sie zu hacken, solange der private Schlüssel nicht offengelegt wird. 0xBitcoin kann in ERC20 kompatiblen hardware wallets, wie z.B. Ledger Nano oder Trezor aufbewahrt werden.


## Mining

Tokens die durch Mining oder Prägung erzeugt werden können wurden bereits in der Vergangenheit vorgeschlagen, allerdings wurde keines erfolgreich mit Proof of Work Mechanismus und automatischer Schwierigkeitsanpassung umgesetzt, es entstand also nie eine rein dezentralisierte Währung. 0xBitcoin wird mit einem simplen Keccak256 (Sha3) Algorithmus mit folgender Methodik gemined:


``` js
   keccak256(nonce, minerEthAddress, challengeNumber) < difficultyTarget
```

Der Parameter „nonce“ ist eine zufällig, durch die mining Software generierte Zahl. Die mining Software versucht eine gültige „nonce“ zu ermitteln, wenn die obere Ausführung das Ergebnis „richtig“ bzw „true“ liefert, dann handelt es sich um eine zulässige Lösung. Der Wert „challengeNumber“ ist der Hash eines vorangegangenen Ethereum Blocks, mit dem Beginn jeder Runde wird der Hash des zuletzt generierten Ethereum Blocks verwendet um auszuschließen, das zukünftige Proof of Work Aufgaben vorraus gemined werden können. Die Ethereum Adresse des Miners ist teil der gehashten Lösung, damit diese nur für ihn selbst gültig ist und nicht durch eine „Man in the Middle“ Attacke abgefangen werden kann, dieser Umstand ermöglicht auch Pool Mining. Der „difficultyTarget“ Wert wird automatisch kleiner, je mehr Hashpower dem Netzwerk hinzugefügt wird.

## Pool Mining 

Immer wenn ein Miner seine Lösung für eine Proof of Work Aufgabe an den 0xBitcoin Smart Contract sendet, muss er eine Transfergebühr (gas fee) an das Ethereum Netzwerk zahlen, diese begleicht die Informationsübermittlung und die Ausführung der „mint()“ Funktion des Programmcodes. Wenn für die Gebühr zu wenig Ether bereitgestellt wird, dauert die Übertragung wesentlich länger, sie wird nicht rechtzeitig ausgeführt bevor ein anderer Miner seine eigene Lösung übermittelt, dies gilt insbesondere in Zeiten in denen sich der „difficulty“ Parameter nicht im Gleichgewichtszustand befindet. Dies führt dazu das die Lösung des ersten Miners verfällt und die „revert()“ Funktion ausgeführt wird. Um die Belastung durch Transfergebühren zu reduzieren, können Miner stattdessen zusammen in einem sogenannten „Pool“ minen, dieser sammelt die Teillösungen seiner Mitglieder und überträgt dann die fertige Lösung an den Smart Contract und bezahlt die Transfergebühr. Hierfür wird der Pool üblicherweise einen kleinen Prozentsatz des Erlöses an 0xBitcoin für sich beanspruchen und den Rest gewichtet an seine Mitglieder auszahlen.

Da die Miner ihre Ethereum Adresse in der Proof of Work Lösung mit angeben müssen, verlangt der Pool das die Miner stattdessen seine Ethereum Adresse benutzen. Hierdurch kann ein Miner nicht seine kompletten Lösungen an den Smart Contract und gleichzeitig Teillösungen an einen Pool senden. Wenn ein Miner im Auftrag eines Pools mined (und somit die Ethereum Adresse von diesem im Proof of Work Algorithmus nutzt) dann ist er nicht in der Lage seine Lösung an den Smart Contract zu übermitteln, ohne das die „revert()“ Funktion ausgeführt wird. Dies verhindert das Miner ihren Pool betrügen können.

Üblicherweise wird ein Pool Teillösungen akzeptieren, diese sind nahe an einer Lösung aber noch nicht nah genug um die Proof of Work Aufgabe zu lösen, dem Miner werden dann sogenannte „shares“ vom Pool ausgestellt. Dies ist dieselbe Funktionsweise wie sie im Bitcoin und Ethereum Pool Mining zu finden ist. Die Wahrscheinlichkeitstheorie besagt, dass mit genug Teillösungen auch irgendwann eine voll zutreffende Lösung gefunden wird.

## Smart Contract

ERC20 Tokens werden üblicherweise alle an den Ersteller oder durch ein ICO Modell ausgegeben, bei dem Ether im Tausch für Tokens an den Ersteller gesendet wird. Anstatt alle 0xBitcoin Tokens an den Ersteller auszustellen, werden diese anfänglich im Smart Contract festgesetzt. Durch das Abrufen der „mint()“ Funktion mit Proof of Work werden diese dann in Tranchen von 50 Stück, ähnlich wie beim klassischen Bitcoin verteilt. Der 0xBitcoin Smart Contract erfüllt als erstes Token die ERC541 Spezifikation, hierdurch werden folgende Smart Contract Methoden ausdrücklich unterstützt: 

## Token
### ERC-20 Interface
#### name

Gibt den Namen des Tokens aus – z.B. `"0xBitcoin Token"`.

Diese Funktion ist optional, sie kann genutzt werden, um die Benutzerfreundlichkeit zu verbessern, ist aber nicht notwendig um mit Schnittstellen und anderen Smart Contracts zu interagieren.

``` js
function name() constant returns (string name)
```

#### symbol

Gibt die Abkürzung des Token Namens aus – z.B. `"0xBTC"`.

Diese Funktion ist optional, sie kann genutzt werden, um die Benutzerfreundlichkeit zu verbessern, ist aber nicht notwendig um mit Schnittstellen und anderen Smart Contracts zu interagieren.

``` js
function symbol() constant returns (string symbol)
```

#### totalSupply

Gibt die Gesamtmenge an Tokens aus.

``` js
function totalSupply() constant returns (uint256 totalSupply)
```

#### balanceOf

Gibt die Menge an Tokens an, die ein Account mit der Adresse `_owner` besitzt.

``` js
function balanceOf(address _owner) constant returns (uint256 balance)
```

### Mining Operations


#### mint

Gibt ein Identifizierungssignal für eine erfolgreiche Hash Überprüfung aus. Um Man in the Middle Attacken zu verhindern, wird empfohlen das der Hash eines kürzlich zurückliegenden Ethereum Blocks sowie die Ethereum Adresse des Senders in den zu überprüfenden Hash eingebettet werden.
Sobald die „mint()“ Funktion erfolgreich ausgeführt wird, berechnet diese die Menge der auszuschüttenden Tokens und führt interne Buchführungsoperationen bzgl des Vorrats an Tokens im Smart Contract aus.

``` js
function mint(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

##### *Mint Event*

Nach der erfolgreichen Überprüfung und Ausschüttung erzeugt die mint Funktion ein sogenanntes Mint Event, bei dem die Adresse des Empfängers, die Menge an auszuzahlenden Tokens, Epochen Zählstand und neuste Aufgabennummer spezifiziert werden.

``` js
event Mint(address indexed from, uint reward_amount, uint epochCount, bytes32 newChallengeNumber);
```

#### getChallengeNumber

Kurz zurückliegender Ethereum Block Hash, der genutzt wird, um vorraus-minen zu verhindern.

``` js
function getChallengeNumber() public constant returns (bytes32) 
```

#### getMiningDifficulty

Die Anzahl an Stellen die eine Proof of Work Lösungs-Überprüfung benötigt, diese gleicht sich üblicherweise automatisch während der „Reward“ (Belohnungs-/Ausschüttungs-) Erstellung an.


``` js
function getMiningDifficulty() public constant returns (uint)
```

#### getMiningReward

Gibt die momentane Ausschüttungsmenge aus, abhängig vom Algorithmus, üblicherweise werden die Ausschüttungsmengen in jeder Ära halbiert, um eine Verknappung zu erreichen.

``` js
function getMiningReward() public constant returns (uint)
```

### Mining Debug Operationen


#### getMintDigest

Liefert ein Test Resultat welches dieselben Hash-Schemata wie der Prozess des mintings neuer Token nutzt.

``` js
function getMintDigest(uint256 nonce, bytes32 challenge_digest, bytes32 challenge_number) public view returns (bytes32 digesttest)
```

OPTINAL - Diese Methode kann genutzt werden, um die Anwendungsfreundlichkeit zu erhöhen, allerdings dürfen Schnittstellen und andere Verträge NICHT davon ausgehen, dass diese Werte präsent sein werden.


#### checkMintSolution

Verifiziert eine einfache Lösung anhand des minting Schemas.

``` js
function checkMintSolution(uint256 nonce, bytes32 challenge_digest, bytes32 challenge_number, uint testTarget) public view returns (bool success) 
```

OPTINAL - Diese Methode kann genutzt werden, um die Anwendungsfreundlichkeit zu erhöhen, allerdings dürfen Schnittstellen und andere Verträge NICHT davon ausgehen, dass diese Werte präsent sein werden.

## Erzeugen neuer 0xBitcoins

The 0xBitcoin Token was deployed to the Ethereum blockchain in February, 2018, with the following attributes:
* No pre-mine
* No ICO
* 21,000,000 tokens total supply
* Difficulty target auto-adjusts with PoW hashrate
* Rewards decrease as more tokens are minted
* ERC20 compatibility

As such, the only way for a user to acquire 0xBitcoins is to mine them or purchase them from miners on decentralized exchanges. The mint function is responsible for verifying the validity of the hash solution, updating the contracts internal state and issuing new 0xBitcoins.

Die ersten 0xBitcoin wurden im Februar 2018 im Ethereum Netzwerk erzeugt. Der Token weist folgende Eigenschaften auf:
* kein pre mine
* kein ICO
* maximale Anzahl der Token auf 21.000.000 begrenzt
* mining difficulty passt sich automatisch der Netzwerk Hashrate an
* die Belohnungen für das mining reduzieren sich mit steigender Anzahl geminter Token
* ERC20 Kompatibilität

Demnach ist die einzige Möglichkeit in den Besitz von 0xBitcoin zu gelangen das mining oder der Erwerb von anderen Minern über Handelsplatformen. Die Funktion, die für das Erzeugen neuer 0xBitcoins verwendet wird, ist für das Verifizieren der Hash Lösung und aktualisieren des inneren Zustandes des smart contracts verantwortlich und gibt bei korrekten Lösungen neue 0xBitcoins aus.

``` js
function mint(uint256 nonce, bytes32 challenge_digest) public returns (bool success) {   
    uint reward_amount = getMiningReward();

    bytes32 digest =  keccak256(challengeNumber, msg.sender, nonce );

    if (digest != challenge_digest) revert();

    //the digest must be smaller than the target
    if(uint256(digest) > miningTarget) revert();
 
    uint hashFound = rewardHashesFound[digest];
    rewardHashesFound[digest] = epochCount;
    if(hashFound != 0) revert();  //prevent the same answer from awarding twice

    balances[msg.sender] = balances[msg.sender].add(reward_amount);

    tokensMinted = tokensMinted.add(reward_amount);

    //set readonly diagnostics data
    lastRewardTo = msg.sender;
    lastRewardAmount = reward_amount;
    lastRewardEthBlockNumber = block.number;
    
    //start a new round of mining with a new 'challengeNumber'
     _startNewMiningEpoch();

    Mint(msg.sender, reward_amount, epochCount, challengeNumber );

    return true;
}
```
*Abb. 1. 0xBitcoin Smart Contract mint() Funktion*


Die Belohnung für das mining ist initial festgelegt und durch denselben Algorithmus wie der klassiche Bitcoin festgelegt. Es folgt dem Paradigma eines vollständig dezentralisierten monetären Systems. Während neue Tokens über die Knotenpunkte eines peer to peer Netzwerkes erzeugt werden, überwacht der 0xBitcoin Algorithmus wie, und in welcher Menge diese erschaffen werden. 

Wie auch Bitcoin, werden 0xBitcoin jedesmal erschaffen, wenn der Benutzer einen neuen Block findet. Er sendet hierbei als erster einen proof of work Beweis für die aktuelle Blockhöhe an den smart contract. Die mining Schwiergkeit wird alle 1024 Blöcke angepasst. Der smart contract ist so aufgebaut, dass er bestrebt ist die Schwierigkeit so lange verändern, bis sich die Frequenz für das Finden neuer Blöcke bei sechs Blöcken je Stunde einpendelt. Dabei nimmt die Anzahl der neu ausgegebenen 0xBitcoin logarithmisch ab - die Belohnung sinkt jedes Mal um 50%, sobald eine neue Era erreicht wird. Durch diese Funktion kann die maximale Anzahl von 0xBitcoin niemals 21 Millionen überschreiten.
 
Damit neue 0xBitcoin erzeugt werden können, muss der Benutzer zusammen mit der Hash-Lösung einen einzigartigen 'nonce' übermitteln. Um diese Lösungen zu erhalten ist die Verwendung eines mining Programms notwendig. Um Angriffe durch zwischengeschaltete Parteien zu verhindern, kombiniert der proof of work Prozess den aktuelle Ethereum-Blockhash mit der wallet Adresse des Absenders. Mining Aufgabe und Hash Lösung werden mittels solidity geprüft und die Lösung über den keccak256 Algorithmus dechiffriert. Sobald eine Lösung gefunden wurde, wird geprüft, ob diese der erwarteten Mining Lösung entspricht und kleiner als die aktuelle Schwierigkeit ist.

Durch die logarithmische Reduktion der Belohnungen im Laufe der Zeit, ist 0cBitcoin eine verlässliche deflationäre Wertanlage. Die Erträge werden dem Absender der Lösung unverzüglich gutgeschrieben und die im Umlauf befindliche Menge von 0xBitcoin wird im smart contract entsprechend erhöht und kann dort von anderer Software bei Bedarf abgerufen werden. Zur Wahrung der Integrität prüft der smart contract ob die aktuelle Zahl in Umlauf befindlicher 0xBitcoin kleiner oder gleich der maximal möglichen Anzahl ist bzw. dass in der aktuellen Era nicht mehr Tokens erzeugt werden, als mathematisch erlaubt wäre. Darüber hinaus zeigt der smart contract die Adresse des letzen wallets, das eine Lösung gefunden hat, sowie die Ethereum-Blocknummer in welcher sie gefunden wurde und vermittelt somit Transparenz des Mining-Prozesses.


### Schwierigkeitsberechnung und Anpassung
Nach jedem Mint-Vorgang überprüft der Smart Contract, ob es an der Zeit ist die Schwierigkeit anzupassen, dies geschieht alle 1024 Mint-Vorgänge. Zuvor wird jedoch noch überprüft ob die gegenwärtige Ausschüttungsära ihr Ende erreicht hat, also die Menge an Tokens das Limit für die Ära überschritten hat, die Berechnung hierfür erfolgt durch einen einfachen Halbierungs-Alogrithmus: 

max_era_supply = total_supply - (total_supply / (2 * (reward_era + 1)))

In der ersten Ära werden 10500000 Tokens ausgegeben, ein Mint-Vorgang liefert dabei 50 Tokens. In der zweiten Ära die bis zu einer Gesamtmenge von 15750000 Tokens verläuft, sind es noch 25 Tokens je Mint-Vorgang. In der dritten Ära werden nur noch 12.5 Tokens ausgeschüttet und immer so weiter, bis die letzte der 40 Ären abgeschlossen ist und somit auch die Ausschüttung durch das Mining. Der Vorgang wird im gesamten ca. 100 Jahre andauern und 0xBitcoin dann eine dezentralisierte Währung auf Ethereum darstellen.  

Die Ausschüttungsära wird genutzt, um die Menge an auszugebenden Tokens zu berechnen. Danach passt der Smart Contract die Schwierigkeit an, indem er bestimmt wie viele Ethereum Blöcke seit der letzten Anpassung gemined wurden. Wenn weniger als 1024*60 Ethereum Blöcke gemined wurden, läuft der Mining Vorgang zu schnell ab, die Schwierigkeit wird sich erhöhen. Erreicht wird diese Anpassung in dem das „Ziel“ verkleinert wird, zulässige Lösungen für den Mint-Vorgang werden seltener und schwieriger zu finden. Auf umgekehrte weise verläuft die Anpassung falls die Schwierigkeit zu hoch ist, der Zielwert wird größer und somit steigt die Wahrscheinlichkeit eine Lösung finden. Alle Schwierigkeitsanpassungen bewegen sich in einem Rahmen von minimal 216 bis maximal 2234.

### Berechnung der Mining Hashrate

Um eine geschätzte Hashrate bzw. Zeit pro Mint zu berechnen, kann die folgende Gleichung genutzt werden:

	TimeToSolveBlock (seconds) = (difficulty * 2 ^ 22) / hashrate (hashes per second)
 
 

### Risiken und Herausforderungen 

Da 0xBitcoin ein ERC20 Token ist, hängt sein Erfolg größtenteils von dem des Ethereum Netzwerks ab. Falls Ethereum nicht durch neue Methoden wie Plasma, Casper und das Loom Netzwerk skaliert, kann auch 0xBitcoin nicht sein volles Potenzial als schnellste und am stärksten dezentralisierte Währung der Welt erreichen.   

### Häufig gestellte Fragen

#### Besitzt 0xBitcoin eine eigene Blockchain? 

Nein. 0xBitcoin existiert als Smart Contract auf der Ethereum Blockchain und erlaubt es, eine schnellere, sicherere und moderne Crypto-Umgebung zu nutzen.

#### Warum gibt es Zeiten in denen viele Mints zurückgeleitet werden?

Die Schwierigkeit der Proof of Work Aufgabe war zu niedrig, somit wurden mehrere Lösungen für dieselbe Aufgabe innerhalb kurzer Zeit an den Smart Contract geschickt. Nur eine von diesen Lösungen kann für jede Runde akzeptiert werden, die anderen werden somit zurückgeleitet.

#### Wie funktioniert Pool Mining mit 0xBitcoin?

Im Grunde genau so wie mit dem klassischen Bitcoin, nur müssen Pools für 0xBitcoin Transaktionsgebühren an das Ethereum Netzwerk zahlen.  

#### Wie oft wird die Schwierigkeit angepasst?

Alle 1024 Blocks bzw Mints.

#### Wie wird die Schwierigkeit angepasst?

Die Schwierigkeitsanpassung erlaubt Sprünge von maximal 100 % nach oben und 50 % nach unten, Ziel ist es ca. 60 mal langsamer als die Ethereum Block-Rate zu sein bzw. 10 Minuten.

#### Wird es eine Ausschüttungshalbierung geben und wenn ja, wann?

Beginnend ab 10.5 Millionen Tokens, danach wenn die Hälfte der verbleibenden Tokens gemined wurden, danach wiederum nach der Hälfte der verbleibenden Tokens und so weiter, bis zu 40 Halbierungen.

#### Ist 0xBitcoin nicht schädlich für die Umwelt da es durch Proof of Work ausgeschüttet wird?

Solange wie Cryptowährungen existieren, wird es Proof of Work mining geben. Auch wenn mining Energie verbraucht, reduziert es somit doch auch Korruption, in dem der Menschheit ein transparentes, dezentralisiertes Transaktionsbuch zur Verfügung gestellt wird. Der Gedanke dahinter ist, dass eine solche Form der dezentralisierten Buchhaltung, ähnlich wie eine Polizei, die weitverbreitete Korruption in den Finanzsektoren rund um den Globus reduziert. Genauso wie wir Polizei und Buchhalter entlohnen, bezahlen wir die Blockchain für ihren Service mit Energie und Rechenleistung.

### Whitepaper Contributors
1. Infernal_toast (contract deployer)
2. Jay Logelin (jlogelin@fas.harvard.edu)

### References

Satoshi Nakamoto. Bitcoin: A Peer-to-Peer Electronic Cash System, 2009. http://www.bitcoin.org/bitcoin.pdf.

Logelin J and 0xBitcoin communitiy members. ERC 541 - Mineable Token Standard Draft, 2018. https://github.com/ethereum/EIPs/pull/918

Fabian Vogelsteller and Vitalik Buterin. ERC-20 Token Standard, 2015. URL https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20-token-standard.md.

TrustNodes. The First PoW Bitcoin Like Token Launches on Ethereum, February 16, 2018. https://www.trustnodes.com/2018/02/16/first-pow-bitcoin-like-token-launches-ethereum

Vitalik Buterin. Ethereum White Paper, 2014. https://github.com/ethereum/wiki/wiki/White-Paper

Epstien J. Why Proof of Work in Bitcoin Means Proof of Value in the Real World, December 20, 2017. https://www.neverstopmarketing.com/proof-work-bitcoin-means-proof-value-real-world/

Bitfury Group Limited. "Proof of Stake versus Proof of Work", 2015. http://bitfury.com/content/5-white-papers-research/pos-vs-pow-1.0.2.pdf

https://en.bitcoin.it/wiki/Controlled_supply

Dai W. "b-money", 1998. http://www.weidai.com/bmoney.txt

Back A. "Hashcash - a denial of service counter-measure", 2002. http://www.hashcash.org/papers/hashcash.pdf

Cunningham A, Ethereum Co-Founder Announces DAICO, a new ICO Fundraising Model (January 15, 2018). https://discover.coinsquare.io/investing/daico-new-ico-fundraising-model/


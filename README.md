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

### The Decentralized Token

Since 0xBitcoin is mined like Bitcoin, it acts just like a commodity and as such its value has a relationship to the difficulty of ‘mining’ it using computation power.  This is analogous to gold having a value related to the difficulty of finding and smelting gold ore. The current state of the Ethereum ICO market with its demonstrable failure rate leaves investors vulnerable to holding pseudo-value backed only by speculation. 0xBitcoin mitigates this problem by providing the Ethereum network with a decentralized bitcoin-like asset which is able to fill the role of a multitude of centralized tokens in a more invulnerable and trustless format.

This powerful mechanism frees individuals from having to use a third party exchange, susceptible to security holes and wallet compromise, and third party escrows. The movement away from centralization is a core tenant of what Satoshi Nakamoto originally intended with classic Bitcoin (Nakamoto, 2009).  0xBitcoin has the facilities to help keep the Ethereum ecosystem open, accountable, trustless and decentralized at every step in the value transfer process.  Unlike Bitcoin, 0xBitcoin can interact decentralzied exchanges such as EtherDelta and ForkDelta since it is compatible with Ethereum smart contracts.  This means that while Bitcoin can only be traded using centralized means, 0xBitcoin can be traded permissionlessly within immutable permanent smart contracts which are not able to be censored or restricted by central entities.  This is another clear advantage and is closer to fulfilling Satoshi’s complete vision. 

### Account System
 
As an ERC20 token, 0xBitcoin uses a traditional Ethereum account. These accounts are free and are impossible to hack or to steal from, given that the private key has not been exposed.  0xBitcoin can be stored in a Ledger Nano, Trezor or any other wallet that supports ERC20 tokens.  


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

Typically, ERC20 tokens will grant all tokens to the owner or will have an ICO which demands that amounts of Ether be sent to the owner for an initial offering of tokens.  Instead of granting tokens to the 'contract owner', all 0xBitcoin tokens are locked within the smart contract initially. These tokens are dispensed, 50 at a time, by calling the function 'mint' and using Proof of Work, similar to mining bitcoin classic. The 0xBitcoin smart contract is the first token to adhere to the ERC541 Draft Specification. As such the following Smart Contract methods are explicitly supported:

## Token
### ERC-20 Interface
#### name

Returns the name of the token - e.g. `"0xBitcoin Token"`.

OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

``` js
function name() constant returns (string name)
```

#### symbol

Returns the symbol of the token. e.g. `"0xBTC"`.

OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

``` js
function symbol() constant returns (string symbol)
```

#### totalSupply

Returns the total token supply.

``` js
function totalSupply() constant returns (uint256 totalSupply)
```

#### balanceOf

Returns the account balance of another account with address `_owner`.

``` js
function balanceOf(address _owner) constant returns (uint256 balance)
```

### Mining Operations


#### mint

Returns a flag indicating a successful hash digest verification. In order to prevent MiTM attacks, it is recommended that the digest include a recent ethereum block hash and msg.sender's address. Once verified, the mint function calculates and delivers a mining reward to the sender and performs internal accounting operations on the contract's supply.

``` js
function mint(uint256 nonce, bytes32 challenge_digest) public returns (bool success)
```

##### *Mint Event*

Upon successful verification and reward the mint method dispatches a Mint Event indicating the reward address, the reward amount, the epoch count and newest challenge number.

``` js
event Mint(address indexed from, uint reward_amount, uint epochCount, bytes32 newChallengeNumber);
```

#### getChallengeNumber

Recent ethereum block hash, used to prevent pre-mining future blocks.

``` js
function getChallengeNumber() public constant returns (bytes32) 
```

#### getMiningDifficulty

The number of digits that the digest of the PoW solution requires which typically auto adjusts during reward generation.Return the current reward amount. Depending on the algorithm, typically rewards are divided every reward era as tokens are mined to provide scarcity.


``` js
function getMiningDifficulty() public constant returns (uint)
```

#### getMiningReward

Return the current reward amount. Depending on the algorithm, typically rewards are divided every reward era as tokens are mined to provide scarcity.

``` js
function getMiningReward() public constant returns (uint)
```

### Mining Debug Operations


#### getMintDigest

Returns a test digest using the same hashing scheme used when minting new tokens.

``` js
function getMintDigest(uint256 nonce, bytes32 challenge_digest, bytes32 challenge_number) public view returns (bytes32 digesttest)
```
OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.


#### checkMintSolution

Verifies a sample solution using the same scheme as the mint method.

``` js
function checkMintSolution(uint256 nonce, bytes32 challenge_digest, bytes32 challenge_number, uint testTarget) public view returns (bool success) 
```
OPTIONAL - This method can be used to improve usability,
but interfaces and other contracts MUST NOT expect these values to be present.

## Minting New 0xBitcoins

The 0xBitcoin Token was deployed to the Ethereum blockchain in February, 2018, with the following attributes:
* No pre-mine
* No ICO
* 21,000,000 tokens total supply
* Difficulty target auto-adjusts with PoW hashrate
* Rewards decrease as more tokens are minted
* ERC20 compatibility

As such, the only way for a user to acquire 0xBitcoins is to mine them or purchase them from miners on decentralized exchanges. The mint function is responsible for verifying the validity of the hash solution, updating the contracts internal state and issuing new 0xBitcoins.

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
*figure 1. 0xBitcoin Smart Contract mint() function*

The mining reward is initially gathered and follows the same algorithm as Bitcoin classic. Essentially following the paradigm of a fully decentralized monetary system, whereby the tokens are created by the nodes of a peer to peer network. The 0xbitcoin algorithm defines how the token will be created and at what rate.

As with Bitcoin, 0xBitcoins are generated every time a user discovers a new block by being the first to submit Proof of Work for each round. The rate of the block creation is adjusted every 1024 to aim for a relatively constant adjustment period equal to approximately 6 0xBitcoin blocks per hour. The number of 0xBitcoins generated per block is set to decrease logarithmically, having a 50% reduction every time half of the remaining supply has been mined.  This ensures that the number of 0xBitcoins in existence will never exceed 21 million. 

A unique 'nonce' has to be passed into the mint function along with the hash solution digest in order for tokens to be dispensed. To find this special number, it is necessary to run a mining program. More specifically, the PoW includes a recent Ethereum block hash combined with the wallet sender's address in order to prevent man in the middle attacks when minting new coins. The challenge and nonce are validated in solidity using the keccak256 hashing algorithm to decipher the challenge's digest. Once the digest has been extracted, it is validated to match the expected challenge result and then check to ensure that it is smaller than the mining target difficulty.

The mining reward is calculated based on the logarithmic halving algorithm making the 0xBitcoin token a reliably deflationary asset. The award is immediately assigned to the sender's wallet address and the ‘tokens minted count’ is incremented within the smart contract for any other software to monitor. Notably, the contract then validates that the tokens minted count is less than or equal to the maximum supply or the given halving era that transaction is taking place. Next, the contract records diagnostics reflecting reward address, amount and ether block number for the purpose of public transparency and for other software to monitor.

### Difficulty Calculation and Adjustment
After every block is minted, the smart contract will determine if it is time to adjust the difficulty.  This occurs every 1024 mined blocks.  Just before this occurs, the contract increments the reward era if necessary - this is, if the tokens minted count has exceeded the maximum era supply which is calculated via a simple halving algorithm: 

max_era_supply = total_supply - (total_supply / (2 * (reward_era + 1)))

This means that the first era supply is 10500000 tokens, the second era supply is 15750000 tokens, the third era supply is 18375000 tokens and so forth.   During the first era, the block reward for a mint() is 50 tokens.  During the second era, the reward is 25 tokens.  During the third era, the reward is 12.5 tokens and so forth.  There are forty eras total until the mining will halt.  This is expected to take about 100 years at which time 0xBitcoin can be used as a decentralized digital currency for Ethereum.  

The reward era is used to calculate the mining reward.  Next, the 0xBitcoin smart contract adjusts the difficulty by first determining how many Ethereum blocks had been mined since the last adjustment.  If less than 1024*60 Ethereum blocks had been mined, 0xBitcoin is being mined too quickly and the difficulty will increase.  This is accomplished by reducing the size of the ‘target’.  When the target is smaller, valid nonces for minting are more rare and are harder to find for future mining rounds.   Alternatively if 0xBitcoin is being mined too slowly the target will increase in value in order to make minting more easy to accomplish.  All difficulty targets are bound within minimum and maximum difficulties of 216 and 2234 respectively.

### Calculating Mining Hashrate

To calculate approximate hashrate or approximate time to find a solution, the following equation can be used:

	TimeToSolveBlock (seconds) = (difficulty * 2 ^ 22) / hashrate (hashes per second)
 
 

### Risks and Challenges 

0xBitcoin is implemented as an Ethereum ERC20 token and so its success is largely dependent on the success of the Ethereum Network.  If Ethereum cannot scale using methods such as Plasma, Casper, and the Loom network, then 0xBitcoin will not be able to realize its full potential as the fastest and most effective decentralized currency in the world.   
  
### Frequently Asked Questions

#### Does 0xBitcoin have its own Blockchain? 

No. 0xBitcoin exists on the Ethereum Blockchain as a Smart Contract. This allows it to leverage a faster, more secure and modern crypto environment.

#### Why are there times when a lot of mints get reverted?

The difficulty was too low compared to hashrate and so multiple valid solutions were submitted to the contract in a very short amount of time.  Only one can be accepted each round and so the others are reverted.

#### How does pool mining work with 0xBitcoin?

Essentially the same way that pool mining works for classic Bitcoin, except 0xBitcoin pools must pay gas fees to the Ethereum network.  

#### How often does difficulty update?

Every 1024 blocks.

#### How does the difficulty update?

It increases up to 100% or down 50% with fractional changes in between in an effort to be approximately 60x slower than eth block rate, or roughly 10 minutes.

#### Will there be a reward halvening event and when?

At 10.5m tokens mined and when half the remaining has been mined then half of that remaining then half of that remaining, up to 40 iterations.

#### Since 0xBitcoin is Proof of Work doesn't that mean it is bad for the environment?

As long as cryptocurrencies exists, mining will always exist.  Even though mining expends energy, it ultimately reduces corruption in society by providing humanity with decentralized and transparent transactional ledgers.  Therefore the idea similar to humanity having to pay for a gigantic decentralized accounting system or police network which is reducing the widespread financial corruption across the globe.  Just as we pay police officers and accountants for their service, we pay blockchain for its service in the form of energy and computation.

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


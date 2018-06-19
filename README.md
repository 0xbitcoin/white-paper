## 0xBitcoin  

#### ( Whitepaper Revision 1.0.1 )

#### 0xBitcoin: The Decentralized Bitcoin Token for Ethereum 
-------------------------------

### Kurzfassung

Das Ethereum Netzwerk hat sich als erstes transparentes Netzwerk mit freiem Zugriff auf nicht manipulierbare Anwendungen etabliert.
Diese Anwendungen, typischerweise Smart Contracts, können nahtlos miteinander interagieren. Um diesen Prozess zu ermöglichen wurden diverse Protokolle zur Definition von Standards, wie z.B. der ERC20 Standard für das gewöhnliche Token-Format, entwickelt. Dies ermöglicht den Transfer von wertvollen, eigenen Daten ohne Mittelsmann. Bis 2018 wurden Token als sog. Sicherheit (ähnlich den Wertpapieren) ausgegeben. Sie wurden direkt vom Erzeuger an die Investoren mit dem Versprechen eines Wertanstieges, welches durch künftige Durchbrüche im Projekte erzielt werden soll, verteilt.
Dem gegenüber steht z.B. die Verteilung neuer Bitcoins. Diese werden nicht direkt an die Investoren ausgegeben, sondern vielmehr durch das sog. Bitcoin Mining neu erzeugt. Dies gibt Bitcoin die Natur eines Rohstoffes, statt einer Sicherheit.
Dieses White Paper beschreibt die ersten ERC20 Tokens die mittels Proof of Work erzeugt werden können, selbst auch als Rohstoff anzusehen sind und auf dem Modell des Bitcoin Mining basieren. 
Wie auch Bitcoins werden diese Token mittels einer Blockchain transferiert und ermöglichen eine Vielzahl von Schnittstellen für weitere Anwendungen. Darüber hinaus ergeben sich aber durch das Verarbeiten der Transaktionen auf der Ethereum Blockchain mannigfaltige Vorteile. 


### Hintergrund

0xBitcoin stellt die Implementierung des ersten dezentralisierten ERC20 Tokens auf Basis von Bitcoin in Solidity dar. Es handelt sich dabei um ein open source Gemeinschaftsprojekt und wird nicht durch ein einzelnes Team gefördert und geleitet. Aufgrund dessen gab es für 0xBitcoin auch kein ICO. Im Gegensatz zu zentralisierten Token verfügt dieses Projekt demnach auch nicht über erhebliche finanzielle Reserven, wie es bei Tokens, welche mittels ICO ausgegeben werden, der Fall ist. Wir als Gemeinschaft sind der Ansicht, dass die Dezentralisierung einen der Kerngedanken der Blockchain verkörpert und dem Nutzer mittels der vorgestellten Architektur Transparenz und ein System, dass ohne Vertrauen in einen Mittelsmann auskommt, bereitgestellt wird. Wir sind davon überzeugt, dass Ethereum und ERC20 Tokens signifikanter Bestandteil künftiger Blockchain Technologie sein werden.

0xBitcoin wurde entwickelt, um als dezentraler "Bitcoin-ähnlicher" Token innerhalb und außerhalb des Ethereum Netzwerkes genutzt zu werden. Probleme hinsichtlich der Zentralisierung und Sicherheit werden vermieden, da der Token über das Ethereum Netzwerk und somit über global verteilte, anonyme Miner gesichert wird. Da 0xBitcoin auf einem Standard-Protokoll (ERC20) basiert, kann es in herkömmlichen Ethereum Wallets gespeichert und mittels Software, welche EIP20/ERC20 Tokens unterstützt, transferiert werden. Da jeder einzelne 0xBitcoin durch vollständig dezentralisiertes Mining erschaffen wurde, gibt es keine zentrale Autorität oder Organisation, welche über die Kontrolle des Tokens verfügt. Es handelt sich um ein offenes Gemeinschaftsprojekt mit flacher Hierarchie und jedes Mitglied hat gleiche Rechte hinsichtlich der Weiterentwicklung. Dieser Weg wurde absichtlich eingeschlagen, um demselben Modell des klassichen Bitcoins zu folgen und 0xBitcoin als Rohstoff zu etablieren.

Durch Satoshi Nakamoto's Bestreben die Sicherheit des klassischen Bitcoin Netzwerkes mittels Proof of Work zu gewährleisten, wurde gleichzeitig eine der größten Errungenschaften geschaffen: das Verknüpfen von Bitcoin mit Rechenleistung. Diese kann von jedem zur Verfügung gestellt werden und resultiert somit in ein einem dezentralisiertem Netzwerk. Die Verantwortung wird auf jeden einzelnen Miner übertragen, was Regierungen keine legislativen Möglichkeiten gibt auf 0xBitcoin einzuwirken. Eine Überwachung und Einflussnahme durch Regierungen auf die Miner ist somit ausgeschlossen. Diese erhalten im Austausch für das Bereitstellen ökonomischen Aufwandes (in Form von Rechenleistung) einen kryptografischen Rohstoff - 0xBitcoin. Dadurch wird eine denzentrale Verteilung gefördert und alle involvierten Parteien zu Interessenvertretern. 0xBitcoin ist der erste Token der es ermöglicht Projekte nicht länger durch zentralisierte, an Fiat gebundene Investitionen zu finanzieren, sondern mittels dezentralisierter Rechenleistung.


### Name Origin of 0xBitcoin
The name 0xBitcoin is derived from a combination of the name of the decentralized and mined commodity Bitcoin with the term ‘0x’ which implies that the asset lives on the Ethereum Network.  This is implied because all Ethereum addresses begin with the characters ‘0x.’  The 0xBitcoin contract is located at Ethereum address [0xb6ed7644c69416d67b522e20bc294a9a9b405b31](https://etherscan.io/address/0xb6ed7644c69416d67b522e20bc294a9a9b405b31) and has validated transparent code which can be audited on the Etherscan service.  

### Ethereum and ICOs	
The Ethereum blockchain in its current state exists as a thriving permissionless ecosystem which allows any individual to store immutable records in a permissionless, invulnerable and transparent manner.  There is no other database system in the world that has this ability except for Ethereum and other similar blockchains.  As blockchain applications become richer and more numerous, there is a need for alternative distribution models than the ICO. Indeed, there have been proposals to mitigate some  initial investment risks through the recent introduction of the DAICO model (Cunningham, 2018) that rely on timed and automated value transfers via the DIACO smart contract tapping mechanism. However, this does not align a token smart contract as a non-security and still has the potential to put investors at risk if not implemented carefully. Allowing users of the network direct access to tokens by performing computations as a proof of work supplies allows any smart contract to distribute a token in a safe, slow, and controlled manner similar to the release of a new commodity.

As of 2017, all Ethereum token distribution methods were flawed and able to be Sybil attacked.  A Sybil attack is a form of computer security attack in which one human pretends to be many humans with multiple computer accounts in order to manipulate a system in a malicious way.  ICOs and airdrops are highly susceptible to Sybil Attacks and since there is no way to verify that all ERC20 tokens distributed by the deployer distributed fairly or unfairly.  0xBitcoin, with its unique Proof of Work distribution method, is resistant to Sybil attacks.  This means that 0xBitcoin is the first trustless Ethereum token in the world.  It can be argued that the distribution of 0xbitcoin is fair since it was only distributed by the solidity code and not by a human.

### Current and Proposed Use Cases
As an implementation of the original Bitcoin software as an Ethereum Smart Contract, 0xBitcoin (or 0xBTC) combines advantages from both Bitcoin and Ethereum.  The asset is decentralized, permissionless, mined and scarce just like Bitcoin which means it shares all of Bitcoin’s usecases and properties as a transparent and permanent digital record of value.  However, above Bitcoin, 0xBitcoin has the speed and scalability of the Ethereum network and is compatible with all ERC20 token services.  This means it can be stored in any Ethereum Wallet, is as secure as Ethereum, and can act as ‘the bitcoin’ for the Ethereum ecosystem.  This is important because Bitcoin is not able to communicate with or interact with the Ethereum smart contract ecosystem.  With 0xBitcoin, the Ethereum network is now effectively upgraded with the ability to interface with a commodity which shares all of the same properties as Bitcoin.  Now, all Ethereum smart contracts can hold, transfer, and trade bitcoin-like tokens permissionlessly and can do so based on immutable rules set forth using their own computer code.
	
To elaborate, the commodity Ether is being used for many purposes within the Ethereum network.  The ultimate usability of Ether as a decentralized store of value is unknown.  This is because Ether is designed as a medium for securing the Ethereum network and not only as a form of ‘bitcoin’ for Ethereum.  For example, if Proof of Stake is implemented for Ethereum, Ether will no longer be mined using Proof of Work.  This will likely leave 0xBitcoin as the only mined asset on Ethereum.  In this way and others, Ether may be transformed in such a manner as to make it best for securing the network and not as a good medium of exchange.  This message has already been implied by the Ethereum development team in 2017.  0xBitcoin intends to help fulfill a role that Ether currently plays in the Ethereum network.  0xBitcoin intends to be the primary medium of exchange and store of value for the Ethereum network.  This will allow Ether to fulfill its original intended function to secure the network at scale and to be the lifeblood of the Ethereum network.  


### Der dezentralisierte Token

Wie auch der klassische Bitcoin, wird der 0xBitcoin mittels Mining erzeugt, verhält sich somit wie ein Rohstoff und erhält seinen Wert u.a. durch die benötigte Rechenleistung zur Erzeugung neuer Blöcke. Dieser Prozess kann mit dem Schürfen von Gold verglichen werden; auch hier ist der Wert des Rohstoffes direkt abhängig von der notwendigen Arbeit um diesen zu fördern und einzuschmelzen. 
Eines der Probleme des aktuellen ICO-Modells im Ethereum Netzwerk ist, dass viele Projekte dem Investor lediglich das Versprechen eines Wertzuwachses geben und der Investor somit das Risiko eingeht einen potenziell wertlosen Token zu erwerben. 0xBitcoin versucht dieses Problem zu umgehen, indem es einen dezentralisierten Bitcoin-ähnlichen Vermögenswert zur Verfügung stellt, welcher die Rolle einer Vielzahl von zentralisierten Token übernehmen kann. Vorteile hierbei sind, dass keinem Mittelsmann vertraut werden muss, da der Prozess über einen Smart Contract abgewickelt wird und dieser nicht angreifbar ist.

Dieses Werkzeug gibt Personen die Möglichkeit sich von zentralisierten Börsen und den damit verknüpften Problemen, wie Sicherheitslücken, Wallet Kompromittierung oder Verwaltung  der finanziellen Mittel durch Dritte  loszusagen. Die Abkehr von der Zentralisierung und der Versuch dies mittels des klassischen Bitcoins zu realisieren, ist ein Kerngedanke Sataoshi Nakamoto's (Nakamoto, 2009). Auch 0xBitcoin stellt sich die Aufgabe das Ethereum Netzwerk bei jeder einzelnen Transaktion offen, rechenschaftspflichtig, dezentralisiert und vertrauenslos zu halten. Da 0xBitcoin, im Gegensatz zum klassischen Bitcoin, kompatibel mit Smart Contracts ist, kann er auch auf denzentralisierten Börsen wie ForkDelta oder EtherDelta gehandelt werden. Durch die Möglichkeit des dezentralisierten Handels ergeben sich für 0xBitcoin vielfache Eigenschaften, wie etwa der berechtigungsfreie Handel innerhalb des unveränderbaren Smart Contracts, welcher nicht durch zentrale Autoritäten zensiert oder eingeschränkt werden kann. Durch diesen Vorteil ist 0xBitcoin noch näher an Satoshi's ursprüngliche Vision angelehnt, als der klassische Bitcoin.


### Abrechnungssystem

0xBitcoin ist ein ERC20 Token und kann mit einem herkömmlichen Ethereum Wallet genutzt werden. Diese Wallets sind kostenfrei und es ist unmöglich aus Ihnen Kryptowährungen zu stehlen oder sie zu hacken, solange der private Schlüssel nicht offengelegt wird. 0xBitcoin kann in ERC20 kompatiblen Hardware Wallets, wie z.B. Ledger Nano oder Trezor aufbewahrt werden.


## Mining

There have been mintable or mined tokens proposed for Ethereum in the past but none of them have ever successfully implemented Proof of Work or automated difficulty adjustment and so never became pure decentralized currencies.  0xBitcoin is mined using a simple Keccak256 (Sha3) algorithm using the following methodology:


``` js
   keccak256(nonce, minerEthAddress, challengeNumber) < difficultyTarget
```

The nonce is a random number selected by the mining software.  The mining software mines to try to find a valid nonce.  If the above statement evalutates to true, then the nonce is a valid solution to the proof of work.   The challengeNumber is just a recent Ethereum block hash.  Every round, the challengeNumber updates to the most recent Ethereum block hash so future works cannot be mined in the past.  The miner's Ethereum Address is part of the hashed solution so that when a nonce solution is found, it is only valid for that particular miner and man in the middle attacks cannot occur.  This also enables pool mining.  The difficulty target becomes smaller and smaller automatically as more hashpower is added to the network.

## Pool Mining 

When mining 0xBitcoin, whenever a miner submits a solution, the miner must pay a small gas fee in order to execute the Ethereum smart contract code for the mint() function.  If the gas fee is too low, the solution will take too long to be mined and if difficulty is not at equillibrium then another mint() solution from another miner will likely be mined first.  This renders the original miners solution invalid and the transaction will revert().  To alleviate gas fees for miners, they can instead mine into a pool.  This way, the pool will then submit the solutions to the smart contract and pay a gas fee.  Then the pool will typically take a small percent of the rewards and give the rest to the miner for providing the PoW solution.  

Since the miner's ethereum address is included in the proof of work, pools require that miners mine using the pool's ethereum address.  This way, the miner cannot submit full solutions to the contract while only giving partial solutions to the pool.  If the miner is mining on behalf of the pool (using the pools address in the PoW algorithm) then it will not be able to submit any of those solutions to the smart contract without a revert().  This allows pools to operate without being cheated by the miners.     

Typically, a pool will accept 'partial solutions' from miners which means the miners will receive 'shares' from the pool for solutions that are close to valid but not quite valid.  This follows the same methodology as Bitcoin and Ethereum Proof of Work pool mining.  Probability theory states that, given enough close solutions, a full solution will eventually be found.  

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

Die ersten 0xBitcoin wurden im Februar 2018 im Ethereum Netzwerk erzeugt. Der Token weist folgende Eigenschaften auf:
* kein pre mine
* kein ICO
* maximale Anzahl der Token auf 21.000.000 begrenzt
* Mining difficulty passt sich automatisch der Netzwerk Hashrate an
* die Belohnungen für das Mining reduzieren sich mit steigender Anzahl geminter Token
* ERC20 Kompatibilität

Demnach ist die einzige Möglichkeit in den Besitz von 0xBitcoin zu gelangen das Mining oder der Erwerb von anderen Minern über Handelsplatformen. Die Funktion, die für das Erzeugen neuer 0xBitcoins verwendet wird, ist für das Verifizieren der Hash Lösung und Aktualisieren des inneren Zustandes des Smart Contracts verantwortlich und gibt bei korrekten Lösungen neue 0xBitcoins aus.

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


Die Belohnung für das Mining ist initial festgelegt und durch denselben Algorithmus wie der klassiche Bitcoin festgelegt. Es folgt dem Paradigma eines vollständig dezentralisierten monetären Systems. Während neue Tokens über die Knotenpunkte eines peer to peer Netzwerkes erzeugt werden, überwacht der 0xBitcoin Algorithmus wie, und in welcher Menge diese erschaffen werden. 

Wie auch Bitcoin, werden 0xBitcoin jedesmal erschaffen, wenn der Benutzer einen neuen Block findet. Er sendet hierbei als erster einen Proof of Work Beweis für die aktuelle Blockhöhe an den Smart Contract. Die Mining Schwiergkeit wird alle 1024 Blöcke angepasst. Der Smart Contract ist so aufgebaut, dass er bestrebt ist die Schwierigkeit so lange zu verändern, bis sich die Frequenz für das Finden neuer Blöcke bei vier Blöcken je Stunde einpendelt. Dabei nimmt die Anzahl der neu ausgegebenen 0xBitcoin logarithmisch ab - die Belohnung sinkt jedes Mal um 50%, sobald eine neue Era erreicht wird. Durch diese Funktion kann die maximale Anzahl von 0xBitcoin niemals 21 Millionen überschreiten.
 
Damit neue 0xBitcoin erzeugt werden können, muss der Benutzer zusammen mit der Hash-Lösung einen einzigartigen 'nonce' übermitteln. Um diese Lösungen zu finden ist die Verwendung eines Mining Programms notwendig. Um Angriffe durch zwischengeschaltete Parteien zu verhindern, kombiniert der Proof of Work Prozess den aktuelle Ethereum-Blockhash mit der Wallet Adresse des Absenders. Mining Aufgabe und Hash Lösung werden mittels Solidity geprüft und die Lösung über den keccak256 Algorithmus dechiffriert. Sobald eine Lösung gefunden wurde, wird geprüft, ob diese der erwarteten Mining Lösung entspricht und kleiner als die aktuelle Schwierigkeit ist.

Durch die logarithmische Reduktion der Belohnungen im Laufe der Zeit, ist 0cBitcoin eine verlässliche deflationäre Wertanlage. Die Erträge werden dem Absender der Lösung unverzüglich gutgeschrieben und die im Umlauf befindliche Menge von 0xBitcoin wird im Smart Contract entsprechend erhöht und kann dort von anderer Software bei Bedarf abgerufen werden. Zur Wahrung der Integrität prüft der Smart Contract ob die aktuelle Zahl in Umlauf befindlicher 0xBitcoin kleiner oder gleich der maximal möglichen Anzahl ist bzw. dass in der aktuellen Era nicht mehr Tokens erzeugt werden, als mathematisch erlaubt wäre. Darüber hinaus zeigt der Smart Contract die Adresse des letzen Wallets, das eine Lösung gefunden hat, sowie die Ethereum-Blocknummer in welcher sie gefunden wurde und vermittelt somit Transparenz des Mining-Prozesses.


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


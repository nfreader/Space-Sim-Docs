#Space Sim Overview

Space Sim is multiplayer a browser based RPG that borrows elements from several other games. 

##Gameplay 
Players pilot their ship throughout the galaxy, ferrying commodity cargo, completing missions or attacking other players as they go. Credits (the game currency) gained from these actions can be used to upgrade ships with more powerful outfits, purchase new ships altogether, and even be used to create entirely new governments.

##Critical differences 

* Ships and players are totally separate. A player could theoretically sell their only ship and be stranded on a given port. That ship can be purchased (along with its outfits and cargo) by another player and so on. 

##In depth mechanics
###Navigation 
Spobs are planets, moons, and space stations (navigable ports) that players can land on. Commodities, fuel, new ships and outfits can be acquired here. A spob's techlevel affects the cost and availability of certain items. Systems contain spobs and can belong to a specific government. Systems orbit stars. Using Bluespace technology, pilots can travel between systems at faster-than-light speeds. Distances that would conventionally take months or years to cross can be closed in only a matter of minutes. Systems orbiting distant stars can be reached in a matter of hours. 

The jumps between systems orbiting different stars are designed as a "time sink", intended to prevent players from blitzing across the entire map before other players have a chance to react. This also focuses player activity into a star's given set of systems. 

Each Bluespace 'jump' consumes one unit of fuel. Fuel can be reacquired on any spob, with the unit cost based on the spob's techlevel (higher tech means lower cost) and it's type: 

* Planets modify the fuel cost by 1
* Moons modify fuel cost by .75
* Stations modify fuel cost by 1.5

####Out of gas 
Players who run out of jump fuel in an uninhabited system can launch distress beacons. These beacons are visible to neighboring systems.

###Governments 

####Legal rating
Legal points are basically karma, used to determine whether or not someone is a pirate. Player can lose legal points by violating cargo trade agreements, reneging on mission contracts and attacking other players and so on. Legal points are gained by ???

There are three categories of governments

####Non-Affiliated
The Association of Non-Affiliated Pilots (ANAP) is the de facto 'independent' government that all players are members of by default. This quasi government has no leaders or special functions. All other governments (except Pirates) are neutral with ANAP and cannot establish any sort of diplomatic relationship with it.

####Pirates
Players who accumulate enough negative legal points are automatically placed into the pirate quasi governemtn. Pirates function identically to ANAP, except all governments consider Pirate players fair game at all times.

####Regular Governments
With enough credits, players can establish their own governments. A few government powers include: 

* Managing their own membership (allowing new members, removing, promoting to offices)
* Levying taxes on commodity trading by non-government members
* Forming alliances with other regular governments, or declaring war on them
* Create their own exclusive outfits and ships
* Take control of ports and systems via an as-of-yet-to-be-determined mechanic
* Determine who can and cannot enter ports

###Communications
There are two communications systems in play

####Blunet Messages
Blunet is an internet that functions primarily in Bluespace, allowing for near-instant transmission of data. Each system will have a Blunet node, through which messages are transmitted. In addition to the usual to/from/subject data, messages also contain the node ID that the message was sent from and the node ID that recieved it.

Normally, the node data is hidden. However, players using a Remote Override device can hack various systems to: 

* Find the node traversal data and use that to determine the receving players location 
* Spoof or disable their own node information
* Access a system's Blunet node and view data about messages that were transmitted or received at that node

...and so much more

####In-System Relay Chat (ISRC)
Analogous to IRC, ISRC is a simple messaging platform that exists in every system. Messages sent to ISRC are received by every other player in the same system. 

###Hacking
A Remote Override device can be purchased at certain ports. This device enables the hacking mechanic. Numerous systems are susceptible to hacking: 

* A player's ship's systems can be modified in various ways:
  * The FTL computer can be manipulated into completing jumps faster, but at the cost of increased fuel consumption or hull damage
  * If you need to run and hide, you can change your ship's name and registration numbers, while simultaneously stranding yourself for several hours
  * Engines, evasive outfits, weapons and so on can be modified to increase your odds of winning a combat encounter
  * More to come
* System message beacons can be hacked and manipulated 
* The game's communications network is susceptible to being compromised as mentioned above
* Mission cargo can be stripped from the rosters and resold at commodity prices (for a legal penalty)

...with more to come as I think of it.










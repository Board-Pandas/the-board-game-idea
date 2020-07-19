# the-board-game-idea
A small and simple board/card game.


--------------------------------------------------
General mixed memoes/ideas:

* All "cards" are "Spell Words" Known Words go to a shared pool. Known words can be Learned, and go to the leaner's hand.

Players cannot share eachothers hand. Intentionally revealing cards in the hand destroys the revealed spell... though maybe this is irrelevant, since spells must be taken from a shared Known pool anyway?

Default to mana the same count as number of players. This pool is shared each round. Turn order must shift to prevent this from being abused. Each full round the max mana pool increases by 1, and refills. 

--------------------------------------------------
Defitions: 

Game Leader: The player responsible for performing actions for NPCs after all players have used their turns. Determined at the start of the game. Defaults to whoever got the first move, or whoever volunteers to do it. Does not have to be one of the main player characters.

Player Character: Starts with 16 hp. There are very few ways to replenish lost HP.

Initial Draw: At the start of the game, before the Unknown deck is shuffled. After all players have determined their class and turn order, players may search the Unknown deck to pick up to 5 starting cards based on their class's Initial Draw rules.

Full Round: When all players and NPCs have used up their turns. After the end of a full round, the player's shared mana maximum is increased by 1, and the current manage is refilled to the new maximum.

Turn: Any character takes 3 actions. For NPCs this is almost always casting every spell they can afford if anything is nearby.

Rank: The power level of a spell. Typically
* Rank 1 - 1 damage
* Rank 2 - 2 damage
* Rank 3 - 4 damage

Shield: Has an element but no (effectively 1) HP. A character with a shield cannot be damaged until the shields are removed.

Action: 
Any of: 
* Gather Resources - Move (number of players) from Unknown Spells to Known Spells
* Cast a Spell - Caster can use the spell on any adjacent targets, or self. Requires having enough mana available to cast. Mana cost is equivalent to the rank of the spell. (Class Abilities may break this rule.)
* Teach a Spell - Target can give a spell to any other player. (Or NPC.) Has no range limit.
* Learn a Spell - Learn any 2 spells from the Known spells. Move them to your hand. 
* Movement - Navigate the map. Move the number of spaces equal to the rank of the card used. After using a spell to move, the spell goes to Unknown.
* Throw - Push any other adjacent character away a number of spaces equal to the spell's rank. (NO DIAGONALS.)

Does Not Include: 
* Class Ability - These are usually automatic. When optional, they don't count as a separate action.
* Signaling / Burning a Spell - Signaling / Burning a Learned spell removes it from your hand, shows it to all other players, then moves it to Unknown. You recover 1 missing HP.

Adjacent: Any other cell neighboring a specific cell, including diagonals.

Unknown Words: All cards start here. On the first turn, each player can go through this deck and pick up to 5 cards their class can use

Known Words: This is a shared pool of cards all players may pick from. Capacity of 20. Any spells added past capacity are immediately moved back to Unknown.

Learned Words: This is referring to any given player's hand of cards. There is no rule limit on the size of a hand.

Spawn: Draw two cards for the new hostile npc. The colors make up its shields. Draw one more card. The rank determines HP (4, 8, 16)

--------------------------------------------------
Default Map: 
8x8 grid
--------------------------------------------------
Objectives: 

idk, highest number of last-hits to opponents after defeating all enemies? Everyone loses if nobody survives to the end.

Other players can be last-hit too and it still counts for points. But it kinda makes you an awful person. Maybe best left to a optional house-rule.
--------------------------------------------------
Character Classes, Starting Cards:

Defender - 
+ You may spend 1 mana to learn any Known rank-1 spell. This does not cost an action. Casting rank 1 spells also do not cost an action. (You may draw resources 3 times for all actions, learn as many spells as you have mana to afford, and cast with everything left)

+ During the Initial Draw, you may take any Fire cards or any Rank 1 spell.

Instructor - 
+ Whenever you would move a rank 2 spell from your hand to Unknown Spells, it instead goes to Known Spells. You cannot use rank 3 spells.

+ During the Initial Draw, you may take any Earth cards, or rank 2 cards.

Singer - 
+ Your rank 3 spells can remove any one shield from an adjacent target, regardless of element. You unlearn (move to Unknown) all Rank 1 spells from your hand when you turn ends.

+ During the Initial Draw, you may take any Wind cards, or rank 3 cards.

Dancer - 
+ Rhythmic Flow - After casting a spell, all other copies of it (same rank and element) that you have Learned are cast as well for 1 mana each- regardless of rank- until out of duplicates or out of mana. (All casts affect the original target.)

+ During the Initial Draw, you take each Water card you encounter until your hand is full. You do not get to choose which ones.
--------------------------------------------------
Special Cards
* Awaken: When drawn, spawn a player-hostile NPC in any adjacent free cell to the character that drew it. If all adjacent spaces are filled, restore all HP to the character that drew this card. Immediately move this card to the Unknown.

* Insight: If drawn by a player, either: 
A: Take one card from the Known pile, but move all other Known cards to Unknown. Or. 
B: Learn ALL Known cards, but your turn ends immediately.

If drawn by an NPC, take 3 cards from the Unknown pile. For each: Add a shield of that element (if not already bearing one of that type), restore HP equal to the rank of the card, then cast the spell on the nearest enemy.

After this is done, return the three cards to Unknown and reshuffle.

* Assimilate: On player draw: If adjacent to an enemy that has shields, you may learn that shield as an attacking spell. this removes the opponent's shield. On NPC draw: The last Known card is moved to the NPC as a new shield.

* Imitate: On Player draw: You cast your strongest spell on yourself. This does not activate class traits. On Enemy draw: Re-cast the last spell anyone cast onto the nearest player. If no spells had been played prior, this does nothing.

* Annihilate: On player draw: All cards in your hand are discarded to Untapped Spells. All car

--------------------------------------------------
Card Elements
Fire
Wind
Water
Earth

--------------------------------------------------
Card Properties
Name
Art
Flavor Text
Rank

Specialty Explanations
NPC-specific instructions.

--------------------------------------------------
Living Spells

On their turn they just topdeck and keep casting until they can't anynmore, I guess. if nothing is nearby, they move in a stright line until thhey hit a wall, then turn and keep going.


--------------------------------------------------
Mooks

???
--------------------------------------------------
Misc

 Cards with limited numeric randomness (f)
* Possibly a map in some fashion (c)
* Colored/Typed/Elemental shields that must be removed (c)
* Crystals, Dragons, and Language are involved in some fashion (f)
* Growing mana counts. (f)
* PvE player goals. (c)
* Relatively simple rules.
* Not much harder to code than it is to implement on pen and paper.
* Stats, movement, and attack all use the same cards to determine. (c)
* Player class types, instead of one stated color/type. (f)
* Shared deck

* ... Which might be a cool play? If you can sacrifice a weak Red spell to signal to your partners that you might have a really good red to use if they save you enough Mana. (d)

--

Cards with limited randomness is like the player predetermining the deck.
A map most certainly could be like branching ways in games. Beat boss a or boss b?
Crystals could be the mana, dragons the caster and language was just a proposal.
--
CH
The Dragon Warrior
[3:47 PM]
The Dragon Wizard(edited)
[3:47 PM]
The Dragon Dancer

1

1
[3:48 PM]
The Dragon Acrobat

FP
Warrior, Wizard, Mage, Dancer
--

Well
[9:00 PM]
let's say there is a board map
[9:00 PM]
And there is two types of units
[9:00 PM]
character units, and the Crystal spells
[9:01 PM]
When fighting a Crystal, that crystal would pull a card that would represent it's stats
[9:01 PM]
hp and whatever
[9:02 PM]
on one side, it has varius numbers with shields (let's say 6 for example)
[9:02 PM]
you roll a dice, and the number you get, it's the armor it has
[9:02 PM]
so you have to use spell cards that have the same type of armor to hit it
---

... Which might be a cool play? If you can sacrifice a weak Red spell to signal to your partners that you might have a really good red to use if they save you enough Mana.
--

Chaincasting?

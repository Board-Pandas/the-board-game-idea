# the-board-game-idea
A small and simple board/card game.


--------------------------------------------------
General mixed memoes/ideas:

* All "cards" are "Spell Words" Known Words go to a shared pool. Known words can be Learned, and go to the leaner's hand.

Players cannot share eachothers hand. Intentionally revealing cards in the hand destroys the revealed spell... though maybe this is irrelevant, since spells must be taken from a shared Known pool anyway?

--------------------------------------------------
Defitions: 

Game Leader: The player responsible for performing actions for NPCs after all players have used their turns. Determined at the start of the game. Defaults to whoever got the first move, or whoever volunteers to do it. Does not have to be one of the main player characters.

Player Character: Starts with 16 hp. There are very few ways to replenish lost HP.

Base Deck: Contains all cards that will be played in the immediate game. When the game starts, this is shuffled and placed into position as the Unknown Words card pile. With no additional cards or house rules, this contains: 
3 Copies of all Rank 1 Spells
2 Copies of all Rank 2 Spells
1 Copy of all Rank 3 Spells
All Special Cards.
All other played-agreed-upon cards.

Initial Draw: After all players have determined their class and turn order, players may search the Unknown Words deck to pick up to 5 starting cards based on their class's Initial Draw rules.

Mulligan: After the Initial Draw, if you do not like your hand you may return all of the cards you drew to the bottom of the Unknown Words and draw one less than you had from the top of the Unknown Words. You may repeat this until you have only 1 card left. If you only have one card, you may not Mulligan. After all players have completed their Initial Draw and any desired Mulligans, mulligans will no longer be available for the rest of the game.

Full Round: When all players and NPCs have used up their turns. After the end of a full round [Insert mechanic to allow power escalation here].

Turn: Any character takes 3 actions. For NPCs this is almost always casting every spell they are holding or drawing more if they are not holding any. NPCs will try to draw 2 cards directly from Unknown Cards. If they attempt to do so and there are no Unknown Cards, they will draw from the leftmost Known Cards instead.

Rank: The power level of a spell. Typically
* Rank 1 - 1 damage
* Rank 2 - 2 damage
* Rank 3 - 4 damage

Shield: Has an element but no (effectively 1) HP. A character with a shield cannot be damaged until the shields are removed.

Action: An action costs 1 of the available actions for a player's turn (usually, 3 actions per turn).
Any of: 
* Research - Move (number of players) from Unknown Spells to Known Spells. If (number of players) is larger than the number of remaining Unknown Spells, take 1 damage for each attempt to draw from nothing.
* Cast a Spell - Caster can use the spell on any adjacent targets, or self.
* Teach a Spell - Target can give a spell to any other player. (Or NPC.) Has no range limit.
* Learn a Spell - Learn any 2 spells from the Known spells. Move them to your hand. 
* Movement - Navigate the map. Move the number of spaces equal to the rank of the card used. After using a spell to move, the spell goes to Unknown.
* Throw - Push any other adjacent character away a number of spaces equal to the spell's rank. (NO DIAGONALS.)

Does Not Include: 
* Class Ability - These are usually automatic. When optional, they don't count as a separate action.
* Signaling / Burning a Spell - Signaling / Burning a Learned spell removes it from your hand, shows it to all other players, then moves it to the bottom of Unknown Words. You recover 1 missing HP.

Adjacent: Any other cell neighboring a specific cell, including diagonals.

Unknown Words: All cards start here. On the first turn, each player can go through this deck and pick up to 5 cards their class can use

Known Words: This is a shared pool of cards all players may pick from. Capacity of 20. Any spells added past capacity are immediately moved back to Unknown.

Learned Words: This is referring to any given player's hand of cards. There is no rule limit on the size of a hand.

Spawn: Draw two cards for the new hostile npc. The colors make up its shields. Draw one more card. The rank determines HP (4, 8, 16)

Converse / Reply: When a player character intends to use a spell, each allied player may use one of their Learned (held) cards to Compliment the other player's spell. Complimenting a spell adds the stats to the existing spell. If the rank is higher than the base spell, the elements are combined. Spells used to compliment are discarded back to Unknown Words.

--------------------------------------------------
Default Map: 
8x8 grid
--------------------------------------------------
Objectives: 

idk, highest number of last-hits to opponents after defeating all enemies? Everyone loses if nobody survives to the end.
Alternatively, just see how survives the longest as enemies become increasingly overpowered?
Alternatively, the first player to defeat 10 enemies becomes a Crystal Devourer with (Number of Players * 20 )HP. If they defeat all other enemies and players, they win. If a player defeats the Crystal Dragon, they replace it with a -5 penalty to Max HP.

Other players can be last-hit too and it still counts for points. But it kinda makes you an awful person. Maybe best left to a optional house-rule.
--------------------------------------------------
Character Classes, Starting Cards:

Defender - 
+ You may Learn and Cast any Rank 1 card for free. This does not cost an action. (You may draw resources 3 times for all actions, learn every Rank 1 Known, and cast them all)
+ You may only use the Move action once per turn.
+ During the Initial Draw, you draw only 1 card.

Instructor - 
+ Whenever you would move a rank 2 spell from your hand to Unknown Spells, it instead goes to Known Spells. You cannot use rank 3 spells.
+ Every turn, you may perform one free Research without using an action.
+ During the Initial Draw, continue drawing until you have 3 rank 2 spells, or 10 spells total.

Singer - 
+ Your rank 3 spells can remove any one shield from an adjacent target, regardless of element. You unlearn (move to Unknown) all Rank 1 spells from your hand when you turn ends.
+ Your spells have infinite range in a straight line North, East, South, or West of your position.
+ During the Initial Draw, continue drawing until you have 2 rank 3 cards, or 10 spells total.

Dancer - 
+ Rhythmic Flow - Whenever you cast a spell, you cast every spell you have Learned of the same Element. (All casts affect the original target.)
+ Any spell you use for movement allows you to move 5 spaces. You recover 1HP any time you use the Move action.
+ During the Initial Draw, draw 5 cards. Then, for every Water element card in-hand, draw an additional card. Finally, draw until your first non-water card.
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

* Annihilate: On player draw: All cards in your hand are discarded to Untapped Spells. All cards discarded are cast on the player in order from left most to right. Any spell that would kill the player is discarded without effect. On NPC Draw: Draw 3 more cards from Unknown. Discard all held cards. Gain a shield of the same type as each spell discarded, if that shield is not already applied. Then, task all of those spells on the nearest target (even if allied) and discard all spells.

* Tome: If there are less than 5 Known cards, move from Unknown to Known until there are at least 5 Known cards. Then move the 5 oldest to hand. If drawn by NPC: Also recover HP based on each card's rank

* Blasphemy: Kept in hand like a normal spell. When used, move all cards from Known to Unknown and recover 1hp for each card moved. then this card is discarded to Unknown Cards.

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


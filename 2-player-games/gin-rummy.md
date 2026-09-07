[return](../master.md)
# Gin Rummy 
> <sub>Reference: [Bicycle](https://bicyclecards.com/how-to-play/gin-rummy)</sub>
2-player card game where players take turns drawing + discarding cards to form sets of cards in their hands. To include more players, see [additional notes](#additional-notes)

## Quick Reference
|Rule|Description|
|---|---|
|[Cards](#setup)|No Jokers|
|[Hands](#setup)|10 cards|
|[Turn](#first-turn)|Draw + Discard from deck/discard pile|
|[Order](#order)|K high, A low|
|[Value](#value)|K/Q/J = 10pt, 10 to A = number value|
|[Melds](#melds)|Sequences (same suit only) or Triplets; 3+ cards|
|[Knock](#knocking)|Max. 10 disjoint card value to knock<br>Opponents may add to knocking player's melds<br>Get difference of values of players' disjoint cards |
|[Undercut](#undercut)|If value of opponent's disjoint cards < value of knocking player's disjoint cards<br>Opponent gets 10 + difference of values of players' disjoint cards
|[Gin](#gin)|No disjoint cards<br>Get 20 + value of opponent's disjoint cards|
|[Win](#objective)|100 pts|

## Table of Contents
- [Setup](#setup)
- [Objective](#objective)
- [Rules](#rules)
    - [Melds](#melds)
    - [Disjoint Cards](#disjoint)
    - [Card Order](#order)
    - [Card Value](#value)
    - [Turns](#first-turn)
    - [Knocking (Ending a Round)](#knocking)
    - [Undercut](#undercut)
    - [Gin](#gin)
- [Scoring](#scoring)
- [Additional Notes](#additional-notes)
## Setup {#setup}
- 52 card deck, no Jokers
- Deal 10 cards to each player face down
- The player who goes first alternates each round
- The deck is placed face-down in the center of the table
- Deal one face-up card into the discard pile next to the deck

## Objective {#objective}
Be the first player to obtain **100 points** across several hands.

## Rules {#rules}
### Melds {#melds}
Each player will aim to form <b>melds</b> (aka combinations, sets, etc.) in their hands.
A meld = <b>3+ cards</b>, either a <b>sequence</b> or a <b>triplet</b>.
| Meld | Definition | Examples |
| --- | --- | ---------- | 
| Sequence | 3+ consecutive cards of the same suit. <br> A can connect with 2 but not with K.| :white_check_mark: A:diamonds:2:diamonds:3:diamonds:<br>:white_check_mark: 8:clubs:9:clubs:10:clubs:J:clubs:Q:clubs:<br>:x: K:hearts:A:hearts:2:hearts:<br>:x:5:diamonds:6:spades:7:diamonds:<br>:x:3:hearts:5:hearts:6:hearts:|
| Triplet | 3+ cards of the same value. |:white_check_mark:K:diamonds:K:clubs:K:hearts:<br>:white_check_mark:2:diamonds:2:clubs:2:hearts:2:spades:<br>:x:5:spades:5:diamonds:<br>:x:J:diamonds:J:clubs:Q:hearts:| 

Melds cannot share overlap of cards. 
Example: if you have 2:diamonds:3:diamonds:4:diamonds:4:clubs:4:spades:, this does not become two valid melds 2:diamonds:3:diamonds:4:diamonds: and 4:diamonds:4:clubs:4:spades:. This hand would only have one valid meld and one incomplete meld.

### Disjoint Cards {#disjoint}
Cards that are in a player's hand but are not a part of any meld. 
Example: In the hand 2:spades:2:hearts:2:clubs:2:diamonds:3:diamonds:4:diamonds:5:diamonds:Q:spades:K:spades:K:clubs:, only Q:spades:K:spades:K:clubs: are disjoint.
### Card Order {#order}
Highest to lowest: K, Q, J, 10 ... 3, 2, A
### Card Value {#value}
- Face/Royal cards (K/Q/J) = 10 points
- A = 1 point
- Number cards = number displayed
    - (10 = 10 points, 9 = 9 points, etc.)
### First Turn {#first-turn}
- The first player has the option of taking the first face-up card in the discard pile and discarding a different card from their hand, ending their turn
- If they pass, the next player is given this option
- If both players pass, the first player must begin their turn by drawing a card from the deck and must discard a card from their hand
    - They may discard the card they drew from the deck
### Every Turn {#every-turn}
- The player must draw a card from the top of the discard pile OR the top of the deck
- The player must then discard a card from their hand 
- :x: The player may NOT draw a card from the discard pile and discard that same card
- :white_check_mark: The player may draw a card from the deck and discard that same card
### Knocking (Ending a Round) {#knocking}
- A player can knock when the total value of their disjoint cards ≤ 10
    - :white_check_mark: A:spades:A:diamonds:2:diamonds:2:clubs:3:diamonds:3:clubs:4:hearts:5:hearts:6:hearts:7:hearts:- Can knock
    - :x: A:diamonds:A:clubs:A:spades:2:diamonds:2:spades:3:spades:J:hearts:Q:hearts:Q:clubs:K:hearts: - Cannot knock
- The player knocks by taking the top card from the draw pile and placing it face down on the discard pile
- Knocking is not mandatory
- The player choosing to knock does so immediately at the beginning of their turn without drawing a card
- Knocking ends the round and all players reveal their hands
- If the player does not declared [Gin](#gin), the other players can remove their disjoint cards by adding them to the knocking player's melds if they keep the meld valid
    - Example: If the knocking player's hand is A:spades:2:diamonds:2:clubs:2:hearts:5:spades:6:spades:7:spades:J:diamonds:Q:diamonds:K:diamonds:, a player with disjoint cards A:clubs:A:diamonds:2:spades:8:spades: may add their 2:spades: to the meld 2:diamonds:2:clubs:2:hearts: and their 8:spades: to the meld 5:spades:6:spades:7:spades:. The A:clubs:A:diamonds: may not be added

### Undercut {#undercut}
The other player **undercuts** the knocking player if the value of knocking player's disjoint cards is **more** than the value of the other player's  **remaining** disjoint cards. 
:white_check_mark: Undercut: The knocking player has disjoint cards 2:spades:3:diamonds: and the other player has disjoint card 4:diamonds:
:x: No undercut: The knocking player has disjoint card A:spades: and the other player has disjoint cards A:diamonds:K:diamonds:

### Gin {#gin}
Gin = A player knocks with no disjoint cards and all melds
- :white_check_mark: Can declare Gin: 6:diamonds:7:diamonds:8:diamonds:9:diamonds:4:spades:5:spades:6:spades:Q:diamonds:Q:clubs:Q:hearts:
- :white_check_mark: Can declare Gin: 7:diamonds:8:diamonds:9:diamonds:10:diamonds:10:clubs:10:clubs:K:diamonds:K:clubs:K:hearts:K:spades:
- :x: Cannot declare Gin: 2:spades:2:diamonds:2:clubs:3:clubs:4:clubs:4:hearts:4:spades:J:diamonds:J:clubs:J:spades:

## Scoring {#scoring}
| Condition | Scoring | Example|
| --- | --- | --- |
| Gin | The player who declared Gin gets:<br>20 points + value of opponent's remaining disjoint cards| Opponent's disjoint cards: 2:diamonds:3:spades:<br>Player who declared Gin gets 25 points|
| Knocking (no undercut) | The player who declared Knock gets:<br>Value of opponent's remaining disjoint cards - Value of knocking player's disjoint cards |Knocking player's disjoint cards: A:hearts:<br>Opponent's disjoint cards: 4:hearts:J:spades:<br>Knocking player gets 13 points
| Knocking (undercut) | Undercutting player gets:<br>10 points + (Value of knocking player's disjoint cards - Value of opponent's remaining disjoint cards) |Knocking player's disjoint cards: 4:diamonds:<br>Undercutting player's disjoint cards: 2:spades:<br>Undercutting player gets 12 points
### Additional Notes {#additional-notes}
- Gin/undercut bonuses could also be 25 points each.
- Some versions have the winner of the previous hand become the dealer of the next hand; in addition, the non-dealer is the first player of that next hand
- To incorporate more players, the hand size could be reduced to 7 cards each.

<!--> END OF DOCUMENT





<-->
***
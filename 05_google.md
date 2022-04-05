### Assignment
* title **google**
* Create or use an existing programming task in a programming language of a class you are teaching (or would like to teach).
  
### Lab 3.03 - War (Card Game)
Create a program that lets a user play a simplified version of the card game ‘War’. In this version, the
users will share a single deck of cards and cards will not be added back to the deck after they have been
played.
Your game should
  - start with a given shuffled deck variable (shuffle function comes from python’s random library,
more details below)
  - ask for player1 and player2’s names.
  - have a function player_turn, with the contract shown below:
##### Name: player_turn
  - Purpose: takes in a player name,
  - draws/removes a card from the deck,
  - prints "user drew card x",
  - and returns the value
##### Arguments: player_name as string, deck as list
##### Returns: integer 
* Jacks will be represented as 11, Queens will be represented as 12, Kings will be represented as 13,
and Aces will be represented as 14. The suit does not matter.
* Create a function card_name to be used by player_turn(), that takes in an integer
representing a drawn card, and returns a string that names the card. 2 prints as "2", 3 is "3",
etc., but 11 is "J", 12 is "Q", 13 is "K", and 14 is "A".
* Make sure to write the contract for card_name()!
* Include a while loop that keeps the game running until there are no cards in the deck.
* If there is a tie, there is “war”. Take the next two cards. Whoever wins that comparison gets all four
cards (including the previous tied cards).
* If there is another tie, continue taking the next two cards until there a winner.
* The winner takes all the “war” cards.
* Keep track of the score.
* The player who takes the greatest number of cards wins.
* Declare the name of the winner and final score at the end of the game.

#### First search that I ran "war card game python" led me to the following sites:
- https://gist.github.com/damianesteban/689612
  - this site was not very usefull because the code that is shown is object-oriented and too complex for my students
  - I was able to learn something from it, but it would be too difficult for the students
- https://stackoverflow.com/questions/67219009/creating-the-warcard-game-using-oop-in-python
  - this site does a great job at walking the students through all aspects of the code; however, the final product, i.e. the code itself is probably meant for college students
  - I would not call it over-complicated, but it can't be used by my 9th graders in our Intro CS class.
- https://pythonalgos.com/level-1-python-war-card-game/
  - this site would be my favorite to suggest for the students. It walks the students throug each step of the coding process and provides the with code that can be copied onto their own Repl
  - not only could the students learn fro it as I did, but also they could expand their coding skills

 

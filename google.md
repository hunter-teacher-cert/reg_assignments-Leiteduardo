### Assignment
* title **google**
* Create or use an existing programming task in a programming language of a class you are teaching (or would like to teach).
  - The task should involve multiple steps, ~5.
* Run a few internet searches that a student might run when presented with your task.
* In a markdown file:
  - Describe the task
  - For each search you ran provide three links from the results
    - Provide a critique on the result. Things to consider:
      - Was it useful?
      - Was it too simple/complex?
      - Was it unecessarily compicated?
      - Did it include copypastable code?
      - Did you learn from it/could a student learn from it?
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

 

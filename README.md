# Ray_CSCI2270_FinalProject

## Initial project summary
I'm planning on simulating a deck of cards using an array. There will be methods to build the deck, shuffle the deck (possibly simulating different types of shuffling), print the deck, find a card, and pick a random card. Beyond that, I will implement a game of blackjack.

The reason for using an array is that the deck of cards itself is a static size (52 cards), so there's no need for the resizability of a linked list or vector. A more flexible data structure could be helpful for representing sets of cards with changing size (e.g. dealt cards), but an array is fine for keeping track of the entire deck.  

## Installation instructions
1. Fork Ray_CSCI2270_FinalProject into a directory on either your class VM or personal computer (Mac should work, any Linux distro should work, Windows is unknown).
2. Make Ray_CSCI2270_FinalProject your working directory (`cd Path/To/Ray_CSCI2270_FinalProject`)
3. Type `make` and hit enter
4. Type `./DeckOfCards` and hit enter

*Please let me know if you have any issues setting anything up*

## Known nitpicks
+ Helper::alphaToDigit in Helper.cpp can be done more elegantly with case statements
+ Some functions (namely DeckOfCards::blackjack) are gigantic, so a code refactor would be ideal
+ It would be best if the card inputs would *only* allow names and suits of cards
+ Some lines are obnoxiously long
+ The "print deck" output is unwieldy, making it so everything fits on one page would be ideal

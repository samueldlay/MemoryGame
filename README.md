# Sam's Memory Card Game
## Author: Samuel Lay


### Functionality/Project Overview

The majority of functions in the source code are organized in the order in which each procedure is executed. A 'shuffleArray' function was originally provided in the JavaScript source code, but I started from the ground up with my own randomize function. Much of the CSS and HTML was provided by Udacity as a static template, with some extra lines of code that I added for stylizing and functionality. Comments have been provided in the JS to detail functionality.

## How the game is played

When the game initially runs, the 'deck' is populated with a randomized array of 16 cards. Upon clicking the first card, each of the following procedures are executed:
* A timer displayed below the title activates when the first card is revealed
* When a second card is clicked/touched
* If it doesn't match, a CSS animation occurs and the cards flip back over
* If it matches, a CSS animation occurs and the two cards remain visible
* One move is equal to the selection of two cards
* Moves are counted until the entire deck is visible
* Once all cards match, a modal window pops up, giving a rundown of your score
* If the score is < 14, one star is removed
* If the score is < 23, two stars are removed
* If the score is > 23, a funny message displays in the modal window
* Time has no bearing on score

## Sources:
* I used https://sabe.io/tutorials/how-to-create-modal-popup-box as guidance for implementing modals.
* The background image that I used can be found at: http://stamfordymca.org/summer-camp/wp-content/plugins/page-layout-builder/images/bg/

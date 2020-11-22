# Slot Machine

## Description

A slot-machine made with HTML5, CSS and JavaScript.

## Requirements to run

Browser based slot machine having minimum feature set:

   Reels
● 3 reels
● 9 symbols / reel

  Actions
● Spin
○ Spins all 3 reels
○ Reels should stop at random position

  Results inspection
● After reels stop SW should check reel position outcome:
○ 2 same icons in any reel at same horizontal position means player wins
○ Indication that player wins


  User case
1. Player press Spin button
2. Reels start to spin and stop at random position.
3. If win line has at least 2 same symbols at the same central horizontal position software indicates player
that he has won

## Design Pattern

The pattern used for javascript classes is called Pseudo Classical Prototypal pattern. All the properties are definied at the class constructor and the methods are definied extending the class' prototype.

## Code Description

For this project I decided to keep every class in a diferent file, because it is better to read, better to debug and better to extend it. 

I would recommend start to read the code from the file [constants.js](js/constants.js) where I kept the project's constants, then go to [resources.js](js/resources.js) where you can find my helper methods (basically the image load, and random generator), then you can follow as pleases you from [engine.js](js/engine.js) and following the method calls into [slotmachine.js](js/slotmachine.js) and [reel.js](js/reel.js). 

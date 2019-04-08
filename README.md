# project names
Pig dice game

## Author
* Sang Brian Cheruiyot

* Fourth independent project,08/04/2019
## description
This is a simple dice game where two players have the chance to roll the dice to try and achieve a score of 100. Each player repeatedly rolls a die until either a 1 is rolled or the player decides to "hold".

The rules of the game are:

* When a player rolls a 1, their total score reverts to 0 and it becomes the next player's turn.
* When the player rolls a 2 - 6, the score is added to their turn total and they can continue to play
* When the player chooses to "hold", their turn total is added to their total score, and it becomes the next player's turn.
* The player who first scores 100 or more points wins.

## specifications
1. It can display the inputted name of the players when 'Play' is clicked.
* Input:

  ` player1:kate
    player2:ruth `
* Output:

  ` Players:   kate              ruth ``
2. Player1 can roll the dice and the result displayed as their turn score.
* Input:
 ` 'roll' button is clicked
  dice score: 3 ``

* Output:
` Turn Score: 6`
3. Player1 can hold the dice and their turn total score is added to their total score. Player2 then has the chance to play.
* Input:

` 'Hold' button is clicked.`
* Output:

  ` Turn Score: 3
   Total Score: 9`
4. Player2 can roll the dice and the result displayed as their turn score.
* Input:

` 'Roll' button is clicked
 Dice Score: 2`
* Output:

` Turn Score: 5`
5. Player2 can hold the dice and their turn score is added to their total score. Player1 then has the chance to play.
* Input:

  ` 'Hold' button is clicked.`
* Output:

 ` Turn Score: 4
   Total Score: 9`       
6. If a player's dice score is a 1, their turn score will be reduced to 0.
* Input:

  ` 'Roll' button is clicked
    Dice Score: 1`
* Output:

  `Previous Turn Score: 30
   New Turn Score: 0`

## setup/installation
To view the website, click Pig Dice Game or copy (https://briansachaa.github.io/Pig-Dice to your browser and load it.

## known Bugs
no known Bugs

## Technologies used
* HTML
* CSS
* JAVASCRIPT
* JQUERY

## LICENSE
MIT License

Copyright (c) [2019] [Sang Brian Cheruiyot]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. Copyright (c) 2019 briansachaa

Pong
====
A [Pong](http://en.wikipedia.org/wiki/Pong) clone implemented in Verilog for the [Altera DE2](http://www.altera.com/education/univ/materials/boards/de2/unv-de2-board.html).

This repository contains the entire Quartus II project for the game. See [pong.v](https://github.com/felixmo/Pong/blob/master/pong.v) for the source.

Info
----
There is a 3 second delay between each round. 

The game ends when a player scores 10 points.
The scores are shown on the seven-segment displays (HEX6 for player 1, HEX4 for player 2).
The winner is displayed on HEX7 & HEX6.

When the game is over, use SW17 to restart the game.

Control | Player 1 | Player 2
:-------:|:--------:|:--------:
Up		| 'W' | KEY3
Down	| 'S' | KEY0
Reset	| SW17 | SW17

License
-------
The project is licensed under the [MIT License](http://opensource.org/licenses/mit-license.html).

Acknowledgments
---------------
* [John Loomis](http://www.johnloomis.org/) for PS/2 keyboard input modules
* [Simon Moore](http://www.cl.cam.ac.uk/~swm11/) for VGA output module
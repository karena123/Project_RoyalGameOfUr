# Project_RoyalGameOfUr
A digital remake of the ancient Mesopotamian board game "Royal Game of Ur" coded in OCaml. The game can be played both in the terminal and on a GUI based on player preference. This was created as a long term group project by Karen Aoki, Adrian Lee, and Paul Sachs.

First, follow the instructions to install in the INSTALL.md file.

The game consists of two players, each with 7 pieces. There are 4 dice to roll, each one either being a one or a zero. The goal is to get all of your pieces from your start, across the shared center path, onto you end path and to the finish.

However, if you are on the middle, shared path, your opponent can take your piece if it lands on the same space. You can also not move if you are going to land your piece on one of your own.

You can add pieces onto the board at any time so long as the tile to add them on is open, depending on your roll.

If you land on a rosetta tile, you are safe from capture and are allowed to roll again and move any piece.

If you roll a 0 or have no valid moves left you must pass your turn.

This game has several boards to play on, two display modes, one in the terminal and one in an X11 window, and allows for you to play locally with a friend or with a bot, which has 3 different difficulty modes.

Controls (Display):

Roll: r Pass: p Quit: q Move Numbered piece (1,2..7): The number key of said piece.

Controls (Terminal Mode): Roll: r Pass: p Quit: q Move: m #, where # is the number of the piece being moved.

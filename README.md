Download Link: https://assignmentchef.com/product/solved-phase-4-gameboard
<br>
5/5 - (1 vote)

Phase 4 Gameboard: Create a Gameboard class that will hold and manage a 2D array of tiles that will represent the game state. To initialize the game board, data will be read in from a text file. The text file has the following format. The first row contains two integers that specify how many rows and columns are in the rectangular game board. The rest of the file gives the initial state of the game board. It has the same format as the output that we have been generating to this point: “Y” is the amulet, “@” is the player, and so on. The Gameboard class, for this phase, only needs one instance variable of type Tile[][]. Write a constructor that accepts a file name as a parameter (a String). Open that file, read the contents, and initialize your two dimensional array of tiles based on the file. It can be assumed that the file will be in the same folder as your code. Write a toString() method that returns the game board as a multi-line String. The first line should give the current health of the player, and the remaining lines should show the board. See the examples below. You can test your class with TestPhase4.java. You should get the output shown below. Make sure the supplied test data files (phase4GameBoard1.txt and phase4GameBoard2.txt) are in the same folder as the rest of your files.



Health: 100

#######

#^Y.t.#

#^<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="c9a189e79d">[email protected]</a>#

#.h..h#

#######

Health: 100

#############

#^Y.t…….#

#^h..T..^…#

#.h..h…<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="9fb1b1df">[email protected]</a>#

#############
Download Link: https://assignmentchef.com/product/solved-cse-232-honors-project-2
<br>
<h2>Assignment Overview</h2>

Overview

OK, you know all about dots and boxes <u>https://en.wikipedia.org/wiki/Dots_and_Boxes</u> and you wrote the game playing elements and a random player to play the game. Now you want to write a much better player that should win the game.




<h2>Winning</h2>

How do you win the game? Can you always win the game. It turns out that d&amp;b is a kind of game called a combinatorial game.

<ul>

 <li>there are two players moving alternately;</li>

 <li>there are no chance devices and both players have perfect information;</li>

 <li>the rules are such that the game must eventually end; and</li>

 <li>there are no draws, and the winner is determined by who moves last.</li>

</ul>

Because of this, it is possible to come up with a winning strategy.




<h2>Winning Player</h2>

You wrote a random player, now I want you to a winning player function called winning_play. You are going to pit winning_play against random_play (your old random player) and see who wins. The outcome should be obvious.




Rather than explain how to win, I would like you to look online and see if you can find a winning strategy. As a start, check out Elwyn Berlekamp’s (he wrote a book on dots-andboxes, no lie) youtube video <u>https://www.youtube.com/watch?v=KboGyIilP6k</u> He lists some good strategies there. You can also find more such info.




Do as much as you can to create a winning player. You may not have time to “solve” the game but you should be able to do <strong><em><u>very well</u></em></strong> against a random player.

<strong> </strong>

<h2>Main Program</h2>

You are going pit winning_play against random_play to play dots-and-boxes.

Your main program will operate in two modes:

<ul>

 <li><u>single play</u>: there are two games here. o One with random_play first o One with winning_play</li>

</ul>

o Generate the two games in great detail in the file single_play.txt.

That exact name!

<ul>

 <li><u>multiple play</u>: play a lot of games, (flip a coin who goes first) and see who wins statistically.</li>

</ul>




<h2>More detail</h2>

<ul>

 <li>prompt for a random seed integer</li>

 <li>prompt for a number of rounds the multi-player (shown below) will play</li>

 <li>in multiple play “flip a coin” to see who goes first and report it</li>

 <li>your program will play two rounds using winning_play and random_play players and report each individual play, stored in a file called</li>

</ul>

“single_play.txt” to be created in the executable’s directory.

<ul>

 <li>For each turn:

  <ul>

   <li>draw the grid</li>

   <li>the score</li>

   <li>whose move it is</li>

   <li>what move was made</li>

   <li>was that a box just made, did they go again</li>

   <li>anything else that might be useful</li>

  </ul></li>

 <li>it then will play the provided number of rounds using a winning_play and a random_play players and report statistics of the results to a file called “multiple_play.txt”. The statistics to include are:

  <ul>

   <li>the number of rounds played o average score overall and for each player o the median score overall and for each player o the highest and lowest score achieved for each player o anything else you think might be a good idea</li>

  </ul></li>

</ul>




<h2>Deliverables</h2>

As before, I want just one code file named “honors2.cpp” with everything in it. Makes it easier to grade. Handin will be to project13 named honors2.




One additional thing. I want a text file (no more than a page) that describes the strategy you implemented and how I can tell that it is working. You might want to embed in the single_play.txt file some info about when you used the strategy so it is clear to me.




Text file name should be strategy.txt Exactly that name!




<h2>Notes</h2>

<ul>

 <li>your winning_play statistics should be awesome, though not necessarily a clean sweep.</li>

 <li>as before, you should be able to play thousands of games in multiple play to get some good stats.</li>

</ul>

o if it takes minutes to do that, you need to rethink it.






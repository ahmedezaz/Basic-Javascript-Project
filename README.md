# Basic-Javascript-Project
Golf.js
In the game of golf, each hole has a par, meaning, the average number of strokes a golfer is expected to make in order to sink the ball in the hole to complete the play. Depending on how far above or below par your strokes are, there is a different nickname.

Your function will be passed par and strokes arguments. Return the correct string according to this table which lists the strokes in order of priority; top (highest) to bottom (lowest):

Strokes	Return
1	"Hole-in-one!"
<= par - 2	"Eagle"
par - 1	"Birdie"
par	"Par"
par + 1	"Bogey"
par + 2	"Double Bogey"
>= par + 3	"Go Home!"
par and strokes will always be numeric and positive. We have added an array of all the names for your convenience.

OUTPUT EXAMPLE: golfScore(4, 1) should return the string Hole-in-one!

Passed
golfScore(4, 2) should return the string Eagle

Passed
golfScore(5, 2) should return the string Eagle

Passed
golfScore(4, 3) should return the string Birdie

Passed
golfScore(4, 4) should return the string Par

Passed
golfScore(1, 1) should return the string Hole-in-one!

Passed
golfScore(5, 5) should return the string Par

Passed
golfScore(4, 5) should return the string Bogey

Passed
golfScore(4, 6) should return the string Double Bogey

Passed


/* end golf.js */

/* counting cards */ 
Count Change	Cards
+1	2, 3, 4, 5, 6
0	7, 8, 9
-1	10, 'J', 'Q', 'K', 'A'

You will write a card counting function. It will receive a card parameter, which can be a number or a string, and increment or decrement the global count variable according to the card's value (see table). The function will then return a string with the current count and the string Bet if the count is positive, or Hold if the count is zero or negative. The current count and the player's decision (Bet or Hold) should be separated by a single space.

Example Output
-3 Hold
5 Bet

/* end counting cards */

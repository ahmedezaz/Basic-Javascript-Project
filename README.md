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

/* recordCard Algorithm */
You are given a JSON object representing a part of your musical album collection. Each album has a unique id number as its key and several other properties. Not all albums have complete information.

You start with an updateRecords function that takes an object like collection, an id, a prop (like artist or tracks), and a value. Complete the function using the rules below to modify the object passed to the function.

Your function must always return the entire object.
If prop isn't tracks and value isn't an empty string, update or set that album's prop to value.
If prop is tracks but the album doesn't have a tracks property, create an empty array and add value to it.
If prop is tracks and value isn't an empty string, add value to the end of the album's existing tracks array.
If value is an empty string, delete the given prop property from the album.
Note: A copy of the collection object is used for the tests.
Example:
After updateRecords(collection, 5439, "artist", "ABBA"), artist should be the string ABBA

Passed
After updateRecords(collection, 5439, "tracks", "Take a Chance on Me"), tracks should have the string Take a Chance on Me as the last element.

Passed
After updateRecords(collection, 2548, "artist", ""), artist should not be set

Passed
After updateRecords(collection, 1245, "tracks", "Addicted to Love"), tracks should have the string Addicted to Love as the last element.

Passed
After updateRecords(collection, 2468, "tracks", "Free"), tracks should have the string 1999 as the first element.

Passed
After updateRecords(collection, 2548, "tracks", ""), tracks should not be set

Passed
After updateRecords(collection, 1245, "albumTitle", "Riptide"), albumTitle should be the string Riptide

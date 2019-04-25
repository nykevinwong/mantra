(1) Algorithm Memorization Game
The game is to motivate the users get interested and involved to memorize algorithm for fun.

Give all lines of a given source code in a given programming language.
The play first enter whaterver he can remember in his chat textboox and press enter.
whatever first word/line/code matched in the source code will give a point and special effect.

Here's an example:

The example shows the code to remove one or more of the matched elements from the list.
The code iterates the list from the end to the start to avoid program from crash when removing an element.

for(int i=arr.length-1;i>0;i--)
   if(arr.get(i)==x) arr.remove(i);
   
Player can do below action and get corresponding feedback in the game.

Player Input Action | Feedback  | Result
--- | --- | ---
| send 'int' | matched the first 'int' word and reveal a hint showing it's a loop without condition and increment part. | user gets the point and show visual effect |
| send 'if(arr.get(i)==x) ' | matched the partial line | user gets the point and show visual effect |

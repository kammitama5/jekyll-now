## Little Puzzles with Haskell

## Tried reworking some of my CodeWars puzzles

<img src="/images/hasky1/h_003.png" width="500">
- This was one to repeat a string given a char and number of times it is to be repeated

<img src="/images/hasky1/h_003.png" width="500">

- This is one to make a number negative if it isn't or otherwise leave it

<img src="/images/hasky1/h_002.png" width="500">

- This was one to remove the head and last element of a list. In Python, you'd do this by slicing.
- In Haskell, I did this by using drop and take. Drop the 1st element lazily after the string is taken except the last element.

<img src="/images/hasky1/h_005.png" width="500">

- Check out this solution, though. Drop the first. Reverse, drop the first (which is the last) and then reverse again. Woah! Sick! 

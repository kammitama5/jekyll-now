## Long Weekend

- So we have a long weekend ahead.
  For many, it means a destination to Catalina Island,
  travelling some place or the other like SF or to visit 
  friends and family.
  
- For me, it's about trying to get some work done. 


## Almost there with implementation

- I'm taking a one-file-version of Tic-Tac-Toe in C++,
  and implementing it in OOP.
  
<img src="/images/Tic/tic_004.png" width="200">
  
- I'm *almost* there, except for a few bugs!
  I just did the bulk of this work today, and it's 
  not really due until the 26th, so..good start!
  
## Bugs!
  
- It accepts input only on the second time the board is drawn

<img src="/images/Tic/tic_001.png" width="500">

- It's only ending the game when it wins..not when board is full....
  (I may not actually have written that function!)
  
<img src="/images/Tic/tic_002.png" width="500">

- It tells you that the player has won, but doesn't ask you 
  if you want to quit or play again :(
  
<img src="/images/Tic/tic_003.png" width="500">

## Other stuff I hope to accomplish this weekend...

- The bulk of my work will be in Python for my nanodegree final project, as I don't really
  have a good solution for VS at home at the moment, unfortunately.
  So my VS time is limited.
  
  
## So the flood...

- JPL asked us to send a card to our cohorts (from our workshop) who are at 
  [JSC](https://www.nasa.gov/centers/johnson/home/index.html) (Johnson Space Centre). They're flooding! :( We have to include a note, and the year in which we did
  the workshop (in my case, it was Jan-April 2016. I hope to intern next year, too!
  
## And....

- That's about it for me. If I have time, I mayyy do some Mathematica, too.
- Also, read up on some Graph Theory or learn Emacs. But highly unlikely.
- Mostly just focusing on Python and finishing up my Nanodegree project, 
  and brushing back up on C++ for me, so the rest of the semester won't kill me.
  
## I heard about this really neat class I'd like to take...

- It's called 'Discrete Structures', and it's offered at my school.
  It's like Logic and Linear Algebra, but with programming. I'd love to take it,
  particularly if it is in C++. We'll see.
  
## I also got some neat slides...

- My mentor is teaching me PLT, and has taught compiler classes. He basically gave me
  two stacks of slides in C++, which he obtained when he took a workshop years ago 
  in, of all places, Detroit. 
  
## Things I learned about 

- [DFA](https://en.wikipedia.org/wiki/Deterministic_finite_automaton) (Deterministic Finite Automation)
- [Ramsey Numbers](http://mathworld.wolfram.com/RamseyNumber.html)
  
## Katas

- Return the index of the odd number in an array or -1 otherwise

```
function oddOne(arr) {
    var ans = -1
    for (var i = 0; i < arr.length; i++){
      if (arr[i] % 2 !== 0){
        ans = arr.indexOf(arr[i])
      }
      
    }
    return(ans)
}
```
- build a square with plus-es

eg 3 should be 
```
+++
+++
+++
```

- solution

```
// nested for-loop
function generateShape(int){
  g = []
  for (var i = 0; i < int; i++)
  {
    for (var j = 0; j < 1; j++){
      g.push(("+").repeat(int))
    }
  }
  g = g.join("\n")
  return g
}
```

- return opposite of array
  eg. ```[1,2,3,4] -> [-1,-2,-3,-4]```
  
```
function oppositeArray(numbers) {
  var arr = []
  for (var i = 0; i < numbers.length; i++){
    arr.push(0 - numbers[i])
  }
  return arr
}
```

- obtain the next perfect square (n * n).
  If the number is less than 0, return 0
  
```
def next_perfect_square(n):
    import math
    if n == 0:
      return 1 
    elif n < 0:
      return 0
    else:
      a = int(math.sqrt(n)) + 1
      b = pow(a, 2)
      return b
```


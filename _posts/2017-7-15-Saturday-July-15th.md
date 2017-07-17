## Spinnaker and a beautiful day of sailing!

- My my, this is quickly becoming a sailing and coding blog! 

- But they do intersect, don't they? Just a while ago I was talking about 
  Netflix's Spinnaker, and today I put one up! :)
  
- It was actually a Gennaker, but it was a wonderful day!

## We saw dolphins! 

- We sailed all the way to Malibu and back.

- We even saw this guy! 

<img src="/images/sea_001.png" width="300">

## I have to get up early in the morning...

- Got to get started on my labs. 
  If not, I'll do them in LA; I should have 
  access to them then, too. But I'd like to get
  them done this weekend
  
## In the meantime...

- Our beautiful Gennaker/ A-sail! 

<img src="/images/sea_002.png" width="300">

<img src="/images/sea_003.png" width="300">


## Katas

- Sum the strings

```
function sumStr(a,b) {
  if ((a  == null) || (b == null))
  {
    return "0"
  }
  else if ((a == "") && (b == "")){
    return "0"
  }
  else if ((a == null) || (a == "")){
    return b
  }
  else if ((b == null) || (b == "")){
    return a
  }
  else{
    return (parseInt(a) + parseInt(b)).toString();
  }
}
```

- take the derivative

```
function derive(coefficient,exponent) {
  var a = coefficient * exponent
  var b = exponent - 1
  return a.toString() + "x^" + b.toString();
}
```

- Sushi go-round

```
def total_bill(s):
    # 0 length return 0
    if len(s) == 0:
      return 0
    else:
      arr = []
      a1 = list(s)
      
      a1 = [x.strip(' ') for x in a1]
      a2 = ''.join(a1)
     
      a = len(a2) / 5
      b = len(a2) *  2
      c = b - a - a 
      return c
```
## Interesting...

- [Homomorphic Encryption for Arithmetic of Approximate Numbers](https://www.youtube.com/watch?v=brAXXghiqM0&feature=em-uploademail). He (and an audience member) mentions [Luhn encryption](http://www.investopedia.com/terms/l/luhn-algorithm.asp). Strangely, stumbled upon this in CodeWars two weeks ago. Basically, it's a weighted sum whose final value must be divisible by ten to be valid. Incredibly elegant. What if it were in a different number base?

- How have I heard of Cofree coalgebras before, but never of [Mongruences](http://blog.sigfpe.com/2006/04/mongruences.html)?
  Something something tau-invariant. Must find out more...
  
- This is a neat blog, too! It's called the [n-Category Cafe](https://golem.ph.utexas.edu/category/2009/09/proof_by_coinduction.html)

- Apparently, there are a lot of [invariants](https://en.wikipedia.org/wiki/Quantum_invariant), particularly with respect to knot   theory, which is a part of topology. And..we're back to hyperbolic geometry. I wonder why everything I've been reading about lately seems to go back to that...

- [Cyclotomic fields](https://en.wikipedia.org/wiki/Cyclotomic_field) - related to number theory, Euler and Galois Theory.

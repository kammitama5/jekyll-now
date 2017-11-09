## Long Time no See...and LambdaConf 2018!

## Hey everyone!

- Long time no see :)

- I've been working locally on some stuff.

## LambdaConf?

- Yes, yes, it's true! I'll be attending! 
- Apparently, unbeknownst to myself, I won a blog competition about 
  LambdaConf 2017, which scored me tickets to next year's LambdaConf!
  I cannot tell you how truly thankful I am for this opportunity!
  I hope one day I'll be in the position to help others! The community 
  is just *really* supportive of me, and I feel really grateful!
  
## Confession

- I've been sort of out of sorts. I've been taking a break and my good
  friend and I aren't on speaking terms, which is sort of a bummer.
  I'm hoping he'll come around. I do miss talking with him, and I really 
  was looking forward to meeting his dogs! (okay, maybe 80 percent was
  about meeting the dogs haha).
- It's really difficult for me in general to be close to anyone, and twice
  this year I've been burned, so it's sort of emotionally taken a toll on me.
  Programmers are definitely a unique bunch, and very much have a particular 
  introversion. With introversion, there is often a lot of misunderstanding.
  So, like any good programmer-in-training,
  I've been a little rant-y on Twitter lol. ¯\_(ツ)_/¯
  
- I'm definitely one to bounce back, though!

## Tomorrow...Haskell!

- I'll be going to a [Haskell talk](https://www.meetup.com/haskellhackers/events/244525354/) on Facebook's GHC Haxl Linker system!
- I'm excited to catch up with friends!
- Oh, and the following day, when I get back, I have an interview for an internship! :)
- Phil also scheduled the next [PureScript meetup](https://www.meetup.com/LA-PureScript/events/244935247/). I'll be in Maryland at the [John Hopkins Applied Physics lab](https://en.wikipedia.org/wiki/Applied_Physics_Laboratory),
  for a [Flight Software Workshop](http://flightsoftware.jhuapl.edu/) on autonomous spacecraft, so I won't be able to make it physically,
  but I'll *definitely* be there for the livestream!

## Final Project

- We have to do a final project in C++.
  People chose stuff like a refrigerator reminder,
  or something that keeps a tally of inventory for a store.
  I'm making a game and teaching myself [SFML](https://www.sfml-dev.org/).
  
## Sprite Sheets

- So far, I've made these using [Piskel](https://www.piskelapp.com/).

<img src="/images/upp/up_001.png" width="300">

<img src="/images/upp/up_002.png" width="200">

## UML

- To stay on track, I've also made myself weekly notifications 
  in my calendar as to what I'll accomplish each week. 
  This week, it's mainly completing the Sprite sheet and loading
  them in the game, along with the background. 
  
- I've also created a UML with a basic structure 

<img src="/images/upp/up_003.png" width="400">

## Google/ Udacity Developer Challenge

- I've started this today, and am going through the first
  lessons! 
  
- What is quite enjoyable is also seeing in a video Nick,
  who has been such a wonderful, supportive ally throughout 
  my journey. I can't thank the community enough!
  
- I'm actually thinking of (don't tell him! lol) of also sending 
  a little care package at some point to my online mentor, Christian,
  who was really supportive of me when I was doing my Nanodegree.
  He lives in Germany!
  
## Things to do/ upcoming

- So um..that daily Hackerrank will have to wait. 
  I'm not sure I can do this *every* day. Maybe once a week is more realistic,
  given all the updates.
- Chug along with the game (week one expectations/ plans)
- Go to class tonight! :)
- Continue with Nanodegree
- Attend Haskell Talk in Sunnyvale! 
- Do your best at your interview :)

## Katas

- sum of square diff -> sum digits

```
  function sumOfDiff(n) {
    var sum = 0;
    var sum1 = 0;
    for (var i = 0; i <= n; i++)
    {
      sum = sum + (i * i)
      sum1 = sum1 + i
    }
    var total = (sum1 * sum1) - sum
    var string1 = total.toString()
    var string2 = string1.split("")
    var arr = [];
    var finalsum = 0;
    for (var j = 0; j <= string2.length-1; j++)
    {
      var square =  parseInt(string2[j]) * parseInt(string2[j])
      finalsum = finalsum + square
    }
    return finalsum
}
```





## Mini-Exam

- I have a mini-exam today.

## Katas

I solved two.

- The first is: 
  Detect if a string starts with "Can you Explain"
  (case-sensitive)
  
```
function detect(comment)
{
  var word = comment.split(" ");
  if ((word[0] == "Can") && (word[1] == "someone") && (word[2] == "explain"))
  {
    return(true);
  }
  else
  {
    return(false);
  }
  
}

```

2 * x + another_value = total_value.
Find x.

```
function twiceOfANumber(added_value, total_value) {
  if ((added_value == 1) && (total_value == 2)){
    return 0.5;
  } 
  else if ((added_value == false) || (total_value == false)){
    return null;
  }
  else if ((added_value == true) || (total_value == true)){
    return null;
  }
  
  else{
    var x = (total_value - (added_value)) / 2.0;
    return x;
  }
  
}
```

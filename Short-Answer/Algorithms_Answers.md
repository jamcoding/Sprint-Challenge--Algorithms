#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n log n)


c) O(n)

## Exercise II

* Binary search tree
* Find the middle floor of "nth" floor to be the current floor
* Drop the egg from 1 minus the current floor number
* If egg breaks

```
top floor is now the current floor - 1

get the middle floor between the top floor and ground floor
```

* if the egg doesn't break
```
Drop egg from a floor one higher than current floor

if it breaks, return the floor egg was dropped from (current floor + 1)

otherwise, get the middle between the current floor and top floor
```

* Runtime -- O(log n)

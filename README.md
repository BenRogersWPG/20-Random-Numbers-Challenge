# 20 Random Numbers Challenge
## Simulate multiple runs of the 20 random numbers game

# The Challenge

1. List numbers 1-20, this will be used as the place spots
2. Run the random number generator (between 1-1000) and place the number where you think it would be best positioned in the list _(for example, if you roll 501, it would be best to place in spot 10)_
3. Keep rolling, and keep placing the numbers in new spots.
4. The challenge is to strategically fill all 20 spots without running into a situation where a number cannot be placed.

## Rules
1. A number can only be placed in a spot if it is greater than the number in the previous spot and less than the number in the next spot (if those spots are occupied).
2. If you can no longer place a number in a spot, then you lose.
3. For example, if you have 301 in spot 7, 330 in spot 8, and roll 316 then you lose, as you can't place it.

## How To Win

* **Win Condition:** The game is successfully completed if all 20 spots are filled in order.
* **Lose Condition:** The game ends in failure if a generated number cannot be placed due to the rules.

# The Code
## The code will simulate a single run, such as below:

```
Placed number 109 in spot #3
Placed number 987 in spot #19
Placed number 865 in spot #17
Placed number 872 in spot #15
Placed number 585 in spot #12
Placed number 515 in spot #10
Placed number 205 in spot #4
Placed number 652 in spot #13
Placed number 41 in spot #1
Placed number 970 in spot #18
Placed number 43 in spot #2
Placed number 561 in spot #11
Placed number 762 in spot #14
Placed number 115 in spot #6
Placed number 48 in spot #8
Placed number 318 in spot #9
Failed to place number 587. No suitable spot available.

Final spots:
Spot #1: 41
Spot #2: 43
Spot #3: 109
Spot #4: 205
Spot #5: Empty
Spot #6: 115
Spot #7: Empty
Spot #8: 48
Spot #9: 318
Spot #10: 515
Spot #11: 561
Spot #12: 585
Spot #13: 652
Spot #14: 762
Spot #15: 872
Spot #16: Empty
Spot #17: 865
Spot #18: 970
Spot #19: 987
Spot #20: Empty

```

## The code can also simulate multiple runs, such as below:
```
Passed 0 times
Failed 13300 times

20 numbers entered - 0
19 numbers entered - 6
18 numbers entered - 75
17 numbers entered - 561
16 numbers entered - 2326
15 numbers entered - 4227
14 numbers entered - 4000
13 numbers entered - 1734
12 numbers entered - 355
11 numbers entered - 15
10 numbers entered - 1
9 numbers entered - 0
8 numbers entered - 0
7 numbers entered - 0
6 numbers entered - 0
5 numbers entered - 0
4 numbers entered - 0
3 numbers entered - 0
2 numbers entered - 0
1 numbers entered - 0
```
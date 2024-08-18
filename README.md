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
Passed 0 times
Failed 13300 times
1 numbers entered - 721
2 numbers entered - 1314
3 numbers entered - 1731
4 numbers entered - 1939
5 numbers entered - 1893
6 numbers entered - 1573
7 numbers entered - 1376
8 numbers entered - 1023
9 numbers entered - 714
10 numbers entered - 474
11 numbers entered - 270
12 numbers entered - 158
13 numbers entered - 66
14 numbers entered - 27
15 numbers entered - 13
16 numbers entered - 7
17 numbers entered - 1


```

## The code can also simulate multiple runs, such as below:
```
Passed 0 times
Failed 13300 times
1 numbers entered - 721
2 numbers entered - 1314
3 numbers entered - 1731
4 numbers entered - 1939
5 numbers entered - 1893
6 numbers entered - 1573
7 numbers entered - 1376
8 numbers entered - 1023
9 numbers entered - 714
10 numbers entered - 474
11 numbers entered - 270
12 numbers entered - 158
13 numbers entered - 66
14 numbers entered - 27
15 numbers entered - 13
16 numbers entered - 7
17 numbers entered - 1

```
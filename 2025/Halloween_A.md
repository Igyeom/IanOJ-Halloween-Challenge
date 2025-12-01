# A. Blackjack
Time limit: **1** second\
Points: <b style="color: limegreen;">100</b>

## Problem Statement
Blackjack is a popular card game where the goal is to maximize your "score", without it exceeding 21. Given a string $S$, where each of its characters represent the cards a player was dealt, output the score of the player using the following rules for each card:
- The score is initially set to zero.
- If the card is a digit between `2` and `9` (inclusive), add the value of the digit to the score.
- If the card is `T`, `J`, `Q` or `K`, add 10 to the score.
- If the card is `A`, add 11 to the score if the final score after scoring all cards will not exceed 21, otherwise add 1.

## Input
The input consists of a single line containing a string $S$, the length of which does not exceed $10$.

## Output
On the first line, output a single integer: the score for the set of cards given in $S$.

## Sample Cases
### Sample Input 1
```
Q6
```
### Sample Output 1
```
16
```

### Sample Input 2
```
JA
```
### Sample Output 2
```
21
```

### Sample Input 3
```
AA
```
### Sample Output 3
```
12
```

### Sample Input 4
```
5K7
```
### Sample Output 4
```
22
```

<a style="font-size: 16pt;" href="https://ianoj.com/problem/104">Submit</a>

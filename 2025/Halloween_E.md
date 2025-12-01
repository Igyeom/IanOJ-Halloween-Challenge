# E. 1, 2, 👏, 4, 5, 👏, 7, 8, 👏, 10, 11, 12, 👏, 14, 15, 👏, ...
Time limit: **1** second\
Points: <b style="color: limegreen;">525</b>

## Problem Statement
This problem is about a popular Korean game called 369. Players take turns saying one number at a time, and the aim is to reach the highest number possible under the following rules:
- If the number contains either $3$, $6$ or $9$ as one of its digits, clap once **for every occurrence**.
- Otherwise, don't clap and simply state the number.

For instance, no claps are given for $4$, but $13$ would result in one clap, and $319$ would result in two claps. How many claps occur when the game is played correctly for all positive integers between $1$ and $N$ (inclusive)?

## Input
The input consists of a single line containing an integer $N$.

$1 \le N \le 10^{18}$

## Output
On the first line, output the number of claps that result from the procedure described in the problem statement.

## Sample Cases
### Sample Input 1
```
40
```
### Sample Output 1
```
22
```

### Sample Input 2
```
520169
```

### Sample Output 2
```
874101
```

### Sample Input 3
```
720485904768
```

### Sample Output 3
```
2571259560028
```


<a style="font-size: 16pt;" href="/submit/E">Submit</a>
<span style="font-size: 16pt;">|</span>
<a style="font-size: 16pt;" href="/problemset">Back</a>
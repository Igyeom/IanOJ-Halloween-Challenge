# C. Buried Treasure
Time limit: **1** second\
Points: <b style="color: limegreen;">300</b>

## Problem Statement
Alice has buried a treasure chest on a two-dimensional coordinate grid, on a point $(x, y)$ such that $x$ and $y$ are both integers.

You are given two coordinates: $(a_1, b_1)$ and $(a_2, b_2)$, as well as two bearings $\theta_1$ and $\theta_2$, in degrees, where $000\degree$ indicates the positive direction on the $y$-axis. All bearings used are guaranteed to be exact.

It is guaranteed that if someone starts walking on the bearing $\theta_i$ from the coordinates $(a_i, b_i)$, they will always eventually pass the buried treasure, for integers $1 \le i \le 2$.

Output the coordinates of the buried treasure. It is guaranteed that there is exactly one solution for all test cases.

## Input
The first line contains three space-separated integers: $a_1$, $b_1$ and $\theta_1$. \
The second line contains three space-separated integers: $a_2$, $b_2$ and $\theta_2$.

$-10^9 \le a_1, b_1, a_2, b_2 \le 10^9$ \
$000 \le \theta_1, \theta_2 < 360$

## Output
On the first line, output two space-separated integers: the $x$-coordinate and the $y$-coordinate of the treasure, in that order.

## Sample Cases
### Sample Input 1
```text
-1 0 45
4 1 315
```
### Sample Output 1
```text
2 3
```

### Sample Input 2
```text
-332 -250 270
-335 -237 225
```

### Sample Output 2
```text
-348 -250
```

### Sample Input 3
```texttext
575 -5 45
606 56 180
```

### Sample Output 3
```
606 26
```

<a style="font-size: 16pt;" href="/submit/C">Submit</a>
<span style="font-size: 16pt;">|</span>
<a style="font-size: 16pt;" href="/problemset">Back</a>
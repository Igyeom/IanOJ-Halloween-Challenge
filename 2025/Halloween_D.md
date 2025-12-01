# D. Composite Function
Time limit: **1** second\
Points: <b style="color: limegreen;">450</b>

## Problem Statement
You are given two integers $N$ and $K$, as well as a polynomial $f(x)$ with degree $D$ and integer coefficients.

Compute the coefficient of $x^K$ in $\underbrace{(f \circ f \circ f \circ \cdots \circ f \circ f)}_{\text{N nested functions}}(x)$, giving your answer modulo $998244353$.

## Input
The first line contains three space-separated integers: $N$, $D$ and $K$.
The second line contains $D+1$ space-separated integers, representing the coefficients of the polynomial $f(x)$ in descending order of degree.

$1 \le N, D \le 50$ \
$1 \le K \le 10$

## Output
On the first line, output the answer described in the problem statement.

## Sample Cases
### Sample Input 1
```
2 2 3
1 4 9
```

### Sample Output 1
```
8
```

### Sample Input 2
```text
50 3 3
1 2 3 4
```

### Sample Output 2
```text
334018807
```

### Sample Input 3
```text
35 27 7
928399835 737973316 95921678 632849462 193856389 715157806 187205081 969324325 416539545 493744781 672144820 103843684 363852930 890140391 843647850 730706731 18278767 982301989 596269396 918592444 582951579 394849722 290246415 743118019 959224218 131786291 690703304 659767148
```

### Sample Output 3
```text
869107886
```

<a style="font-size: 16pt;" href="/submit/D">Submit</a>
<span style="font-size: 16pt;">|</span>
<a style="font-size: 16pt;" href="/problemset">Back</a>
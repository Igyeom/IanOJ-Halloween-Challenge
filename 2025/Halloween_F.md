# F. Fizz Buzz with Words
Time limit: **1** second\
Points: <b style="color: limegreen;">625</b>

## Problem Statement
Given a positive integer $N$, find the number of occurrences of each of the 26 letters of the alphabet when playing Fizz Buzz with all integers $x$ within the range $1$ to $N$ (inclusive), using the following rules:
- If $x$ is divisible by both 3 and 5, write down `fizzbuzz`.
- If $x$ is divisible by 3 only, write down `fizz`.
- If $x$ is divisible by 5 only, write down `buzz`.
- If none of the above conditions are met, write down $x$ **in words**.

To prevent ambiguity, the use of the word `and` as a separator should not be considered (e.g. `103` is not `one hundred and three`). Hence, some examples for larger numbers include:
- `103` becomes `one hundred three` using this ruleset.
- `5068` becomes `five thousand sixty eight` using this ruleset.
- `6749` becomes `six thousand seven hundred forty nine` using this ruleset.
- `749449` becomes `seven hundred forty nine thousand four hundred forty nine` using this ruleset.
- `749450` becomes `buzz` using this ruleset.
- `348744621833095001` becomes `three hundred forty eight quadrillion seven hundred forty four trillion six hundred twenty one billion eight hundred thirty three million ninety five thousand one` using this ruleset.

If $N = 15$, your program should count occurrences of each letter in the following string:
```text
one
two
fizz
four
buzz
fizz
seven
eight
fizz
buzz
eleven
fizz
thirteen
fourteen
fizzbuzz
```

## Input
The input consists of a single line containing an integer $N$.

$1 \le N \le 10^{18}$

## Output
On the first line, output 26 space-separated integers: the number of times each letter from  `a` to `z` appears when writing down all outputs from $1$ to $N$ according to the rules described in the problem statement.

## Sample Cases
### Sample Input 1
```
15
```
### Sample Output 1
```text
0 3 0 0 11 7 1 2 7 0 0 1 0 5 4 0 0 3 1 5 5 2 1 0 0 16
```

### Sample Input 2
```
252720
```
### Sample Output 2
```text
134251 50544 0 539735 764215 237008 67764 477908 372770 0 0 6570 0 690234 370553 0 0 349047 269847 582905 431213 99574 101652 67818 210602 269568
```

### Sample Input 3
```
498335635969957774
```

### Sample Output 3
```
530758899362104294 365180353844635701 0 3347590392722905204 4983145575430878439 1275440951981337676 458271851860362109 2644182940152545714 4265366992153808865 0 0 2156810813240699279 265513226844777480 4747088083211453613 2510048180509777637 0 265245672517310814 2962228845547713133 1182765604720185434 3238997775862535530 2390359945212066599 744418754568041782 512018771881723888 458626198532340190 1275554823590269381 531558011701288290
```

<a style="font-size: 16pt;" href="/submit/F">Submit</a>
<span style="font-size: 16pt;">|</span>
<a style="font-size: 16pt;" href="/problemset">Back</a>

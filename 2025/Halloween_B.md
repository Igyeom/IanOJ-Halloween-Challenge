# B. Cave Johnson and Lemons
Time limit: **1** second\
Points: <b style="color: limegreen;">200</b>

## Problem Statement
_"When life gives you lemons, don't make lemonade - make life take the lemons back!"_

Cave Johnson hates lemons. Black Mesa can send $N$ boxes of lemons to Cave, and each box can contain either $0$, $1$, $2$, or $3$ lemons, and the number of lemons in each box is represented by the array of integers $A_i$.

The hidden message that should be decrypted by Cave Johnson (assuming he can refrain from going insane within the next few seconds) depends on the number of lemons contained in each box.

To decrypt the message, start with an empty binary string.

- If the box is empty, Cave should append a bit `0` to the back of the string.
- If the box contains $1$ lemon, Cave should append a bit `1` to the back of the string.
- If the box contains $2$ lemons, Cave should flip every bit in the binary string. (more precisely, `0` is replaced with `1`, and `1` is replaced with `0`)
- If the box contains $3$ lemons, Cave should append the [ASCII](https://en.wikipedia.org/wiki/ASCII) character corresponding to the current binary string to the final message, and clear the string to an empty state. If there aren't enough bits to form a valid character, you may pad the front of the string with zeros. (e.g. `1110` -> `0001110`)

What is the final message that results from this process? All characters in the message are guaranteed to be printable to the standard output stream. Note that there are no new-line characters in the resulting message.

## Input
The first line contains an integer $N$. \
The second line contains $N$ space-separated integers $A_i$, representing the number of lemons in each box.

$1 \le N \le 1{,}000$ \
$0 \le A_i \le 3$

## Output
On the first line, output the message that is obtained from the procedure described in the problem statement.

## Sample Cases
### Sample Input 1
```
9
0 1 0 1 1 0 0 1 3
```

### Sample Output 1
```text
Y
```

### Sample Input 2
```
28
0 1 0 1 0 0 0 1 3 2 0 1 0 0 1 0 1 1 3 0 1 0 1 0 1 0 1 3
```

### Sample Output 2
```
QKU
```

### Sample Input 3
```
36
0 1 0 0 0 0 1 1 3 0 1 0 0 0 0 0 1 3 0 1 0 1 0 1 1 0 3 0 1 0 0 0 1 0 1 3
```
### Sample Output 3
```text
CAVE
```

<a style="font-size: 16pt;" href="https://ianoj.com/problem/105">Submit</a>

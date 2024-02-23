## 1.2 Binomial Coefficients
### Subsets

Taking the set $A=\{1,2,3,4,5\}$, we can find how many subsets of $A$ in total there are by iterating over each and making a "yes" or "no" choice to add it to a subset.

Using the **multiplicative principle**, we can do $2\cdot 2\cdot 2\cdot 2\cdot 2 = 2^5$ to get the total amount of possible subsets.

But what if we wanted to find how many subsets have three elements?

First let it be known that $\{x,y,z\} = \{z,y,x\}$. Because there are $5$ elements in the set, the first element in our subset has $5$ different possibilities, the second element has $4$, and the last has $3$.  using the **multiplicative principle**, we see that $5\cdot 4\cdot 3 = 60$, giving us $60$ different $3$ element-length subsets.  However $60$ is not the answer as $60 > 32$. $(32$ is the maximum possible numbers of subsets$)$.  There are $6$ different outcomes for each set of three elements, $(3\cdot 2\cdot 1 = 6)$, so we do $(60\div6 = 10)$ for the final answer.

|Number of elements:|0|1|2|3|4|5|
|-|-|-|-|-|-|-|
|Number of Subsets:|1|5|10|10|5|1|

---

### Bit Strings

A bit string is a string of binary digits.  The ***length*** of a bit string is the number of bits in the string.  The number of $1$'s in a bit string is it's ***weight***.

$\bold{B} ^n$ is the *set* of all $n$-bit strings.
$\bold{B}^n_k$ is the *set* of all $n$-bit strings of weight $k$.

$\bold{B}^3_2 = 011, 101, 110$.

The number of $5$-bit strings is equal to $2^5$, finding $|\bold{B}^5_3|$ is harder, we can use ***recurrence relation***:

$|\bold{B}^5_3| = |\bold{B}^4_2| + |\bold{B}^4_3|$, then

$|\bold{B}^4_2| = |\bold{B}^3_1| + |\bold{B}^3_2|$	and $|\bold{B}^4_3| = |\bold{B}^3_2| + |\bold{B}^3_3|$ 

$|\bold{B}^4_2| = 3 + 3$
$|\bold{B}^4_2| = 6$

$|\bold{B}^4_3| = 3 + 1$
$|\bold{B}^4_3| = 4$

$|\bold{B}^5_3| = 6 + 4$
$|\bold{B}^5_3| = 10$

A bit string can be thought of as a *code* for a subset.  Where a $1$ indicates an element is in a subset, and a $0$ indicates the element is not.

$A=\{1,2,3,4,5\}$

$11001 = \{1,2,5\}$
$00101 = \{3,5\}$

$\bold{B}^x_3$ is a set or subset that contains 3 elements.

---
### Lattice Paths
Consider a ***lattice path***, one of the shortest possible paths connecting two points on a grid.

from $(0,0)$ to $(3,2)$ there will always be $5$ steps, and each step will always be a step to the right or a step up.  For example, a valid path could be RRUUR, (R = right, U = up).  If we give R's a value of $1$, and U's a value of $0$. 

There would be $|\bold{B}^5_3|$, so $10$ paths in total.

---
### Binomial Coefficients
a ***Binomial Coefficient*** is an expanded version of a binomial.

$(x+y)^4 = x^4 + 4x^3y+6x^2y^2+4xy^3+y^4$.

There's a pattern when FOIL-ing large exponents:

$(x+y)^5=x^5+5x^4y+(?)x^3y^2+(?)x^2y^3+5xy^4+y^5$.

Notice how the equation starts with $x^5+5x^4y$ and ends with $5xy^4+y^5$

the terms start with $x^5$ then go to $x^4y$, $x^3y^2$, etc. $-x^1+y^1$ until we get back to $y^5$.  The $2$nd and last -$1$ term of any FOIL-ed expression like this is always the exponent as well, $x^5 + \bold{5x^4y}$, $\bold{5xy^4}+y^5$

The $(?)$ from earlier are equal to $|\bold{B}^5_3| = 10$, as we have $5$ things and each can be one of $2$ things, with a total of $3$ things.

$(^n_k) = |\bold{B}^n_k|$

$(^n_k) = (^{n-1}_{k-1}) + (^{n-1}_k)$.
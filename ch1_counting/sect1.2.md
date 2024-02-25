## Binomial Coefficient Excercises

#### Let $S = \{1,2,3,4,5,6\}$ 
- How many subsets are there total?
	- There are $2^6$, or $64$ total subsets.
	
- How many subsets have $\{2,3,5\}$ as a subset?
	- There are $2^3$ subsets (yes / no for the elements that are not $2$, $3$, or $5$).
	
- How many subsets contain at least one odd number?
	- The total amount of subsets $(2^6)$ minus the amount of subsets with only even numbers $(2^3) = 56$.
	
- How many subsets contain exactly one even number?
	- number of even numbers (3), and the rest of the numbers are yes or no's, $3\cdot 2^3 = 24$.
---
#### Let $S = \{1,2,3,4,5,6\}$
- How many subsets are there of cardinality 4?
$$|\bold{B}^6_4| = |\bold{B}^5_3| + |\bold{B}^5_4|$$
$$|\bold{B}^5_3|=|\bold{B}^4_2|+|\bold{B}^4_3|$$
$$|\bold{B}^5_4| = |\bold{B}^4_3| + |\bold{B}^4_4|$$
$|\bold{B}^5_4| = 4+ 1$ , $|\bold{B}^5_3| = 6 + 4$ , $|\bold{B}^6_4| = 5 + 10 = 15$

- How many subsets of cardinality $4$ have $\{2,3,5\}$ as a subset?
	- $3$, we already have three of the elements of each subset, so we just need another, which is one of the three not already in these subsets.
- How many subsets of cardinality $4$ contain at least one odd number?
	- There are only $3$ even numbers in the full set, so each subset must have at least one odd number.
- How many subsets of cardinality $4$ contain exactly one even number?
	- $3$ subsets, one for each even number in the original set.
---
#### Let $A = \{1,2,3,\dots,9\}$.
- How many subsets of $A$ are there? That is, find $|P(A)|$.  Explain.
	- There are $2^9 = 512$ subsets, each element is either a yes or no (two states), and we multiply them all together.
	
- How many subsets of $A$ contain exactly $5$ elements? Explain.
	- Using Pascal's Triangle, we see that $(^9_5) = 126$

---

#### How many $9$-bit strings (that is, bit strings of length $9$) are there which:
- Start with the sub-string $101$? Explain.
	- $2^6 = 64$, we know the first three elements, so we do yes / no for the last $6$.
- Have weight $5$ and start with the sub-string $101$?
	- $(^6_3) = 20$, after $101$ we have $6$ possible places to put $3$ $1$'s.
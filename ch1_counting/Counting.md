### The Additive Principle
The additive principle says that if event $A$ can happen $m$ different ways, and event $B$ can occur in $n$ disjoint ways (meaning $A$ and $B$ cannot happen at the same time), then the event "$A$ or $B$" can occur in $m + n$ ways.

This principle also works when there are more than two disjointed events.
if $A \cap B = \empty$ 
(meaning there is no common element in both $A$ and $B$)
$|A\cup B | = |A| + |B|$

### The Multiplicative Principle

if the state of event $A$ (which has $m$ different states) does not influence the state of event $B$ (which has $n$ different states), then the event "$A$ and $B$" can occur $m\times n$ different ways.

Similar to the additive principle, this works for more than two events.

#### Cartesian Product

$A\times B = \{(x,y): x \in A \land y \in B\}$

This is the set of all ordered pairs for $(x,y)$ or $(A,B)$

$A\times B$ is called the Cartesian product of $A$ and $B$.

#### What does this mean?

$|A\times B| = |A| \cdot |B|$.

This can be extended as well.

### Principle of Inclusion/Exclusion

For any finite sets $A$ and $B$,
$|A \cup B| = |A| + |B| - |A \cap B|$.

For any finite sets $A$, $B$, and $C$,
$|A\cup B\cup C| = |A| + |B| + |C| - |A\cap B| - |A\cap C| - |B\cap C| + |A\cap B\cap C|$

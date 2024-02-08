
# Atomic and Molecular Statements
## by Parker Borek
---
## Logical Connectives
* simple statements can be combined into more complex ones using logical connectives.
    * Telephone numbers in the USA have 10 digits and 42 is a perfect square.

This sentence combines the statements "Telephone numbers in the USA have 10 digits" and "42 is a perfect square."

|        |P⋀Q        |P⋁Q        |P→Q|P↔Q|¬P|
|-       |-          |-          |-|-|-|
|read |P and Q    |P or Q     |if P then Q|P if and only if Q|not P|
|called|conjunction|disjunction|implication or conditional|biconditional|negation|

||P⋀Q|P⋁Q|P→Q|P↔Q|¬P|
|-|-|-|-|-|-|
|P is true, Q is true|true|true|true|true|false|
|P is true, Q is false|false|true|false|false|false|
|P is false, Q is true|false|true|true|false|true|
|P is false, Q is false|false|false|true|true|true|

## Exercises

|        |P⋀Q        |P⋁Q        |P→Q|P↔Q|¬P|
|-       |-          |-          |-|-|-|
|read |P and Q    |P or Q     |if P then Q|P if and only if Q|not P|
|called|conjunction|disjunction|implication or conditional|biconditional|negation|

1. Suppose P and Q are the statements: 
	- P: Jack passed math.
	
	- Q: Jill passed math.
		- Translate "Jack and Jill both passed math" to symbols.<sub>1</sub>
		
		- Translate "If Jack passed math, then Jill did not" to symbols.<sub>2</sub>
		- Translate "P⋁Q" to English.<sub>3</sub>
		- Translate "¬(P⋀Q)→Q" to English."<sub>4</sub>
		- Suppose you know that if Jack passed math, then so did Jill. What can you conclude if you know that:
			- Jill passed math?<sub>5</sub>
			
			- Jill did not pass math?<sub>6</sub>

## Bibliography

- [Wikipedia](https://en.wikipedia.org/wiki/Logical_conjunction)

- [Lander.edu](https://philosophy.lander.edu/logic/conjunct.html)

## Answers

 1. P⋀Q.

 2. P→¬Q.
 3. Jack passed math (inclusive or) Jill passed math.
 4. If Jack and Jill both did not pass math, then Jill did.
 5. Nothing more.
 6. Jack also did not pass.

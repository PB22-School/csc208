
## 1.1 Additive and Multiplicative Principles Exercises  
  
#### Your wardrobe consists of $5$ shirts, $3$ pairs of pants, and $17$ bow ties. How many different outfits can you make?  
  
- Using the **multiplicative principle**, the answer is $255$ because $5\cdot 3\cdot 17 = 255$.  
---  
#### For your college interview, you must wear a tie. You own $3$ regular (boring) ties and $5$ (cool) bow ties.  
a) how many choices do you have for neck-wear?  
- You have $8$ choices, $(3 + 5)$ (**additive principle**).  
  
b) You realize that the interview is for clown college, so you should probably wear both a regular tie and a bow tie. How many choices do you have now?  
- You'd have $15$ choices, $(3\cdot 5)$.  
  
c) For the rest of your outfit, you have 5 shirts, 4 skirts, 3 pants, and 7 dresses. You want to select either a shirt to wear with a skirt or pants, or just a dress. How many outfits do you have to choose from?  
- You can wear either a shirt with a either a skirt or a pair of pants (this is exclusive so we add skirts and pants) or a dress, so the equation is like this: $shirts\cdot(skirts+pants)+dresses=outfits$ or $5\cdot(4+3)+7=42$, so **42 outfits**.  
---  
#### Your Blu-ray collection consists of $9$ comedies and $7$ horror movies. Give an example of a question for which the answer is:  
a) $16$.  
- A question that has $16$ as an answer could be: "You want to watch a movie, how many choices do you have?" there are $16$ choices because $9+7=16$.  
  
b) $63$.  
- "You want to watch two movies from different genres, how many choices do you have?" would work here because $(9\cdot7) = 63$.  
---  
#### We usually write numbers in decimal form (or base $10$), meaning numbers are composed using $10$ different "digits" $\{0,1,\dots,9\}$. Sometimes though it is useful to write numbers in hexadecimal or base $16$. Now there are $16$ distinct digits that can be used to form numbers: $\{0,1,\dots,9,A,B,C,D,E,F\}$. So for example, a $3$ digit hexadecimal number might be $2B8$.  
a) How many $2$-digit hexadecimals are there in which the first digit is $E$ or $F$? Explain your answer in terms of the additive principle (using either events or sets).  
- If the first digit is an $E$, there are $16$ other digits the second digit could be. It's the same if the first digit is $F$, so the equation is $16+16=32$  
  
b) Explain why your answer to the previous part is correct in terms of the multiplicative principle (using either events or sets). Why do both the additive and multiplicative principles give you the same answer?  
- The multiplicative principle and additive principle gives you the same answer because $x+x=2x$ (where $x$ is just the number of values the second digit could have).  
  
c) How many $3$-digit hexadecimals start with a letter ($A$-$F$) and end with a numeral ($0$-$9$)? Explain.  
- $960$ as $(6\cdot 16\cdot 10 ) = 960$, the first digit of these hexadecimal numbers is any element from the set ($A$-$F$), the second digit is any element from the set ($0$-$F$), and the third digit is any element from the set ($0$-$9$), where the choice from any set does not impact any other set, so we use the **multiplicative principle**.  
  
d. How many $3$-digit hexadecimals start with a letter ($A$-$F$) or end with a numeral ($0$-$9$) (or both)? Explain.  
- The answer is $16^3$ or $4096$ because the statement allows every hexadecimal number with three digits.

---

#### Suppose you have sets $A$ and $B$ with $|A| = 10$ and $|B| = 15$.
a) What is the largest possible value for $|A\cap B|$?
- $10$, if all of the elements in $A$ are in $B$

b) What is the smallest possible value for $|A\cap B|$?
- $0$. if none of the elements in $A$ are in $B$.

c) What are the possible values for $|A\cup B|$?
- the answer is between $15$ and $25$, depending on how many elements $A$ and $B$ share.

---

#### If $|A| = 8$ and $|B| = 5$, what is $|A\cup B| + |A\cap B| = 13$?
- $|A\cup B| = 8$, and $|A\cap B| = 5$, then $8 + 5 =13$.

---

#### A group of college students were asked about their TV watching habits.  Of those surveyed, $28$ students watch *The Walking Dead*, $19$ watch *The Blacklist*, and $24$ watch _Game of Thrones_. Additionally, $16$ watch _The Walking Dead_ and _The Blacklist_, $14$ watch _The Walking Dead_ and _Game of Thrones_, and $10$ watch _The Blacklist_ and _Game of Thrones_. There are $8$ students who watch all three shows. How many students surveyed watched at least one of the shows?

- $(28 + 19 + 24) - (16 + 14 + 10) + 8 = 39$, add the singles and triples, and subtract the doubles.

---

#### In a recent survey, 30 students reported whether they liked their potatoes Mashed, French-fried, or Twice-baked. 15 liked them mashed, 20 liked French fries, and 9 liked twice baked potatoes. Additionally, 12 students liked both mashed and fried potatoes, 5 liked French fries and twice baked potatoes, 6 liked mashed and baked, and 3 liked all three styles. How many students _hate_ potatoes? Explain why your answer is correct.
- $(15 + 20 + 9) - (12 + 5 + 6) + 3 = 24$.  $24$ is the number of people who like potatoes, so we can do $30 - 24 = 6$ to get the number of people who don't like potatoes.
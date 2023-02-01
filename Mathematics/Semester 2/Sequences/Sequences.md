# Related
---
[[Arithmetic Sequences]]

# In-Class Lecture
---
A sequence is an ordered list.
Think of it as a function with a domain as the natural numbers in the sequence.
>[!info]+
>$t_{1}$, $t_{2}$, $t_{3}$ … $t_{n}$ is how the numbers are referred.
>$t = 2, 4, 6, 8, 10$
$t_{1} = 2$, $t_{2} = 4$, $t_{3} = 6$, $t_{4} = 8$, $t_{5} = 10$, etc.

>[!info]+
>Term number is the number in the subscript. e.g. ‘$1$’ in $t_{1}$

A sequence may be defined by listing the terms in order, by giving the rule a function, or by a recursive division.
>[!example]+
>$t = 2, 5, 8, 11$ | $t_{n}=t_{n-1}+3, t_{1}=2$
>$t_{5}=t_{4}+3$
>$t_{5}=11+3$
$t_{5}=14$

>[!example]+
>$a_{1}=6 | a_{n}=2a_{n-1}+1$
>
>$a_{2}=2*a_{1}+1=2*6+1=13$
>$a_{3}=2*a_{2}+1=2*13+1=27$
>$a_{4}=2*a_{3}+1=2*27+1=55$
$a_{5}=2*a_{4}+1=2*55+1=111$

>[!example]+
>$t_{n}=(-1)^{n}*3^{n}$
>$t_{1}=(-1)^{1}*3^{1}=-3$
>$t_{2}=(-1)^{2}*3^{2}=9$
>$t_{3}=(-1)^{3}*3^{3}=-27$
$t_{4}=(-1)^{4}*3^{4}=81$

>[!example]+
>$t_{n}=t_{n-1}+t_{n-2}$
>$t_{7}=42, t_{6}=68, t_{9}=110, t_{10}=178$
$t= 2, 4, 6, 10, 16, 26$

| $a_{1}$ | $a_{2}$ | $a_{3}$ | $a_4$ | $a_{5}$ |
| ------- | ------- | ------- | ----- | ------- |
| $25$    | $-26$   | $25$    | $15$  | $-14$   |
$a_{n}-a_{n+1}=2a_{n+1}$

# Textbook - 8.01 (pg380)
---
You have previously studied number patterns in mathematics. The mathematical name for a number pattern is a sequence. A simple sequence of numbers is 5, 10, 15, 20, 25, … The numbers in a sequence are called terms. In the sequence above, the first term ($t_{1}$) is 5, the second term ($t_{2}$) is 10 and so on. In this case, each term can be found by adding 5 to the previous one. The pattern of the sequence 1, 2, 3, 6, 11, 20, 37, 68, … is a little harder to find. After the first 3 terms, each term is the sum of the previous 3

>[!info]+ Hailstone sequences
>Sequences such as
>$5, 16, 8, 4, 2, 1, 4, 2, 1,...$
>and
>$11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1, 4, 2, 1$
>are known as **hailstone sequences** because they ‘bounce around’ like a hailstone when it hits the ground, before coming to rest. Hailstone sequences are generated as follows:
>1) Start with any positive integer $n$.
>2) If $n$ is even, divide by $2$ to give $n'=\frac{n}{2}$
>	1) If $n$ is odd, multiply it by 3 and add 1 to give $n'=3n+1$
>3) Take $n'$ as the new starting number and repeat the process.
>Try out different starting values and see how many terms are generated before the sequence eventaully settles to $4, 2, 1, 4, 2, 1,...$
>This is known as the Collatz conjecture, name after Lothar Collatz, who first proposed in 1937 that every starting point would eventaull reach 1. Today it is one of mathematics unsolved problems. Could there be a sequence that never settles down to this repeating cycle?
>
><div class="rich-link-card-container">
>	<a class="rich-link-card" href="https://www.youtube.com/watch?v=094y1Z2wpJg" target="_blank">
>		<div class="rich-link-image-container">
>			<div class="rich-link-image" style="background-image: url('https://i.ytimg.com/vi/094y1Z2wpJg/maxresdefault.jpg')">
>			</div>
>		</div>
>		<div class="rich-link-card-text">
>			<h1 class="rich-link-card-title">The Simplest Math Problem No One Can Solve - Collatz Conjecture</h1>
>			<p class="rich-link-card-description">
>			The Collatz Conjecture is the simplest math problem no one can solve — it is easy enough for almost anyone to understand but notoriously difficult to solve. ...
>			</p>
>			<p class="rich-link-href">https://www.youtube.com/watch?v=094y1Z2wpJg</p>
>		</div>
>	</a>
></div>



>[!IMPORTANT]+
>A sequence is an ordered list. In most cases, you can think of it as a function whose domain is the natural numbers. Each member of a sequence is called a term. The first term, second term, and nth term are often written as $t_{1}, t_{2}$ and $t_{n}$. The term number is written as a subscript to the term symbol. Terms are also often written as $a_{1}, a_{2}, a_{3},$ and so on.
>A sequence may be defined by listing the terms in order, by giving the rule as a function, or by a recursive definition.
>A recursive definition gives each term as a rule involving the previous term (or terms), except for the first term(s), which have to be specified.

# Ex. 8.01
---
Q1
a. $1, 2, 3, 4, 5$
c. $-3, 5, 2, 7, 9$
Q2
b. $7, 5, \frac{13}{3}, 4, \frac{19}{5}$
f. $2^{1}, 2^{3}, 2^{10}, 2^{41}$
Q3
a. $40$
b. $-16$
c. $27$
d. $55$
Q4
a. $1, 3, 5, 7, 9, 11, 13, 15, 17$
b. $23$
c. $2048$, pieces will **not** fit on the chessboard
Q5
a. $1, 2, 3, 4, 5, 6, 7$
b. $1, 3, 7, 15, 31, 63, 127$
c. $2^{10}-1=1023 (2^{n}-1)$
# Related
---
[[Geometric Sequences]]
[[Sum of Arithmetic Sequences (Arithmetic Series)]]

# In-Class Lecture
---
Sum of a finite geometric series
>[!important]+
>$S_{n}=t_{1}+t_{1}r+t_{1}r^{2}+t_{1}r^{3}+...+t_{1}r^{n-2}+t_{1}r^{n-1}$
>For a finite geometric series with $r \neq 1$
>$S_{n}=\frac{t_{1}(r^{2}-1)}{r-1}$ or $S_{n}=\frac{t_{1}(1-r^{n})}{1-r}$

>[!example]+
>Find the sum of $2+6+18+54+...$ to 12 terms
>The series is geometric with $t_{1}=2$, $r=3$, and $n=12$.
>$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$
>$S_{n}=\frac{2(3^{12}-1)}{3-1}=531440$

>[!example]+
>If the last term, $t_{n}$, is known, then the sum can be found as follows:
>	$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$ (for $r>1$)
>	$=\frac{t_{1}r^{n}-t_{1}}{r-1}$
>	$=\frac{t_{1}r^{n-1}\times r-t_{1}}{r-1}$
>	$=\frac{rt_{n}-t_{1}}{r-1}$

>[!important]+
>When the last term ($t_{n}$) in a geometic sequence is known then the sum of the series is
>$S_{n}=\frac{rt_{n}-t_{1}}{r-1}$ for $r>1$ or $S_{n}=\frac{t_{1}-rt_{n}}{1-r}$ for $r<1$.

>[!example]+ Example 19
>Evaluate the geometric sequence $1+3+9+...+19683$.
>$a=1$
>$r=3$
>$S_{n}=\frac{rt_{n}-t_{1}}{r-1}$
>$=\frac{3\times 19683-1}{3-1}$
>$=\frac{59048}{2}$
>$=29524$
>The sum of the series is $29524$

>[!example]+ Example 20
>If $2+4+...+t_{n}=2046$, how many terms are there in the sequence?
>$t_{1}=2$
>$r=2$
>$S_{n}=2046$
>$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$
>$2046=\frac{2(2^{n}-1)}{2-1}$
>$2046=2(2^{n}-1)$
>$1023=2^{n}-1$
>$2^{n}=1024$
>$n=10$
>Alternative method
>$S_{n}=\frac{rt_{n}-t_{1}}{r-1}$
>$2046=\frac{2\times t_{n}-2}{2-1}$
>$2t_{n}-2=2046$
>$2t_{n}=2048$
>$t_{n}=1024$
>$t_{1}r^{n-1}=1024$
>$2\times 2^{n-1}=1024$
>$2^{n}=1024$
>$n=10$
>There are 10 terms in the series.

>[!example]+ Example 21
>The common ratio of a geometric sereies is $4$ and the sum of the first $5$ terms is $3069$. Find the first term
>$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$
>$3069=\frac{t_{1}(4^{5}-1)}{4-1}$
>$t_{1}(4^{5}-1)=9207$
>$t_{1}=\frac{9207}{1023}$
>$t_{1}=9$
>The first term of the series is $9$.

# Textbook 08.07 (pg 403)
---
When the creator of the game of chess showed his invention to his country’s ruler, he was so impressed that he granted the clever inventor the right to claim any prize he desired. Being a smart man he decided upon the following as his prize: that for the first square of the chessboard, he would receive one grain of rice, two for the second one, four on the third one, and so forth, doubling the amount each time. The ruler unknowingly accepted his request and was not sure that it was a sufficient prize for such a creation. The ruler ordered the man be paid for his prize and after an extended period of time the ruler’s accountant indicated that there were not enough assets in the kingdom to meet the desired prize!

In fact, it is an amount many times more than the global production of rice.
To be able to count the number of grains of rice it is necessary to know how to sum a geometric series.
As is the case with an AP, a finite geometric series is the sum of the terms of a finite geometric sequence, so the series $t_{1}+t_{1}r+t_{1}r^{2}+t_{1}r^{3}+...+t_{1}r^{n-1}$ is the sum of the terms of the GP: $t_{1} t_{1}r, t_{1}r^{2}, t_{1}r^{3},...,t_{1}r^{n-1}$.
We first demonstrate the method with a numerical example
Let $S_{6}=3+6+12+24+48+96$
Adding the first and last terms does not give the same answer as adding the second and second last terms, etc. However, if you multiply each term by the common ratio $(r = 2)$, most of the terms reappear.
$2S_{6}=6+12+24+48+96+192$
Now subtract these two equations:
$2S_{6}-S_{6}=(6+12+24+48+96+192)-(3+6+12+24+48+96)$
$S_{6}=192-3$ (All but 2 terms cancel)
$S_{6}=189$

The general case works the same way
$S_{n}=t_{1}+t_{2}+t_{3}+...+t_{n-2}+t_{n-1}+t_{n}$
$S_{n}=t_{1}+t_{1}r+t_{1}r^{2}+...+t_{1}+r^{n-3}+t_{1}r^{n-2}+t_{1}r^{n-1}$ (1)
$rS_{n}=t_{1}r+t_{1}r^{2}+t_{1}r^{3}+...+t_{1}r^{n-2}+t_{1}r^{n-1}+t_{1}r^{n}$ (2)
$(2)-(1)$ gives
$rS_{n}-S_{n}=t_{1}r^{n}-t_{1}$
$S_{n}(r-1)=t_{1}(r^{n}-1)$
$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$ for $r\neq 1$
If the last term, $t_{n}$, is knwon, then the sum can be found as follows.
$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$ (for $r>1$)
$S_{n}=\frac{t_{1}r^{n}-t_{1}}{r-1}$
$S_{n}=\frac{t_{1}r^{n-1}\times r-t_{1}}{r-1}$
$S_{n}=\frac{rt_{n}-t_{1}}{r-1}$

>[!important]+
>The sum of the first $n$ terms of a geometric series is given by:
>$S_{n}=\frac{a(r^{n}-1)}{r-1}$ for $r>1$ or $S_{n}=\frac{a(1-r^n)}{1-r}$ for $r<1$.
>When the last term ($t_{n}$) in a geometric sequence is known then the sum of the series is
>$S_{n}=\frac{rt_{n}-t_{1}}{r-1}$ for $r>1$, or $S_{n}=\frac{t_{1}-rt_{n}}{1-r}$ for $r<1$.

Of course, the sums for $r>1$ and $r<1$ are algebraically the same. It is just convinient to avoid negatives.
You can work out the sum for the trivial case with $r=1$.

>[!example]+ Example 19
>Evaluate the geometric sequence $1+3+9+...+19683$.
>$a=1$
>$r=3$
>$S_{n}=\frac{rt_{n}-t_{1}}{r-1}$
>$=\frac{3\times 19683-1}{3-1}$
>$=\frac{59048}{2}$
>$=29524$
>The sum of the series is $29524$


>[!example]+ Example 20
>If $2+4+...+t_{n}=2046$, how many terms are there in the sequence?
>$t_{1}=2$
>$r=2$
>$S_{n}=2046$
>$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$
>$2046=\frac{2(2^{n}-1)}{2-1}$
>$2046=2(2^{n}-1)$
>$1023=2^{n}-1$
>$2^{n}=1024$
>$n=10$
>Alternative method
>$S_{n}=\frac{rt_{n}-t_{1}}{r-1}$
>$2046=\frac{2\times t_{n}-2}{2-1}$
>$2t_{n}-2=2046$
>$2t_{n}=2048$
>$t_{n}=1024$
>$t_{1}r^{n-1}=1024$
>$2\times 2^{n-1}=1024$
>$2^{n}=1024$
>$n=10$
>There are 10 terms in the series.

>[!example]+ Example 21
>The common ratio of a geometric sereies is $4$ and the sum of the first $5$ terms is $3069$. Find the first term
>$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$
>$3069=\frac{t_{1}(4^{5}-1)}{4-1}$
>$t_{1}(4^{5}-1)=9207$
>$t_{1}=\frac{9207}{1023}$
>$t_{1}=9$
>The first term of the series is $9$.


# Ex 08.07
---
1)
	a) $5465$
	b) $122.61$
	c) $32767$
	d) $510$
	e) $97656.20$
2) $8.628$
3) $85.792$
4) $3577$
6) $n=15$
8) $75$ or $-25$
9) $217$ or $-77$
12) $101\frac{1}{27}$ meters
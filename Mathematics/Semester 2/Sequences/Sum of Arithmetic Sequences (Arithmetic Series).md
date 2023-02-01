# Related
---
[[Semester 2/Sequences/Sequences]]
[[Arithmetic Sequences]]
# In-Class Lecture
---
> [!IMPORTANT]+ Formula
> The sum of a *finite* arithemtic sequence with the first term to difference $d$, and the last term $t_{n}$, then
> $S_{n}=\frac{n}{2}(2a+(n-1)d)$
> **OR**
> $S_{n}=\frac{n}{2}(2t_{1}+(n-1)d)$
> Some refer to the first term as $a$ and the last term may be known as $l$.

**Warmup**
1) What is the sum of 1 to 100?
	$S_{n}=\frac{n}{2}[2a+(n-1)d]$
	$S_{n}=\frac{10}{2}[2*1+(10-1)d]=55$
2) What is the sum of 5001 to 7000?
	1) $S_{n}=\frac{2000}{2}[5001+7000)]=12001000$

>[!example]+ Evaluate sum of sequence
>1) Evaluate the arithemetic sequence $9+14+19+…+224$.
	>$t_{1}=9, d=5, t_{n}=224$
		>$224=9+(n-1)*5*$
	>$5n+4=224$
		>$5n=220$
		>$n=44$
	>$S_{n}=\frac{n}{2}[a+l]$
		>$S_{44}=\frac{44}{2}[9+224]$
		>$=22+233$
		>$=5126$
	>$\therefore 9+14+19+...+224=516$
	
>[!example]+ Number of terms
>2) If $10+13+16+...+t_{n}=198$, how many terms are there in the series?
	>$t_{1}=10, d=3, S_{n}=198$
	>$S_{n}=\frac{n}{2}[2t_{1}+(n-1)d]$
	>$198=\frac{n}{2}[2(10)+(n-1)*3*]$
	>$396=3n^{2}+17n$
	>$3n^{2}+17n-396=0$
	>$(n-9)(3n+44)=0$
	>$n=9, -\frac{44}{3}$
	>Since $n>0$, then $n \neq -14 \frac{2}{3}$
	>Ther are 9 terms in the series

>[!example]+ $t_{6}=23$ and $S_{10}=210$, find $S_{20}$
>3) The 6th term of an arithmetic series is $23$ and the sum of the first 10 terms is $210$. Find the sum of the first 20 terms.
>$t_{6}=23$ and $S_{10}=210$
>$t_{1}=5d=24$ {1}
>$5[2t_{1}+9d]=210$ {2}
>$2t_{1}+10d=46$ $[1]×2$
>$2t_{1}=9d=42$ $[2]/5$
>$d=4$
>$t_{1}+5×4=23$
>$t_{1}=3$
>$S_{20}=10[2×3+19×4]$
>$=820$

>[!Example]+ Sum of to $n$ terms
>Find the sum of $4+7+10+13+...$ to $50$ terms
>The series is arithmetic with $t_{1}=4, d=3, n=50$
>Now $S_{n}=\frac{n}{2}(2t_{1}+(n-1)d)$
>$\therefore S_{50}=\frac{50}{2}(2×4+49×3)$
>$=3875$

>[!example]+ Sum of $-6+1+8+15+…+141$
>Find the sum of $-6+1+8+15+...+141$.
>The series is arithmetic with $t_{1}=-6, d=7,$ and $t_{n}=141$.
>First we need to find $n$.
>Now $t_{n}=141$
>$\therefore t_{1}+(n-1)d=141$
>$\therefore -6+7(n-1)d=141$
>$\therefore 7(n-1)=147$
>$\therefore n-1=21$
>$\therefore n=22$
>Using $S_{n}=\frac{n}{2}(t_{1}+t_{n}),$
>$S_{22}=\frac{22}{2}(-6+141)$
>$=11×135$
>$=1485$

>[!example]+ Number of terms
>If $10+13+16+...+t_{n}=198$, how many terms are in the series?
>$t_{1}=10, d=3, S_{n}=198$
>$S_{n}=\frac{n}{2}[2t_{1}+(n-1)d]$
>$198=\frac{n}{2}[2(10)+(n-1)×3]$
>$396=3n^{2}+17n$
>$3n^{2}+17n-396=0$
>$(n-9)(3n+44)=0$
>$n=9, - \frac{44}{3}$
>Since $n>0$, then $n \neq -14 \frac{2}{3}$
>There are 9 terms in the series
# Textbook 08.04 (pg 391)
---
Carl Friedrich Gauss (1777−1855) was an infant prodigy. He enjoyed numerical computation as a child and one story from his early schooling is often told as follows.
One day, in order to keep the class busy, the teacher asked the students to add up all the numbers from one to a hundred. Almost immediately Gauss placed his slate on the table, saying, ‘There it is.’
The teacher was not amused and thought it was a joke. Finally, when the other students had finished, it was revealed that Gauss was indeed correct.
The ten-year-old boy had mentally computed the sum of the arithmetic progression $1+2+3+...+99+100$ in next to no time without any additions.
Gauss said he solved the problem by observing that $100 + 1 = 101, 99 + 2 = 101, 98 + 3 = 101$, etc., and so there are 50 pairs of numbers totalling 101. Thus the answer is $50 × 101$, or $5050$.
The sum of a sequence of numbers is called a series. Many series occur in real life − think of the way that plants grow, or the way money accumulates as it earns interest in a bank.
For example, the sequence $3, 7, 11 … , 31$ when summed becomes the series $3, 10, 21, ... 136$
When you add the arithmetic sequence $3, 7, 11, …, 31$ you get the series $3, 3 + 7, 3 + 7 + 11, 3 + 7 + 11 + … + 31$. You can work out the sum using Gauss’ method as follows.
Write $S_8 = 3 + 7 + 11 + 15 + 19 + 23 + 27 + 31.$
Rearrange to get $S_{8} = (3 + 31) + (7 + 27) + (11 + 23) + (15 + 19) = 4 × 34 = 136$.
You can use Gauss’ method for an odd number of terms as well.
Consider the arithmetic series $9 + 17 + 25 + 33 + 41 + 49 + 57$.
The middle term, $33 = \frac{1}{2}×66 =\frac{1}{2}(9+57)$ .
For this series, $S_{7} = (9 + 57) + (17 + 49) + (25 + 41) + 33 = 3 \frac{1}{2}×66=231$.
The middle term of an arithmetic series with an odd number of terms is always going to be half the total of the first and last terms. Suppose an arithmetic sequence has first term $a$, common difference d and there are $(2n + 1)$ terms.
Then the $(2n + 1)$th term, the last term = $a + 2nd.$
The middle term is the $(n + 1)$th term = $a+nd=\frac{1}{2}(2a+2nd)=\frac{1}{2}[a+(a+2nd)]=\frac{1}{2}[first+last]$.
To use Gauss’ method for an arithmetic series, you add the first and last terms and multiply by half the number of terms.
For a general arithmetic series, let $S_{n}=t_{1}+t_{2}+t_{3}+...+t_{n}=\frac{n}{2}(t_{1}+t_{n})=\frac{n}{2}(a+l)$ where $a$ is the first term and $l$ is the last term.
You can rearrange the formula as $S_{n}=\frac{n}{2}(t_{1}+t_{n})=\frac{n}{2}(t_{1}+(t_{1}+(n-1))d)=\frac{n}{2}(2t_{1}+(n-1)d)$.
>[!Important]+ Formula
>The sum of the **arithmetic series** $S_{n}$ with the first term $t_{1}$, common difference $d$ and $n$ terms is given by
>$S_{n}=\frac{n}{2}(2t_{1}+(n-1)d)=\frac{n}{2}(t_{1}+t_{n})$,
>where $S_{n}=t_{1}+t_{2}+t_{3}+...+t_{n}$, $t_{n}$ is sometmes replaces with the letter l.

You can also prove the formula $2S_{n}=S_{n}+S_{n}$ by writing the second sum in reverse order;
$S_{n}=t_{1}+t_{2}+t_{3}+...+t_{n}$
$=t_{1}+(t_{1}+d)+(t_{1}+2d)+...+[t_{1}+(n-3)d]+[t_{1}+(n-2)d], [t_{1}+(n-1)d]$
$S_{n}=[t_{1}+(n-1)d]+[t_{1}+(n-2)d]+[t_{1}+(n-3)d]+...+(t_{1}+2d)+(t_{1}+d)+t_{1}$
Adding gives
$2S_{n}=[2t_{1}+(n-1)d]+[2t_{1}+(n-1)d]+[2t_{1}+(n-1)d]+...+[2t_{1}+(n-1)d]+[2t_{1}+(n-1)d]$
$2S_{n}=n[2t_{1}+(n-1)d]$
Dividing by 2, you get $S_{n}=\frac{n}{2}(2t_{1}+(n-1)d)$.

# Ex 08.04
---
 2)
	 a) 375
	 b) 555
	 c) 480
	 d) -870
	 e) 465
3)
	a) 21 terms
	b) 11 terms
	c) n=2 or 11
	d) 8 or 13 terms
	e) 47
4)
	a) $t_{1}=14, d=4$
	b) $t_{1}=-3, d=5$
	c) $S_{20}=3420$
	d) $S_{20}=1010$
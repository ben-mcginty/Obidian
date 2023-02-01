# Related
---
[[Sum of Geometric Sequence (Geometic Series)]]
[[Geometric Sequences]]
# In-Class Lecture
---
Warm up:
	Prove:
	$S_{n}=t_{1}+t_{2}+t_{3}+...+t_{n-2}+t_{n-1}+t_{n}$
	$S_{n}=t_{1}+t_{1}r+t_{1}r^{2}+...+t_{1}+r^{n-3}+t_{1}r^{n-2}+t_{1}r^{n-1}$ (1)
	$rS_{n}=t_{1}r+t_{1}r^{2}+t_{1}r^{3}+...+t_{1}r^{n-2}+t_{1}r^{n-1}+t_{1}r^{n}$ (2)
	$(1)-(2)$ gives
	$rS_{n}-S_{n}=t_{1}r^{n}-t_{1}$
	$S_{n}(r-1)=t_{1}(r^{n}-1)$
	$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$ for $r\neq 0$
	$(2)-(1)$ gives
	$rS_{n}-S_{n}=t_{1}r^{n}-t_{1}$
	$S_{n}(r-1)=t_{1}(r^{n}-1)$
	$S_{n}=\frac{t_{1}(r^{n}-1)}{r-1}$ for $r\neq 1$
$S_{n}=t_{1}r^{0}+t_{1}r^{1}+t_{1}r^{2}+...$

>[!example]+ $\frac{3}{4}+ \frac{15}{16}+ 1 \frac{11}{64}+...$
>$\frac{3}{4}+ \frac{15}{16}+ 1 \frac{11}{64}+...$
>$a=\frac{3}{4}$, $r=\frac{15}{16}÷ \frac{3}{4}= \frac{5}{4}$
>$S_{\infty}=\frac{(\frac{3}{4})^{4}}{1- \frac{5}{4}}=❎$ 

>[!example]+ $3+2 \frac{1}{4}+1 \frac{11}{16}+...$
>$3+2 \frac{1}{4}+1 \frac{11}{16}+...$
>$a=3$, $a=2 \frac{1}{4}÷3=\frac{2}{4}$
>$S_{\infty}=\frac{3}{\frac{1-3}{4}}=12$

>[!example]+ $-\frac{2}{3}+ \frac{5}{12}- \frac{25}{96}+...$
>$-\frac{2}{3}+ \frac{5}{12}- \frac{25}{96}+...$
>$a=\frac{2}{-3}$, $r=\frac{5}{12}÷- \frac{2}{3}=- \frac{5}{8}$
>$S_{\infty}=\frac{\frac{8}{-3}}{1-(-\frac{5}{8})}$
>$=- \frac{16}{9}$

>[!example]+ Write $0.2\overline{54}$ as a fraction
>Write $0.2\overline{54}$ as a fraction
>$=\frac{1}{5}+\frac{54}{1000}+\frac{54}{100000}+...$
>$a=\frac{54}{1000}$, $r=\frac{1}{100}$
>$S_{\infty}=\frac{\frac{54}{1000}}{1- \frac{1}{100}}=\frac{3}{55}$
>$\frac{1}{5}+\frac{3}{55}=\frac{14}{55}$

# Textbook 08.08 (pg 407)
---
>[!note]+ Investigation - Infinte sums of GPs
>Find the sum of each of the following geometric series to the given numbers of terms.
>$40+20+10+...$ to $5$ terms, $8$ terms and $50$ terms.
>$2+4+8+...$ to $5$ terms, $8$ terms and $15$ terms.
>$90-30+10-...$ to $5$ terms, $8$ terms and $50$ terms.
>$10-30+90-...$ to $5$ terms, $8$ terms and $15$ terms.
>What can you say about each of these series?
>What determines wether or not these sums converge.

>[!important]+
>A geometric series converges if $-1 < r < 1$ and the **limiting sum** of a geometric series with first term a and common ratio r, written as $S_{\infty}$, is given by $S_{\infty}=\frac{a}{1-r}=\frac{t_{1}}{1-r}$.
>The limiting sum is also called the **sum to infinity**.

For $-1 < r < 1$, as $n$ increases, $r^{n}$ decreases, getting closer and closer to zero.
$S_{n}=\frac{a(1-r^{n})}{1-r}$
So for -$1 < r < 1$, as n becomes very large,
$S_{n}$ gets close to $\frac{a(1-0)}{1-r}=\frac{a}{1-r}$

>[!example]+ Example 22 | Which of the following series have a limiting sum?
>Which of the following series have a limiting sum?
>1) $\frac{3}{4}+ \frac{15}{16}+ 1 \frac{11}{64}...$
>	$r=\frac{1 \frac{11}{64}}{\frac{5}{16}}= \frac{\frac{5}{16}}{\frac{3}{4}}=1 \frac{1}{4}$
>	Since $r>1$, this series does not have a limiting sum
>2) $100+50+25+...$
>	$r= \frac{25}{50}=\frac{50}{100}=\frac{1}{2}$
>	Since $-1<r<1$, this series does have a limiting sum.
>3) $3+2 \frac{1}{4}+1 \frac{11}{16}+...$
>	$r=\frac{2 \frac{1}{4}}{3}= \frac{1 \frac{11}{16}}{2 \frac{1}{4}}=\frac{3}{4}$
>	Since $-1<r<1$, this series does have a limiting sum.

>[!example]+ Example 23 | Evaluate the following
>a) $2+1+\frac{1}{2}+\frac{1}{4}+\frac{1}{8}+\frac{1}{16}+...$
>	$r=\frac{1}{2}$
>	$S_{\infty}=\frac{a}{1-r}$
>	$\frac{2}{1-\frac{1}{2}}$
>	$=4$
>b) $6+2+\frac{2}{3}+...$
>	$r=\frac{\frac{2}{3}}{2}=\frac{2}{6}=\frac{1}{3}$
>	$S_{\infty}=\frac{a}{1-r}$
>	$=\frac{6}{1-\frac{1}{3}}=9$
>c) $r=\frac{\frac{32}{81}}{\frac{16}{27}}=\frac{\frac{16}{27}}{\frac{8}{9}}=\frac{16}{24}=\frac{2}{3}$
>	$S_{\infty}=\frac{a}{1-r}$
>	$=\frac{\frac{8}{9}}{1- \frac{2}{3}}=\frac{8}{3}=2 \frac{2}{3}$

You can write the recurring part of a decimal as a GP. Then you can change it to a fraction using the sum to infinity.

>[!example]+ Example 24 | Write $0.2\overline{54}$ as a fraction
>Write $0.2\overline{54}$ as a fraction
>$=\frac{1}{5}+\frac{54}{1000}+\frac{54}{100000}+...$
>$a=\frac{54}{1000}$, $r=\frac{1}{100}$
>$S_{\infty}=\frac{\frac{54}{1000}}{1- \frac{1}{100}}=\frac{3}{55}$
>$\frac{1}{5}+\frac{3}{55}=\frac{14}{55}$

# Ex 08.08
---
2)
	f)
	h)
3)
	d)
	f)
5)
7)
8)
11)
12)
13)
14)
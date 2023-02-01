# Related
---
[[Scientific Notation and Significant Figures]]
[[Radical and Fractional Indicies]]
[[Index Laws]]

# In-Class Lecture
---
**Warm Up**
Simplify:
	a) $3^{2x-8}\times3^{5-3x}$
		$=3^{(2x-5)+(5-3x)}$
		$=3^{-x}=\frac{1}{3^{x}}$
	b) $13^{6q-3}\div13^{4q-7}$
		$=13^{(6q-3)-(4q-7)}$
		$=13^{2q+4}$
	c) $12^{8r+3}\times24^{7r-2}$
		$=(2^{2(8r+2)})\times3^{(8r+3)}\times2^{3(7r-2)}\times3^{(7r-2)}$
		$=2^{16r+6+21r-6}\times3^{8r+3+7r-2}$
		$=2^{37r}\times3^{15r+1}$
	d) $\frac{6^{2n-m}\times9^{n+m}}{36^{n-m}}$
		$=\frac{2^{2n-m}\times3^{2n-m}\times3^{2(n+m)}}{2^{2(n-m)}\times3^{2(n-m)}}$
		$=\frac{2^{2n-m}\times3^{2n-m}\times3^{2m-2n}}{2^{2n-2m}\times3^{2m-2n}}$
		$=2^{(2n-m)(2n-2m)}\times3^{(2n-m)+(2n+2m)-(2n+2m)}$
		$=2^{m}\times3^{2n+3m}$

Objectives of the lesson:
- Establish & use the algebraic features of exponential functions
- Recognise the qualitive features of the graph $y=2^{x}$ including asymptotes, and its translations
- Identify contents suitable for modelling by exponential functions

Exponential functions
>[!important]+
>The most simple expoential functions are in the form f $y=2^{x}$, where $a>0$ and $a\neq1$.
>For example, $y=2^{x}$ is an exponential function.

*Table of values for $y=2^{x}$ (see graph below for visual)*
| x   | -3  | -2  | -1  | 0   | 1   | 2   | 3   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| y   | 1/8 | 1/4 | 1/2 | 1   | 2   | 4   | 8   |

```functionplot
---
title: Exponential (2^x)
disableZoom: false
bounds: [-5, 5, -0, 35]

---
f(x) = 2^x
```

When $x=-10$, $y=-2^{-10}\approx0.001$
When $x=-50$, $y=2^{-50}\approx8.88\times10^{-16}$
$x\rightarrow\infty$, $y\rightarrow0^{+}$
$y=0$ in a horizontal asymptote.

$y=k\times a^{x-c}+b$
$k$ → growth constant
$a$ → smoosh/stretch
$b$ → vertical movement
$c$ → horizontal movement

# Textbook 11.04 (pg 504)
---
An epidemic occurs when new cases of a disease appear at a much greater rate than normally expected. If an epidemic spreads through human populations across a large area, it is known as a pandemic. Famous examples of pandemics include the bubonic plague (black death) in Medieval Europe, the Spanish influenza (flu) pandemic in 1918–19 and the sudden acute respiratory syndrome (SARS) epidemic in 2003.
One of the reasons that a bacterial disease like cholera spreads so quickly through untreated water supplies is that the bacterium multiplies rapidly. In a research laboratory, a culture containing 20 μg of bacteria was observed over a period of time. It was initially found to increase by 30% every 10 minutes. Growth at this rate for an hour is shown in the following table.
| Number of 10-minute time periods | Growth ratio | Mass of bacteria (μg)                           |
| --------------------------------- | ------------ | ---------------------------------------------- |
| 0                                 | -            | $20$                                           |
| 1                                 | 1.3 times    | $20\times1.3$                                  |
| 2                                 | 1.3 times    | $20\times1.3\times1.3=20\times(1.3)^{2}$       |
| 3                                 | 1.3 times    | $20\times(1.3)^{2}\times1.3=20\times(1.3)^{3}$ | 
| 4                                 | 1.3 times    | $20\times(1.3)^{3}\times1.3=20\times(1.3)^{4}$ |
| 5                                 | 1.3 times    | $20\times(1.3)^{4}\times1.3=20\times(1.3)^{5}$ |
| 6                                 | 1.3 times    | $20\times(1.3)^{5}\times1.3=20\times(1.3)^{6}$ |

So after an hour the bacteria had grown from $20 μg$ to $20 × (1.3)^{6} μg$ or about $97 μg$, which is a growth of almost 500%.
From the table, it can be seen that the mass in μg of the bacterium can be modelled as
$M(t)=20\times(1.3)^{t}$
where $t$ is the number of 10-minute periods after the commencement of the observations.
The growth of this bacteria is an example of a function where the variable is an exponent. This is known as an exponential function.

>[!important]+
>The general form of a simple exponential function is:
>$f(x)=Aa^{x}$
>where $A$ and $a$ are constants, $a>0$ and $a\neq1$.
>For $A,a>0$, the domain is the real numbers and the range is the positive real numbers.

It is important not to confuse exponential functions ($y=a^x$ ) with power functions ($y=x^{n}$).
Functions like $y=6\times5^{4x+3}$ and $f(x)=7^{x^{2}}$ are also exponential functions, but not simple ones.



# Textbook 11.05 (pg 507)
---
Most plants and animals begin as a single cell. This cell divides into two, the subsequent cells divide, and so on. The process continues in this way until (in some organisms) the cells begin to specialise, when some will divide faster or slower than others. The division of cells and the number of cells can be shown as follows.
| Reproductions, *r* | Cells, *c* |
| ------------------ | ---------- |
| 0                  | 1          |
| 1                  | 2          |
| 2                  | 4          |
| 3                  | 8          |
| 4                  | 16         |
The rule for the number of cells is $f(r)=c=2^{r}$. Calculating further values of the function gives:
| r   | c=2^r |
| --- | ----- |
| 0   | 1     |
| 1   | 2     |
| 2   | 4     |
| 3   | 8     |
| 4   | 16    |
| 5   | 32    |
| 6   | 64    |

```functionplot
---
title: Number of cells
bounds: [0, 6, 0, 64]
---
f(x) = 2^(x)
```
>[!example]+ Example 12
>Plot the graph of $y=4\times1.5^{x}$ for $-2\leq x\leq4$ and comment on the graph’s features.
>```functionplot
>---
>disableZoom: false
>bounds: [-2, 4, 0, 20]
>grid: true
>xLabel: x
>yLabel: y
>---
>f(x) = 4*1.5^x
>```
>*
>The graph has a $y$-intercept of $4$. The graph is always positive and is increasing as $x$ increases. The slope of the graph is also increasing as $x$ increases. As $x$ becomes larger in the negative direction, the graph gets closer and closer to $0$.

A CAS Calculator can also be used to draw the graph of an exponential function.

>[!example]+ Example 13
>Draw the graph of $y=8\times0.7^{x}$ for $-2\leq x\leq5$ and comment on the features of the graph.
>```functionplot
>---
>disableZoom: false
>bounds: [-2, 5, 0, 20]
>grid: true
>xLabel: x
>yLabel: y
>---
>f(x) = 8*0.7^x
>```

Exponential functions of the for $y=Aa^{x}$ have two basic shapes.

>[!important]+ Graphs of exponential functions of the form $y=Aa^{x}$
>```functionplot
>---
>disableZoom: false
>bounds: [-5, 5, 0, 32]
>grid: true
>xLabel: x
>yLabel: y
>---
>f(x) = 2^x
>g(x) = 0.5^x
>```
>*Blue is $2^{x}$ (increasing exponential function), red is $\frac{1}{2}^{x}$ (decreasing exponential function)*

The graphs of $y=Aa^{x}$ (where $A,a>0$) have a $y$-intercept at $A$ are always positive.
For an increasing exponential function, $y=Aa^{x}$, when $x\rightarrow-\infty,y\rightarrow0$.
For a decreasing exponential function, $y=Aa^{x}$, when $x\rightarrow\infty,y\rightarrow0$.
This means that the $x$-axis is a horizontal asymptote for the function.
From the previous investigation, you can also see that the value of $A$ influences the general shape of the graph of $y=Aa^{x}$
- When $a>1$, larger values of $A$ result in functions that increase more rapidly than for smaller values of $A$.
- When $0<a<1$, larger values of $A$ result in functions that decrease more rapidly than for smaller values of $A$.

# Textbook 11.06  (pg 512)
---
In the previous section of this chapter you looked at graphs of functions of the form $y=Aa^{x}$, where $A, a>0$.
We will now look at the graphs of other exponential functions.
The function $y = Aa^{x+b}+c$ is the general exponential function. Based on the work of this investigation, you can see that the graphs of $y = Aa^{x+b}+c$ and $y = Aa^{x}$ can be compared using the values of $A$, $b$ and $c$.

>[!important]+Translations of exponential functions
>When comparing graphs of the exponential functions $y=Aa^{x}$ and $y=Aa^{x+b}+c$ where $a$ is the base ($a>0$) and $A$, $b$, and $c$ are real constants ($A>0$):
>- the value of $b$ represents the translation of the graph of $y=Aa^{x}$, $b$ units to the left when $b>0$ or $b$ units to the right when $b<0$.
>- the value of $c$ represents a translation of the graph of $y=Aa^{x}$, $c$ units up when $c>0$ or down when $c<0$.
>- the horizontal asymptote of the exponential function $y=A^{x+b}+b$ is $y=c$.

>[!example]+ Example 14
>The graph of $y=a^{x}$ is shown to the right.
>Use this graph to draw a sketch of the function $y=a^{x-3}$ (using $a=2$ for simplicity.)
>```functionplot
>---
>title: Exponential (2^(x-3))
>bounds: [-10, 10, 0, 40]
>---
>f(x) = 2^(x-3)
>f(x) = 2^(x)
>```
>$y=a^{x-3}=a^{x+(-3)}$
>$b>0$
>$b>0$ means that the graph of $y=a^{x}$ is translated 3 units to the right to form the graph of $y=a^{x-3}$
>*(red is $y=a^{x}$, blue is $y=a^{x-3}$)*

The $y$-intercept is an important piece of information that is required to sketch or identify an exponential function.
When sketching graphs of an exponential functions of the form $y=Aa^{x+b}+c$, remember that the function is increasing if $a>1$, and decreasing if $0<a<1$.

>[!example]+ Example 15
>Sketch the graphs of:
>a) $y=3(2^{x})+1$
>	$a=2>1, A=3, b=0, c=1$
>	Since $a>1$, the graoh is increasing. $b=0$ so there is no horizontal translation.
>	$c=1$, so the graph is translated up by 1. The horizontal asymptote is at $y=1$. The $y$-intercept is at $3\times2^{0}+1=4$.
>	At $x=1, y=3\times2^{1}+=7$
>```functionplot
>---
>title: Exponential (3(2^(x))+1)
>bounds: [-10, 10, 0, 40]
>---
>f(x) = 3(2^(x))+1
>```
>b) $y=\frac{1}{2}\times10^{x-1}$
>$a=10>1,A=\frac{1}{2},b=-1,c=0$
>Since $a > 1$, the graph is increasing. $b = −1$ so there is a translation $1$ to the right.
>$c = 0$ so there is no vertical translation. The horizontal asymptote is at $y = 0$
>The $y$-intercept is a $\frac{1}{2}\times10^{-1}=0.05$
>At $x=1,y=\frac{1}{2}\times10^{0}=0.5$
>```functionplot
>---
>title: Exponential (1/2 × 10^(x-1))
>bounds: [-10, 10, 0, 40]
>---
>f(x) = .5*10^(x-1)
>```

Exponential graphs of the forms $y=Aa^{x+b}+c$ can be sketched by transforming the graph of $y=a^{x}$

>[!important]+
>Sketching exponents using transformations
>For the general exponential function $f(x)=Aa^{x+b}+c$:
>- the graph of $y=a^{x}$ has the horizontal asymptote $y=0$, $y$-intercept ($0,1$) and passes through the points $(1,\frac{1}{a})$ and $(1,a)$.
>- For $a>1$ it is increasing and for $0<a<1$ it is decreasing.
>- the constant $A$ dilates the graph by a factor of $A$ vertically from the $x$-axis - that is, the graph is stretched when $A>1$ and compressed vertically when $0<A<1$.
>- the constant $b$ translates the graph horizontally left $(b>0)$ or right $(b<0)$.
>- the constant $c$ translates the graph vertically up ($c>0$) or down ($c<0$)
>- the horizontal asymptote becomes $y=c$ and the $y$-intercept translates to ($-b,A+c$)

>[!example]+ Example 16
>Sketch the graph of $y=2^{x+3}-4$ by transforming the graph of $y=2^{x}$
>$a=2,A=1,b=3,c=-4$
>```functionplot
>---
>title: Exponential (2^(x-3))
>bounds: [-10, 10, -5, 40]
>---
>f(x) = 2^(x+3)-4
>f(x) = 2^(x)
>```
>*red is $y=2^{x+3}-4$, blue is $2^{x}$*


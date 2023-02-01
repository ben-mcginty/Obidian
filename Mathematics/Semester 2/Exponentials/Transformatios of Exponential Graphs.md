# Related
---
[[Exponential Functions]]
[[Index Laws]]

# In-Class Lecture
---
Warm up:
Simplify
1) $\frac{(8^{2f-3})\times16^{4-f}}{4^{f+2}}$
2) $\frac{3^{5x-6}\times9^{8-3x}}{18^{2x-7}}$

Using Desmos, gradually increase the complexity f the function $y=2^{x}$ to $y=k\times a^{x-c}+b$ and see the effect of changing the values

>[!important]+
>For the general equation $y=k\times a^{x-c}+b$ where $a>0$, $a\neq1$, $k\neq0$:
> - $a$ controls how steeply the graph increases or decreases
> - $c$ controls horizontal translation
> - $b$ controls vertical translation
> - the equation of the horizontal asymptote is $y=b$
>```functionplot
>---
>title: Exponential shapes
>---
>a(x) = 2*2^x
>b(x) = 2*0.5^x
>c(x) = -2*2^x
>d(x) =  -2*0.5^x
>```
> - if $k>0$, $a>1$, the function is increasing (blue).
> - if $k>0$, $0<a<1$, the function is decreasing (red).
> - if $k<0$, $a>1$, the function is decreasing (green).
> - if $k<0$, $0<a<1$, the function is increasing (yellow.)

We can sketch the graphs of exponential functions using:
- The horizontal asymptote
- The $y$-intercept
- two other points, for example, when $x=2$, and $x=-2$

>[!important]
>All exponential graphs are similar in shape and have a horizontal asymptote.

Sketch the graph of $y=2^{-x}-3$
Hence, sketch the domain and range of $f(x)=2^{-x}-3$
For $y=2^{-x}-3$, the horizontal asymptote is $y=-3$
When $x=0$, $y=2^{0}-3$
$=1-3$
$=-2$
$\therefore$ the $y$-intercept is $-2$.
When $x=2$, $y=2^{-2}-3$
$=\frac{1}{4}-3$
$=-2\frac{3}{4}$
When $x=-2$, $y=2^{2}-3=1$
The domain is $\{x|x∈ℝ\}$. The range is $\{y|y>-3\}$.
```functionplot
---
title: 2^{-x}-3
bounds: [-4, 4, -3, 10]
---
a(x) = 2^(-x)-3
```

Sketch the  graphs of each of the following pairs of functions. For the second function in each pair, state the equation of the asymptote, the $y$-axis intercept and the range (the $x$-axis intercept need not be given).
a) $f:ℝ\rightarrowℝ$, $f(x)=2^{x}$ and $g:ℝ\rightarrowℝ$, $g(x)=2^{x}+3$
```functionplot
---
bounds: [-5,5,0,10]
---
a(x) = 2^x
b(x) = 2^(x)+3
```

Graph of $g(x)=2^{x}+3$
- the asymptote has equation $y=3$
- the $y$-axis intercept is $g(0)=2^{0}+3=4$
- the range of the function $g$ is $(3,\infty)$.

b) $f:ℝ\rightarrowℝ$, $f(x)=3^{x}$ and $g:ℝ\rightarrowℝ$, $g(x)=2\times3^{x}+1$
```functionplot
---
bounds: [-5,5,0,10]
---
a(x) = 3^x
b(x) = 2*3^(x)+1
```
Graph of $g(x)=2\times3^{x}+1$
- the asymptote has equation $y=1$
- the $y$-axis intercept is $g(0)=2\times3^{0}+1=3$
- the range of the function $g$ is $(1,\infty)$.

c) $f:ℝ\rightarrowℝ$, $f(x)=3^{x}$ and $g:ℝ\rightarrowℝ$, $g(x)=-3^{x}+2$
```functionplot
---
bounds: [-10,5,-10,10]
---
a(x) = 3^x
b(x) = -3^(x)+2
```
Graph of $g(x)=-3^{x}+2$
- the asymptote has equation $y=2$
- the $y$-axis intercept is $g(0)=-3^{0}+2=1$
- the range of the function $g$ is $(-\infty,2)$.

Sketch each of the following:
a) $y=2\times3^{x}$
b) $y=3^{2x}$
c) $y=-3^{2x}+4$
```functionplot
a(x) = 2*3^(x)
b(x) = 3^(2x)
c(x) = -3^(-2x)+4
```

Sketch the graph $y=2^{x+3}-4$ by transforming the graph of $y=2^{x}$
```functionplot
a(x) = 2^(x)
b(x) = 2^(x+3)-4
```
Asymptote at $y=-4$
When $x=-1$, $y=0$
When $x=0$, $y=4$
When $x=1$, $y=12$

# Textbook 11.06 (pg 512)
---
In the previous section of this chapter you looked at graphs of functions of the form $y=Aa^{x}$, where $A,a>0$.
We will now look at the graphs of other exponential functions.
The function $y=Aa^{x+b}+c$ is the general exponential function. Based on the work of these investigation, you can see that the graphs of $y=Aa^{x+b}+c$ and $y=Aa^{x}$ can be compared using the values of $A$, $b$ and $c$.

>[!important]+ Translations of exponential functions
>When comparing graphs of the exponential functions $y=Aa^{x}$ and $y=Aa^{x+b}+c$ where $a$ is the base ($a>0$), and $A$, $b$ and $c$ are real constants ($A>0$).
>- The value of $b$ represents a translation of the graph of $y=Aa^{x}$, $b$ units to the left where $b>0$ or $b$ units to the right where $b<0$.
>- The value of $c$ represents the translation of the graph og $y=Aa^{x}$, $c$ units up when $c>0$ or $c$ units down when $c<0$.
>- The horizontal asymptote of the exponential function $y=Aa^{x+b}+c$ is $y=c$

>[!example]+ Example 14
> The graph of $y=a^{x}$ (where $a=2$ *(blue)*) is shown below.
> Use this graph to sketch the function $y=a^(x-3)$ (where $a=2$ *(red)*)
> ```functionplot
>a(x) = 2^(x)
>b(x) = 2^(x-3)
>```
>$y=a^{x-3}=a^{x+(-3)}$
>$b<0$
>$b<0$ means that the graph of $y=a^{x}$ is translated 3 units to the right to form the graph of $y=a^{x-3}$

The $y$-intercept is an important piece of information that is required to sketch or identify an exponential function.
When sketching graphs of exponential functions of the form $y=Aa^{x+b}+c$, remember that the function is increasing if $a>1$ and decreasing if $0<a<1$.

>[!example]+ Example 15
> Sketch the graphs of:
> a) $3(2^{x})+1$ (blue)
> 	- $y=Aa^{x+b}+c$
> 	- $=3(2^{x})+1$
> 	- $a=2>1$, $A=3$, $b=0$, $c=1$
> 	- Since $a>1$, the graph is increasing.
> 	- $b=0$ so there is no horizontal translation.
> 	- $c=1$ so the graph is translated up 1.
> 	- The horizontal asymptote is at $y=1$.
> 	- The $y$-intercept is at $3\times2^{0}+1=4$
> 	- At $x=1,y=3\times2^{1}+1=7$
> b) $y=\frac{1}{2}\times10^{x-1}$ (red)
> 	- $y=Aa^{x+b}+c$
> 	- $y=\frac{1}{2}\times10^{x-1}$
> 	- $a=10>1$, $A=\frac{1}{2}$, $b=-1$, $c=0$
> 	- Since $a>1$, the graph is increasing.
> 	- $b=-1$, so there is a translation of $1$ to the right.
> 	- $c=0$ so there is no vertical translation.
> 	- The horizontal asymptote is at $y=0$
> 	- The $y$-intercept is at $\frac{1}{2}\times10^{-1}=0.05$
> 	- At $x=1,y=\frac{1}{2}\times10^{0}=0.5$
>```functionplot
>---
>bounds: [-5, 3, -1, 10]
>---
>a(x) = 3(2^(x))+1
>b(x) = .5*10^(x-1)
>```

Exponential graphs in the form $y=Aa^{x+b}+c$ can be sketched by transforming the graph of $y=a^{x}$

>[!important]+ Sketching exponentials using transformations
>For the general exponential function $f(x)=Aa^{x+b}+c$:
> - The graph of $y=a^{x}$ has horizontal asymptote $y=0$, $y$-intercept ($0,1$) and passes through the points ($-1,\frac{1}{a}$) and ($1,a$).
> - For $a>1$ it is increasing and for $0<a<1$ it is decreasing
> - the constant $A$ dilates the graph by a factor if $A$ vertically from the $x$-axis - that is the graph is stretched vertically when $A>1$ and compressed vertically when $0<A<1$.
> - The constant $b$ translates the graph horizontally left ($b>0$) or right ($b<0$)
> - The constant $c$ translates the graph vertically up ($c>0$) or down ($c<0$)
> - The horizontal asymptotes becomes $y=c$ and the $y$-intercept translates to ($-b$, $A+c$)

>[!example]+ Example 16
>Sketch the graph of $y=2^{x+3}-4$ by transforming the graph of $y=2^{x}$
>$y=Aa^{x+b}+c$
>$y=2^{x+3}-4$
>$a=2$, $A=1$, $b=3$, $c=-4$
>Since $a>1$, the graph is increasing
>$b=3$, so there is a translation of 3 to the left.
>$c=-4$ so the graph is translated down $4$.
>The horizontal asyptote is at $y=-4$
>The $y$-intercept is at $2^{3}-4=4$
>At $x=1,y=2^{4}-4=12$
>```functionplot
>---
>bounds: [-10, 2, -5, 10]
>---
>a(x) = 2^(x+3)-4
>```

# Ex 11.06
---
1) $D$
2) $C$
3) $E$
4) $A$
5) $B$
6) $B$
7) $E$
8)
	a) $y=a^{x-5}$ (blue)
	b) $y=a^{x}-6$ (red)
	c) $y=a^{x+2}$ (green)
	d) $y=a^{x}+4$ (yellow)
	*($a=2$ for simplicity's sake)*
```functionplot
a(x) = 2^(x-5)
b(x) = 2^(x)-6
c(x) = 2^(x+2)
d(x) = 2^(x)+4
```
9)
	a) $y=0$ / $x=0$, $y=1$
	b) $y=0$ / $x=0$, $y=2$
	c) $y=1$ / $x=0$, $y=2.92$
	d) $y=-5$ / $x=0$, $y=-4.5$
	e) $y=0$ / $x=0$, $y=6$
	f) $y=3$ / $x=0$, $y=15.10$
10)
	a) 
		- $y$-intercept: $y=-2$
		- $x=-1$, $y=-2\frac{3}{4}$
		- $x=0$, $y=-2$
		- $x=1$, $y=1$
	b) 
		- $y$-intercept: $y=-1$
		- $x=-1$, $y=-\frac{3}{4}$
		- $x=0$, $y=-0.5$
		- $x=1$, $y=0$
	c) 
		- $y$-intercept: $y=2$
		- $x=-1$, $y=3\frac{1}{2}$
		- $x=0$, $y=5$
		- $x=1$, $y=8$
	d) 
		- $y$-intercept: $y=-1$
		- $x=-1$, $y=1$
		- $x=0$, $y=0$
		- $x=1$, $y=-\frac{1}{2}$
	e) 
		- $y$-intercept: $y=-1$
		- $x=-1$, $y=-\frac{4}{5}$
		- $x=0$, $y=0$
		- $x=1$, $y=4$
	f) 
		- $y$-intercept: $y=3$
		- $x=-1$, $y=2$
		- $x=0$, $y=5$
		- $x=1$, $y=7$
```functionplot
a(x) = 4^(x)-3
b(x) = 2^(x-1)-1
c(x) = 3(2^(x))+2
d(x) = (.5)^(x)-1
e(x) = 3^(x+2)-4
f(x) = 3^(x-5)+2
```
11)
	a) $3^{x}+5$ (Blue)
	b) $3^{x}+4$ (Red)
	c) $3^{x}-6$ (Green)
	d) $3^{x-5}$ (Yellow)
	e) $3^{x+2}-4$ (Blue)
	f) $3^{x-5}+2$ (Orange)
```functionplot
a(x) = 3^(x)+5
b(x) = 3^(x+4)
c(x) = 3^(x)-6
d(x) = 3^(x-5)
e(x) = 3^(x+2)-4
f(x) = 3^(x-5)+2
```
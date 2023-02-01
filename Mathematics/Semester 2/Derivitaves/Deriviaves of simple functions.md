# Related
---
[[The derivitave of a power]]

# In-Class Lecture
---
Lorem ipsum

# Textbook 9.02
---
A non-linear curve does not have a constant gradient but you can find an approximation to the gradient by using a secant. A secant is a straight line passing through two points on the graph of a function. The line segment between the two points is called a chord. The closer these two points are, the closer the approximate gradient is to the exact gradient. You know that the formula $m=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}$ is used to find the gradient of a straight line, given two points are $(x_{1},y_{1})$ and $(x_{2},y_{2})$. You can also write the gradient of this slope as $m=\frac{change~in~y}{change~in~x}$, or $m=\frac{\delta y}{\delta x}$.
Consider the graph of $y = f(x)$ shown below. $P$ is any point $(x, y)$ and $Q$ is another point on the same curve. The horizontal distance between $P$ and $Q$ is $\delta x$ and the vertical distance is $\delta y$. Therefore the point $Q$ is $(x + \delta x, y + \delta y)$
Now you can find the gradient of the chord $PQ$.
$m=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}$
$=\frac{y+\delta y-y}{x+\delta x-x}$
$=\frac{\delta y}{\delta x}$
You can see from the graph below that if you bring the point $Q$ closer and closer to $P$, the distance between $P$ and $Q$ becomes smaller and smaller. Eventually the secant becomes a tangent at the point $P$. The gradient of the chord $PQ$ approximates the gradient of the tangent at $P$. The shorter the chord, the better the approximation. So the gradient of the tangent at $P$ can be written as $\lim\limits_{\delta x\to0}\frac{(\delta y)}{(\delta x)}$.
Writing$ y = f(x)$, the coordinates of $P$ and $Q$ can be written as $(x, f(x))$ and $(x + \delta x, f(x + \delta x))$ respectively. Therefore, the gradient of the secant $PQ$ can be rewritten as:
$m=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}$
$=\frac{f(x+\delta x)-f(x)}{x+\delta x-x}$
$=\frac{f(x+\delta x)-f(x)}{\delta x}$
Similarly, the gradient of the tangent at $P$ is written as $\lim\limits_{\delta x\to0}\frac{f(x+\delta x)-f(x)}{\delta x}$, provided that the limit exists. It is normal practice to replace the $\delta x$ with a letter $h$ for limits of this kind to get $\lim\limits_\frac{f(x+h)-f(x)}{h}$. The diagram for this version of the gradient of the secant and tangent is shown below.
![[Pasted image 20220905202055.png]]
>[!important]+
>The gradient of a function at $P$ is the limiting value of the gradient of the secant $PQ$ as $Q$ approaches $P$. As $Q$ approaches $P$, $h$ becomes arbitrarily small as it approaches 0.
>Gradient of a secant $=\frac{f(x+h)-f(x)}{h}$
>Gradient of a tangent $=\lim\limits_{h\to0}\frac{f(x+h)-f(x)}{h}$

>[!important]+
>The derivative of a function at $x$ is define as $f'(x)=\lim\limits_{h\to0}\frac{f(x+h)-f(x)}{h}$, provided that the limit exists.

# Ex 9.02
---
Lorem ipsum
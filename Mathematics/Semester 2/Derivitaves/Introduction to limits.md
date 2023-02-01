# Related
---
[[Deriviaves of simple functions]]
[[The derivitave of a power]]

# In-Class Lecture
---
Lorem ipsum

# Textbook 9.01
---
The limit of a function $f(x)$ is the value that it gets closer and closer to as the function’s independent variable $x$ gets closer and closer to a particular value, $c$, say. Getting closer and closer to is called approaching and means you can make the value of $f(x)$ as close as you like to the limiting value by making $x$ close enough to $c$. It is only called a limit if it is the same whether $x$ approaches $c$ from above or below. You can estimate a limit from a graph or from a table of values.
Look at $f(x)=x^{2}+1$. From the table of values and graph below you can see that as $x$ gets close to $3$ the value of the function approaches $10$.

| Approaching from below | see left     | Approaching from above | see left      | 
| ---------------------- | ------------ | ---------------------- | ------------- |
| $x$                    | $f(x)$       | $x$                    | $f(x)$        |
| $2$                    | $5$          | $4$                    | $17$          |
| $2.5$                  | $7.25$       | $3.5$                  | $13.25$       |
| $2.9$                  | $9.41$       | $3.1$                  | $10.61$       |
| $2.99$                 | $9.9401$     | $3.01$                 | $10.0601$     |
| $2.999$                | $9.994001$   | $3.001$                | $10.006001$   |
| $2.9999$               | $9.99940001$ | $3.0001$               | $10.00060001$ |
As $x$ approaches 3 from the positive direction, $f(x)$ approaches 10.
As $x$ approaches 3 from the negative direction, $f(x)$ approaches 10.
Therefore, as x approaches 3 from either direction, $f(x)$ approaches 10.
You can write this as $\lim\limits_{x \to 3} (x^{2}+1)=10$.
'approaches' is a written as an arrow, so $x \to 3$ means 'as $x$ gets close to 3','as $x$ tends to 3' or 'as $x$ approaches 3'.
Now look at what happens to the behaviour of $f(x)=1/x$, $x\neq0$ as $x\to0$ from each direction. If we examine the graph below, you will notice that as $x\to0$ from the positive direction, $f(x)$ becomes large and positive (approaches infinity). Also, as $x\to0$ from the negative direction, $f(x)$ becomes large and negative. ($f(x)\to-\infty$)
There is no common value that $f(x)$ approaches as $x\to0$, so no limit exists.
```functionplot
---
title: Exponential (2^x)
disableZoom: false
bounds: [-10, 10, -10, 10]

---
f(x) = 1/x
```
>[!important]
>The limit of a function is the value that it approaches as the variable approaches a particular value from either direction. For a function $f(x)$ as $x$ gets close to $c$ we write the limit, if it exists, as $\lim\limits_{x \to c} f(x)$

For the limit to exist, it must be the same whether you approach the value of x from above the value or below it. In the case of $\lim\limits_{x \to c} (x^{2}+1)=10$, the value of the limit is the same as the value of the function at the point.
Now, let's consider $f(x)=\frac{x^{2}-9}{x-3}$.
If you substitute $x=3$ to work this out, you get $\frac{0}{0}$.
A denominator of zero means that $f(x)=\frac{x^{2}-9}{x-3}$ is undefined at $x=3$.
However, you can work out a limit as $x$ gets close to 3.

>[!example]+ Example 1
>Use a table of values to find out $\lim\limits_{x\to0}(\frac{x^{2}-9x}{x})$
>$f(x)=\frac{x^{2}-9x}{x}$
>$\lim\limits_{x\to0}(\frac{x^{2}-9x}{x})=-9$

>[!example]+ Example 3
>Find $\lim\limits_{x\to-2}\frac{(2x^{2}+3x-2)}{(x+2)}$
>$\frac{(2x^{2}+3x-2)}{(x+2)}=\frac{(2x-1)(x+2)}{x+2}$
>$=2x-1$
>$\lim\limits_{x\to-2}\frac{(2x^{2}+3x-2)}{(x+2)}=\lim\limits_(2x-1)$ if $x\neq2$
>$=-5$
>$\lim\limits_{x\to-2}(\frac{2x^{2}+3x-2}{x+2})=-5$


# Ex 9.01
---
Lorem ipsum
# Related
---
Lorem ipsum

# In-Class Lecture
---
Lorem ipsum

# Textbook 9.04
---
From the work in the previous section, you may have seen a pattern emerge for the derivatives of simple powers. You will need to recall the binomial theorem from Chapter 2 for this work.
The process of finding the derivative is called differentiating.
>[!example]+ Example 9
>Differentiate $f(x)=x^{4}$ from first principles
>$f(x+h)=(x+h)^{4}$
>$=x^{4}+4x^{3}+6x^{2}h^{2}+4xh^{3}+h^{4}$
>$f'(x)=\lim\limits_{h\to0}\frac{f(x+h)-f(x)}{h}$
>$=\lim\limits_{h\to0}\frac{(x^{4}+4x^{3}h+6x^{2}h^{2}+4xh^{3}+h^{4}-x^{4})}{h}$
>$=\lim\limits_{h\to0}\frac{4x^{3}h+6x^{2}h^{2}+4xh^{3}+h^{4}}{h}$
>$=\lim\limits_{h\to0}\frac{h(4x^{3}+6x^{2}h+4xh^{2}+h^{3})}{h}$
>$=\lim\limits_{h\to0}(4x^{3}+6x^{2}h+4xh^{2}+h^{3})$
>$=4x^{3}$
>The derivative of $f(x)=x^{4}$ is $f'(x)=4x^{3}$

From the binomial theorem, you can work out the following expansions.
$(x+h)^{5}=x^{5}+5x^{4}h+10x^{3}h^{2}+10x^{2}h^{3}+...$
$(x+h)^{6}=x^{6}+6x^{5}h+15x^{4}h^{2}+20x^{3}h^{3}+...$
$(x+h)^{7}=x^{7}+7x^{6}h+21x^{5}h^{2}+35x^{4}h^{3}+...$
and so on.
The expansions of $(x+h)^{n}$ always begin with $x^{n}+nx^{n-1}h+Ax^{n-2}h^{2}+Bx^{n-3}h^{3}+...$, where $A=({n\atop 2})=\frac{n(n-1)}{1\times2}$ and $B=({n\atop3})=\frac{n(n-1)(n-2)}{1\times2\times3}$.
We can use this to find the derivative of $x^{n}$ for any positive integer power of $x$.

>[!important]
>The derivitave of $f(x)=x^{n}$ is given by $f'(x)=nx^{n-1}$

# Ex 9.04
---
Lorem ipsum
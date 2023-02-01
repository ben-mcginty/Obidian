# Related
---
[[Deriviaves of simple functions]]
[[The derivitave of a power]]

# In-Class Lecture
---
The process of finding a function from a derivative is called antidifferentiation.
The general antiderivative of $2x$ is $x^{2}+c$ where $c$ is an arbitrary real number.
This can be expressed as: $\int 2x~\delta x = x^{2}+c$
Integrate:
1. $\frac{\delta y}{\delta x}=5x^{2}$
	1. $y=\frac{5}{3}x^{3}+c$
2. $f'(x)=\frac{3}{5x^{2}}$
	1. $f(x)=- \frac{3}{5x}+c$
3. $\frac{\delta y}{\delta x}=\sqrt[3]{x^{5}}$
	1. $y=\frac{3}{8}x\sqrt[3]{x^{5}}+c$

# Textbook 10.7
---
The derivative of a function is also known as the gradient function. The derivative gives the rate of change of the original function. For a polynomial function, we can use the derivative to calculate the gradient of the polynomial at any point on the curve. This is also the instantaneous rate of change at that point. Work through the following investigation.

>[!info]+ INVESTIGATION - Differentiating forwards and backwards
>We use the process called differentiation to derive the gradient function or derivative, $f'(x)$, from the original function, $f(x)$. The reverse of differentiation is known as antidifferentiation or integration. If we know the derivative, we can differentiate in reverse or work backwards from it to find a possible original function from the gradient function.
>1. Copy the table below into your workbook.
>2. Complete the table by working down the list in order.
>3. As you go down the list, look for patterns that emerge.
>4. Describe in words how the original function can be found from the derivative.
>![[Pasted image 20221027205129.png]]

What is the pattern for finding a function whose derivative is a power?
The pattern can be ‘Add 1 to the power of $x$ and divide by the new power’. We can write this in symbols as follows.

>[!important]+
>An antiderivative of a function is another function whose derivative is the given function.
>If $f′(x) = ax^{n}$ , then $f(x) = \frac{ax^{n+1}}{n+1}$ (where $n\geq0$), so $(\frac{ax^{n+1}}{n+1})$ is a possible antiderivative of $ax^{n}$ .

You can check this by differentiating $\frac{ax^{n+1}}{n+1}$

In Example 18, you could find many other antiderivatives of $f(x)$, such as $x^{3}-5x^{2}+4x+1$, $x^{3}-5x^{2}+4x+5$ and $x^{3}-5x^{2}+4x-7$ are also antiderivatives of $f(x) = 3x^{2} – l0x + 4$. The derivative of a constant is zero, so you can make as many antiderivatives as you like by adding constants to one antiderivative. The antiderivative of a function is usually written with a constant term ‘$+ c$’. Any particular antiderivative can then be obtained by substituting the appropriate value for the constant. An antiderivative is conventionally shown using the capital letter of the function name.

>[!important]
>For a function $f(x)$, if $F'(x)=f(x)$, then $F(x)$ is an antiderivative of $f(x)$.
>The antiderivative is also called a primitive or indefinite integral.
>All other antiderivatives of $f(x)$ are of the form $F(x)+c$, where c is a constant.

It is very important to keep in mind that an antiderivative is a function. However, all the antiderivative functions of a particular function differ only by constants.
It may be necessary to express a function in polynomial form before you can find the antiderivative.

# Ex 10.7
---
Lorem ipsum
# Related
---
[[Instantaneous Rates of Change & the slope of a curve]]

# In-Class Lecture
---
Lorem ipsum

# Textbook 7.02
---
The speedometer (‘speedo’) on a car gives us an immediate indication of the speed at an instant, without having to worry about averages. When we use a number of chords or secants to work out average speeds, we replace the curve of the distance–time graph by a series of straight lines. This is shown below.
![[Pasted image 20220829130717.png]]
>[!important]+ Chords, secants and tangents
>A secant is a straight line that passes through two points on a curve.
>A chord is the segment of a straight line cut off by a curve.
>A tangent is a straight line that touches a curve.


As more chords are used, the change in time for each chord gets smaller, and the shape of the graph made by the chords gets closer to the shape of the actual graph. If the change in time for each chord is reduced to an instant, we get exactly the same shape as the actual graph. The average speeds also become instantaneous speeds. We can do this for a single chord, but it is easier to see what happens if we use a secant instead. This is shown in the following.
![[Pasted image 20220829171734.png]]
The secant cuts the curve in two places, forming the ends of a chord. As we reduce the change in time, the secant becomes more like a tangent, which touches the curve at just one point. The slope of a secant (or chord) gives the average speed, so the gradient of a tangent gives the instantaneous speed. This applies to any rate of change.
>[!important]+
>The instantaneous rate of change of a variable at a point is the gradient of the tangent to the graph at that point.

>[!example]+ Example 4
>A valve on a tank of water is opened to drain its contents. Use a tangent to the graph shown here to find the flow rate 10 minutes after the valve is opened.
>![[Pasted image 20220829171840.png]]
>![[Pasted image 20220829171852.png]]
>$(0, 350)$ and $(20, 45)$ are on the tangent line.
>$m=(\frac{y_{2}-y_{1}}{x_{2}-x_{1}})$
>$\frac{45-350}{20-0}=-15kL/min$
>The water is flowing out at about $15kL/min$.


# Textbook 7.04
---
You have to use the tangent to find the instantaneous rates of change for mathematical functions. For mathematical functions, we simply call this the rate of change.
>[!example]+ Example 7
>Plot the graph of $f(x)=x^{2}+x-1$ from $-3$ to $2$ and find the rate of change at $x=1$ by drawing a tangent.
>![[Pasted image 20220829184234.png]]
>$(0,2)$ and $(2,4)$ are on the tangent.
>$m=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}=\frac{4-(-2)}{2-0}=3$
>The rate of change at $x=1$ is $3$.

# Textbook 7.05
---
Drawing graphs and using the tangents to find approximate rates of change of functions is very tedious, even when using a CAS calculator. In this section you will learn how to find approximate rates of change using small intervals. Remember that a change in a quantity is shown by the Greek capital delta, $\Delta$.
>[!important]+
>A small change in a quantity $x$ is shown by putting the lower case Greek letter $\delta$ in front of the variable, so $\delta x$ means a small change in the value of $x$.

You have already seen that as smaller and smaller chords are used, the secant through a chord gets closer and closer to the tangent of a curve. It doesn’t matter whether the chord is taken from above, below or around the point of interest. The diagrams below show the progressions, with the tangent shown in blue and the secants in pink.
![[Pasted image 20220829184633.png]]
The average rate of change of the function for each secant is still given by $\frac{\Delta y}{\Delta x}$, but for small changes we write this as $\frac{\delta y}{\delta x}$ and say that it approximates the rate of change.

>[!important]+
>Given a point $(x_{0},f(x_{0}))$ and values $x_{b}$ and $x_{a}$ such that $x_{b}<x_{0}<x_{a}$:
> - A line through $(x_{0},f(x_{0}))$ and $(x_{a},f(x_{a}))$ is called a secant from above the point.
> - A line through $(x_{b},f(x_{b}))$ and $(x_{0},f(x_{0}))$ is called a secant from below the point.
> - A line through $(x_{b},f(x_{b}))$ and $(x_{a},f(x_{a}))$ is called a secant from around the point.
>![[Pasted image 20220829185107.png]]

>[!example]+ Example 9
>Use $\delta x=0.1$ to find the approximate rate of change of $f(x)=x^{3}+2x+3$ at $x=2$ with the secant above the point.
>$f(2)=2^{3}+2\times2+3=15$
>$f(2.1)=2.1^{3}+2\times2.1+3=16.461$
>$\delta y=16.461-15=1.461$
>Rate of change $=\frac{\delta y}{\delta x}=\frac{1.641}{0.1}=14.61$

You need to use $x_{a}=x_{0}-\frac{\delta x}{2}$ and $x_{b}=x_{0}+\frac{\delta x}{2}$ for secants around the point.

>[!example]+ Example 10
>Use $\delta x=0.1$ to find the approximate rate of change of $f(x)=\frac{1}{x+1}$ at $x=2$, with the secant around the point.
>$f(1.95)=\frac{1}{1.95+1}=\frac{29}{50}$
>$f(2.05)=\frac{1}{2.05+1}=\frac{20}{61}$
>$\delta y=\frac{20}{61}- \frac{20}{59}=-0.011114198...$
>Rate of change $\approx \frac{\delta y}{\delta x}$
>$=\frac{-0.011114198...}{0.1}$
>$=-0.11114198...$
>$=-0.111$

# Ex 7.02, 7.04 & 7.05
---
Lorem ipsum
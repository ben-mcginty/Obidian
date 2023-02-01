# Formulas
→ Differentiation
Position Velocity Acceleration
← Antidifferentiation
$r=t_{n}\div t_{n-1}$
$S_{\infty}=\frac{a}{1-r}$
$\lim\limits_{x→a} \frac{f'(x)}{g'(x)}=\lim\limits_{x→a}{\frac{f(x)}{g(x)}}$
$\frac{ax^{n+1}}{n+1}$
$\frac{\delta s}{\delta t}=v$
$\frac{\delta v}{\delta t}=a$
$\frac{\frac{\delta s}{\delta t}}{\delta t}=a$
# Sequences
- A sequence is an ordered list. It is a function whose domain is the natural numbers. Each member of a sequence is called a term, denoted by $t_{n}$ or $a_{n}$ where $n$ is the term number. The sum of a sequence is called a series. Finite sequences have a finite number of terms while infinite sequences go on indefinitely [[Semester 2/Sequences/Sequences]]
- An arithmetic sequence or arithmetic progression (AP) has a first term denoted by $t_{1}$ or $a$ with each term differing from the previous one by the common difference, $d$. The general term of an AP is given by $t_{n}=t_{1}+(n-1)$ or recursively by $t_{n+1}=t_{n}+d$. [[Arithmetic Sequences & TI-84 Plus CE]] [[Arithmetic Sequences]]
- The common difference of an AP is given by:
	- $d=t_{n}-t_{n-1}$ or $d=t_{n+1}-t_{n}$.
- For a sequence $t_{1}$, $t_{2}$, $t_{3}$,… the corresponding series is $t_{1}$, $t_{1}+t_{2}$, $t_{1}+t_{2}+t_{3}$,… [[Sum of Arithmetic Sequences (Arithmetic Series)]]
- The sum of $n$ terms of an arithmetic series with the first term $t_{1}$ and common difference $d$ is given by $S_{n}=\frac{n}{2}[2t_{1}+(n-1)d]$ or $S_{n}=\frac{n}{2}[t_{1}+t_{n}]$, where $t_{n}$ is the last term. [[Geometric Sequences]]
- A geometric sequence or geometric progression (GP) has a constant called the common ratio that is the ratio of any two successive terms. The first term is written as $a$ or $t_{1}$ and the common ratio as $r$. A GP may be defined recursively by $t_{n+1}=rt_{n}$, where $n \geq 1$.
- The common ratio may be expressed as $r=\frac{t_{n}}{t_{n-1}}$.
- The general term of a GP is given by $t_{n}=ar^{n-1}$ or $t_{1}r^{n-1}$
- A sequence that has a limit as $n\rightarrow\infty$ is said to converge to the limit. [[Infinite Geometric Series]]
- A sequence that does not have a limit as $n\rightarrow\infty$ is said to diverge.
- A geometric sequence for which $-1<r<1$ converges to 0
- A geometric sequence for which $r<-1$ or $r>1$ diverges. The size of the terms increases without bound.
- The sum of $n$ terms of a geometric series is given by $S_{n}=\frac{t_{1}(t^{n}-1)}{r-1}$ or $S_{n}=\frac{t_{1(1-r^n})}{1-r}$, for $r\neq 1$. [[Sum of Geometric Sequence (Geometic Series)]]
- If the last term of a geometric sequence ($t_{n}$) is known, then the sum is $S_{n}=\frac{rt_{n}-t_{1}}{r-1}$ or $S_{n}=\frac{t_{1}-rt_{n}}{1-r}$
- A geometric series converges if $-1<r<1$. The limiting sum (sum to infinity) as a series with first term $a$ and common ratio $r$ is given by $S_{\infty}=\frac{t_{1}}{1-r}$
# Exponentials 
- $a^{n}$ is known as a **power** [[Index Laws]]
- $a^{n}=a\times a\times...\times a$ (to $n$ factors) where $n$ is a positive integer and $a$ is a real number.
- $n$ us called the **index** or the **exponent** and $a$ is called the **base**.
- The **index laws** allow us to multiply and divide by powers. The index laws and extensions are:
	- $a^{m}\times a^{n}=a^{m+n}$
	- $a^{m}\div a^{n}=a^{m-n}$
	- $(a^{m})^{n}=a^{m\times n}$
	- $(ab)^{n}=a^{n}b^{n}$
	- $(\frac{a}{b})^{n}=\frac{a^{n}}{b^{n}}$
	- $a^{0}=1$
	- $a^{-n}=\frac{1}{a^{n}}$
	- $\frac{1}{a^{-n}}=a^{n}$
- The square root sign, $\sqrt{}$, is also called the **radical** sign. [[Radical and Fractional Indicies]]
- A number written in **scientific notation** is written between 1 and 10 multiplied by a power of 10. [[Scientific Notation and Significant Figures]]
- Numbers can be expressed to a desired number of significant figures according to the precision required. Digits that have meaning in terms of a number’s precision are called significant figures.
- A function of the form $f(x)=ab^{x}$ is called an **exponential function**. For $a$, $b > 0$ the domain is the real numbers and the range is the positive real numbers [[Exponential Functions]]
- The general form of a simple exponential function is
	$f(x) = Aax^{x+b}+c$
	where $a$ is the base and $A$, $b$ and $c$ are real constants
- The **graph of an exponential function** is always positive. For a growth function the slope increases with increasing values of $x$, while for a decay function the slope decreases. [[Transformatios of Exponential Graphs]]

- When sketching exponential functions in general form, key features are used:
	- The general shape
	- The asymptote (which is affected by the constant $c$).
	- The $y$-intercept (when $x\neq0$)
	- One other significant point
- Exponential graphs in the form $f(x)=Aa^{x+b}+c$ can also be sketched by **transforming** the graph of $y=a^{x}$
	- $A$ dilates the graph vertically by a factor is $A$, (stretched for $A>1$, compressed for $0<A<1$).
	- $b$ translates the graph horizontally (left for $b>0$, right for $b<0$).
	- $c$ translates the graph vertically (up for $c>0$, down for $c<0$)
- An exponential equation (indicial equation) is one where the variable is in an exponent. [[Exponential Equations]]
- Exponential (or indicial) equations may be solved algebraically by using the fact that if $a^{m}=a^{n}$, them $m=n$
- Exponential equations may also be solved using a CAS calculator.
- A function that grows or decays by a **constant factor** can be modelled as an exponential function of the form $f(x)=Aa^{x}$, where $A=f(0)$ is the **initial value** or starting point, $a$ is the **growth factor** or **base**, and $x$ is the **exponent** or **index**. For a **growth function** $a>1$, and for a **decay function** $a<1$. [[Exponential Modelling]]
# Derivatives 
- The derivative of the function $f(x)$ is written as $f'(x)$, $\frac{\delta f}{\delta x}$, or $\frac{\delta}{\delta x}f(x)$.
- The derivative of the function $f(x)$ is the gradient of the function at the point $x$, so $f'(x)$ is called the gradient function.
- The sign of the derivative shows whether a function is increasing $(f'(x)>0)$, decreasing $(f'(x)<0)$, or stationary$(f'(x)=0)$.
- The rules for finding derivatives where $a$, $b$ and $k$ are constants are:
	- If $y=f(x)=k$, then $\frac{\delta y}{\delta x}=f'(x)=0$
	- If $y=kf(x)$, then $\frac{\delta y}{\delta x}=kf'(x)=k\frac{\delta y}{\delta x}$
	- If $y=f(x)=kx^{n}$, then $\frac{\delta y}{\delta x}=f'(x)=knx^{n-1}$
	- $\frac{\delta}{\delta x}[f(x)+g(x)]=f'(x)+g'(x)$
	- $\frac{\delta}{\delta x}[f(x)-g(x)]=f'(x)-g'(x)$
	- $\frac{\delta}{\delta x}[af(x)+bg(x)]=af'(x)+bg'(x)$
- The derivative of a polynomial is found using the rules for the derivative of $x^{n}$ and linear combinations.
- The derivative of a function is the instantaneous rate of change of the function.
- The reverse of the process of differentiation is called antidifferentiation or integration ($\int, \iint, \iiint$).
- An antiderivative is also called a primitive or indefinite integral.
- The antiderivative of $ax^{n}$ is $\frac{ax^{n+1}}{n+1}$ (where $n\geq0$).
- If $F'(x)=f(x)$, then all antiderivatives are of the form $F(x)+c$.
# Calculus
- The average rate of change of a function from $x_{1}$ to $x_{2}$ is given by $\frac{f(x_{2})-f(x_{1})}{x_{2}-x_{1}}$.
- The instantaneous rate of change of a function if given by the derivative. it is called the gradient function and it gives the slope of the tangent at a point.
- Speed, velocity, acceleration and flow rate are all rates of change.
- For motion in a straight line:
	- the displacement is a change of position.
	- the derivative of position ($x$) or displacement ($s$) with respect to time ($t$) is velocity ($v$) and the derivative of velocity is acceleration ($a$).
	  $\frac{\delta s}{\delta t}=v$ and $\frac{\delta v}{\delta t}=a$
	- the antiderivative of velocity is position or displacement and the antiderivative of acceleration is velocity.
- The sign of the derivative shows whether a function is increasing, decreasing or stationary.
- At stationary points, the derivative is zero. The type of stationary is determined by the change of sign of the derivative near the stationary point.
	- A local minimum occurs when the derivative changes from negative to 0 to positive as $x$ increases.
	- A local maximum occurs when the derivative changes from positive to 0 to negative as $x$ increases.
	- A point of inflection occurs when the derivative has the same sign each side of a stationary point.
- A global maximum or global minimum value of a function is a maximum or minimum over the whole domain.
- To sketch a polynomial function, investigate the zeros, sign, stationary point/s, intervals where the function is increasing and decreasing $y$-intercept and behaviour as the magnitude of $x$ becomes large.
- Values of a function, its derivatives and stationary points can be estimated by reading from the graph of the function or by using numerical methods (on a calculator).
- To find the greatest and least values of a function in an interval, investigate the stationary points, $y$-intercepts and values of the function at the boundaries of the interval.
- When solving optimisation problems on an interval, use the following steps:
	- Read the problem carefully.
	- Draw a diagram and introduce variables for the unknown quantities.
	- List all known factors and relationships, showing relationships by equations.
	- Determine the quantity to be maximised or minimised and express it by a function of one variable.
	- Find the interval over which quantity.
	- Find the maximum or minimum and express the answer in terms of the question.
	- State any assumptions and examine the solution for possible extension to other cases.
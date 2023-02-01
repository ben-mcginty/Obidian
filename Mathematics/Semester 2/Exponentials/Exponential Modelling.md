# Related
---
[[Exponential Functions]]
[[Exponential Equations]]

# In-Class Lecture
---
## Growth and Decay
Populations of animals, people and bacteria usually *grow* in an exponential way.
Radioactive substances, and items that depreciate in value, usually *decay* exponentially.
## Growth
Consider a population of $100$ mice which under favourable conditions is increasing by $20\%$ each week.
To increase a quantity by $20\%$, we multiply it by $1.2$.
If $P_{n}$ is the population after $n$ weeks, then:
$P_{0}=100$
$P_{1}=P_{0}\times1.2=100\times(1.2)^{1}$
$P_{2}=P_{1}\times1.2=100\times(1.2)^{2}$
$P_{3}=P_{2}\times1.2=100\times(1.2)^{3}$, and so on.
From this pattern, we see that $P_{n}=100\times(1.2)^{n}$
```functionplot
---
title: Exponential Modelling
bounds: [0,6,100,300]
---
a(x) = 100*(1.2)^(x)
```

An entomologist monitoring a grasshopper plague notices that the area is affected by the grasshoppers is given by $A(n)=1000\times(1.15)^{n}ha$, where $n$ is the number of weeks after the initial observation.
a. Find the original affected area
	$A(0)=1000\times1.15^{0}$
	$A(0)=1000\times1$
	$A(0)=1000$
	$\therefore$ the original affected area was $1000ha$.
b. Find the affected area after:
	i. 5 weeks
		$A(5)=1000\times1.15^{5}$
		$A(5)\approx2010$
		$\therefore$ the affected area is about $2010ha$.
	ii. 10 weeks
		$A(10)=1000\times1.15^{10}$
		$A(10)\approx4046$
		$\therefore$ the affected area is about $4046ha$.
c.  Draw the graph of the affected area over time
```functionplot
---
title: Exponential Modelling
bounds: [0, 20, 1000, 16000]
---
a(x) = 1000*1.15^(x)
```
d. Use the graph or technology to find how long it will take for the affected are to reach $8000ha$.
	From the graph in **c**, it appears that it would take about 15 weeks for the affected area to reach $8000ha$

## Decay
Consider a radioactive substance with original weight $20$ grams. It *decays* or reduces by $5\%$ each year. The multiplayer for this is $95\%$ or $0.95$.

If $W_{n}$ is the weight after $n$ years, then:
$W_{0}=20g$
$W_{1}=W_{0}\times0.95=20\times(0.95)^{1}$ grams
$W_{2}=W_{1}\times0.95=20\times(0.95)^{2}$ grams
$W_{3}=W_{2}\times0.95=20\times(0.95)^{2}$ grams
$W_{20}=20\times(0.95)^{20}\approx7.2$ grams
$W_{100}=20\times(0.95)^{100}\approx0.1$ grams
From this pattern we see that $W_{n}=20\times(0.95)^{n}$


# Textbook 11.08
---
In section 11.04 ([[Exponential Functions]]) of this chapter, you looked at an example about a culture containing $20µg$ of a bacterium that increases by $30\%$ every $10$ minutes.
The mass in $μg$ of the bacterium can be modelled as $M(t) = 20 × (1.3)^{t}$ , where $t$ is the number of $10$-minute periods after the commencement of the observations. As long as $t$ is a positive integer, you could model this as a geometric progression with $t_{1} = 20$ and $r = 1.3$. An exponential function is better because you can have negative and decimal values of $t$.
The growth of this bacteria is an example of a growth function that increases by a constant factor. The general rule for such functions is $f(x) = Aa^{x}$ . At $x = 0$, $f(0) = A$, so $A$ is the initial value (starting value) and $a$ is the growth factor.

>[!example]+ Example 20
>A bacterial colony has about 2000 bacteria. The number of bacteria triples every day. Assuming that growth continues in this way:
>
>$N(x)=ab^{x}$
>Initial value $a\approx2000$
>Growth factor $b=3$
>$N(d)\approx2000\times3^{d}$
>
>a. how many bacteria will be in the colony after 60 hours?
>$60$ hours = $2.5$ days
>$N(2.5)\approx2000\times3^{2.5}$
>$\approx31200$
>There will be approximately $312000$ bacteria after $60$ hours
>b. how many bacteria will be in the colony after 5 days?
>$N(5)\approx2000\times3^{5}$
>$\approx486000$
>There will be about $486000$ bacteria after $5$ days

Exponential models can also be used when the values are decreasing by constant factors. For these models, the growth factor is less than $1$, so we call the function a decay function instead of a growth function.

>[!important]+
>Exponential growth and decay
>The general form of a growth or decay function is
>$f(x)=Aa^{x}$
>where $A=f(0)$ is the initial value or starting point and $a$ is the growth factor
>For a growth function, $a>1$
>For a decay function, $0<a<1$.

>[!example]+ Example 21
>The amount of air left in a leaking spaceship is decreasing by $30\%$ every minute and the pressure decreases proportionally. When the leak first occurred, the pressure was $105kPa$. What will the pressure be after $6$ minutes?
>Growth factor $a=0.7$, $A=105$
>$P(m)=105\times0.7^{m}$
>$P(6)=105\times0.7^{6}$
>$\approx12.4kPa$
>After $6$ minutes, the pressure will be about $12.4kPa$. Find that leak!

>[!example]+ Example 22
>The difference between the temperature of a cup of coffee and its surrounding decreases by $4\%$ every minute. A fresh cup has a temperature of $70\degree C$. A cup of coffee is considered too cold to drink if it is below $40\degree C$. Model the temperature of the cup of coffee and find out how long it takes to become 'undrinkable'.
>The difference in temperature between the coffee and the room decreases by $4\%$ each minute. This is an exponential decay function. Let the coffee temperature after m minutes be $C(m)$. Assume that the room temperature stays at $20°C$. Let the difference between the coffee and room temperatures after m minutes be $D(m)$.
>$D(m)=C(m)-20$
>$C(m)=D(m)+20$
>$C(m)=Aa^{m}+20$
>$C(m)=50\times(0.96)^{m}+20$
>$C(5)=50\times(0.96)^{5}+20\approx60.8$
>$C(10)\approx53.2$
>$C(20)\approx42.1$
>$C(25)\approx38.0$
>$C(22)\approx40.4$
>$C(23)\approx39.6$
>$C(22.5)\approx39.96$

A growth or decay function can sometimes be modelled as an exponential one from a table of values. In order to model as an exponential function, the growth or decay factor must be *constant*.
Look at the values below.
| n   | m   |
| --- | --- |
| 0   | 5   |
| 1   | 10  |
| 2   | 20  |
| 3   | 40  |
| 4   | 80    |
You can see that every time $n$ increases by 1, $m$ doubles. Clearly $m=5\times2^{n}$. You should check that this is true for the *whole* table.

>[!note]+ Investigation
>Radiocarbon dating is a dating method that uses the naturally occurring isotope carbon-14 ($\frac{6}{14}$C) to determine the age of material containing carbon. The carbon-14 isotope is produced in the upper atmosphere as a result of cosmic rays hitting nitrogen atoms. The proportion of carbon-14 in carbon dioxide stays the same because the radioactive decay is balanced by production of more carbon-14 in the upper atmosphere by cosmic rays.
>Carbon-14 is absorbed by plants during photosynthesis, so it is present in the same proportion as in the atmosphere in all living organisms. Of course, when something dies, its stops getting more carbon-14, so the carbon-14 present just decays.
>For a quantity subject to exponential decay the time required for the quantity to decay to half of its initial value is known as its half-life. The half-life of carbon-14 is 5730 years.
>In the late 1940s an American scientist, Williard Libby, developed a technique for ‘dating’ archaeological material by measuring the amount of carbon-14 present compared with that found in things living now. The becquerel (Bq) is the SI unit of radioactivity. It is defined as the activity of a quantity of radioactive material in which one nucleus decays per second.
>Consider the case of an old bone that produced 10 Bq per gram of bone carbon-14 in 2010, compared with the bones of recently dead animals that produce 20 Bq per gram of bone carbon. Because the half-life of carbon-14 is 5730 years, the animal from which the old bone came would have died in about 3720 bce.
>1. The table below shows the radiation produced by an organic object at different times from its death. Use the table on the right to construct an exponential model of radioactive decay.
>2. Use your model to estimate the ages of bones with radiation readings of:
>	1. 9.7Bq per gram of bone carbon
>	2. 2.3Bq per gram of bone carbon
>3. Can radioactive dating be used to date any fossils?
>4. Is there a limit to the age of fossils that can be dated?
>5. The method relies on the production of carbon-14 in the atmosphere being constant. Is this true?
>6. What is the 'Suess effect'?

| Age (years) | Radiation (Bq)                       |
| ----------- | ------------------------------------ |
| 0           | 10                                   |
| 5730        | $20\times\frac{1}{2}=20\times2^{-1}$ |
| 11460       | $20\times(\frac{1}{2})^{2}=20\times2^{-2}$                                     |

# Ex 11.08
---

1.
	a. $45$
	b. $1.15$
2.
	a. $1100$
	b. $0.82$
3.
	a. $3\times(1.05)^{n}$
	b. 
		i. $3.47$
		ii. $4.89$
		iii. $7.96$
	c. $104.8$
4.
	a. $3000\times(1.08)^{n}$
	b.
		i. $\$3779.29$
		ii. $\$6476.77$
		iii.  $\$20545.43$
	c. $9.01$ years
5.
	a. $24900\times(0.85)^{n}$
	b. 
		i. $\$15291.71$
		ii. $\$11048.26$
		iii. $\$4902.17$
	c. $\approx19.78$ years
6.
	a. $T=500-480\times0.9$
	b.
		i. $216.6\degree C$
		ii.$322.6\degree C$
		iii. $465.5\degree C$
	c. $14.9$ minutes
7.
	a. $p=3\times2^{m}$
	b. $=68$
8.
	a. $q=24\times1.8^{x}$
	b. $=117.3402$
9.  $y=50\times1.4^{x}=318.1810$
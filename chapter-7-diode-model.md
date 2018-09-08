# Chapter 7 - Diode Model



\[TOC\]

### Exponential Model \(10-20%\)

![Diode 4](http://pcih4qs1o.bkt.clouddn.com/Diode%204.jpg)

$$-V_B + I_xR_1 +V_{D1} =0$$ $$-V_B + I_x + V_T \ln{I_x \over I_s} = 0$$

Too hard to solve $I\_x$

So, in next lecture, we will find another way to simplify the problem.

### Constant-Voltage Model \(70-80%\)

#### Observations

![Diode Model 1](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%201.jpg)

#### Modeling

Based on those observations we got,

![Diode Model 2](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%202.jpg)

* If $V_x &lt; V_{D-on} \Rightarrow $ Diode Off $\equiv $![Diode Model 3](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%203.jpg)
* If $V_x &gt; V_{D-on} \Rightarrow $ Diode Off $\equiv $![Diode Model 4](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%204.jpg)

**Range of $V\_{D-on} :700 - 800 mV$**, whether we choose which value between this range, the voltage won't change much.

### Ideal Diode Model \(10-20%\)

passes "+" voltages blocks "-" voltages

![Diode Model 5](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%205.jpg)

### Example 1

![Diode Model 6](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%206.jpg)

#### Quiz

Vary $V\_x$ from $0 \rightarrow \infty$, plot the $I\_x$ as the function of $V\_x$.

![Diode Model 7](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%207.jpg)

### Example 2

![Diode Model 8](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%208.jpg)

| Cause | Result |
| :--- | :--- |
| $V_x &lt; V_{D-on}$ | $V\_{D1} = V\_x$ |
| $V_x &gt; V_{D-on}$ | $V_{D1} = V_{D-on}$ |

### Reverse Breakdown

![Diode Model 9](http://pcih4qs1o.bkt.clouddn.com/Diode%20Model%209.jpg)

Features:

1. There's a capacitance associated with the junction
2. There's a small leakage current.
3. If the reverse is large enough, there will be a huge reverse current breakdown occurs and yield a lot of current.


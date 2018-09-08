# Chapter 6 - Diode

\[TOC\]

### Definition

A two-terminal device that carries current when its voltage is positive and no current when its voltage is negative. ![Diode 1](http://pcih4qs1o.bkt.clouddn.com/Diode%201.jpg)

$$I_x = I_s (e^{V_x \over V_T} -1)$$

不同半导体材料构成的二极管的反向饱和电流$I\_s$不同 ： ![Diode 2](http://pcih4qs1o.bkt.clouddn.com/Diode%202.jpg) 因此，$I\_s$是二极管的固有属性，与电压电流无关。

### Note

If the forward bias voltage $V\_x &gt; 4V\_T$, $I\_x \approx I\_s e^{V\_x \over V\_T}$

\(通常情况下，我们采用此式来代表二极管两端电压和电流的关系\)

### Quiz

![Diode 3](http://pcih4qs1o.bkt.clouddn.com/Diode%203.jpg)

Since, $$I_x \approx I_s e^{V_x \over V_T}$$ Therefore, $$V_x = V_T \ln {I_x \over I_s}$$

### Examples

* If $I\_s = 10^{-16} A$ and we measure a forward-bias current of $1 mA$, what's voltage is applied to the diode?

$$V_F = V_T \ln {I \over I_s} = 778mV$$

_P.S._ $e^{778mV \over 26mV} &gt;&gt; 1$

* How much should the voltage increase to raise the current by a factor of 10?

  $$V_{F1} = V_T \ln{I_1 \over I_s}$$

  $$V_{F2} = V_T \ln{I_2 \over I_s}$$

  $$V_{F2} - V_{F1} = V_T \ln {I_2 \over I_1}$$

  For 10x increase in current, we need to increase the voltage by $V\_T \ln 10 \approx 60 mV$

_P.S._ $V\_T = {k\_T \over q} \rightarrow 26mV$ @ $T = 300k$

**A beautiful result** : If we have an exponential device which is the case with a diode, in order to increase its current by a factor of 10, all we need to do is increase its voltage by 60 $mV$.

**Typically, forward-bias voltages for diodes are in the range of 700 - 800 $mV$**


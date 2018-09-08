# Chapter 8 - Analysis of Diode Circuits

\[TOC\]

### Summary of Diode Models

* Diode Model : exp, constant-v, ideal
  * All three models are nonlinear.
  * All three models distinguish between positive and negative voltages.

    _\("Rectification"\(整流\): keep all the positive voltages, and throw all the negative voltages\)_

  * The ideal model "passes" positive voltages; the constant-v model "passes" voltages greater than $V\_{D-on}$; the exp model "passes" voltages **significantly** if $V\_D &gt; 700 - 800 mV$.

### Application Examples

* Charger/Adapter（充电器/电源适配器）
  1. 通过变压器降低电压幅值。
  2. 通过整流电路（内含二极管），使电流方向恒为正。
  3. 通过低通滤波器，保留电流的直流部分。

### Practice with Diode Circuits

#### Example \(Using ideal model of diode\)

* \(a\) ![Analysis of Diode Circuits 1](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%201.jpg)
* \(b\) ![Analysis of Diode Circuits 2](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%202.jpg)
* \(c\) Find the relationship between $V_x$ and $I\_x$ ; $V\_x$ and $V_{out}$ ![Analysis of Diode Circuits 3](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%203.jpg) ![Analysis of Diode Circuits 4](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%204.jpg)
* \(d\) ![Analysis of Diode Circuits 5](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%205.jpg)

### Application Example 2

![Analysis of Diode Circuits 6](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%206.jpg)

每个二极管上有约为800$mV$的压降，两个串联，就能形成1.6$V$的压降。

* The voltage across each diode is a **weak function** of its current.
* The diodes operate as a simple **voltage regulator**.

### Principles of Diode Circuit Analysis

1. Begin by assuming certain states of all diodes, check the final result against these assumptions.
2. If a diode is about to turn on or off, it must sustain a voltage of $V\_{D-on}$, but its current is small
3. If a diode is on and carries a current, the current must flow from the anode to the cathode.

### Example 1

> Using constant-voltage model of diode

![Analysis of Diode Circuits 7](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%207.jpg)

Raise $V_x$ so much that $V\_N$ reaches $\(V_{D-on} + V\_B\) \Rightarrow D1$ begins to **turn on** Since the current thru $D1$ is still small $\Rightarrow$ Voltage drop across $R1$ is small. \(which can be neglected\)

#### Quiz 1

Plot "$V\_N$ vs $V\_x$"

![Analysis of Diode Circuits 8](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%208.jpg)

### Example 2

> Using constant-voltage model of diode

Swap $D1$ with $R1$ , the relationship between $V\_x$ and $I\_x$ doesn't changed. ![Analysis of Diode Circuits 9](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%209.jpg)

#### Quiz 2

Plot "$V\_N$ vs $V\_x$"

## Other Examples of Diode Circuits

### Example

![Analysis of Diode Circuits 10](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%2010.jpg)

### Quiz

Plot $V\_N$ vs $V\_x$

![Analysis of Diode Circuits 11](http://pcih4qs1o.bkt.clouddn.com/Analysis%20of%20Diode%20Circuits%2011.jpg)


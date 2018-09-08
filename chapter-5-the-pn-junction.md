# Chapter 5 - The PN Junction

\[TOC\]

### Quick Experiment

![PN Junction 1](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%201.jpg)

### Two Questions

1. How do the charge carrier redistribute themselves after **the pn junction** is formed?
2. How does **the pn junction** behave under
3. Equilibrium ---- 平衡状态（零偏置）
4. Reverse Bias ---- 反向偏置
5. Forward Bias ---- 正向偏置

### PN Junction in Equilibrium

![PN Junction 2](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%202.jpg)

#### Equilibrium Condition

* Diffusion Current of electrons = Drift Current of electrons
* Diffusion Current of holes = Drift Current of holes

  \(比较大小 ，取绝对值\)

Since, $$J_{drift} = ( \mu_n nq + \mu_p nq) E$$ $$J_{diffusion} = (D_n{d_n \over d_x} - D_p{d_p \over d_x}) q$$

Therefore, $$D_p {d_p \over d_x} q = \mu_p pEq$$ $$D_p {d_p \over p} = \mu_p E d_x$$ $$\int_{p_n}^{p_p} D_p{d_p \over p} = \mu_p \int_{x_1}^{x_2} E d_x$$

Definition of voltage between A and B : $$V_{AB} = -\int_A^B E d_x = V_B - V_A$$ $$\int_{x_1}^{x_2} E d_x = V_1- V_2$$

So, $$D_p \ln {p_p \over p_n} = \mu_p (V_{x_1} - V_{x_2}) = \mu_p V_0$$

$$V_0 = {D_p \over \mu_p} \ln {{N_a N_d} \over n_i^2}$$

Apply Einstein's Relation ---- ${D \over \mu} = {kT \over q}$ , $$V_0 = {KT \over q} \ln {{N_a N_d} \over n_i^2}$$

\*\*$V\_0$ is called " Built in Potential "\*\* ---- 内在电势

_P.S._ ${kT \over q} \rightarrow 26mV$ @ $T = 300k$

#### Quiz

Is there an electric field outside the depletion region?

* Electric field = 0 ; Voltage drop = 0 in the "neutral region"

_P.S._ Apply Guass's Law , the net charge outside the depletion region is **zero**.

#### Observation

1. Same $V\_0$ expression is obtained if the electron currents are considered.
2. If $N\_a$ and $N\_d$ are on the order of $10^{16} / cm^3$, $$V_0 \approx 26mV \cdot \ln {10^32 \over 10^20} \approx 720 mV$$ $\Rightarrow$ _Typical values of $V\_0$ are from 700 to 800 $mV$_
3. $V\_0$ is localized \(_be limited in the depletion region_\)
4. We cannot measure $V\_0$ from outside.

### PN Junction in Reverse Bias

In Reverse Bias, PN Junction can be modeled as a capacitor. ![PN Junction 3](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%203.jpg) In Reverse Bias, the depletion region becomes wider. ![PN Junction 4](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%204.jpg) Capacitior Model of PN Junction ![PN Junction 5](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%205.jpg) Electronically-Variable Capacitor ----" Varator " ![PN Junction 6](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%206.jpg)

### PN Junction in Forward Bias

![PN Junction 7](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%207.jpg)

![PN Junction 8](http://pcih4qs1o.bkt.clouddn.com/PN%20Junction%208.jpg) $$I_x = I_s (e^{V_x \over V_T} -1)$$

$I\_s$ : Reverse Saturation Current $V\_T = {k\_T \over q} \rightarrow 26mV$ @ $T = 300k$


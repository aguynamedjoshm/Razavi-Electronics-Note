# Chapter 9 - Pratical Diode Circuits

\[TOC\]

### Outline

* Rectifiers \(整流器\) $\Rightarrow$ Charger / Adapter
* Limiters $\Rightarrow$ FM Receivers / Optical Communications \(光通信\)
* Voltage Doublers $\Rightarrow$ RF receivers \(射频收发器\) / Flash Memories
* Level Shifts $\Rightarrow$ General Circuits

### Rectifiers \(整流器\)

#### Basic Concepts

1. Analyze circuit to obtain: $I -V$ characteristic, input - output characteristic. Also, can analyze by studying the time response. ![Pratical Diode Circuits 1](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%201.jpg)
2. Concept of "Tracking". e.g., $V_N = V\_x - V_{D-on} \Rightarrow$ $V\_N$ tracks $V\_x$, perhaps with a constant difference.
3. Quick review of capacitors

   ![Pratical Diode Circuits 2](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%202.jpg)

#### Half-Wave Rectifiers

![Pratical Diode Circuits 3](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%203.jpg)

**Half-Wave Rectifiers with smoothing cap （理想状态）**

![Pratical Diode Circuits 4](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%204.jpg)

1. 当$V\_{in}$越过峰值后，电容两端电压的变化：
   * 若电容电压增加，则必须有电流灌入电容，然而$V\_{in}$在减小，所以电容两端电压无法增加。
   * 若电容电压减小，则必须有电流流出电容，然而电流无法从二极管负极流到正极，所以电容两端电压无法减小。
   * 因此电容两端电压不变。
2. 当$V_{in}$越过峰值后，二极管关闭： 负极电压维持不变，正极电压减小，二极管压降小于$V_{D-on}$。

⚠️ 反向电压不能击穿二极管。

* Two points
  * Role of $R_1$ in the original circuit?_ ![Pratical Diode Circuits 5](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%205.jpg) _**Fundamental reason for the exist of $R\_1$**: If voltage is 0, the current thru the component is 0. And the resistance is a finite value. If the there is no resistor, the value of the $V_{out}$ is undefined.
  * Can we plot _input-output characteristic_ for the rectifier with capacitor? For a circuit that have a **storage element**. It's too _complicated_ and _useless_ . What we are interested is the time response For a capacitor, $I = C{d\_v \over d\_t}$, so the current is depend both on voltage and time.

**Half-Wave Rectifier with Cap and Load \(实际状态\)**

![Pratical Diode Circuits 6](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%206.jpg)

如果波纹很小，那么衰减时间大约是输入电压的周期。

**Value of Ripple Amplitude**

![Pratical Diode Circuits 7](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%207.jpg)

#### Full-Wave Rectifier

**Observation**

![Pratical Diode Circuits 8](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%208.jpg)

* If $S_1$ and $S\_2$ are on $\Rightarrow V_{out} = V\_{in}$ 
* If $S_3$ and $S\_4$ are on $\Rightarrow V_{out} = V\_{in}$

**FWR**

![Pratical Diode Circuits 9](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%209.jpg)

**FWR with Cap**

![Pratical Diode Circuits 10](http://pcih4qs1o.bkt.clouddn.com/Pratical%20Diode%20Circuits%2010.jpg)

**Value of Ripple Amplitude :**

* HWR : $ \over {R_1 C\_1}} \cdot T_{in}$
* FWR : $ \over {R_1 C\_1}} \cdot {T_{in} \over 2}$


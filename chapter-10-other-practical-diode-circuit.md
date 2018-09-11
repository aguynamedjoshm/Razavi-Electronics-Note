# Chapter 10 - Other practical diode circuit

### Limiting Circuits

![Other Pratical Diode Circuits 1](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%201.jpg)

### Voltage Doubler/ Multiplier

#### Application

[RFID（Radio Frequency IDentification） - 射频识别](https://zh.wikipedia.org/wiki/射频识别)

Interesting Challenge in RFID Design: How to power up the RFID chip before it works.

**RFID System**

![Other Practical Diode Circuits 2](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%202.jpg)

A rectifier is not enough to drive a chip\(the voltage is too low\), so we replace it by a "**Voltage Multiplier**"

#### Observations

1. To charge a cap, you need to place "$+$" charge on one side and "$-$" charge one the other.
2. "$V\_{out}$" would not change because no current flow thru the output side. ![Other Practical Diode Circuits 3](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%203.jpg)
3. 非线性元件的阻抗分压 ![Other Practical Diode Circuits 4](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%204.jpg)
4. 讨论：当输入电压从峰值$V\_0$下降时，电容右端电压（即输出电压正极）如何变化？
   * 显然电压不能升高，那么还剩下“不变” 和 “降低”两种状态。
   * 若电压不变，电容左端电压降低，那么电流从左至右流过电容，即电流要从二极管阳极流向阴极，而这显然不成立
   * 因此，电压降低，呈“跟随状态”。

     ![Other Practical Diode Circuits 5](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%205.jpg)
5. 类似的，当电压从“$-V\_0$”上升时，此时电容右端积聚了正电荷，电流有通过二极管阳级流向阴极的“趋势“，二极管被关闭。 ![Other Practical Diode Circuits 6](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%206.jpg)
6. Voltage Doubler: 类似之前的分析过程，每个波峰之前，循环理想”二极管模型“ _导通短路_ 和 _截止开路_ 的变化过程。 ![Other Practical Diode Circuits 7](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%207.jpg)

### Level Shifter

通过电流源来保证二极管始终处于导通状态，因此二极管上一定有"$V_{D-on}$"的压降。$V_{D-on}$为电路输入电压和输出电压的差值 -- 即电平偏移值 ![Other Practical Diode Circuits 8](http://pcih4qs1o.bkt.clouddn.com/Other%20Pratical%20Diode%20Circuits%208.jpg)


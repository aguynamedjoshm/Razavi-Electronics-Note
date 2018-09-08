# Chapter 3 - Drift \(漂移\)

A carrier transport mechanism

### Definition :

current conduction due to electric field \( $$E$$ \)

* 在半导体两端施加电压，产生电场，使其中的载流子发生定向移动，产生电流。
* 载流子有一个峰值速度（类似于降落伞的速度变化）

> 要想找出 $$U$$ 和 $$I$$ 的关系, 我们要探究硅晶体的 $$R$$ 是怎么得到的。

![Drift Model 1](http://pcih4qs1o.bkt.clouddn.com/Drift%20Model%201.jpg)

$$V=I \cdot R$$ $$R=\rho{L \over A}$$

> \($$\rho$$ 是电阻率\)

Velocity of electrons : $$V$$

$$V \propto E$$

$$V = \mu_n \cdot E$$

### Observation :

![Drift Model 2](http://pcih4qs1o.bkt.clouddn.com/Drift%20Model%202-2.jpg)

Electric field : $$E = {V_B \over L}$$

> 我们**定义**在单位时间内流经硅晶体横截面积的电荷总量为“Total Charge”，其值为电流的大小

**Total Charge** =  $$VWh \cdot nq$$  =  $$|I|$$  =  $$ \mu_n {V_B \over L} \cdot Wh \cdot nq$$

So,

$$R = {L \over \mu_n Whnq} = {1 \over \mu_n nq} \cdot {L \over A}$$

> 对比公式 ： $$R=\rho{L \over A}$$
>
> \(**If its majority carrier are electrons**\) We can find that ：电阻率 $$\rho$$ 是 $${1 \over \mu_n nq}$$

### Current Density $$J_n$$ \(For electrons\)

$$J_n = \mu_n E nq$$

> Current density $$J_n$$ = $$I \over S$$ 
>
> $$|I|$$ = $$ \mu_n {V_B \over L} \cdot Wh \cdot nq$$
>
>  $$S = Wh$$

$$J_n = \mu_n {V_B \over L} nq$$

### Total current density $$J$$

> Both electrons and holes have current density 在电场中，带正电的空穴顺电场方向移动，带负电的电子逆电场方向移动，两者形成的电流方向相同，叠加。

$$J = ( \mu_n nq + \mu_p nq) \cdot E$$

> $$\mu_n \Rightarrow$$ electron mobility $$\approx$$ 1350 $$cm^2 / V \cdot S $$
>
>  $$\mu_p \Rightarrow$$ electron mobility $$\approx$$ 400 $$cm^3 / V \cdot S$$

That's the general equation for the "**Drift Current**" .


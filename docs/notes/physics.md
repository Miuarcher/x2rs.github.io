# 大物补天

## 8 平衡态

### 8.1 平衡态

无外界影响，宏观量保持不变，动态平衡

没有宏观量的流

热平衡，热力学第零定律

### 理想气体状态方程

$$
pV=\nu RT
$$

玻尔兹曼常数

$$
k_B=\frac{R}{N_A}=1.38 \times 10^{-23}J/K
$$

所以

$$
pV=\nu k_B N_A T=Nk_BT
$$

$N$ 为总分子数

$$
p=\frac{N}{V} k_B T = n k_B T
$$

$n$ 为单位体积内的分子数

### 对大量分子组成的气体系统的统计假设

（1）气体处在平衡态时，分子在容器中的空间分布，平均来说是均匀的 （不考虑重力影响）

$$
n = \frac{dN}{dV}=\frac{N}{V}
$$

dV——体积元
（宏观小，微观大）
“非常大的小”

dN, dV 宏观小，微观大

dN, dV 不是无穷小

### 理想气体速度分布各向同性(isotropic)

$$\overline{v_x^2}=\overline{v_y^2}=\overline{v_z^2}=\frac{1}{3} \overline{v^2}$$

气体在平衡态时，具有相同速率的分子向各个方向运动的平均分子数是相同的（速度分布的各向同性）若定义

$$
\overline{v_x}=\frac{\sum_i v_{xi}}{N}
$$

$$
\overline{v_x^2}=\frac{\sum_i v_{xi}^2}{N}
$$

则显然有

$$
\overline{v_x}=\overline{v_y}=\overline{v_z}=0
$$

$$
\overline{v_x^2}=\overline{v_y^2}=\overline{v_z^2}=\frac{1}{3}\overline{v^2}
$$

因为

$$
\overline{v^2}=\overline{v_x^2}+\overline{v_y^2}+\overline{v_z^2}
$$

设第 $i$ 组分子的速度在 $\overline{v_i}\sim\overline{v_i}+\mathrm d \overline{v_i}$ 区间内，以 $n_i$ 表示单位体积内第 $i$ 组分子的数量。$m$：分子质量，$n=\sum n_i$

一次碰撞分子动量变化 $2mv_{ix}$，完全弹性碰撞，在 $\mathrm d t$ 时间内与 $\mathrm d A$ 碰撞的分子数 $n_i \underbrace{v_{ix}\mathrm d t}_{能碰到容器壁对应的距离}\underbrace{\mathrm d S}_{面元}$。

他们给容器壁的总冲量：
$$
2mn_iv_{ix}^2 \mathrm d t\mathrm d S
$$
考虑不同速度分子，一半朝左一半朝右，朝左碰右壁，朝右碰左壁：
$$
\mathrm d I=\sum_{i,v_{ix}>0 朝左} 2mn_i v_{ix}^2 \mathrm d t\mathrm d S=\sum_i m n_iv_{ix}^2 \mathrm d t\mathrm d S
$$
得到
$$
p=\frac{\mathrm d F}{\mathrm d S}=\frac{\mathrm d I/\mathrm d t}{\mathrm d S}=\sum_i mn_iv_{ix}^2 =nm\frac{\sum_i n_i v_{xi}^2}{\underbrace{\sum_i n_i}_{n}}=nm\overline{v_x^2}=\frac{1}{3}nm\overline{v^2}
$$
代入平均分子动能 $\overline{\varepsilon _t}=\frac{1}{2}m\overline{v^2}$，得到 $p=\frac{2}{3}n\overline{\varepsilon_t}$。

代入 $p=nk_B T$，结论 $\overline{\varepsilon_t}=\frac{3}{2}k_B T$， 温度标志着物体内部分子热运动的剧烈程度，它是大量分子热运动的平均平动动能 $\overline{\varepsilon_t}$ 的统计平均值的量度。

均方根速率：$\overline{\varepsilon_t}=\frac{1}{2}m\overline{v^2}=\frac{3}{2}k_B T$，得到

$$
\sqrt{\overline{v^2}}=\sqrt{\frac{3k_B T}{m}}\overset{\times N_A}{=}\sqrt{\frac{3RT}{M}}
$$

## 道尔顿分压定理
$$
n=\sum_i n_i\\
p=\sum \frac{2}{3} n_i \overline{\varepsilon_i}=\frac{2}{3} \sum_i n_i \overline{\varepsilon}=k_B T\sum_i n_i=\sum_i p_i
$$
混合气体的压强等于各气体的分压之和。

## 速率分布函数

阿巴阿巴阿巴

阿巴阿巴阿巴

阿巴阿巴阿巴

阿巴阿巴阿巴

阿巴阿巴阿巴

不会！

我觉得就是概统的概率密度吧qwq

## 速度分布函数

速度范围：

$$
v_x \to v_x+dv_x
$$

$$
v_y \to v_y+dv_y
$$

$$
v_z \to v_z+dv_z
$$

设取在该速度范围的分子数为dN，则速度分布函数定义为

$$
F(v_x,v_y,v_z)=\frac{1}{N}\frac{dN}{dv_xdv_ydv_z}
$$

### 麦克斯韦速度分布函数

麦克斯韦证明了，处于平衡态的理想气体系统，满足：

$$
F(v_x,v_y,v_z)=(\frac{m}{2\pi k_B T})^{\frac{3}{2}}e^{\frac{m}{2k_B T}(v_x^2+v_y^2+v_z^2)}
$$

### 麦克斯韦速率分布函数

$$
f(v)=4\pi(\frac{m}{2\pi k_B T})^{\frac{3}{2}}e^{\frac{m}{2k_B T}v^2}v^2
$$

证明：利用速度分布律可以导出速率分布律

分子速率处于$v$和$v+dv$间的几率是分子速度矢量端点落在以$v$和$v+dv$为内外半径球壳内的几率。

$$
f(v)dv = F(v_x,v_y,v_z) \cdot 4 \pi v^2 dv
$$

*我感觉就是表面积*

**注意到**，令

$$
\frac{k_B T}{m} = \sigma^2
$$

即

$$
\frac{m}{k_B T} = \frac{1}{\sigma^2}
$$

则上面两个分布函数变为：

$$
F(v_x,v_y,v_z)=(\frac{1}{2\pi \sigma^2})^{\frac{3}{2}}e^{\frac{1}{2 \sigma^2}(v_x^2+v_y^2+v_z^2)}
$$

$$
f(v)=4\pi(\frac{1}{2\pi \sigma^2})^{\frac{3}{2}}e^{\frac{1}{2 \sigma^2}v^2}v^2
$$


芝士正态分布！！！！！$\sigma$是速度分量的标准差！！！

### 三个重要的速率

最可几速率
$$
v_p=\sqrt{\frac{2k_B T}{m}}=\sqrt{2}\sigma
$$

平均速率
$$
\overline{v}=\sqrt{\frac{8k_B T}{\pi m}}=\sqrt{\frac{8}{\pi}}\sigma
$$

均方根速率
$$
\sqrt{\overline{v^2}}=\sqrt{\frac{3k_B T}{m}}=\sqrt{3}\sigma
$$

### 分子的速率分布律实验验证 泄流

思考，在容器壁上开一个小孔，从小孔里面泄流出来的气体分子的速率分布能不能代表容器内部的气体分子速率分布。答案是不能，因为气体分子速率越大，从小孔泄出的概率越高，通过下面的推导，我们能够验证泄流速率和速度分布有以下关系：$f_e(v) \propto vf(v)$.

碰壁频率：**单位时间内撞到单位面积上的分子数**，以 $\Gamma$ 表示。

计算得到碰壁频率为：
$$
\Gamma=n \frac{1}{4}\left(\frac{8k_B T}{\pi m}\right)^{1/2}=\frac{1}{4}n\overline{v}
$$

如果从数密度 $n$ 的容器向真空泄流，写成微分方程的形式，其中 $S$ 为小孔的面积：
$$
\frac{\mathrm{d} N}{\mathrm{d} t}=-\frac{1}{4}n \overline{v}S
$$
用麦克斯韦速率分布律可以将碰壁频率表示为：
$$
\Gamma=\frac{1}{4}n \underbrace{\int_0^\infin vf(v)\mathrm d v}_{\overline{v}}\equiv \int_0^\infin \gamma(v)\mathrm d v
$$

其中 $\displaystyle \gamma (v)=\frac{1}{4}nv f(v)$，物理意义为**单位时间，从小孔单位面积上射出的在速率 $\boldsymbol  v$ 附近单位速率间隔内的分子数**。

泄流速率分布函数是指**分子束中速率在 $\boldsymbol v$ 附近单位速率间隔内的分子数占总泄流分子数的比率**，也就是代表了泄流气体分子速率的分布函数，由归一化，得到：
$$
f_e(v)=\frac{\gamma(v)}{\Gamma}=\frac{\frac{1}{4} nv f(v)}{\frac{1}{4} n\overline{v}}=\frac{v}{\overline{v}} f(v)=\frac{1}{2}\left(\frac{m}{k_B T}\right)^2 e^{-\frac{m}{2k_B T}v^2}v^3
$$

可见：$f_e(v) \propto vf(v)$.

---------

理想气体，温度 $T$，求气体分子按平动动能的分布律 $f(\varepsilon) \ (\varepsilon=\frac{1}{2}\mu v^2)$ 并求最可几速率。

需要把 $f(v)$ 变成 $f(\varepsilon)$，满足在 $v$ 附近，$\varepsilon=\frac{1}{2}mv^2$ 附近：
$$
f(v)\mathrm d v=f(\varepsilon)\mathrm d \varepsilon=\frac{\mathrm d N}{N}
$$
代入 $v^2=2\varepsilon/m$，$\displaystyle \mathrm d v=\frac{\mathrm d \varepsilon}{\sqrt{2\mu \varepsilon}}$.
$$
f(\varepsilon)=4\pi \left(\frac{\mu}{2\pi kT}\right)^{3/2} e^{-\mu v^2/(2kT)} v^2 \frac{1}{\sqrt{2\mu \varepsilon}}=\frac{2}{\sqrt{\pi}} \left(\frac{1}{kT}\right)^{3/2} \varepsilon ^{1/2} e^{-\varepsilon/(kT)}
$$

### 玻尔兹曼能量分布

问题：在重力场的作用下，如何求 $h\to h+\Delta h$ 范围内的分子数。

**玻尔兹曼能量分布**：

如果分子的势能相同，由麦克斯韦速度分布函数：
$$
\mathrm{d} N=NF(v_x,v_y,v_z)\mathrm{d}^3\boldsymbol v=N\left(\frac{m}{2\pi k_BT}\right)^{3/2} e^{-\frac{m}{2kT}\left(v_x^2+v_y^2+v_z^2\right)}\mathrm{d}^3 \boldsymbol v\propto e^{-\varepsilon_k/(k_B T)}
$$
如果气体系统处于外场（如重力场中），每个分子的能量 $\varepsilon=\varepsilon_k+\varepsilon_p$.

可以推出同时处在六个间隔 $\boldsymbol v \to \boldsymbol v +\mathrm d ^3 \boldsymbol v,
\boldsymbol r \to \boldsymbol r +\mathrm d ^3 \boldsymbol r$ 的分子几率和指数函数成正比，也就是
$$
\boxed{\mathrm{d} N\propto{\large{e}}^{-\dfrac{\varepsilon_k+\varepsilon_p}{kT}}={\large{e}}^{-\dfrac{\varepsilon}{kT}}}
$$
（体现了能量越小，几率越大）

设归一化因子 $C$，则处于这个区间内的分子数：
$$
\mathrm d N=C e^\frac{-\varepsilon}{kT}\mathrm d^3 \boldsymbol v\mathrm d^3 \boldsymbol r
$$
写成：
$$
\mathrm{d} N=n_0\left(\frac{m}{2\pi k_B T}\right)^{3/2}e^{-\frac{\varepsilon_k+\varepsilon_p}{kT}}\mathrm d^3 \boldsymbol v\mathrm d^3 \boldsymbol r=n_0 e^{-\frac{\varepsilon_p}{kT}}F(\boldsymbol v)\mathrm{d}^3 \boldsymbol v\mathrm{d}^3 \boldsymbol r
$$
其中 $n_0$ 是待定常数。

则处在空间体积元 $\mathrm{d} x\mathrm{d} y\mathrm{d} z$ 内的分子数为：
$$
\mathrm{d} N'=n_0 e^{-\frac{\varepsilon_p}{kT}} \mathrm{d}^3 \boldsymbol r \iiint F(\boldsymbol v)\mathrm{d}^3 \boldsymbol v=n_0 e^{-\frac{\varepsilon_p}{kT}}\mathrm{d}^3 \boldsymbol r 
$$
因此在 $x,y,z$ 附近分子的数密度为：
$$
\boxed{n=\frac{\mathrm{d} N'}{\mathrm{d}^3 \boldsymbol r}=n_0 e^{-\varepsilon_p/kT}}
$$
其中 $n_0$ 代表 $\varepsilon_p=0$ 处单位体积内具有各种速度的分子总数。称为**玻尔兹曼分布律**。

重力场中 $\varepsilon_p=mgz$，则
$$
n=n_0 e^{-mgz/kT}
$$

$$
P=nkT=n_0 kT e^{-mgz/kT}=P_0 e^{-mgz/kT}
$$

$$
z=\frac{kT}{mg}\ln P_0/P
$$

知道了地面的气体压强和待测高度的气体压强，可以测出高度。

------

稳定大气温度 $T$，以地面为重力势能零点，试证明大气分子 $\overline{E_p}=kT$.

取截面积为 $\mathrm d S$，高度为 $\mathrm d z$ 的小体积。
$$
\overline{E_p}=\frac{\iint mgz \cdot n_0 e^{-mgz/kT}\mathrm d S\mathrm d z}{\iint n_0 e ^{-mgz/kT}\mathrm d S\mathrm d z}
$$

----------

分子原子在能级上的分布也遵守玻尔兹曼定律：$\displaystyle N_i \propto e^{-\frac{E_i}{kT}}$

一般假定 $N_i=Ce^{-\frac{E_i}{kT}}$，然后根据 $\displaystyle \sum N_i=N$ 求出 $C$.

-------

系统有4000个粒子,能级0,E,2E,初始,三能粒子数分别为2000,1700,300,问是否是平衡态？ 平衡态下应如何分布?

1. 系统分子数 $\displaystyle C\left(1+e^{-\frac{E}{kT}}+e^{-\frac{2E}{kT}}\right)=4000$
2. 系统能量守恒 $Ce^{-\frac{0}{kT}}\cdot 0+Ce^{-\frac{E}{kT}}\cdot E+Ce^{-\frac{2E}{kT}}\cdot 2E=2000\cdot 0+1700\cdot E+300\cdot 2E=2300E$.

### 能量均分定理

自由度：决定某物体在空间的位置所需要的独立坐标数。

- **单原子分子** $t=3,r=0,s=0$ 三个自由度。
- **双原子分子（刚性）** $t=3,r=2,s=0$ 五个自由度。
- **多原子分子（刚性）** $t=3,r=3,s=0$ 六个自由度。
- **双原子分子（非刚性）** $t=3,r=2,s=1$ 七个自由度。
- **多原子分子（非刚性）** $s=3n-6,t=3,r=3$.

**能量均分定理（Equipartition Theorem）**

在温度为 $T$ 的平衡态下，物质分子的每一个自由度都具有相同的平均动能，其大小都等于 $k_BT/2$，<u>对每一振动自由度还有 $k_B T/2$ 的平均势能</u>。

设平动自由度 $t$，转动自由度 $r$，振动自由度 $s$，则 **一个分子** 的平均能量：
$$
\overline{E}=(t+r+2s)\frac{1}{2}kT=\frac{i}{2}kT
$$
**理想气体内能**
$$
E=E_k (对应 t+r+s)+E_{pa}(对应s)+E_{pm}(理想气体无分子间势能)
$$
$\displaystyle \frac{3}{2}kT$ 是一个分子的平均动能。

对于 $\nu \mathrm{~mol}$ 气体，得到
$$
E=N\left(\frac{i}{2}kT\right)=\nu  N_A\left(\frac{i}{2}kT\right)=\nu \left(\frac{i}{2}RT\right)=\frac{i}{2}PV
$$
因此：
$$
\boxed{E=\frac{i}{2}PV}
$$
理想气体的内能只能是温度的函数。

----

绝热容器被绝热板分隔为 $A,B$ 两部分，两部分的体积、压强相等，均为 $P_0,V_0$，$A$ 内储存 $1\mathrm{~mol}$ 单原子理想气体，$B$ 内储存 $2\mathrm{~mol}$ 双原子理想气体。

求

1. 内能 $E_A,E_B$。

   $\displaystyle  E_A=1\cdot \frac{3}{2}RT_A=\frac{3}{2}P_0V_0$

   $\displaystyle E_B=2\cdot \frac{5}{2}RT_B=\frac{5}{2}P_0V_0$.

2. 抽出绝热板，两种气体混合后处于平衡时的温度。

   混合气体能量守恒，也就是：
   $$
   E_A+E_B=1\cdot \frac{3}{2}RT+2\cdot \frac{5}{2}RT=\frac{13}{2}RT
   $$

   $$
   T=\frac{8 P_0V_0}{13 R}
   $$

----------

容器内贮有质量为 $m$ 摩尔质量为 $M$ 的理想气体， 设容器以速度 $u$ 作定向运动，今使容器突然停止，问： 

1. 定向运动机械能转化为什么形式的能量？转化为无规则热运动的动能。

2. 分子速度平方的平均值增加多少？（单原子、双原子）

   对于单原子分子，容器动能全部转化为分子的平动动能，因此
   $$
   \frac{1}{2}mu^2= \Delta \left(\frac{m}{M} N_A  \frac{3}{2} k_BT\right)=\Delta \left(\frac{m}{M} N_A \overline{\varepsilon_t}\right)=\Delta \left(\frac{m}{M} N_A \frac{1}{2} \frac{M}{N_A} \overline{v^2}\right)
   $$
   $u^2=\Delta \overline{v^2}$.

   对于双原子分子，还有一部分能量转化为分子的转动动能。
   $$
   \frac{1}{2}mu^2= \Delta \left(\frac{m}{M} N_A  \frac{5}{2} k_BT\right)=\Delta \left(\frac{m}{M} N_A \frac{5}{3}\overline{\varepsilon_t}\right)=\Delta \left(\frac{m}{M} N_A \frac{5}{6} \frac{M}{N_A} \overline{v^2}\right)
   $$
   因此 $\Delta \overline{v^2}=\frac{3}{5}u^2$

# References

[kumikosjtu.github.io](https://kumikosjtu.github.io/%E5%A4%A7%E5%AD%A6%E7%89%A9%E7%90%86/Ch8-%E5%88%86%E5%AD%90%E5%8A%A8%E7%90%86%E8%AE%BA.html)
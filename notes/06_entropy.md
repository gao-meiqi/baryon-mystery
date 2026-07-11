
#### 印象里 entropy 就只是log(g) 
- 热力学熵来自我们不知道系统处于哪个微观态, 纠缠熵来自即使整个系统是纯态，只观察一部分时，也会因为与另一部分纠缠而失去信息??
- 熵是系统微观状态数的度量
- 描述一个概率分布的信息量 概率分布? 
----
- 但是热统里似乎 也会有量子统计
- how comes? 
- [请到thermal那里寻找答案0.0]

#### entropy
- 1932, von Neumann entropy 可观测量? observable 应该是 Hermitian operator
> 和经典一样 还是态的性质 只不过系统状态由密度矩阵\rho表示
- 请注意 
1.波函数不够
2.来到了纯态 混合态

----
而我们能得到的只有observable的期望值
- density matrix
- 对所有可测量信息的压缩
- Tr(ρO)=实验值
> observable 决定了 density matrix
- gauge: 先决定哪些observable参与定义ρV, algebra
> density matrix 依赖于 observable algebra

#### with gauge theory 
- Hilbert space能够分解吗
- 先决定哪些observable参与定义ρV, algebra
- 这种满足加法、乘法、共轭封闭的集合，在数学上就叫 operator algebra
> density matrix: for all observables in the algebra
- 普通自由标量场，这个代数几乎是唯一的，所以你感觉不到它的存在；而在 gauge theory 中，它突然变得不唯一，于是这层原本隐藏的结构就暴露出来了


#### with Renormalization Group 
- 经典 Ising 
- 量子系统 
- 粗粒化
- 怎么粗粒化?? 粗粒化什么?? 

> 粗粒化的对象选中了纠缠熵
> 经典RG：不断平均spin。
> 量子RG：不断减少纠缠。
- 1992 Steven White, Density Matrix Renormalization Group
- disentangler 去掉短程纠缠

> Entanglement is the organizing principle of quantum matter
- 它不是一个一次测量就能得到的物理量
- 状态（state）的几何量
- 你需要很多很多完全一样的系统，重构 density matrix
- 它反映了 信息结构的性质
- 1961, Rényi; 2009, H.Casini, QFT
- 纠缠熵是对子系统之间纠缠度的量化，也可以理解为量子层面上对不确定性的一种量化，或者说是对系统所缺失信息的一种量化

> 为什么经典RG是在平均spin 或者说 怎么理解 经典RG我之前学的[铁磁或者说所有RG都在这个语境下变成经典RG了吗]


#### long-range correlation

- 凝聚态的人特别喜欢拿纠缠熵找 critical point

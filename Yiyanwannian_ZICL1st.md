---
timezone: Asia/Shanghai
---

> 请在上边的 timezone 添加你的当地时区，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区
> 时区请参考以下列表，请移除 # 以后的内容

timezone: Pacific/Honolulu # 夏威夷-阿留申标准时间 (UTC-10)

timezone: America/Anchorage # 阿拉斯加标准时间 (UTC-9)

timezone: America/Los_Angeles # 太平洋标准时间 (UTC-8)

timezone: America/Denver # 山地标准时间 (UTC-7)

timezone: America/Chicago # 中部标准时间 (UTC-6)

timezone: America/New_York # 东部标准时间 (UTC-5)

timezone: America/Halifax # 大西洋标准时间 (UTC-4)

timezone: America/St_Johns # 纽芬兰标准时间 (UTC-3:30)

timezone: America/Sao_Paulo # 巴西利亚时间 (UTC-3)

timezone: Atlantic/Azores # 亚速尔群岛时间 (UTC-1)

timezone: Europe/London # 格林威治标准时间 (UTC+0)

timezone: Europe/Berlin # 中欧标准时间 (UTC+1)

timezone: Europe/Helsinki # 东欧标准时间 (UTC+2)

timezone: Europe/Moscow # 莫斯科标准时间 (UTC+3)

timezone: Asia/Dubai # 海湾标准时间 (UTC+4)

timezone: Asia/Kolkata # 印度标准时间 (UTC+5:30)

timezone: Asia/Dhaka # 孟加拉国标准时间 (UTC+6)

timezone: Asia/Bangkok # 中南半岛时间 (UTC+7)

timezone: Asia/Shanghai # 中国标准时间 (UTC+8)

timezone: Asia/Tokyo # 日本标准时间 (UTC+9)

timezone: Australia/Sydney # 澳大利亚东部标准时间 (UTC+10)

timezone: Pacific/Auckland # 新西兰标准时间 (UTC+12)

# ZK 残酷共学第 1 期残酷指引

> ⚠️ 正式开始前请确保你在身体上和精神上都处于合适的状态，请刻意练习，残酷面对 🆒。为方便检索 The First ZK Intensive CoLearning 简写为 ZICL1st，第 2 期即为ZICL2nd，第 3 期即为 ZICL3rd，以此类推。

> ⚠️ 报名需要按要求认真填写下面 [ XXX ] 部分，方可通过报名审核，通过审核即可开始自主学习。

## 共学内容

第一期的重点是向大家介绍什么是 ZK、 ZKP 的基础知识，以及 Circom 代码入门，有一定难度，共学资料如下：

- 第一周：7 月 29 日 - 8 月 4 日：Introduction and History of ZKP
    - 20min 的视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
    - 70min 的播客：[零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
    - [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
    - [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
    - [（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
    - 100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
- 第二周：8 月 5 日 - 8 月 11 日：Overview of Modern SNARK Constructions
    - 80min的视频： [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
    - [1-Polynomial-Interaction-and-Proof](https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html)
    - [2-Non-interactivity&Distributed-Setup](https://learn.z2o-k7e.world/zk-snarks/2-Non-interactivity&Distributed-Setup.html)
    - [3-General-Purpose-Computation](https://learn.z2o-k7e.world/zk-snarks/3-General-Purpose-Computation.html)
    - [4-Construction-Properties.md](https://learn.z2o-k7e.world/zk-snarks/4-Construction-Properties.html)
    - [5-Pinocchio-Protocol](https://learn.z2o-k7e.world/zk-snarks/5-Pinocchio-Protocol.html)
- 第三周：8 月 12 日 - 8 月 18 日：Write some Circom
    - 基础电路：
        - [ZK Shanghai 基础电路教学](https://www.youtube.com/watch?v=CTJ1JkYLiyw&ab_channel=SutuLabs)
        - 编辑器：[zkREPL](https://zkrepl.dev/)
        - [基础电路练习](https://github.com/wenjin1997/zkshanghai-workshop/blob/main/lecture2-homework.md) 这部分材料结合了Circom源码，可以多花时间来研究
    - 实用电路：
        - [ZK Shanghai 实用电路教学](https://www.youtube.com/watch?v=smJz5RdY0Nc)
        - 课程资源：[snarkjs resources (zkiap.com)](https://zkiap.com/snarkjs)、[What Is Semaphore? | Semaphore](https://docs.semaphore.pse.dev/)

本次共学资料前两周的 lecture 来自 [zk-learning](https://zk-learning.org/)，博客来自 [《探索零知识证明系列》](https://learn.z2o-k7e.world/zkp-intro/toc.html)和[《从零开始学习 zk-SNARK》](https://learn.z2o-k7e.world/zk-snarks/toc.html)，第三周的 Circom 部分来自 [0xparc](https://zkiap.com/)，视频讲解为 [ZK Shanghai](https://zkshanghai.xyz/) 的中文版本。郭宇老师还推荐了这篇文章[《Survey-SNARKs》](https://www.di.ens.fr/~nitulesc/files/Survey-SNARKs.pdf)，学有余力者可以依此找到更多的扩展内容。

### **最后，非常感谢安比实验室郭宇老师对于本次共学资料选择的指导！**

---

# {Punkcan}
1. 自我介绍
	1. web3 btc l2 developer。
2. 你认为你会完成本次残酷学习吗？
	1. 尝试尽力吧
3. 目前阶段对于 ZK 的了解？
	1. 还在理解公式中

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：
  - 观看youtube视频: [初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
- 学习内容小结：
  - 理解zk的本质是一个P = NP 的问题，zk是一个证明系统，可以证明一个事情是正确的，但是不会泄露任何信息。

### 2024.07.30

- 学习主题：
    - 听播客: [零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
- 学习内容小结：
    - 理解zk-SNARK 和 zk-STARK的不同
    - 理解rollup的原理, optimistic rollup 和 zk rollup的区别
    - 理解optimistic rollup的安全性问题，为什么要引入 federation, 多签和预签机制

### 2024.07.31

- 学习主题：
    - 看视频: [ZKP Lecture 1: Introduction and History of ZKP](`https://www.youtube.com/watch?v=uchjTIlPzFo`)
- 学习内容小结：
    - 以硬币和三色国土为例，理解零知识证明的概念
    - 讲解了零知识证明的历史，本人理解不是很深，还需后续学习

### 2024.08.01

- 学习主题：
    - 看文档: [探索零知识证明系列](https://learn.z2o-k7e.world/zkp-intro/toc.html)
- 学习内容小结：
  - 阅读： 探索零知识证明系列
  - 通过 地图三染色问题的零知识证明、阿里巴巴洞穴、模拟与图灵机、柏拉图的洞穴寓言 等例子介绍「模拟」


### 2024.08.02

- 学习主题：
  - 看文档: [寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E5%AF%BB%E6%89%BE%E7%9F%A5%E8%AF%86)
  - 看文档: [证明零知识](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E8%AF%81%E6%98%8E%E9%9B%B6%E7%9F%A5%E8%AF%86)
- 学习内容小结：
  - 零知识证明性质： Completeness（完备性）、Soundness（可靠性）、Zero-Knowledge（零知识）
  - Schnorr协议公式： z*G ?= R + c*PK = rG + c*(aG)

### 2024.08.03

- 学习主题：
  - 看文档: [证明零知识](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E8%AF%81%E6%98%8E%E9%9B%B6%E7%9F%A5%E8%AF%86)
  - 学习内容小结：
    - 通过弱版本的协议SHVZK证明Schnorr的安全性
    - 「抽取器」需要利用「时间倒流」的超能力才能计算出Schnorr的签名私钥
    
### 2024.08.04

- 学习主题：
  - 看文档: [证明零知识](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E8%AF%81%E6%98%8E%E9%9B%B6%E7%9F%A5%E8%AF%86)
- 学习内容小结：
  - ecdsa和Schnorr算法类似
  - ecdsa和Schnorr算法都存在的缺点：两次签名中使用同一个随机数，那么签名者的私钥将会暴露出来，计算公式
      ```shell
      k = (c - c')/(s - s')
      a = (k * s - c)/e
      ```
  - 随机数必须是具有密码学安全强度的随机数，否则会导致私钥泄露
  - 作者脑洞我们生活是否在模拟世界中生存


### 2024.08.05

- 学习主题：
  - 看视频:  [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
- 学习内容小结：
  - 讲解zk-SNARK和Blockchain的结合方式：链下存储全量交易，链上验证少量交易
  - 用sony相机照片（C2PA）的例子举例说明zk-SNARK在非区块链行业的应用场景
  - 讲解NARK,zk-SNARK，（不是很懂）
  - 讲解Ploy-IOP、Multilinear-IOP、Vector-IOP, (不是很懂)


### 2024.08.06

- 学习主题：
  - 看文档:  [1-Polynomial-Interaction-and-Proof](https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html)
- 学习内容小结：
  - Schwatz-Zippel: 不可能找到共享连续段的两条不相等曲线，也就是任何多项式在任意点的计算结果都可以看做是其唯一身份的表示。也就是说只要能证明多项式上的某个随机点就可以证明这个多项式（只有在知道了多项式，才能算出这个点对于的值）
  - 利用因式的性质构造出了一个证明协议，但这个协议存在一些缺陷，主要是由于
    - 一旦 prover 知道了 t(r) ，他就可以反过来任意构造任何一个可以整除 t(r) 的 p(r)
    - prover 知道了点 (r,  t(r)⋅h(r)) 的值，就可以构造经过这一点的任意(高次)多项式，同样满足校验
    - 协议并没有对 prover 的多项式阶数(次数)进行约束
    - 同态加密
      - 通过模运算形成的集合被称为「有限域」，
      - 通过计算指数再进行模运算形成的集合构成「循环群」。
      - 常见的同态加密方式除了整数幂取模之外，还有椭圆曲线上的倍乘。
      - 公式：
      ```shell
      E(v) = g^v (mod n)
    
      # v 是想要加密的值
      # 模数 n 是双方都知道的, 它通常写在加密代码中
      # 生成元 g 是一个整数，作为一个基用来生成一系列的数字比如 g^v
      # g^v 通常称为密钥，用来对数据进行加密
    ```
  - 协议过程: 将v转换为多项式，重走一遍协议，这里由于公式不方便书写,附上链接：[协议过程](https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html#%E5%8D%8F%E8%AE%AE%E8%BF%87%E7%A8%8B)


### 2024.08.07

- 学习主题：
  - 看文档:  [2-Non-interactivity&Distributed-Setup](https://learn.z2o-k7e.world/zk-snarks/2-Non-interactivity&Distributed-Setup.html)
- 学习内容小结：
  - 简洁的非交互式多项式知识论证(zk-SNARKOP): [Succinct Non-Interactive Argument of Knowledge of Polynomial](https://learn.z2o-k7e.world/zk-snarks/2-Non-interactivity&Distributed-Setup.html#succinct-non-interactive-argument-of-knowledge-of-polynomial)
  - 解决交互到非交互问题：Pairing: Multiplication of Encrypted Values（配对：加密值的乘法）
  - Trusted Party Setup
    - CRS: Common Reference String
    - 一种解决办法就是由多个参与方使用前面小节中介绍的数学工具来生成一个组合式CRS，这样这些参与方就都不知道「秘密」
    - 为了多个参与者串谋或不诚实问题，可以额外再要求除了第一个以外的每一个参与者去加密然后公开他的参数
  - 文章小结：
    - 保证 prover 的证明是按照规则正确构造的 ——> KEA ( a′ = a^α (mod n)) )
    - 保证知识的零知性 ——> “无成本的” δ 变换
    - 可复用证明 ——> 非交互式
    - 非交互中如何设置安全公开且可复用的参数 ——> 参数加密，verifier 借助 pairing 进行验证
    - 保证参数的生成者不泄密 ——> MPC’s Setup



### 2024.08.08

- 学习主题：
  - 看文档:  [3-General-Purpose-Computation](https://learn.z2o-k7e.world/zk-snarks/3-General-Purpose-Computation.html)
- 学习内容小结：
  - 将要证明的程序转换为数学语言表达的形式（即加减乘除的计算）
    - 如: f(w,a,b)=w(a⋅b)+(1−w)(a+b)
    - 引入概念： 左操作数 运算操作 符右操作数 = 输出
  - 用多项式在某处的取值来进行计算以此表示数学计算，进而[进行证明](https://learn.z2o-k7e.world/zk-snarks/3-General-Purpose-Computation.html#single-variable-operand-polynomial)
  - 用多项式在多处的取值来进行计算表示多个数学运算，进而[加以证明](https://learn.z2o-k7e.world/zk-snarks/3-General-Purpose-Computation.html#multi-variable-operand-polynomial)
  - 对证明的“程序”在不同计算中使用的相同的变量进行约束

### 2024.08.09

- 学习主题：
  - 看文档: [4-Construction-Properties.md](https://learn.z2o-k7e.world/zk-snarks/4-Construction-Properties.html)
- 学习内容小结：
  - 通过插值计算和乘法，利用表达式： C_a * a +  C_b * b = C_r * r 来实现计算加减除
    - 加 (a+b)×1=r
    - 减 (a+−1⋅b)×1=r
    - 除 b×r=a
      - 多项式结构代表的运算，并非是为了计算出结果，而是在 prover已经知晓的变量赋值的情况下，检验这个运算的过程是否正确。换句话说，即约束 prover 必须提供一致的值，无论这些值是什么。
    - 最终 w(ab)+(1−w)(a+b)=v( w∈{0, 1} ) 用来表示加减乘除的计算
  - 保证操作数和输出的不可替代性
    - 使用其它的操作数中的可变多项式，即 L`(s)=o_1(s) + r_1(s) + r_1(s) + ...
    - 完全交换操作数多项式， 也就是把 O(s) 和 L(s) 换成 O(s)×R(s)=L(s)
    - 复用相同的操作数多项式，即 L(s)×L(s)=O(s)
  - 保证跨操作数的可变一致性
    - 在所有的操作数之间创造一个作为“变换的校验和”(shifted checksum) 的变量多项式(variable polynomial)
    - 创建一个包含了所有 variable 的 variable poly, 对这些所有的 variable 整体做 α-shift, 就一个都别跑都被约束住了) 那么就可以限制 P 使其只能够赋予(给每个变量)相同的值。 V 可以将这些每个变量的多项式加起来
  - 处理非延展性变量和变量一致性
    - 在 setup 阶段将 encrypted space中的 β_s 项与随机秘密值 γ (gamma) 相乘, 从而使 verification key 中加密的 β_s 与加密值 Z(s) 不兼容
  - 变量值一致性检查优化
    - Pinocchio 协议通过选择不同的生成元 g ，从而对每个 operand 实行“移位”


### 2024.08.10

- 学习主题：
  - 看文档: [5-Pinocchio-Protocol](https://learn.z2o-k7e.world/zk-snarks/5-Pinocchio-Protocol.html)
- 学习内容小结：
  - [zk-SNARK 协议最终流程](https://learn.z2o-k7e.world/zk-snarks/5-Pinocchio-Protocol.html#zk-snark-%E5%8D%8F%E8%AE%AE)
  - 允许证明计算的有效协议
    - 简明 (Succinctly) —— 独立于计算量，证明是恒定的，小尺寸的
    - 非交互性 (Non-interactive) —— 证明只要一经计算就可以在不直接与 prover 交互的前提下使任意数量的 verifier 确信
    - 可论证的知识 (with Argument of Knowledge) —— 对于陈述是正确的这点有不可忽略的概率，即无法构造假证据；并且 prover 知道正确陈述的对应值（即：证据），例如，如果陈述是 “B 是 sha256(a) 的结果” 那么就说明 prover 知道一些值 a 能够使得 B = sha256(a) 成立，因为 B 只能够通过 a 的知识计算出来，换句话说就是无法通过 B 来反算出 a（假定 a 的熵足够）。
    - 陈述有不可忽略的概率是正确的 (even@安比实验室: 这里指 Soundness 可靠性)，即，构造假证据是不可行的
    - 零知识 ( zero-knowledge) —— 很“难”从证明中提取任何知识，即，它与随机数无法区分。


### 2024.08.11

- 学习主题：
  - 看视频: [ZK Shanghai 基础电路教学](https://www.youtube.com/watch?v=CTJ1JkYLiyw&ab_channel=SutuLabs)
- 学习内容小结：
  - circom 代码演示
  - 课程网址： 
    - https://zkshanghai.xyz/syllabus.html
    - https://zkiap.com/
    - 课程PPT: https://zkshanghai.xyz/lecture/2-circom1.pdf
  - 算术电路
    - 有限域 𝔽 = {0, … , 𝑝 − 1} 基于某一素数𝑝 > 2
    - 算术电路 𝐶: 𝔽𝑛 ⇾ 𝔽
      - 是计算复杂性理论中的概念，与电子电路毫无关联
      - 有向无环图
      - 输入节点标记为1, 𝑥1, … , 𝑥𝑛
      - 内部节点标记为+,-,x
      - 每个内部节点也称为门(gate)
  - 常见代码转电路方式
    - 判零函数 let y = input > 0 ? 0 : 1;
    - 选择 let y = s ? (a + b) : (a * b);
    - 二进制化 5 -> 101
    - 比较 let y = s1 > s2 ? 1 : 0;
    - 循环 for (let i = 0; i < N; i++) { y += 1; }
    - 交换 
      ```shell
      if (s) {
         output1 = input2;
         output2 = input1;
       } else {
         output1 = input1;
         output2 = input2;
       }
       ```
    - 逻辑
      ```shell
       let y = a & b;
       let y = !a;
       let y = a | b;
       let y = a ^ b;
       ```
    - 排序： 如冒泡排序
  - 常见库介绍
    - snarkjs
    - [circom-starter](https://github.com/0xPARC/circom-starter)
    - hardhat circom

### 2024.08.12

- 学习主题：
  - 看视频: [ZK Shanghai 实用电路教学](https://www.youtube.com/watch?v=smJz5RdY0Nc)
- 学习内容小结：
  - 简单签名方案分3部分
    - KeyGen → (sk, pk): 选择一个随机密钥 sk 和对应的公钥 pk
    - Sign(m, sk) → s: 给定消息 m 和密钥 sk，输出签名 s
    - Verify(m, s, pk) → 1/0: 给定消息 m、签名 s 和公钥 pk，验证签名是否有效
    - circom 签名代码演示
  - 群里面的成员非常多并且数量可变时，引入merkle tree解决
  - 哈希计算安全特性
    - 抗第一原像攻击
    - 抗第二原像攻击
    - 抗碰撞
  - 不同的哈希函数对不同的电路友好性不一样
  - 课程PPT: https://zkshanghai.xyz/lecture/4-circom2.pdf

### 2024.08.13

- 学习主题：
  - 阅读文档: 
    - [snarkjs resources (zkiap.com)](https://zkiap.com/snarkjs)
    - [What Is Semaphore? | Semaphore](https://docs.semaphore.pse.dev/)
- 学习内容小结：
  - snarkjs 代码转电路的js库
  - Semaphore 一种zk协议，可以用来构建zk应用：私人投票、举报、匿名去中心化自治组织和混合器等


<!-- Content_END -->

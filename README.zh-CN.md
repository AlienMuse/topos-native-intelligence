<p align="center">
  <a href="https://doi.org/10.5281/zenodo.23538544"><img src="assets/hero.svg" alt="GM-Omega-Infinity: Topos-Native Intelligence — 五卷与一个子对象分类子的 D6 拓扑斯蜂巢" width="100%"></a>
</p>

<p align="center">
  <a href="https://doi.org/10.5281/zenodo.23538544"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.23538544.svg" alt="DOI"></a>
  <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh-hans"><img src="https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-0A131E?style=flat" alt="许可：CC BY-NC-ND 4.0"></a>
  <a href="https://github.com/AlienMuse/topos-native-intelligence/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/release-1.0.0-1E5A88?style=flat" alt="版本 1.0.0"></a>
  <img src="https://img.shields.io/badge/pages-4%2C020-536372?style=flat" alt="4,020 页">
  <img src="https://img.shields.io/badge/formulas-62%2C000%2B-536372?style=flat" alt="62,000+ 个公式">
  <img src="https://img.shields.io/badge/series-02-536372?style=flat" alt="系列 02">
  <a href="VERIFY.md"><img src="https://img.shields.io/badge/OpenPGP-signed-B8913B?style=flat" alt="OpenPGP 签名"></a>
  <a href="VERIFY.md"><img src="https://img.shields.io/badge/timestamps-RFC%203161%20%C2%B7%20Bitcoin-B8913B?style=flat" alt="RFC 3161 与比特币时间戳"></a>
</p>

<p align="center">
  <b><a href="https://github.com/AlienMuse/topos-native-intelligence/releases/download/v1.0.0/GM-Omega-Infinity-v1.0.0-Preview.pdf">阅读预览版</a></b>（156 页，72.2 MB）·
  <a href="#下载">下载</a> ·
  <a href="#五卷">五卷</a> ·
  <a href="#引用">引用</a> ·
  <a href="VERIFY.md">校验</a> ·
  <a href="README.md">English</a>
</p>

<br>

# GM-Omega-Infinity: Topos-Native Intelligence

Vincent Liu · Research Architecture Edition 1 · 2026 · [English](README.md)

《GM-Omega-Infinity: Topos-Native Intelligence — A Sheaf-Theoretic Architecture for Verifiable Machine
Intelligence》是一部五卷合一的专著（正文为英文），共 4,020 页。它是 WiseMotif Monograph of Mathematical Intelligence
的第二部著作，也是 Grothendieckian Programme 的元推理内核（meta-reasoning kernel）。该 Programme 的核心是第一部著作
[《The Grothendieckian Machine》](https://github.com/AlienMuse/grothendieckian-machine)
（[doi:10.5281/zenodo.23480696](https://doi.org/10.5281/zenodo.23480696)）：前作阐明数学世界如何被构造、比较与迁移；
本书追问，一个智能系统若要在这些世界内部推理，其内部必须是什么——推理何以是局部的，局部推理为何必须彼此相容，
以及当它们不相容时能得出什么。

本书的回答是：**推理应当原生于拓扑斯（topos）。** 上下文是一个 site，它所承载的证据是 site 上的层，
结论是整体截面——只有在局部证据能够粘合之处它才存在。

<table>
  <tr>
    <td align="center"><b>5</b><br><sub>卷，合为一册</sub></td>
    <td align="center"><b>14 · 102</b><br><sub>部 · 章</sub></td>
    <td align="center"><b>4,020</b><br><sub>页</sub></td>
    <td align="center"><b>62,000+</b><br><sub>公式<br>行间公式 4,935</sub></td>
    <td align="center"><b>3,360</b><br><sub>编号声明<br>定理 580 · 命题 1,234</sub></td>
    <td align="center"><b>380</b><br><sub>算法</sub></td>
    <td align="center"><b>124 · 550</b><br><sub>矢量图 · 表</sub></td>
  </tr>
</table>

## 核心思想：原生于拓扑斯的推理

本书始于一个很窄的问题：对语言模型而言，"局部"一词意味着什么？模型读取上下文，并作出应由上下文支撑的断言。
若问上下文的哪些部分可以支撑一个断言、哪些部分的组合能决定其并集上的支撑，标准架构无从回答。没有覆盖（covering）
的概念，层条件——在交叠上一致的数据能粘合成整体上的数据——就什么也约束不了。这样的模型仍可能表现得自洽，
但它并不**必须**自洽；**"表现出某种性质"与"必须具有该性质"之间的距离，正是本书的主题。**

循着 Grothendieck 处理难题的方式——先构造让问题变得自然的环境——本书把这一转向施加于推理本身。整个架构围绕三个推论组织：

- **一致性是必须履行的条件。** 每一层都要说明它是否保持限制映射；若不保持，用什么来度量。
- **不一致是信息。** 粘合的障碍是系统的输出——一个有位置、有大小的上同调类——而不是要压制的错误。
- **上下文的改变是一个态射。** 适配、迁移与检索都是沿 site 态射的基变换；改变之后保留下来的，就是该态射所保持的。

### 内核的七种运算

| 运算 | 内核做什么 |
|---|---|
| **覆盖** | 由证据池构造 site，并给出覆盖族充分性的明确判据 |
| **赋值** | 在 site 上放置层，各茎的维数可以不同，并带限制映射 |
| **传输** | 把注意力重建为下降：值先被传入交叠处的共同茎，再在那里比较 |
| **粘合** | 由带精确反向的规范求解器把局部截面调和为整体截面；不能调和时报告残差 |
| **障碍** | 把不能粘合的部分度量为交叠上的一个类；没有独立的交叠数据时弃权 |
| **判定** | 以 Kripke–Joyal 强制（forcing）求值命题，每个结论都附带它成立的那部分 site |
| **基变换** | 沿 site 态射迁移到新上下文，并说明保持了什么、遗忘了什么 |

## 五卷

| | 卷 | 部 | 交付内容 |
|---|---|---|---|
| **I** | *Diagnosis and the Source Mathematics* | 前言、I–II | 五个结构性缺陷、typed transfer 的规则，以及源层数学——site、层、内部逻辑、∞-拓扑斯、上同调与下降、Deligne 权、almost mathematics、Kan 扩张、和乐、六函子、motive——全部处于定理级别 |
| **II** | *The Architecture and Its Mixture of Experts* | III–IV | 单一底空间上的九层 L0–L8；Topos-MoE：专家是开子拓扑斯，路由是构造充分覆盖 |
| **III** | *Learning, Systems, Validation, and Position* | V–X | 被证明保持或破坏结构的目标函数、以下降验证奖励的强化学习、执行与服务、参考实现、检验工具与严谨性台账 |
| **IV** | *Provenance and Adjudication* | XI | Grothendieck 纲领、点函子、motive 与 inter-universal Teichmüller 理论，逐项裁定可迁移性；不确定性演算；typed transfer 的复合律 |
| **V** | *Transferable Cores, Their Algorithms, and the Replacement Case* | XII–XIV | 七条谱系——Grothendieck、Deligne、Faltings、Voevodsky、Scholze、Lurie、Mochizuki——提炼为可迁移内核、转化为算法，并集中评估替代问题 |
| | *Apparatus* | A0–A16 | 记号、证明与扩展证明、术语表、带代码的完整示例、算法汇编、规范伪代码、预注册方案、任务生成器、Lean 4 源码、归属登记表、负面结果、参考文献 |

## 主要结果（节选）

- 正交胞腔层的非交换容量要么为零，要么有一个只依赖于茎维数的正下界——它是二值证书，而非连续分数。
- 一般的加权注意力**不能**经由常被用来解释它的 coend 分解。
- 对每个 *k* ≥ 2，都存在一个等预算实例，使 top-*k* 路由严格冗余。
- 专家之间的二阶分歧在图上和可缩单形上恒为平凡；四面体边界上的四个专家是它可能非平凡的最小配置。
- 层神经网络所用的粘合损失有一个与数据无关的极小点，这解释了它们坍缩为恒等层的已报道现象，也禁止把该损失作为主要训练项。
- 组相对策略优化的优势函数，就是 rollout 神经（nerve）上的零阶 Laplacian 作用于奖励，差别只在两种归一化。
- 在声明的数值契约下，一个参数注入能在本架构内逐位实现 Transformer 的前向映射，梯度与训练轨迹也相同——这是单向的程序等同，而非架构等同。

## 本书是什么，不是什么

**本书是**一部基础理论著作：机器智能的元推理内核，规定得足够精确，可以被实现、检验，若有错误也可以被驳倒。
每个断言都在提出之处标明等级——**T** 定理、**M** 可测量、**D** 设计决策、**X** 隐喻——每个尚未完成的义务都标为未完成。

**本书不是** Transformer 的替代品：书中证明了若干局部特化，它们的假设各不相同，没有任何定理把它们组合成单一前向映射。
**本书不报告任何实验：**书中没有训练好的模型，所有实证陈述都是等待执行的预注册方案。inter-universal Teichmüller 理论
得到了详尽讨论，但被隔离：架构中没有任何部分依赖于它是否正确。

## 从哪里开始读

| 读者 | 建议起点 |
|---|---|
| 数学家 | 第二部与证明附录（A1、A10），再读架构 |
| 工程师 | 第 3.1 章（架构总览）与第 1.3 章的合规矩阵 |
| 学习理论研究者 | 第一部，然后第五、六部与第九部的实验方案 |
| 怀疑者 | 第十部的严谨性台账与第十四部的替代评估 |

[预览版](https://github.com/AlienMuse/topos-native-intelligence/releases/download/v1.0.0/GM-Omega-Infinity-v1.0.0-Preview.pdf)包含前置部分（Series Note、前言、摘要、阅读指南、目录）与第一部全文。

## 下载

| 文件 | 页数 | 大小 |
|---|---:|---:|
| [**全书**](https://github.com/AlienMuse/topos-native-intelligence/releases/download/v1.0.0/GM-Omega-Infinity-v1.0.0-Complete.pdf)——第一至五卷与附录 | 4,020 | 105.6 MB |
| [预览版](https://github.com/AlienMuse/topos-native-intelligence/releases/download/v1.0.0/GM-Omega-Infinity-v1.0.0-Preview.pdf)——前置部分与第一部 | 156 | 72.2 MB |

同样的文件（校验值完全相同）存档于 Zenodo：[doi:10.5281/zenodo.23538545](https://doi.org/10.5281/zenodo.23538545)。
封面为 600 ppi 全出血；所有字体均已嵌入；PDF 已线性化，可快速打开。

## 引用

> Liu, V. (2026). *GM-Omega-Infinity: Topos-Native Intelligence — A Sheaf-Theoretic Architecture for Verifiable
> Machine Intelligence* (Research Architecture Edition 1, version 1.0.0). Zenodo. https://doi.org/10.5281/zenodo.23538544

概念 DOI 10.5281/zenodo.23538544 始终指向最新版本；引用这一版本的确切文件请用版本 DOI 10.5281/zenodo.23538545。BibTeX 见[英文说明](README.md#citation)。

## 真实性

发布的每个文件都列在 `SHA256SUMS` 中，经 OpenPGP 签名，并附 RFC 3161 与 OpenTimestamps（比特币）两种时间戳。
签名密钥与第一部相同，指纹：`DA1A 1AEF D8B2 C17C FF3F 1D1B 3905 0F50 7A4F EC17`。本仓库的 Release 不可更改。校验方法见 [VERIFY.md](VERIFY.md)。

## 许可与 AI 使用

本书以 [CC BY-NC-ND 4.0](LICENSE) 授权：可在署名、非商业、不作改动的前提下分享。书中印出的代码清单与机器可读模式另可依
Apache License 2.0 使用，以便开发者在实现中直接使用。翻译及其他用途需获得书面许可。详见 [NOTICE.md](NOTICE.md) 与
[TRADEMARKS.md](TRADEMARKS.md)。

**保留文本与数据挖掘权利**（欧盟指令 2019/790 第 4(3) 条）。未经书面许可，不得用本书训练或微调机器学习模型。
个人读者可以用 AI 工具阅读、检索、解释或翻译本书，供自己学习研究。完整政策见
[TDM-AND-AI-POLICY.md](TDM-AND-AI-POLICY.md)。

## 参与

一部这样的书，只有在别人尝试驳倒它之后才算完成，本书正是为此而写。最有价值的贡献有三种：

- **反驳**——定理的反例、所声明退化的失效，或某个模块未能通过它自己声明的检验的实验。
- **补全**——书中标为未完成的义务都已表述得足够精确，可以直接接手。
- **构造**——实现冻结 site 子集，并按预注册方案运行。

勘误请提交 [errata issue](https://github.com/AlienMuse/topos-native-intelligence/issues/new?template=errata.yml)；被采纳的更正将在下一版中署名致谢（见 [ERRATA.md](ERRATA.md)）。

---

<p align="center"><sub>
  <a href="https://wisemotif.ai">WiseMotif Monograph of Mathematical Intelligence</a> · Series 02 · Mathematics and Artificial Intelligence<br>
  第一部：<a href="https://github.com/AlienMuse/grothendieckian-machine"><i>GAI-MUA: The Grothendieckian Machine</i></a><br>
  © 2026 Vincent Liu
</sub></p>

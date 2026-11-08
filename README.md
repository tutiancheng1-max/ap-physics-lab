# AP Physics Lab · 交互实验库

[![简体中文](https://img.shields.io/badge/%E8%AF%AD%E8%A8%80-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-1f6f5c?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/Language-English-cfd8d3?style=for-the-badge)](README.en.md)

**在线使用：** https://tutiancheng1-max.github.io/ap-physics-lab/

面向 **AP Physics 2** 与 **AP Physics C: Electricity and Magnetism** 学生的交互模型库。共 49 个模型、220 个课堂任务，按 2024 年 College Board 课程框架（CED）的单元组织。打开网页即可使用，无需安装、无需登录。

### 怎么用

1. 打开 https://tutiancheng1-max.github.io/ap-physics-lab/，在左侧选择课程（Physics 2 或 C E&M）和单元。
2. 在单元顶部选一个模型，再点一张「任务」卡片。每个任务给出一个具体场景和一个要先预测的问题。
3. 在「预测与证据」里先写下预测，再拖动画面中的橙色控制点或右侧滑块，观察读数和图像的变化。
4. 回答任务下方的检查题，点「检查答案」后显示对错和正确答案（数值题允许 ±2% 误差）。每个任务的解析在页面下方「实验思路与物理关系」中，建议做完再展开。
5. 需要留证据时，点「记录测量」保存当前参数、读数和预测；「导出记录」可下载 CSV 交给老师。

### 主要功能

- **可操作的画面**：电荷、探针、线圈、透镜、闭合曲线等都可以直接拖动；部分模型可播放过程动画。
- **任务 + 检查题**：每个任务都有针对该场景的检查题和解析。题目数值与画面读数不同，需要自己推理计算。
- **A/B 对照**：「当前参数 → A」可保存一组参数作参考，改参数后与之比较。
- **电路实验台**：自由搭建直流、RC、LR、LC 电路，带示波器、电势回路和 23 个预设任务。
- **超纲内容明确标注**：超出 AP 考纲的部分（如位移电流、有限长导线）标为「拓展」。
- **三种语言模式**：页头按钮切换 中 → 中+EN（中文后标注英文术语）→ EN（纯英文界面）。也可在链接后加 `?lang=en` 直接打开英文版。
- **手机可用**：窄屏下实验画面可左右滑动查看。
- **可离线**：下载本仓库的 `index.html`，用浏览器双击打开即可，功能完全相同。

### 给老师

- 每个模型都有固定链接，可以直接发给学生，例如：https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/maxwell
- 下表每个模型名都是链接，括号里是任务数。
- 学生的记录、作答和语言偏好只保存在各自浏览器的本地存储中，网站不收集任何数据。换设备或清除浏览器数据后记录会丢失，课堂作业请让学生导出 CSV 提交。
- `reference-figures.pdf` 是部分模型的 MATLAB 参考曲线，用于核对数值。
- 发现问题或有建议，请在本仓库提交 Issue。

### 内容一览

### AP Physics 2

| Unit | 单元 | 模型（任务数） |
|---|---|---|
| 9 | 热力学 | [气体过程 · 活塞、热量与 P–V 图](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/9/thermo)（7）；[气体微观图像 · 压强、温度和速率](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/9/gas)（4）；[热接触 · 平衡温度与能量转移](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/9/thermalContact)（4） |
| 10 | 电力、电场与电势 | [多电荷场 · 探针与等势线](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/10/fields)（4）；[匀强电场中的粒子 · 轨迹与能量](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/10/electricMotion)（4）；[静电场做功 · 两条路径的积分](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/10/potential)（4）；[电容器 · 电荷流动与能量账本](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/10/capacitor)（4）；[电容组合 · 电荷、电压与储能](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/10/capacitorNet)（4） |
| 11 | 电路 | [自由电路实验台](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/11/circuit)（23）；[电阻率 · 长度与截面积](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/11/resistivity)（4） |
| 12 | 磁学与电磁学 | [洛伦兹力 · 三维轨道与速度分解](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/12/particle)（5）；[长直导线 · 磁场与平行导线](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/12/wireField)（3）；[载流导线受力 · 方向与大小](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/12/wireForce)（4）；[磁偶极子 · 力矩与势能](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/12/dipole)（3）；[线圈穿越磁场 · 分段过程与斜率](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/12/induction)（4）；[导体棒滑轨 · 感应与能量守恒](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/12/motional)（4） |
| 13 | 几何光学 | [光学工作台 · 成像与屏幕](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/13/optics)（6）；[折射与全反射 · 临界角实验](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/13/refraction)（3）；[水下物体的视深（cm）](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/13/depth)（3） |
| 14 | 波、声与物理光学 | [波的边界 · 入射、反射与透射](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/14/boundary)（4）；[驻波 · 行波叠加与共振](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/14/standing)（4）；[管中驻波 · 位移与压强](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/14/pipes)（4）；[偏振片 · 三片实验](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/14/polarization)（4）；[衍射光栅 · 缝数、缝距与包络](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/14/diffraction)（4）；[薄膜干涉 · 相位、振幅与反射谱](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/14/thin)（4）；[多普勒效应 · 声源与观察者](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/14/doppler)（4） |
| 15 | 现代物理 | [光电效应 · 遏止电压实验](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/15/photoelectric)（4）；[物质波 · 电子与光子](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/15/deBroglie)（3）；[黑体辐射 · 峰值与总功率](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/15/blackbody)（3）；[康普顿散射 · 能量与动量账本](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/15/compton)（4）；[氢原子能级与光谱线](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/15/spectra)（5）；[放射性衰变 · 随机事件与半衰期](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/15/decay)（4）；[核反应 · 电荷数、质量数与能量](https://tutiancheng1-max.github.io/ap-physics-lab/#ap2/15/nuclear)（4） |

### AP Physics C: E&M

| Unit | 单元 | 模型（任务数） |
|---|---|---|
| 8 | 电荷、电场与高斯定律 | [高斯定律 · 球面上的每一份通量](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/8/gauss)（5）；[多电荷场 · 探针与等势线](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/8/fields)（4）；[对称电荷分布 · E(r) 的形状](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/8/symmetry)（7）；[带电细杆 · kQ₀/R² 为场强单位](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/8/rod)（3）；[通量与环量 · 麦克斯韦方程的共同语言](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/8/fluxCirculation)（8） |
| 9 | 电势 | [静电场做功 · 两条路径的积分](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/9/potential)（4）；[电势斜率 · kQ₀/R 为电势单位](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/9/potentialSlope)（3）；[连续电荷的电势 · 从分段到积分](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/9/continuous)（4）；[匀强电场中的粒子 · 轨迹与能量](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/9/electricMotion)（4） |
| 10 | 导体与电容器 | [静电感应 · 球半径 R、电荷 q₀ 为单位](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/10/conductor)（3）；[导体空腔 · 感应电荷与接地](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/10/shielding)（4）；[电容器 · 电荷流动与能量账本](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/10/capacitor)（4）；[电容组合 · 电荷、电压与储能](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/10/capacitorNet)（4） |
| 11 | 电路 | [自由电路实验台](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/11/circuit)（23）；[电阻率 · 长度与截面积](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/11/resistivity)（4） |
| 12 | 磁场与电磁学 | [电流元叠加 · 圆环与螺线管](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/biot)（4）；[长直导线 · 磁场与平行导线](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/wireField)（3）；[安培环路 · μ₀I₀ 为积分单位](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/ampere)（3）；[安培定律 · 对称磁场 B(r)](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/ampereSymmetry)（4）；[洛伦兹力 · 三维轨道与速度分解](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/particle)（5）；[载流导线受力 · 方向与大小](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/wireForce)（4）；[磁偶极子 · 力矩与势能](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/dipole)（3）；[通量与环量 · 麦克斯韦方程的共同语言](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/12/fluxCirculation)（8） |
| 13 | 电磁感应 | [线圈穿越磁场 · 分段过程与斜率](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/induction)（4）；[变化磁场 · 环向感生电场](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/inducedE)（3）；[两种电场 · 保守场与涡旋场](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/twoEFields)（4）；[导体棒滑轨 · 感应与能量守恒](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/motional)（4）；[旋转线圈 · 磁通与交流电动势](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/generator)（4）；[LR / LC 实验台](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/circuit)（23）；[通量与环量 · 麦克斯韦方程的共同语言](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/fluxCirculation)（8）；[充电电容 · 安培–麦克斯韦定律（拓展）](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/displacement)（4）；[麦克斯韦方程组 · 总览](https://tutiancheng1-max.github.io/ap-physics-lab/#cem/13/maxwell)（5） |

---

AP® 是 College Board 的注册商标。College Board 与本网站无关，也未为其背书。

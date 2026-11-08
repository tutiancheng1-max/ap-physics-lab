# AP Physics Lab · 交互实验库

[中文](#中文) · [English](#english)

**在线使用 / Open online:** https://tutiancheng1-max.github.io/ap-physics-lab/  ·  **English:** https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en

---

## 中文

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

## English

An interactive model library for **AP Physics 2** and **AP Physics C: Electricity and Magnetism** students: 49 models and 220 classroom tasks, organized by the units of the College Board 2024 Course and Exam Description (CED). It runs in the browser with nothing to install and no sign-in.

### How to use

1. Open https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en and pick a course (Physics 2 or C E&M) and a unit on the left.
2. Choose a model at the top of the unit, then click a **Task** card. Each task sets up a specific scenario and asks you to predict something first.
3. Write your prediction under "My prediction and evidence", then drag the orange handles in the scene or the sliders on the right and watch the readings and graphs change.
4. Answer the check question below the task and click **Check answer** to see whether you are right and the correct answer (numeric answers allow ±2%). Each task's explanation is in **Experiment reasoning and physics** further down the page; open it after you have tried.
5. To keep evidence, click **Record measurement** to save the current parameters, readings and prediction; **Export log** downloads a CSV you can hand in.

### Features

- **Hands-on scenes**: drag charges, probes, coils, lenses and closed curves directly; many models animate the process.
- **Tasks with check questions**: every task has its own check question and explanation, with values different from the on-screen readings, so students have to reason and calculate.
- **A/B comparison**: "Current parameters → A" stores a reference set to compare against after you change parameters.
- **Circuit bench**: build DC, RC, LR and LC circuits freely, with an oscilloscope, loop-potential steps and 23 preset tasks.
- **Beyond-syllabus content is labeled**: material outside the AP framework (displacement current, finite wires, etc.) is marked "extension".
- **Three language modes**: the header button cycles 中 → 中+EN (Chinese with English terms) → EN (full English). Add `?lang=en` to any link to open it in English.
- **Works on phones**: on narrow screens the scene scrolls sideways.
- **Works offline**: download `index.html` from this repository and open it in a browser; everything works the same.

### For teachers

- Every model has a permanent link you can send to students, e.g. https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/maxwell
- Every model name in the table below is a link; the number in parentheses is the task count.
- Students' logs, answers and language choice stay in their own browser's local storage; the site collects no data. Logs are lost when students switch devices or clear browser data, so have them export the CSV for assignments.
- `reference-figures.pdf` contains MATLAB reference curves for checking several models' numbers.
- Please open an Issue in this repository for bugs or suggestions.

### Contents

### AP Physics 2

| Unit | Title | Models (tasks) |
|---|---|---|
| 9 | Thermodynamics | [Gas processes · piston, heat and P–V diagram](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/9/thermo) (7); [Microscopic picture of a gas · pressure, temperature and speed](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/9/gas) (4); [Thermal contact · equilibrium temperature and energy transfer](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/9/thermalContact) (4) |
| 10 | Electric Force, Field, and Potential | [Multi-charge field · probe and equipotentials](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/10/fields) (4); [Particle in a uniform electric field · trajectory and energy](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/10/electricMotion) (4); [Work by the electrostatic field · integral along two paths](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/10/potential) (4); [Capacitor · charge flow and energy bookkeeping](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/10/capacitor) (4); [Capacitor combinations · charge, voltage and stored energy](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/10/capacitorNet) (4) |
| 11 | Electric Circuits | [Free-circuit bench](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/11/circuit) (23); [Resistivity · length and cross-sectional area](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/11/resistivity) (4) |
| 12 | Magnetism and Electromagnetism | [Lorentz force · 3D orbit and velocity components](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/12/particle) (5); [Long straight wire · magnetic field and parallel wires](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/12/wireField) (3); [Current-carrying wire force · direction and magnitude](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/12/wireForce) (4); [Magnetic dipole · torque and potential energy](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/12/dipole) (3); [Coil crossing a magnetic field · stages and slopes](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/12/induction) (4); [Sliding rod on rails · induction and energy conservation](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/12/motional) (4) |
| 13 | Geometric Optics | [Optics bench · imaging and screen](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/13/optics) (6); [Refraction and total internal reflection · critical-angle experiment](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/13/refraction) (3); [Apparent depth of an underwater object (cm)](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/13/depth) (3) |
| 14 | Waves, Sound, and Physical Optics | [Wave boundary · incidence, reflection and transmission](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/14/boundary) (4); [Standing waves · traveling-wave superposition and resonance](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/14/standing) (4); [Standing waves in pipes · displacement and pressure](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/14/pipes) (4); [Polarizers · three-polarizer experiment](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/14/polarization) (4); [Diffraction grating · number of slits, slit spacing and envelope](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/14/diffraction) (4); [Thin-film interference · phase, amplitude, and reflectance spectrum](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/14/thin) (4); [Doppler effect · source and observer](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/14/doppler) (4) |
| 15 | Modern Physics | [Photoelectric effect · stopping-potential experiment](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/15/photoelectric) (4); [Matter waves · electrons and photons](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/15/deBroglie) (3); [Blackbody radiation · peak and total power](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/15/blackbody) (3); [Compton scattering · energy and momentum bookkeeping](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/15/compton) (4); [Hydrogen energy levels and spectral lines](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/15/spectra) (5); [Radioactive decay · random events and half-life](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/15/decay) (4); [Nuclear reactions · atomic number, mass number and energy](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#ap2/15/nuclear) (4) |

### AP Physics C: E&M

| Unit | Title | Models (tasks) |
|---|---|---|
| 8 | Electric Charges, Fields, and Gauss's Law | [Gauss's law · flux through each patch of the sphere](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/8/gauss) (5); [Multi-charge field · probe and equipotentials](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/8/fields) (4); [Symmetric charge distributions · shape of E(r)](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/8/symmetry) (7); [Charged thin rod · kQ₀/R² is the field unit](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/8/rod) (3); [Flux and circulation · the common language of Maxwell's equations](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/8/fluxCirculation) (8) |
| 9 | Electric Potential | [Work by the electrostatic field · integral along two paths](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/9/potential) (4); [Potential slope · kQ₀/R is the potential unit](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/9/potentialSlope) (3); [Potential of continuous charge · from segments to an integral](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/9/continuous) (4); [Particle in a uniform electric field · trajectory and energy](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/9/electricMotion) (4) |
| 10 | Conductors and Capacitors | [Electrostatic induction · sphere radius R, charge q₀ as units](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/10/conductor) (3); [Conducting cavity · induced charge and grounding](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/10/shielding) (4); [Capacitor · charge flow and energy bookkeeping](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/10/capacitor) (4); [Capacitor combinations · charge, voltage and stored energy](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/10/capacitorNet) (4) |
| 11 | Electric Circuits | [Free-circuit bench](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/11/circuit) (23); [Resistivity · length and cross-sectional area](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/11/resistivity) (4) |
| 12 | Magnetic Fields and Electromagnetism | [Current-element superposition · ring and solenoid](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/biot) (4); [Long straight wire · magnetic field and parallel wires](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/wireField) (3); [Amperian loop · μ₀I₀ as integral unit](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/ampere) (3); [Ampère's law · symmetric magnetic field B(r)](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/ampereSymmetry) (4); [Lorentz force · 3D orbit and velocity components](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/particle) (5); [Current-carrying wire force · direction and magnitude](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/wireForce) (4); [Magnetic dipole · torque and potential energy](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/dipole) (3); [Flux and circulation · the common language of Maxwell's equations](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/12/fluxCirculation) (8) |
| 13 | Electromagnetic Induction | [Coil crossing a magnetic field · stages and slopes](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/induction) (4); [Changing magnetic field · circulating induced electric field](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/inducedE) (3); [Two kinds of electric field · conservative and vortex](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/twoEFields) (4); [Sliding rod on rails · induction and energy conservation](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/motional) (4); [Rotating coil · flux and AC emf](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/generator) (4); [LR / LC bench](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/circuit) (23); [Flux and circulation · the common language of Maxwell's equations](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/fluxCirculation) (8); [Charging capacitor · Ampère–Maxwell law (extension)](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/displacement) (4); [Maxwell's equations · overview](https://tutiancheng1-max.github.io/ap-physics-lab/?lang=en#cem/13/maxwell) (5) |

---

AP® is a trademark registered by the College Board, which is not affiliated with, and does not endorse, this site.

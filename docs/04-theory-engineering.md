# 维度 4 · 偏理论还是偏工程

> 判断依据：**期刊/会议层级**（顶会顶刊 vs 应用/开源期刊）+ **方法类型**（架构/损失/理论创新 vs YOLO 变体/轻量化/部署）。

## 4.1 偏理论（架构/损失/建模创新）

| 方法 | 会议/期刊 | 创新点 |
|---|---|---|
| RHCNet | CVPR 2026 | 残差引导层次校准 + 语义卷积，结构/损失创新 |
| AMSP-UOD | AAAI 2024 | 涡旋卷积 + 随机扰动，噪声分布建模理论 |
| Turbidity-Similarity Decoupling | IEEE TIP 2026 | 浊度-相似度特征解耦理论 |
| WaterFlow | ICASSP 2026 | 物理先验 Rectified Flow，显式成像物理约束 |
| Wat3R | ECCV 2026 | 无标注 3D 几何学习理论 |
| IEUOD | ICASSP 2026 | 人机视觉偏好不一致的偏好对齐分析 |
| Are All Marine Species Created Equal? | WACV 2026 | 类别性能差异的诊断性理论分析 |
| 扩散/Retinex/Mamba 增强系列 | TIP/TPAMI 2026 | HRMamba、PKGD、单步潜扩散等，生成模型/物理建模理论 |

## 4.2 偏工程（改进/轻量化/落地）

| 类别 | 出处 | 特点 |
|---|---|---|
| 22 篇 Scientific Reports YOLO 改进 | Sci Rep 2024–2026 | YOLOv8/v11 变体、轻量化、可变形卷积等工程改进 |
| 轻量化检测系列 | IEEE/会议 | LighterDet、YOLO-lite、URD-YOLO、UWaterDetect 等部署导向 |
| 声纳/鱼类/水产应用 | IEEE/会议 | 面向特定场景的工程落地 |
| 数据集与方法配套 | TCSVT/ICCV 等 | DUO/UDD/DebrisVision/SCSFish2025 等数据集 + 配套方法 |

## 4.3 选题定位参考


- **偏理论方向**：关注退化、错位、域迁移等基础问题，主要发表于 CVPR / TIP / AAAI 等（如 RHCNet、AMSP-UOD、Turbidity Decoupling）；
- **偏工程方向**：以 YOLO 改进、轻量化与特定场景（声纳、鱼类、水产）为主，发表门槛相对较低，但同质化程度较高；
- **两者结合**：以理论模块（Mamba、ViT、扩散、物理先验）支撑具体任务，如 MFPD（Mamba 解码）、WaterFlow（物理先验）。

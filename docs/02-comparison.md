# 维度 2 · 对比实验

## 2.1 性能锚点（联网检索，标注来源）

> 绝对 mAP 多数论文未在摘要/检索片段中公开，下表为**可检索到的真实数字**，其余标注「见论文」。

| 方法 | 会议/期刊 | 数据集 | 性能 | 备注 |
|---|---|---|---|---|
| RHCNet | CVPR 2026 | DUO | AP 70.53 / AP50 87.56 / AP75 77.29 | ResNet-50 骨干，70.04M 参数/145.16G FLOPs，优于 CIDNet(+1.7 AP) |
| RHCNet | CVPR 2026 | UTDAC | AP 53.35 / AP50 86.93 / AP75 58.97 | 小目标 APS 27.23，优于 YOLOv11/CIDNet(+3.6 AP) |
| AMSP-UOD | AAAI 2024 | URPC / RUOD | mAP 相对提升 +10% / +7% | 涡旋卷积+随机扰动，绝对 mAP 见论文表 |
| LUIEO | IEEE TIM 2025 | RUOD / DUO | mAP50 相对提升约 +5.7% | 33.8M 参数 / 80 FPS，增强+检测统一 |

**来源**：RHCNet（CVPR 2026 open access + Papers with Code）；AMSP-UOD（AAAI 2024）；LUIEO（IEEE TIM 2025 / arXiv）。

## 2.2 方法 × 数据集（有代码的方法）

> 下表仅列**开源代码**的 47 篇方法及其所用数据集（取自调研原文）。

| 方法 | 会议/期刊 | 年份 | 任务 | 所用数据集 | 代码 |
|---|---|---|---|---|---|
| IEUOD: Improving Underwater Object Detection via Shallow Fea | IEEE | 2026年 | 增强+检测 | URPC2020（共7543张，训练5543/验证800/测试1200），含4类水下目标（海参、海胆、扇贝、海星），来自水下机器人抓取竞赛 | [代码](https://github.com/szu-qwd/IEUOD) |
| LUIEO: A Lightweight Model for Integrating Underwater Image  | IEEE Transactions on Instrum | 2025年 | 增强+检测 | RUOD（14000张，训练9800/验证4200，10类水下生物）+ DUO（7782张，验证1111，4类）+ UIEB（950张增强测试）+ U45（增强 | [代码](https://github.com/DrZhangZW/LUIEO) |
| A New Dataset, Poisson GAN and AquaNet for Underwater Object | IEEE Transactions on Circuit | 2021年 | 检测 | UDD：2227张真实开放海洋养殖场4K图像，3类为海参、海胆、扇贝；另利用Poisson GAN构建大规模扩增数据集AUDD及预训练数据集。 | [代码](https://github.com/chongweiliu/UDD_Official) |
| RHCNet: Residual-Guided Hierarchical Calibration Network for | CVPR 2026 | 2026年 | 检测 | DUO（7782张，水下多种环境）+ UTDAC（5643张，多类水下生物）+ COCO（118287张，80类，用于泛化性验证） | [代码](https://github.com/YitengGuo/RHCNet) |
| AMSP-UOD: When Vortex Convolution and Stochastic Perturbatio | AAAI-24 | 2024年 | 检测 | URPC2020（Zhanjiang）和 RUOD | [代码](https://github.com/zhoujingchun03/AMSP-UOD) |
| Are All Marine Species Created Equal? Performance Disparitie | WACV 2026 | 2026年 | 检测 | DUO（训练6671/测试1111，4类：海参/海胆/扇贝/海星）+ RUOD-4C（仅含上述4类的RUOD子集，训练3013/测试1255） | [代码](https://github.com/melaniewille/uod-class-disparities) |
| DebrisVision: Bridging the Synthetic-to-Real Gap for Enhance | ICCV 2025 | 2025年 | 鱼类/垃圾 | DebrisVision（自建，25,000张，9,430张真实+15,570张合成，含多类水下垃圾，标注：边界框+分割掩码+深度图+文本描述） | [代码](https://github.com/EswarMachara/DebrisVision) |
| Wat3R: Underwater 3D Geometry Learning without Annotations | ECCV 2026 (European Conferen | 2026 | 3D | Water3D (自建), Sea-thru, FLSea-VI, FLSea-Stereo, SQUID, SeaThru-NeRF | [代码](https://github.com/LSXI7/Wat3R) |
| OGRA-YOLOv8: Overlapping Gridded and Rhombus Attention for U | ICASSP 2026 | 2026 | 检测 | DUO, URPC2020 | [代码](https://github.com/LYJ0126/OGRA-YOLOv8) |
| AquaticCLIP: A Vision-Language Foundation Model and Dataset  | IEEE TNNLS (IEEE Transaction | 2026 | 基础模型 | 自建 2M 数据集，以及 MAI, SAI, FishNet, FNOI, LSF, CC, DeepFish, Brackish, URPC, SUIM, U | [代码](https://github.com/BasitAlawode/AquaticCLIP) |
| MFPD: Mamba-Driven Feature Pyramid Decoding for Underwater O | IEEE Signal Processing Lette | 2026 | 检测 | DUO, UTDAC | [代码](https://github.com/YitengGuo/MFPD) |
| WaterFlow: Explicit Physics-Prior Rectified Flow for Underwa | ICASSP 2026 (IEEE Internatio | 2026 | 显著性 | USOD10K, UFO-120 | [代码](https://github.com/Theo-polis/WaterFlow) |
| YOLO-UOD: Location-Edge Co-Perception Network With Multiscal | IEEE Transactions on Geoscie | 2026 | 检测 | DUO, RUOD, UTDAC2020 | [代码](https://github.com/liuyuanjie123-tech/YOLO-UOD) |
| Prompt Then Refine: Prompt-Free SAM-Enhanced Collaborative L | IEEE TNNLS (IEEE Transaction | 2026 | 显著性 | USOD10K, USOD | [代码](https://github.com/BeibeiIsFreshman/SAM-USOD) |
| MANTA: Physics-Informed Generalized Underwater Object Tracki | WACV 2026 (IEEE/CVF Winter C | 2026 | 视频 | WebUOT-1M, UOT32, UTB180, UW-COT220 | [代码](https://github.com/Kazedaa/MANTA) |
| Turbidity-Similarity Decoupling: Feature-Consistent Mutual L | IEEE TIP (IEEE Transactions  | 2026 | 显著性 | USOD10K, USOD, RMAS | [代码](https://github.com/BeibeiIsFreshman/DSNet_CL) |
| Downstream Task-Inspired Underwater Image Enhancement: A Per | IEEE TIP (IEEE Transactions  | 2026 | 增强 | TI-UIED (自建), SUIM, LIACi, RUOD | [代码](https://github.com/oucailab/DTIUIE) |
| ViT-UWA: Vision Transformer Underwater-Adapter for Dense Pre | IEEE TIP (IEEE Transactions  | 2026 | 密集预测/分割 | USIS10K, UIIS, SUIM, COCO, SODA | [代码](https://github.com/Linqirui/ViT-UWA) |
| DVM: Dual-Prompt Video Mamba for Indiscernible Object Counti | IEEE TCSVT (IEEE Transaction | 2026 | 视频 | VF5K (自建), YoutubeFish-35, IOCfish5K | [代码](https://github.com/Amelie01/DVM) |
| Enhancing Underwater Images via Adaptive Semantic-Aware Code | IEEE TGRS (IEEE Transactions | 2026 | 增强 | UIEB, SUIM-E, LSUI, UFO-120 | [代码](https://github.com/oucailab/SUCode) |
| HRMamba: A Hybrid Retinex and State-Space Model for Underwat | IEEE Transactions on Image P | 2026 | 增强 | UIEB; LSUI | [代码](https://github.com/YeFan-web/HRMamba/) |
| Rethinking the Importance of High-Frequency Components in Tr | IEEE Transactions on Image P | 2026 | 增强 | LSUI | [代码](https://github.com/joshyZhou/HIT_) |
| Color Correction Meets Cross-Spectral Refinement: A Distribu | IEEE Transactions on Multime | 2026 | 增强 | UIEB; LSUI | [代码](https://github.com/LaibinChang/DiffColor) |
| PyUIE: A Coarse-to-Fine Deep Pyramid Network for Underwater  | IEEE Transactions on Multime | 2026 | 增强 | UIEB; LSUI | [代码](https://github.com/ttttllt/PyUIE) |
| WWE-UIE: A Wavelet & White Balance Efficient Network for Und | IEEE/CVF Winter Conference o | 2026 | 增强 | UIEB; LSUI | [代码](https://github.com/chingheng0808/WWE-UIE) |
| D2Mamba: Dual Domain Guided Informed Search in State Space M | IEEE/CVF Winter Conference o | 2026 | 增强 | UIEB | [代码](https://github.com/Alik033/D2Mamba) |
| Single-Step Latent Diffusion for Underwater Image Restoratio | IEEE Transactions on Pattern | 2025 (2026 | 增强 | UIEB; USOD10K | [代码](https://github.com/kongdai123/SLURPP) |
| SAT-UIR: Self-Assessment Training for Semi-Supervised Underw | IEEE Transactions on Circuit | 2025 (2026 | 增强 | UIEB; LSUI | [代码](https://github.com/aroid721/SAT-UIR) |
| A Lightweight Polarization-Guided Plug-In for Underwater Ima | IEEE Transactions on Circuit | 2025 (2026 | 增强 | UIEB; LSUI | [代码](https://github.com/jgy0/UPGD) |
| Detection-Guided Deep Unfolding for Joint Underwater Image E | IEEE Access | 2026 | 增强+检测 | UJED | [代码](https://github.com/yumuruk/DGUNet) |
| Real-Time Underwater Visual Target Sensing System With Multi | IEEE Journal of Oceanic Engi | 2026 | 检测 | UIEB; RUOD | [代码](https://github.com/Adios-Cowboy/UVTS-2) |
| Fast Scene-Adaptive Underwater Image Enhancement via Mamba-G | IEEE Access | 2026 | 增强 | UIEB | [代码](https://github.com/IHCLab/UIE-SLIC) |
| UIESNN: A Scale-Aware Spiking Network for Underwater Image E | International Joint Conferen | 2026 | 增强 | LSUI | [代码](https://github.com/ChrisChen1023/UIESNN) |
| PKGD: Physics Knowledge-Guided Diffusion Model for Underwate | IEEE Transactions on Geoscie | 2026 | 增强 | UIEB; LSUI | [代码](https://github.com/Yyh-cc/PKGD) |
| Learning a Physical-Aware Diffusion Model Based on Transform | IEEE Transactions on Geoscie | 2026 | 增强 | LSUI; UIEB | [代码](https://github.com/chenydong/PA-Diff) |
| DA-GAN: Dual-Attention GAN for Underwater Image Enhancement  | IEEE Transactions on Geoscie | 2026 | 增强 | UIEB; LSUI | [代码](https://github.com/littlebearRedgood/DAGAN) |
| Wavelet-Driven Spatial-Frequency Modulation Network for Unde | IEEE ICASSP | 2026 | 增强 | UIEB | [代码](https://github.com/Wujian6/UIE) |
| AquaClarity: Vision Transformer Enhances Underwater Image vi | IEEE Transactions on Consume | 2026 | 增强 | Underwater Benchmark Dataset | [代码](https://github.com/CXH-Research/AquaClarity) |
| UEAOD: Underwater Image Enhancement-Assisted Object Detectio | IEEE Transactions on Geoscie | 2026 | 增强+检测 | RUOD | [代码](https://github.com/zhuyy116/UEAOD) |
| UStyle: Waterbody Style Transfer of Underwater Scenes by Dep | IEEE Journal of Oceanic Engi | 2026 | 增强 | UF7D | [代码](https://github.com/uf-robopi/UStyle) |
| M4FT: Mamba, Migratory, Mobile, and Multiple Fish Tracking | IEEE Transactions on Circuit | 2026 | 视频 | BrackishMOT-M4FT | [代码](https://github.com/vranlee/M-4-FT) |
| Melan-YOLO: a dual-strategy framework with custom architectu | Scientific Reports（Sci Rep）， | 2026年（在线发表 | 检测 | SeaClear Marine Debris Dataset（8610张，40类，含海洋垃圾、动植物、机器人部件）+ RUOD（5543张，10类海洋生物） | [代码](https://github.com/AndacF/MELAN-YOLO) |
| YOLO-Starfish: fish object detection learning complex underw | Scientific Reports（Sci Rep）， | 2026年 | 鱼类/垃圾 | UFFD（自建淡水鱼类数据集，16904张去重图像，训练13523/验证5071（含3381张Unseen+1690张Seen），19类，含“UNKNOWN F | [代码](https://github.com/Sdafah/YOLO-Starfish) |
| Optimized YOLOv8s framework with deformable convolution for  | Scientific Reports（Sci Rep）， | 2025年 | 检测 | LFIW（Labeled Fishes in the Wild，从1326张中筛选873张有效鱼图像，按8:2划分686/187）+ OI（Open Image | [代码](https://github.com/WangXin81/O-YOLOv8s-DC) |
| An improved YOLOv11 network for marine debris detection in u | Scientific Reports（Sci Rep）， | 2026年2月3日（ | 鱼类/垃圾 | TrashCan-Instance（7212张，训练6065/验证1147，22类）+ TrashCan-Material（16类，按材质分类） | [代码](https://github.com/DavidJing777/yolo-marine) |
| A Lightweight underwater detector enhanced by Attention mech | Scientific Reports（Sci Rep）， | 2024年 | 增强+检测 | URPC2020（5543张，训练/验证/测试按7:2:1，4类：海胆、海参、扇贝、海星） | [代码](文中注明补充材料在线可用（https://doi.org/10.1038/s41598-024-75809-z）) |
| SCSFish2025: a large dataset from South China sea for coral  | Scientific Reports（Sci Rep）， | 2025年8月17日 | 鱼类/垃圾 | SCSFish2025（自建，11956张，1920×1080，30类珊瑚礁鱼类，120084个标注框，含模糊/遮挡/姿态困难样本标注） | [代码](https://github.com/FudanZhengSYSU/SCSFish2025) |

## 2.3 对比实验说明

- 光学检测最常用基准：**DUO / RUOD / URPC2020**（4~10 类，COCO 口径 mAP）；
- 增强最常用基准：**UIEB / LSUI**（PSNR / SSIM / UCIQE）；
- 显著性：**USOD10K / UFO-120**；声纳：**SCTD / Orca / Side-Scan Mine**；
- 小目标（APS）是水下检测的核心难点，评估方法时应重点关注 APS 与 AP50 的差距。

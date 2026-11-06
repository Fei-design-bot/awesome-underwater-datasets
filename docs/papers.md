# 论文总表

> 共 94 篇（去重后），来自两份调研 Excel。完整信息见本地 Excel。

| # | 论文 | 期刊/会议 | 年份 | 任务 | 代码 | 数据集 |
|---|---|---|---|---|---|---|
| 1 | IEUOD: Improving Underwater Object Detection via Shallow F | IEEE | 2026年 | 增强+检测 | [代码](https://github.com/szu-qwd/IEUOD) | URPC2020（共7543张，训练5543/验证800/测试1200），含4类水下目标（海参、海胆、扇贝、海星），来自 |
| 2 | LUIEO: A Lightweight Model for Integrating Underwater Imag | IEEE Transactions on Ins | 2025年 | 增强+检测 | [代码](https://github.com/DrZhangZW/LUIEO) | RUOD（14000张，训练9800/验证4200，10类水下生物）+ DUO（7782张，验证1111，4类）+ UI |
| 3 | A New Dataset, Poisson GAN and AquaNet for Underwater Obje | IEEE Transactions on Cir | 2021年 | 检测 | [代码](https://github.com/chongweiliu/UDD_Official) | UDD：2227张真实开放海洋养殖场4K图像，3类为海参、海胆、扇贝；另利用Poisson GAN构建大规模扩增数据集A |
| 4 | RHCNet: Residual-Guided Hierarchical Calibration Network f | CVPR 2026 | 2026年 | 检测 | [代码](https://github.com/YitengGuo/RHCNet) | DUO（7782张，水下多种环境）+ UTDAC（5643张，多类水下生物）+ COCO（118287张，80类，用于泛 |
| 5 | AMSP-UOD: When Vortex Convolution and Stochastic Perturbat | AAAI-24 | 2024年 | 检测 | [代码](https://github.com/zhoujingchun03/AMSP-UOD) | URPC2020（Zhanjiang）和 RUOD |
| 6 | Are All Marine Species Created Equal? Performance Disparit | WACV 2026 | 2026年 | 检测 | [代码](https://github.com/melaniewille/uod-class-disparities) | DUO（训练6671/测试1111，4类：海参/海胆/扇贝/海星）+ RUOD-4C（仅含上述4类的RUOD子集，训练3 |
| 7 | DebrisVision: Bridging the Synthetic-to-Real Gap for Enhan | ICCV 2025 | 2025年 | 鱼类/垃圾 | [代码](https://github.com/EswarMachara/DebrisVision) | DebrisVision（自建，25,000张，9,430张真实+15,570张合成，含多类水下垃圾，标注：边界框+分割 |
| 8 | Wat3R: Underwater 3D Geometry Learning without Annotations | ECCV 2026 (European Conf | 2026 | 3D | [代码](https://github.com/LSXI7/Wat3R) | Water3D (自建), Sea-thru, FLSea-VI, FLSea-Stereo, SQUID, SeaTh |
| 9 | OGRA-YOLOv8: Overlapping Gridded and Rhombus Attention for | ICASSP 2026 | 2026 | 检测 | [代码](https://github.com/LYJ0126/OGRA-YOLOv8) | DUO, URPC2020 |
| 10 | AquaticCLIP: A Vision-Language Foundation Model and Datase | IEEE TNNLS (IEEE Transac | 2026 | 基础模型 | [代码](https://github.com/BasitAlawode/AquaticCLIP) | 自建 2M 数据集，以及 MAI, SAI, FishNet, FNOI, LSF, CC, DeepFish, Bra |
| 11 | MFPD: Mamba-Driven Feature Pyramid Decoding for Underwater | IEEE Signal Processing L | 2026 | 检测 | [代码](https://github.com/YitengGuo/MFPD) | DUO, UTDAC |
| 12 | WaterFlow: Explicit Physics-Prior Rectified Flow for Under | ICASSP 2026 (IEEE Intern | 2026 | 显著性 | [代码](https://github.com/Theo-polis/WaterFlow) | USOD10K, UFO-120 |
| 13 | YOLO-UOD: Location-Edge Co-Perception Network With Multisc | IEEE Transactions on Geo | 2026 | 检测 | [代码](https://github.com/liuyuanjie123-tech/YOLO-UOD) | DUO, RUOD, UTDAC2020 |
| 14 | Prompt Then Refine: Prompt-Free SAM-Enhanced Collaborative | IEEE TNNLS (IEEE Transac | 2026 | 显著性 | [代码](https://github.com/BeibeiIsFreshman/SAM-USOD) | USOD10K, USOD |
| 15 | MANTA: Physics-Informed Generalized Underwater Object Trac | WACV 2026 (IEEE/CVF Wint | 2026 | 视频 | [代码](https://github.com/Kazedaa/MANTA) | WebUOT-1M, UOT32, UTB180, UW-COT220 |
| 16 | Turbidity-Similarity Decoupling: Feature-Consistent Mutual | IEEE TIP (IEEE Transacti | 2026 | 显著性 | [代码](https://github.com/BeibeiIsFreshman/DSNet_CL) | USOD10K, USOD, RMAS |
| 17 | Downstream Task-Inspired Underwater Image Enhancement: A P | IEEE TIP (IEEE Transacti | 2026 | 增强 | [代码](https://github.com/oucailab/DTIUIE) | TI-UIED (自建), SUIM, LIACi, RUOD |
| 18 | ViT-UWA: Vision Transformer Underwater-Adapter for Dense P | IEEE TIP (IEEE Transacti | 2026 | 密集预测/分割 | [代码](https://github.com/Linqirui/ViT-UWA) | USIS10K, UIIS, SUIM, COCO, SODA |
| 19 | DVM: Dual-Prompt Video Mamba for Indiscernible Object Coun | IEEE TCSVT (IEEE Transac | 2026 | 视频 | [代码](https://github.com/Amelie01/DVM) | VF5K (自建), YoutubeFish-35, IOCfish5K |
| 20 | Enhancing Underwater Images via Adaptive Semantic-Aware Co | IEEE TGRS (IEEE Transact | 2026 | 增强 | [代码](https://github.com/oucailab/SUCode) | UIEB, SUIM-E, LSUI, UFO-120 |
| 21 | HRMamba: A Hybrid Retinex and State-Space Model for Underw | IEEE Transactions on Ima | 2026 | 增强 | [代码](https://github.com/YeFan-web/HRMamba/) | UIEB; LSUI |
| 22 | Rethinking the Importance of High-Frequency Components in  | IEEE Transactions on Ima | 2026 | 增强 | [代码](https://github.com/joshyZhou/HIT_) | LSUI |
| 23 | Color Correction Meets Cross-Spectral Refinement: A Distri | IEEE Transactions on Mul | 2026 | 增强 | [代码](https://github.com/LaibinChang/DiffColor) | UIEB; LSUI |
| 24 | PyUIE: A Coarse-to-Fine Deep Pyramid Network for Underwate | IEEE Transactions on Mul | 2026 | 增强 | [代码](https://github.com/ttttllt/PyUIE) | UIEB; LSUI |
| 25 | WWE-UIE: A Wavelet & White Balance Efficient Network for U | IEEE/CVF Winter Conferen | 2026 | 增强 | [代码](https://github.com/chingheng0808/WWE-UIE) | UIEB; LSUI |
| 26 | D2Mamba: Dual Domain Guided Informed Search in State Space | IEEE/CVF Winter Conferen | 2026 | 增强 | [代码](https://github.com/Alik033/D2Mamba) | UIEB |
| 27 | Single-Step Latent Diffusion for Underwater Image Restorat | IEEE Transactions on Pat | 2025 (2026 | 增强 | [代码](https://github.com/kongdai123/SLURPP) | UIEB; USOD10K |
| 28 | SAT-UIR: Self-Assessment Training for Semi-Supervised Unde | IEEE Transactions on Cir | 2025 (2026 | 增强 | [代码](https://github.com/aroid721/SAT-UIR) | UIEB; LSUI |
| 29 | A Lightweight Polarization-Guided Plug-In for Underwater I | IEEE Transactions on Cir | 2025 (2026 | 增强 | [代码](https://github.com/jgy0/UPGD) | UIEB; LSUI |
| 30 | Detection-Guided Deep Unfolding for Joint Underwater Image | IEEE Access | 2026 | 增强+检测 | [代码](https://github.com/yumuruk/DGUNet) | UJED |
| 31 | Real-Time Underwater Visual Target Sensing System With Mul | IEEE Journal of Oceanic  | 2026 | 检测 | [代码](https://github.com/Adios-Cowboy/UVTS-2) | UIEB; RUOD |
| 32 | Fast Scene-Adaptive Underwater Image Enhancement via Mamba | IEEE Access | 2026 | 增强 | [代码](https://github.com/IHCLab/UIE-SLIC) | UIEB |
| 33 | UIESNN: A Scale-Aware Spiking Network for Underwater Image | International Joint Conf | 2026 | 增强 | [代码](https://github.com/ChrisChen1023/UIESNN) | LSUI |
| 34 | PKGD: Physics Knowledge-Guided Diffusion Model for Underwa | IEEE Transactions on Geo | 2026 | 增强 | [代码](https://github.com/Yyh-cc/PKGD) | UIEB; LSUI |
| 35 | Learning a Physical-Aware Diffusion Model Based on Transfo | IEEE Transactions on Geo | 2026 | 增强 | [代码](https://github.com/chenydong/PA-Diff) | LSUI; UIEB |
| 36 | DA-GAN: Dual-Attention GAN for Underwater Image Enhancemen | IEEE Transactions on Geo | 2026 | 增强 | [代码](https://github.com/littlebearRedgood/DAGAN) | UIEB; LSUI |
| 37 | Wavelet-Driven Spatial-Frequency Modulation Network for Un | IEEE ICASSP | 2026 | 增强 | [代码](https://github.com/Wujian6/UIE) | UIEB |
| 38 | AquaClarity: Vision Transformer Enhances Underwater Image  | IEEE Transactions on Con | 2026 | 增强 | [代码](https://github.com/CXH-Research/AquaClarity) | Underwater Benchmark Dataset |
| 39 | UEAOD: Underwater Image Enhancement-Assisted Object Detect | IEEE Transactions on Geo | 2026 | 增强+检测 | [代码](https://github.com/zhuyy116/UEAOD) | RUOD |
| 40 | UStyle: Waterbody Style Transfer of Underwater Scenes by D | IEEE Journal of Oceanic  | 2026 | 增强 | [代码](https://github.com/uf-robopi/UStyle) | UF7D |
| 41 | M4FT: Mamba, Migratory, Mobile, and Multiple Fish Tracking | IEEE Transactions on Cir | 2026 | 视频 | [代码](https://github.com/vranlee/M-4-FT) | BrackishMOT-M4FT |
| 42 | Underwater Object Detection based on YOLO-v3 network（基于 YO | IEEE | 2021年 | 检测 |  | 自建真实侧扫声纳图像数据集，共7000张，含4类目标（管道、桶、四棱锥、四棱柱） |
| 43 | Enhanced Underwater Object Detection in Sonar Images with  | IEEE | 2024年（参考文献 | 声纳 |  | 自建前视声纳（BlueView M900）数据集：训练集2982张（试验水池采集+风格迁移增强），测试集975张（屏障湖 |
| 44 | YOLO-AES: A Lightweight Model for Real-Time Underwater Obj | IEEE | 2024年 | 检测 |  | DUO（Underwater Dataset for Object detection）开源水下图像数据集，包含海参、海 |
| 45 | VVNet: Underwater Object Detection Network based on Vision | 2024 International Sympo | 2024年 | 检测 |  | URPC2017（训练17655张/测试985张，分辨率720×405）+ URPC2018（训练2901张/测试800 |
| 46 | GEE-UOD: An Underwater Object Detection Network Based on G | IEEE | 2024年（参考文献 | 增强+检测 |  | RUOD（Rethinking General Underwater Object Detection Dataset） |
| 47 | DWP2-YOLO11: Deformable Convolution and Multi-Scale Head f | 2025 the 8th Internation | 2025年 | 检测 |  | URPC2020（5543张，4类：海参、海胆、扇贝、海星，按7:2:1划分）+ DUO（5208张，同上4类，去重后重 |
| 48 | CSTransNet: A Cross-Scale Transformer Network for Underwat | IEEE | 2024年（参考文献 | 检测 |  | DUO（7782张）+ AUDD（18457张）+ Brackish（12902张，训练9967/测试1468），均为公 |
| 49 | Enhanced Underwater Object Detection Using Real-ESRGAN and | 2025 5th International C | 2025年9月12- | 增强+检测 |  | Aquarium Dataset + Trash Dataset，共3300张图像（70%训练/30%测试），含鱼类、水 |
| 50 | Improved YOLOv8 Underwater Object Detection Combined with  | 2024 International Sympo | 2024年 | 检测 |  | URPC2020水下机器人竞赛数据集子集，共2858张图像（分辨率720×405），含4类：海胆、海参、扇贝、海星，按2 |
| 51 | LighterDet: A Lightweight Underwater Object Detection Meth | IEEE | 2024年（参考文献 | 检测 |  | URPC（Underwater Robot Professional Contest）水下光学图像数据集，共7395张图 |
| 52 | UWaterDetect: A Lightweight Underwater Object Detection Mo | IEEE | 2024年（参考文献 | 检测 |  | RUOD（Rethinking Underwater Object Detection Dataset），共14000张 |
| 53 | Research on Underwater Object Detection Algorithm Based on | 2023 2nd International C | 2023年 | 检测 |  | 自建水下机器人抓取竞赛数据集（大连獐子岛），共4161张图像，含4类：海参、海胆、扇贝、海星，按7:1:2划分训练/验证 |
| 54 | UOD-FPN: An Effective Feature Pyramid Network for Underwat | 2023 International Confe | 2023年 | 检测 |  | DUO（7782张）+ RUOD（14000张，10类），均为公开水下目标检测数据集 |
| 55 | Underwater Fish Object Detection based on Attention Mechan | 2022 7th International C | 2022年 | 鱼类/垃圾 |  | 自建水下鱼类数据集，共约1500张图像，含11类水下鱼类，按9:1划分训练/验证 |
| 56 | A Lightweight YOLOv11 Framework with Attention-Enhanced Mu | 2026 6th International C | 2026年6月19- | 增强+检测 |  | 公开水下基准数据集（文中未明确具体数据集名称，含多种海洋目标，在低光照、浑浊、颜色失真等恶劣条件下拍摄） |
| 57 | MCC-YOLO: An Improved Underwater Object Detection Algorith | 2025 5th International C | 2025年 | 检测 |  | DUO（Underwater Object Detection Dataset），共7782张图像（训练5560/验证1 |
| 58 | YOLO-lite: A novel lightweight model for underwater object | 2025 4th International S | 2025年 | 检测 |  | 自建数据集（来自水下机器人竞赛-水下目标检测算法竞赛），经清理去噪后共5320张图像（85%训练/15%测试），含4类： |
| 59 | URD-YOLO: An Enhanced YOLOv8n-Based Algorithm for Underwat | 2025 4th International C | 2025年 | 增强+检测 |  | URPC2020（中国水下机器人专业竞赛数据集），共6574张图像（80%训练/20%测试），含4类：海参、海胆、扇贝、 |
| 60 | DSML-YOLO: A Fast and Lightweight Underwater Object Detect | 2024 4th IEEE Internatio | 2024年 | 声纳 |  | Orca开源项目声纳数据集（经数据增强从6000张扩至12000张，训练8000/验证2000/测试2000），含8类： |
| 61 | Lightweight Underwater Object Detection Algorithm for Auto | IEEE | 2025年（参考文献 | 检测 |  | SCTD（Sonar Common Target Detection Dataset）声纳通用目标检测数据集，含多种水下 |
| 62 | Underwater Object Detection model based on YOLOv3 architec | 2021 7th International C | 2021年 | 鱼类/垃圾 |  | Fish4Knowledge（F4K）公开鱼类视频数据集，本实验从中提取2500帧图像并手动标注（训练2000/验证25 |
| 63 | Underwater Object Detection Based on Improved YOLOv8（基于改进Y | 2024 4th International S | 2024年 | 检测 |  | DUO水下目标检测数据集（源自URPC 2017-2020竞赛数据经感知哈希去重），共7782张图像，含4类：海参（78 |
| 64 | Real-Time Object Detection Technology for Complex Underwat | IEEE | 2024年（参考文献 | 检测 |  | Brackish Underwater Computer Vision Project公开数据集，共14518张图像，含 |
| 65 | HAD-Net: A Hybrid Attention Driven Dynamic Network for AUV | 未明确标注（疑为IEEE Transaction | 2025年（参考文献 | 检测 |  | URPC2020（训练5543张+测试1200张，含4类：海胆、海参、扇贝、海星）+ TrashCan（水下垃圾实例分割 |
| 66 | The Common Objects Underwater (COU) Dataset for Robust Und | 2025 IEEE/RSJ Internatio | 2025年10月19 | 鱼类/垃圾 |  | COU（Common Objects Underwater），约9757张分割标注图像，24类水下人造物体（如剪刀、塑料 |
| 67 | Robust Detection of Aggregated Small Objects in Degraded U | 2026 International Confe | 2026年 | 检测 |  | UTDAC2020（6461张，训练5168/测试1293，4类：海胆、海星、海参、扇贝，多分辨率）+ DUO（7782 |
| 68 | Research on Underwater Small Target Detection Technology B | IEEE Access | 2024年 | 检测 |  | URPC2018、URPC2020水下机器人竞赛数据集；论文在URPC2018完整数据集及URPC2020相关划分上进行 |
| 69 | An Efficient Lightweight Network for Underwater Small Obje | IEEE Access | 2026年 | 检测 |  | URPC2021水下机器人竞赛数据集，包含海参、海胆、扇贝、海星等水下小目标类别。 |
| 70 | CWSCNet: Channel-Weighted Skip Connection Network for Unde | IEEE Transactions on Ima | 2024年（IEEE | 检测 |  | RUOD、URPC2017、URPC2018三个公开水下目标检测数据集。 |
| 71 | DFFR: DETR With Foreground-Guided Feature Refinement Netwo | IEEE Transactions on Ind | 2026年（DOI所 | 检测 |  | 论文实验所用数据集名称与规模不明确。 |
| 72 | Towards Robust Object Detection in Underwater Sonar Imager | CVPR 2026 Workshop on Ma | 2026年 | 声纳 |  | FLS：Marine Debris（1869张，11类）+ UXO（含3类）+ SAS：ITMINEX（613张，MIL |
| 73 | SFL-YOLO: an improved YOLOv11-based model for underwater o | Scientific Reports（Sci R | 2026年6月29日 | 检测 |  | URPC2020（共5543张，训练3878/测试1107/验证554，4类：海参、海胆、扇贝、海星）+ RUOD（共1 |
| 74 | Melan-YOLO: a dual-strategy framework with custom architec | Scientific Reports（Sci R | 2026年（在线发表 | 检测 | [代码](https://github.com/AndacF/MELAN-YOLO) | SeaClear Marine Debris Dataset（8610张，40类，含海洋垃圾、动植物、机器人部件）+ R |
| 75 | YOLO-MFD: a multi-scale feature and dynamic head framework | Scientific Reports（Sci R | 2026年 | 检测 |  | DUO（7782张，训练6671/测试1111，4类：海参、海胆、扇贝、海星）+ UDD（2227张，3类：海参、海胆、 |
| 76 | A small underwater object detection model with enhanced fe | Scientific Reports（Sci R | 2025年1月18日 | 增强+检测 |  | UDD（2227张，3类：海参、海胆、扇贝）+ DUO（7782张，4类：海参、海胆、扇贝、海星） |
| 77 | YOLO-Starfish: fish object detection learning complex unde | Scientific Reports（Sci R | 2026年 | 鱼类/垃圾 | [代码](https://github.com/Sdafah/YOLO-Starfish) | UFFD（自建淡水鱼类数据集，16904张去重图像，训练13523/验证5071（含3381张Unseen+1690张S |
| 78 | Optimized YOLOv8s framework with deformable convolution fo | Scientific Reports（Sci R | 2025年 | 检测 | [代码](https://github.com/WangXin81/O-YOLOv8s-DC) | LFIW（Labeled Fishes in the Wild，从1326张中筛选873张有效鱼图像，按8:2划分686 |
| 79 | Lightweight underwater object detection method based on mu | Scientific Reports（Sci R | 2025年7月29日 | 增强 |  | URPC2020（5543张，训练/验证/测试按7:1:2，4类：海参、海胆、海星、扇贝）+ S-UODAC2020（7 |
| 80 | Efficient underwater object detection based on feature enh | Scientific Reports（Sci R | 2025年2月18日 | 增强+检测 |  | UTDAC2020（6461张，4类）+ RUOD（14000张，10类），分别按约8:2划分训练/测试 |
| 81 | Cyber physical solutions for aquatic monitoring using YOLO | Scientific Reports（Sci R | 2025年11月21 | 检测 |  | COD10K（大规模伪装目标检测数据集，含5大类，其中aquatics含鬼管鱼、比目鱼等）+ Halibut（水下比目鱼 |
| 82 | Dense extreme inception networkbased edge detection with d | Scientific Reports（Sci R | 2025年12月2日 | 鱼类/垃圾 |  | Aquarium数据集（Kaggle公开数据集，https://www.kaggle.com/datasets/slav |
| 83 | Lightweight enhanced YOLOv8n underwater object detection n | Scientific Reports（Sci R | 2024年11月13 | 增强+检测 |  | RUOD（14000张，训练9800/验证4200，10类：鱼、潜水员、海星、珊瑚、海龟、海胆、海参、扇贝、鱿鱼、水母） |
| 84 | Intelligent underwater mine detection using multi-backbone | Scientific Reports（Sci R | 2026年5月12日 | 声纳 |  | Side-Scan Sonar Imaging for Mine Detection（Kaggle公开数据集，https |
| 85 | An accurate realtime underwater object segmentation using  | Scientific Reports（Sci R | 2026年1月7日（ | 增强 |  | 自建水下数据集（7420张高分辨率图像，含鱼类、珊瑚、水下人造物等，按80:10:10划分训练/验证/测试）+ 多个公开 |
| 86 | An improved YOLOv11 network for marine debris detection in | Scientific Reports（Sci R | 2026年2月3日（ | 鱼类/垃圾 | [代码](https://github.com/DavidJing777/yolo-marine) | TrashCan-Instance（7212张，训练6065/验证1147，22类）+ TrashCan-Materia |
| 87 | Deep-AquATTEN: a hybrid multi-module attention architectur | Scientific Reports（Sci R | 2026年 | 鱼类/垃圾 |  | YOLO-ViT数据集（4764张，训练4221/验证287/测试256，10类鱼类，经旋转/灰度变换增强）+ Croa |
| 88 | An owl-inspired temporal transformer for enhanced shrimp d | Scientific Reports（Sci R | 2026年 | 鱼类/垃圾 |  | 自建水下虾类数据集（UVBDS套件，100张含标注图像，70%训练/15%验证/15%测试，YOLO格式） |
| 89 | Research on multi-scale fusion image enhancement and impro | Scientific Reports（Sci R | 2024年11月16 | 增强+检测 |  | URPC2020（5543张，训练/验证/测试按8:1:1，4类：海参、海胆、扇贝、海星）+ 自建ROV水池数据集（32 |
| 90 | Research on underwater disease target detection method of  | Scientific Reports（Sci R | 2025年 | 检测 |  | 自建侧扫声纳病害数据集（共1663张，训练/验证8:2，3类：沉船1049张、溺亡人员358张、护岸破损256张） |
| 91 | A Lightweight underwater detector enhanced by Attention me | Scientific Reports（Sci R | 2024年 | 增强+检测 | [代码](文中注明补充材料在线可用（https://doi.org/10.1038/s41598-024-75809-z）) | URPC2020（5543张，训练/验证/测试按7:2:1，4类：海胆、海参、扇贝、海星） |
| 92 | Integrating simplified Swin-T with modified EFS-Net for at | Scientific Reports（Sci R | 2026年2月2日（ | 检测 |  | HOMOMO（自建，123876张，1920×1080，训练60%/验证20%/测试20%，二分类：管道/非管道）+ R |
| 93 | AquaYOLO: Advanced YOLO-based fish detection for optimized | Scientific Reports（Sci R | 2025年 | 鱼类/垃圾 |  | DePondFi（自建，8150张，约5万标注框，训练5705/验证1630/测试815，南印度泰米尔纳德邦4个养鱼场区 |
| 94 | SCSFish2025: a large dataset from South China sea for cora | Scientific Reports（Sci R | 2025年8月17日 | 鱼类/垃圾 | [代码](https://github.com/FudanZhengSYSU/SCSFish2025) | SCSFish2025（自建，11956张，1920×1080，30类珊瑚礁鱼类，120084个标注框，含模糊/遮挡/姿 |

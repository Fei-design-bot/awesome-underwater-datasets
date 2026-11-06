# 数据集清单

> 共 39 个数据集，名称/规模/类别/链接均来自调研文献原文。

## 目标检测 · 光学

| 名称 | 英文/全称 | 规模 | 类别 | 链接 | 备注 |
|---|---|---|---|---|---|
| **URPC2017** | Underwater Robot Picking Contest 2017 | 训练 17,655 / 测试 985 | 4 类（海参/海胆/扇贝/海星） | URPC 系列公开镜像（openi / github） | 水下机器人抓取竞赛，720×405 |
| **URPC2018** | Underwater Robot Picking Contest 2018 | 训练 2,901 / 测试 800 | 4 类 | URPC 系列公开镜像 | 多分辨率 |
| **URPC2020** | Underwater Robot Picking Contest 2020 | 7,543（训练 5,543/验证 800/测试 1,200） | 4 类 | https://www.kaggle.com/datasets/lywang777/urpc2020 | 使用最广的竞赛数据 |
| **URPC2021** | Underwater Robot Picking Contest 2021 | — | 4 类 | URPC 系列公开镜像 | 水下小目标 |
| **DUO** | Detecting Underwater Objects | 7,782（验证 1,111） | 4 类 | https://github.com/chongweiliu/DUO | 源自 URPC2017-2020 感知哈希去重 |
| **RUOD** | Rethinking Underwater Object Detection | 14,000（训练 9,800/验证 4,200） | 10 类 | https://github.com/dlut-dimt/RUOD | 通用水下检测基准 |
| **UDD** | Underwater Dataset for Detection | 2,227 张 4K | 3 类（海参/海胆/扇贝） | https://github.com/chongweiliu/UDD_Official | 开放海洋养殖场 |
| **AUDD** | Aquatic UDD（扩增） | 18,457 张 | — | 随 UDD_Official 发布 | Poisson GAN 扩增 |
| **UTDAC2020** | Underwater Target Detection and Counting | 6,461（训练 5,168/测试 1,293） | 4 类 | 官方赛事数据 | 多分辨率 |
| **Brackish** | Brackish Underwater CV | 14,518 张 / 28,518 框 | 6 类（螃蟹/鱼/水母/虾/小鱼/海星） | 公开数据集 | 含大量小目标 |
| **COU** | Common Objects Underwater | 9,757 张 | 24 类人造物体 | https://z.umn.edu/cou-dataset | 泳池/湖泊/海洋三环境 |
| **Aquarium** | Aquarium Dataset | 1,400 张 | 7 类 | https://www.kaggle.com/datasets/slavkoprytula/aquarium-data-cots | Kaggle 公开 |
| **S-UODAC2020** | Underwater Object Detection & Counting | 7 种域类型各 791 张 | 4 类 | 随论文索取 | 多域 |

## 声纳检测

| 名称 | 英文/全称 | 规模 | 类别 | 链接 | 备注 |
|---|---|---|---|---|---|
| **SCTD** | Sonar Common Target Detection | — | 多类 | 公开数据集 | 声纳通用目标检测 |
| **Orca 声纳** | Orca Sonar Dataset | 6,000→12,000（增强） | 8 类 | 开源项目 | 立方体/人体/球体/圆柱体等 |
| **Side-Scan Sonar Mine** | Sonar Imaging Mine Detection | 668 张 | 2 类（水雷/非水雷） | https://www.kaggle.com/datasets/sierra022/sonar-imaging-mine-detection/data | 侧扫声纳 |
| **Marine Debris (FLS)** | Marine Debris FLS Datasets | 1,869 张 | 11 类 | https://github.com/mvaldenegro/marine-debris-fls-datasets | 前视声纳垃圾 |

## 垃圾 · 实例分割

| 名称 | 英文/全称 | 规模 | 类别 | 链接 | 备注 |
|---|---|---|---|---|---|
| **DebrisVision** | Synthetic-to-Real Marine Debris | 25,000（9,430 真实+15,570 合成） | 多类 | https://github.com/EswarMachara/DebrisVision | 框+掩码+深度+文本 |
| **SeaClear** | Marine Debris Dataset | 8,610 张 | 40 类 | https://data.4tu.nl/datasets/4f1dff25-e157-4399-a5d4-478055461689 | 垃圾/动植物/机器人部件 |
| **TrashCan** | TrashCan-Instance | 7,212（训练 6,065/验证 1,147） | 22 类 | https://www.godac.jamstec.go.jp/catalog/dsdebris/e/index.html | 含 ROV 与动植物 |

## 图像增强

| 名称 | 英文/全称 | 规模 | 类别 | 链接 | 备注 |
|---|---|---|---|---|---|
| **UIEB** | Underwater Image Enhancement Benchmark | 950 张 | — | https://li-chongyi.github.io/proj_benchmark.html | 增强最常用基准 |
| **LSUI** | Large-Scale Underwater Image | — | — | https://github.com/LintaoPeng/U-shape_Transformer_for_Underwater_Image_Enhancement | 大规模真实水下 |
| **SUIM-E** | SUIM Enhancement | — | — | https://li-chongyi.github.io/proj_benchmark.html |  |
| **USIS10K** | Underwater Salient Instance Segmentation | 10,000 张 | 实例分割 | https://github.com/doilion/UCIS |  |
| **UJED** | Underwater Joint Enhancement | — | — | https://drive.google.com/drive/folders/1KiMzLJUgL0Y1zAQmyfXt4KhZCTc59HAB |  |
| **TI-UIED** | Task-Inspired UIED | — | — | https://pan.baidu.com/s/1bn0ZRFZYGz1TaNzTwrDwew?pwd=v7fv | 任务驱动 |
| **UFO-120** | Underwater Flying Objects | 120 序列 | — | https://li-chongyi.github.io/proj_benchmark.html |  |
| **UF7D** | Underwater Fish 7 Dataset | — | — | https://www.dropbox.com/scl/fo/ab7eim7wh5ezlwfh43v6l/AHCChi7xj9stdV48AT1Ati0 |  |

## 显著性

| 名称 | 英文/全称 | 规模 | 类别 | 链接 | 备注 |
|---|---|---|---|---|---|
| **USOD10K** | Underwater Salient Object Detection | 10,000 张 | 显著性 | https://github.com/LinHong-HIT/USOD10K |  |
| **USOD / RMAS** | Underwater Salient Object Detection | — | 显著性 | https://github.com/LinHong-HIT/USOD10K |  |

## 鱼类 · 水产

| 名称 | 英文/全称 | 规模 | 类别 | 链接 | 备注 |
|---|---|---|---|---|---|
| **Fish4Knowledge** | F4K | 鱼类视频 | 单类（鱼） | 公开数据集 | 经典鱼类视频基准 |
| **LFIW** | Labeled Fishes in the Wild | 873 张有效 | 单类（鱼） | https://www.fisheries.noaa.gov/west-coast/science-data/labeled-fishes-wild | NOAA 官方 |
| **SCSFish2025** | South China Sea Coral Reef Fish | 11,956 张 | 30 类珊瑚礁鱼类 | https://github.com/FudanZhengSYSU/SCSFish2025 | 含模糊/遮挡/姿态困难样本 |
| **DePondFi** | DePond Fish | 8,150 张 | 多鱼种 | 随论文索取 | 南印度养鱼场 |
| **DeepFish / OzFish** | Fish Detection | 4,505 / 2,305 张 | 鱼类 | 公开数据集 | 跨数据集泛化测试 |

## 视频 · 3D

| 名称 | 英文/全称 | 规模 | 类别 | 链接 | 备注 |
|---|---|---|---|---|---|
| **VF5K** | Underwater Video Fish 5K | 5,000 段视频 | 鱼类视频 | 随代码发布 | 视频检测/跟踪 |
| **BrackishMOT-M4FT** | Brackish Multi-Object Tracking | — | 多目标跟踪 | https://drive.google.com/drive/folders/1wZiD702m6Nyje58PzWBT5jEKm4Mt1E9B |  |
| **Water3D / Sea-thru / FLSea / SQUID** | Underwater 3D Geometry | — | 3D | 随开源代码发布 | 水下 3D 几何 |
| **WebUOT-1M / UOT32 / UTB180 / UW-COT220** | Underwater Object Tracking | — | 跟踪 | 公开数据集 | 水下目标跟踪 |

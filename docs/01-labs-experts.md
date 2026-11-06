# 维度 1 · 国内外实验室与核心学者

> 以下团队与学者均提取自调研文献的作者列，按研究方向归纳。

## 国内团队

| 机构 | 核心人物 | 代表工作 | 备注 |
|---|---|---|---|
| 大连海事大学 | Jingchun Zhou（周景春）、Zongxin He | AMSP-UOD（AAAI'24，涡旋卷积+随机扰动） | 水下目标检测代表性工作，代码开源 |
| 香港理工大学 | Kin-Man Lam（林健民） | AMSP-UOD 合作者 | 国际知名视觉学者 |
| 哈尔滨工程大学 | Yiteng Guo（郭毅腾）、Weidong Zhang | RHCNet（CVPR'26）、MFPD（SPL'26） | 残差引导校准、Mamba 解码 |
| 深圳大学 | Wenjia Ouyang、Weidong Qiu、Xiaopin Zhong、Zongze Wu | IEUOD（ICASSP'26，增强浅层特征引导检测） |  |
| 中国海洋大学 | Bosen Lin、Feng Gao、Junyu Dong（董军宇） | Downstream Task-Inspired UIE（TIP'26）、Adaptive Semantic-Aware（TGRS'26） | 增强系列多篇顶刊 |
| 重庆大学 | Fulin Luo、Bo Du（杜博） | YOLO-UOD（TGRS'26）、Color Correction Meets Cross-Spectral（TMM'26） |  |
| 南京团队 | Wujie Zhou（周武杰）、Beibei Tang | Turbidity-Similarity Decoupling（TIP'26）、Prompt Then Refine SAM（TNNLS'26） | 显著性+解耦 |
| 大连理工大学 | Chongwei Liu（刘崇巍）、Zhihui Wang | DUO/UDD/AUDD 数据集、AquaNet（TCSVT'21） | 提供领域广泛使用的数据集 |
| 华中科技大学 / 海南大学 / 岭南大学 | WaterFlow 作者团队 | WaterFlow（ICASSP'26，物理先验 Rectified Flow） |  |
| 台湾团队 | Ching-Heng Cheng；Xuhang Chen | WWE-UIE（WACV'26）、AquaClarity（TCE'26） |  |

## 国外团队

| 机构 | 核心人物 | 代表工作 | 备注 |
|---|---|---|---|
| DebrisVision 团队 | Sivaji Retta、Sai Manikanta Eswar Machara、Iyyakutti Iyappan Ganapathi | DebrisVision（ICCV'25）、AquaticCLIP（TNNLS'26） | 多模态数据集 + VLM 基础模型 |
| WACV 诊断团队 | Melanie Wille、Tobias Fischer、Scarlett Raine | Are All Marine Species Created Equal?（WACV'26） | 类别性能差异诊断 |
| IIT Guwahati | Alik Pramanick、Arijit Sur | D2Mamba（WACV'26，双域状态空间搜索） |  |
| 土耳其团队 | Andac Findikq、Huseyin Aydilek | Melan-YOLO（Sci Rep'26） |  |
| 日本团队 | Cong Thanh Dang、Hiroshi Sato、Masao Kubo | DWP2-YOLO11（可变形卷积） |  |
| 德国团队 | Ganzorig Baatar、Divas Karimanzira、Thomas Rauschenbach | 前视声纳目标检测 |  |
| Wat3R 团队 | Jiangwei Ren、Xingyu Jiang、Zijie Song | Wat3R（ECCV'26，水下 3D 几何） |  |

## 使用建议

- **数据与基准**：大连理工（DUO/UDD/AUDD）、DebrisVision 等团队提供了领域广泛使用的数据集；
- **检测方法**：大连海事（AMSP-UOD）、哈工程（RHCNet/MFPD）等团队提出了代表性检测架构；
- **诊断与基础模型**：WACV 类别差异诊断、AquaticCLIP 等可作为选题与上游预训练的参考。

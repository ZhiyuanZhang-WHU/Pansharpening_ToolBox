# Pansharpening_ToolBox
# 多光谱与全色图像融合开源代码参考
本项目基于有监督与无监督的多光谱图像融合方法，整理最新的pansharpening开源工作，方便该领域科研人员与爱好者了解该领域的最新进展！

This project is built upon supervised and unsupervised pansharpening methods. It organizes the latest open-source work related to pansharpening, making it convenient for researchers and enthusiasts in this field to stay updated on the latest advancements!
## Supervised pansharpening

| Methods  | Name |Articles |Code| Conferences or Journals |Publish Year |
| ------------- | ------------- |------------- |------------- |------------- |------------- |
| PNN | Pansharpening by Convolutional Neural   Networks  | [article](https://www.mdpi.com/2072-4292/8/7/594) |  [code](https://github.com/ThomasWangWeiHong/Pansharpening-by-Convolutional-Neural-Network)  | Remote Sens.  |2016 |
|  DRPNN | Boosting the Accuracy of Multispectral Image Pansharpening by Learning a Deep Residual Network  | [article](https://ieeexplore.ieee.org/abstract/document/8012503)  | [code](https://github.com/Decri/DRPNN-Deep-Residual-Pan-sharpening-Neural-Network)  | GRSL| 2017 |
|  FusionNet | Detail Injection-based Deep Convolutional Neural Networks for Pansharpening  | [article](https://ieeexplore.ieee.org/document/9240949)  | [code](https://github.com/liangjiandeng/FusionNet)  | TGRS | 2020 |
|  HyperTransformer | HyperTransformer: A Textural and Spectral Feature Fusion Transformer for Pansharpening  | [article](https://ieeexplore.ieee.org/abstract/document/9880014)  | [code](https://github.com/wgcban/HyperTransformer?tab=readme-ov-file)  | CVPR | 2022  |
|  ADKNet |Source-Adaptive Discriminative Kernels based Network for Remote Sensing Pansharpening  | [article](https://www.ijcai.org/proceedings/2022/179)  | [code](https://github.com/liangjiandeng/ADKNet)  | IJCAI | 2022  |
|  Hyper-DSNet | A Deep-Shallow Fusion Network with Multi-Detail Extractor and Spectral Attention for Hyperspectral Pansharpening  | [article](https://ieeexplore.ieee.org/document/9870551)  | [code](https://github.com/liangjiandeng/Hyper-DSNet)  |JSTARS | 2022  |
|  MSDDN |Multi-scale Dual Domain Guidance Network for Pan-sharpening  | [article](https://ieeexplore.ieee.org/document/10119207)  | [code](https://github.com/alexhe101/MSDDN)  | TGRS | 2023 |
|  BiMPan |Bidomain Modeling Paradigm for Pansharpening  | [article](https://dl.acm.org/doi/10.1145/3581783.3612188)  | [code](https://github.com/coder-qicao/BiMPan)  | ACM MM | 2023 |
|  P2Sharpen |P2Sharpen: A progressive pansharpening network with deep spectral transformation | [article](https://www.sciencedirect.com/science/article/pii/S1566253522001798)  | [code](https://github.com/Baixuzx7/P2Sharpen)  | IF| 2023 |
|  PGCU |Probability-based Global Cross-modal Upsampling for Pansharpening  | [article](https://arxiv.org/abs/2303.13659)  | [code](https://github.com/Zeyu-Zhu/PGCU)  | CVPR| 2023 |



## Unsupervised pansharpening

| Methods  | Name |Articles |Code| Conferences or Journals |Publish Year |
| ------------- | ------------- |------------- |------------- |------------- |------------- |
|Pan-GAN  | Pan-GAN: An unsupervised pan-sharpening   method for remote sensing image fusion  | [article](https://www.sciencedirect.com/science/article/pii/S1566253520302591)  | [code](https://github.com/yuwei998/PanGAN)  | IF| 2020 |
|UCNN  | Pansharpening via Unsupervised Convolutional   Neural Networks  | [article](https://ieeexplore.ieee.org/abstract/document/9136909)  |  | JSTARS| 2020 |
|PGMAN  | PGMAN: An Unsupervised Generative Multiadversarial Network for Pansharpening  | [article](https://arxiv.org/abs/2012.09054)  | [code](https://github.com/zhysora/PGMAN) | JSTARS| 2021 |
|LDPNet  | PGMAN: An Unsupervised Generative Multiadversarial Network for Pansharpening  | [article](https://arxiv.org/abs/2111.12483)  | [code](https://github.com/NWPUZhoufei/LDP-Net) | CVPR| 2021 |
|UCGAN  | Unsupervised Cycle-Consistent Generative   Adversarial Networks for Pan Sharpening  | [article](https://ieeexplore.ieee.org/abstract/document/9755137)  | [code](https://github.com/zhysora/UCGAN) | TGRS| 2022 |
|Lambda-PNN  | Unsupervised Deep Learning-based Pansharpening with Jointly-Enhanced Spectral and Spatial Fidelity | [article](https://ieeexplore.ieee.org/document/10198408)  |  [code](https://github.com/matciotola/Lambda-PNN) | TGRS| 2023|
|USCPNet  | Unsupervised Pan-Sharpening Network Incorporating Imaging Spectral Prior and Spatial-Spectral Compensation | [article](https://ieeexplore.ieee.org/document/10583923)  |  | TGRS| 2024 |
|PLRDiff  | Unsupervised Hyperspectral Pansharpening via Low-rank Diffusion Model | [article](https://www.sciencedirect.com/science/article/pii/S1566253524001039)  |  [code](https://github.com/xyrui/PLRDiff) | IF| 2024 |
|ZS-Pan  | Zero-shot Semi-supervised Learning for Pansharpening | [article](https://www.sciencedirect.com/science/article/pii/S1566253523003172)  |  [code](https://github.com/coder-qicao/ZS-Pan) | IF| 2024 |

## Evaluation Metrics

### Supervised
PSNR、SSIM、ERGAS、SAM、Q

### Unsupervised
$D_Lambda$、$D_s$、$QNR$


## Useful Collections
以下链接包含pansharpening任务常见的开源代码集合以及公开数据集、评价指标等。

The following links contains a collection of commonly used open-source codes for the pansharpening task, as well as public datasets, evaluation metrics, and so on.

[DLPan-Toolbox](https://github.com/liangjiandeng/DLPan-Toolbox)

[Pancollection](https://github.com/liangjiandeng/PanCollection)

[FuseBox](https://github.com/sjtrny/FuseBox)









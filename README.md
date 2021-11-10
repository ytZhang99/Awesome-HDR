# Awesome-HDR (in progress)
Collect High Dynamic Range Imaging Related Papers and Codes.
Especially for Multi-exposure Fusion and High Dynamic Range Imaging

## Deep Learning Based Approaches

### 2021
| Title                   | Model                               | Paper                         | Code                          |     Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|----------------------------|-------|
|ADNet: Attention-guided deformable convolutional network for high dynamic range imaging | ADNet | [CVPR-2021W](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Liu_ADNet_Attention-Guided_Deformable_Convolutional_Network_for_High_Dynamic_Range_Imaging_CVPRW_2021_paper.pdf) | [ADNet](https://github.com/Pea-Shooter/ADNet) | Deformable Convolution | Dynamic |
|Deep Coupled Feedback Network for Joint Exposure Fusion and Image Super-Resolution | CF-Net | [TIP-2021](https://www.researchgate.net/profile/Yutong-Zhang-27/publication/349458866_Deep_Coupled_Feedback_Network_for_Joint_Exposure_Fusion_and_Image_Super-Resolution/links/60ab15e2a6fdcc6d626d23f3/Deep-Coupled-Feedback-Network-for-Joint-Exposure-Fusion-and-Image-Super-Resolution.pdf) | [CF-Net](https://github.com/ytZhang99/CF-Net) | Joint MEF and SR, Feedback Mechanism | Static |
|Labeled from Unlabeled: Exploiting Unlabeled Data for Few-shot Deep HDR Deghosting | FSHDR | [CVPR-2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Prabhakar_Labeled_From_Unlabeled_Exploiting_Unlabeled_Data_for_Few-Shot_Deep_HDR_CVPR_2021_paper.pdf) | [FSHDR](https://github.com/Susmit-A/FSHDR) | Few-shot Learning | Dynamic |

### 2020
| Title                   | Model                               | Paper                         | Code                          |            Main Idea or Key Words | Label |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|-----------------------------------|-------|
|Deep Convolutional Neural Network for Multi-modal Image Restoration and Fusion | CU-Net | [TPAMI-2020](https://arxiv.org/pdf/1910.04066) | [CU-Net](https://github.com/cindydeng1991/TPAMI-CU-Net) | Interpretable Network, Multi-modal image processing | Static |
|U2Fusion: A Unified Unsupervised Image Fusion Network | U2Fusion | [TPAMI-2020](https://www.researchgate.net/profile/Jiayi-Ma-2/publication/343218239_U2Fusion_A_Unified_Unsupervised_Image_Fusion_Network/links/5f1fd81645851515ef50431c/U2Fusion-A-Unified-Unsupervised-Image-Fusion-Network.pdf) | [U2Fusion](https://github.com/hanna-xu/U2Fusion) | Unsupervised Learning | Static |
|Deep Guided Learning for Fast Multi-Exposure Image Fusion | MEF-Net | [TIP-2020](https://ece.uwaterloo.ca/~k29ma/papers/19_TIP_MEF-Net.pdf)| [MEF-Net](https://github.com/makedede/MEFNet) | Unsupervised Learning, Guided Filter | Static |
|Deep HDR Imaging via A Non-Local Network| NHDRRnet | [TIP-2020](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8989959) | [NHDRRnet](https://github.com/tuvovan/NHDRRNet) | Non-local | Dynamic |

## Traditional Approaches
| Title                   | Model                               | Paper                         | Code                          |            Main Idea or Key Words | Label | Year |
|-------------------------|-------------------------------------|-------------------------------|-------------------------------|-----------------------------------|-------|------|
|Detail-Preserving Multi-Exposure Fusion with Edge-Preserving Structural Patch Decomposition | MSPD-MEF | [TCSVT-2021](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9330785) | [MSPD-MEF](https://github.com/xiaohuiben/MESPD_TCSVT-2021) | Structural Patch Decomposition | Static & Dynamic | 2021 |
|Fast Multi-Scale Structural Patch Decomposition for Multi-Exposure Image Fusion | FMMEF | [TIP-2020](https://ece.uwaterloo.ca/~k29ma/papers/20_TIP_MS-SPF-MEF.pdf) | [FMMEF](https://github.com/xiaohuiben/fmmef-TIP-2020) | Multi-scale, Structural Patch Decomposition | Static & Dynamic |2020|
|Robust Multi-Exposure Image Fusion: A Structural Patch Decomposition Approach| SPD-MEF | [TIP-2017](https://ece.uwaterloo.ca/~k29ma/papers/17_TIP_SPD-MEF.pdf) | [SPD-MEF](https://ece.uwaterloo.ca/~k29ma/codes/SPD-MEF.rar) | Robust, Structural Patch Decomposition | Static & Dynamic | 2017 |
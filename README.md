
# Awesome Camouflaged Object Detection <a href="https://github.com/sindresorhus/awesome"><img src="figs/awesome.png" alt="Awesome" style="max-width: 100%;" width="100"></a>

A curated collection of awesome resources for **Camouflaged Object Detection (COD)**, including: 
- Camouflaged/Concealed Object Detection (COD)  
- Camouflaged/Concealed Object Segmentation (COS)  
- Camouflaged/Concealed Scene Understanding (CSU)
  
🔥 We commit to maintaining regular updates to ensure the continuous enhancement of this resource.

:loudspeaker: [08/2024] Update ECCV2024, MM2024 papers.  
:loudspeaker: [04/2024] Update CVPR2024 papers.  
:loudspeaker: [01/2024] Update ICLR2024, WACV2024 papers.   
:loudspeaker: [12/2023] Update NeurIPS2023, AAAI2024 papers.   
:loudspeaker: [08/2023] Update ICCV2023, MM2023, etc. papers for COD and CIS.   
:loudspeaker: [04/2023] Update CVPR2023 papers for COD and CIS.

:heavy_exclamation_mark: <sub>![Static Badge](https://img.shields.io/badge/dataset-grey)</sub>

--------------------------------------------------------------------------------------

<!--TOC-->

## Content:
<!-- - [Overview](#Overview) -->
- [Preprint](#Preprint)
- [Camouflaged Object Detection (COD)](#COD)
- [Video Camouflaged Object Detection (VCOD)](#VCOD)
- [Camouflaged Instance Segmentation (CIS)](#CIS)
- [Weakly-supervised COD](#WSCOD)
- [Zero-Shot COD](#Zero-Shot-COD)
- [Referring COD](#RefCOD)
- [Open-Vocabulary COS](#OVCOS)
- [RGB-P COS](#RGBP-COS)
- [Other Related](#Other-Related)
- [Datasets](#Datasets)
- [Appendix](#Appendix)

--------------------------------------------------------------------------------------



<!--Transformer for COD:
  1) [COD] Boosting COD with Boosting Camouflaged Object Detection with Dual-Task Interactive Transformer, ICPR
-->


## :triangular_flag_on_post: Highlight :triangular_flag_on_post:
<!--:triangular_flag_on_post:-->

- **Referring Camouflaged Object Detection** `R2CNet` <sub>![Static Badge](https://img.shields.io/badge/R2C7K-grey)</sub> <br>
  Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng <br>
  *TPAMI*, 2025
  <sub>[![Static Badge](https://img.shields.io/badge/Paper-white?logoSize=auto)](https://arxiv.org/abs/2306.07532)</sub>
  <sub>[![Static Badge](https://img.shields.io/badge/Code-white?logoSize=auto)](https://github.com/zhangxuying1004/RefCOD)</sub>

- **ZoomNeXt: A Unified Collaborative Pyramid Network for Camouflaged Object Detection** `ZoomNeXt` <br> 
  Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu <br>
  *TPAMI*, 2024
  <sub>[![Static Badge](https://img.shields.io/badge/Paper-white?logoSize=auto)](https://arxiv.org/abs/2310.20208)</sub>
  <sub>[![Static Badge](https://img.shields.io/badge/Code-white?logoSize=auto)](https://github.com/lartpang/ZoomNeXt)</sub>

- **Leveraging Hallucinations to Reduce Manual Prompt Dependency in Promptable Segmentation** `ProMaC` <br> 
  Jian Hu, Jiayi Lin, Junchi Yan, Shaogang Gong <br> 
  *NeurIPS*, 2024 
  <sub>[![Static Badge](https://img.shields.io/badge/Paper-white?logoSize=auto)](https://arxiv.org/abs/2408.15205)</sub>
  <sub>[![Static Badge](https://img.shields.io/badge/Code-white?logoSize=auto)](https://github.com/lwpyh/ProMaC_code)</sub>

- **Spider: A Unified Framework for Context-dependent Concept Understanding** `Spider` <br>
  Xiaoqi Zhao, Youwei Pang, Wei Ji, Baicheng Sheng, Jiaming Zuo, Lihe Zhang, Huchuan Lu <br>
  *ICML*, 2024
  <sub>[![Static Badge](https://img.shields.io/badge/Paper-white?logoSize=auto)](https://arxiv.org/abs/2405.01002)</sub>
  <sub>[![Static Badge](https://img.shields.io/badge/Code-white?logoSize=auto)](https://github.com/Xiaoqi-Zhao-DLUT/Spider-UniCDSeg)</sub>
  
- **Hierarchical Graph Interaction Transformer with Dynamic Token Clustering for Camouflaged Object Detection** `HGINet` <br>
  Siyuan Yao, Hao Sun, Tian-Zhu Xiang, Xiao Wang, Xiaochun Cao <br>
  *TIP*, 2024
  <sub>[![Static Badge](https://img.shields.io/badge/Paper-white?logoSize=auto)](https://arxiv.org/abs/2408.15020)</sub>
  <sub>[![Static Badge](https://img.shields.io/badge/Code-white?logoSize=auto)](https://github.com/Garyson1204/HGINet)</sub>




## Preprint

| **Pub.** | **Model** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| arXiv | <sup>`HPGT`</sup> | A Holistically Point-guided Text Framework for Weakly-Supervised Camouflaged Object Detection      <br> <sup><sub>*Tsui Qin Mok, Shuyong Gao, Haozhe Xing, Miaoyang He, Yan Wang, Wenqiang Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2501.06038)\|Code
| arXiv | <sup>`CaMF`</sup> | Towards Real Zero-Shot Camouflaged Object Segmentation without Camouflaged Annotations      <br> <sup><sub>*Cheng Lei, Jie Fan, Xinran Li, Tianzhu Xiang, Ao Li, Ce Zhu, Le Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2410.16953)\|[Code](https://github.com/R-LEI360725/ZSCOS-CaMF)
| arXiv | <sup>`AGLNet`</sup> | Adaptive Guidance Learning for Camouflaged Object Detection      <br> <sup><sub>*Zhennan Chen, Xuying Zhang, Tian-Zhu Xiang, Ying Tai*</sub></sup>  | [Paper](https://arxiv.org/abs/2405.02824)\|[Code](https://github.com/ZNan-Chen/AGLNet)
| arXiv | <sup>`-`</sup> | Leveraging Open-Vocabulary Diffusion to Camouflaged Instance Segmentation   <br> <sup><sub>*Tuan-Anh Vu, Duc Thanh Nguyen, Qing Guo, Binh-Son Hua, Nhat Minh Chung, Ivor W. Tsang, Sai-Kit Yeung*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.17505)\|Code 
| arXiv | <sup>`PAD`</sup> | Pre-train, Adapt and Detect: Multi-Task Adapter Tuning for Camouflaged Object Detection    <br> <sup><sub>*Yinghui Xing, Dexuan Kong, Shizhou Zhang, Geng Chen, Lingyan Ran, Peng Wang, Yanning Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.10685)\|Code
| arXiv | <sup>`UJSCODv2`</sup> | Joint Salient Object Detection and Camouflaged Object Detection via Uncertainty-aware Learning   <br> <sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Tong Zhang, Yiran Zhong, Mingyi He, Yuchao Dai*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.04651)\|[Code](https://npucvr.github.io/UJSCOD/) 
| arXiv | <sup>`DQnet`</sup> | DQnet: Cross-Model Detail Querying for Camouflaged Object Detection <br> <sup><sub>*Wei Sun, Chengao Liu, Linyan Zhang, Yu Li, Pengxu Wei, Chang Liu, Jialing Zou, Jianbin Jiao, Qixiang Ye*</sub></sup> | [Paper](https://arxiv.org/abs/2212.08296)\|[Code](https://github.com/CVPR23/DQnet) 
| arXiv |  <sup>`-`</sup>   | Exploring Depth Contribution for Camouflaged Object Detection <br> <sup><sub>*Mochu Xiang, Jing Zhang, Yunqiu Lv, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2106.13217v3)\|Code
| arXiv |  <sup>`MCIFNet`</sup> | Towards Accurate Camouflaged Object Detection with Mixture Convolution and Interactive Fusion <br> <sup><sub>*Bo Dong, Mingchen Zhuge, Yongxiong Wang, Hongbo Bi, Geng Chen*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.05687.pdf)\|[Code](https://github.com/BigHeartDB/MCIFNet)  
| arXiv |  <sup>`BASNet`</sup>  | Boundary-Aware Segmentation Network for Mobile and Web Applications <br> <sup><sub>*Xuebin Qin, Deng-Ping Fan, Chenyang Huang, et al.*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.04704.pdf)\|[Code](https://github.com/xuebinqin/BASNet) 



## COD 

### Review 

| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |  
| 2024 | AIR | A Survey of Camouflaged Object Detection and Beyond    <br> <sup><sub>*Fengyang Xiao, Sujie Hu, Yuqi Shen, Chengyu Fang, Jinfa Huang, Chunming He, Longxiang Tang, Ziyun Yang, Xiu Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.14562v1)\|[Res](https://github.com/ChunmingHe/awesome-concealed-object-segmentation) 
| 2024 | Neucom | A systematic review of image-level camouflaged object detection with deep learning  <br> <sup><sub>*Yanhua Liang, Guihe Qin, Minghui Sun, Xinchao Wang, Jie Yan, Zhonghan Zhang*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223011736)\|[Res.](https://github.com/Liangyh18/COD_survey)
| 2024 | MulSys | A survey on deep learning-based camouflaged object detection  <br> <sup><sub>*Junmin Zhong, Anzhi Wang, Chunhong Ren & Jintao Wu*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s00530-024-01478-7)\|
| 2023 | VI | Advances in Deep Concealed Scene Understanding   <sub>![Static Badge](https://img.shields.io/badge/CDS2K-grey)</sub>  <br> <sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Peng Xu, Ming-Ming Cheng, Christos Sakaridis, Luc Van Gool*</sub></sup> | [Paper](https://link.springer.com/article/10.1007/s44267-023-00019-6#article-info)\|[Proj](https://github.com/DengPingFan/CSU)  
| 2021 |  TCSVT  | Rethinking Camouflaged Object Detection: Models and Datasets   <br><sup><sub>*Hongbo Bi, Cong Zhang, Kang Wang, Jinghui Tong, Feng Zheng*</sub></sup>   | [Paper](https://ieeexplore.ieee.org/document/9598866)\|


### 2025 

| **Pub.** | **Model** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |  
| TPAMI<br><sup>2025</sup> | <sup>`CamoDiffusion`</sup> | Conditional Diffusion Models for Camouflaged and Salient Object Detection  <br> <sup><sub>*Ke Sun; Zhongxi Chen; Xianming Lin; Xiaoshuai Sun; Hong Liu; Rongrong Ji*</sub></sup>  <sup><sub>*/ AAAI2024 Extension*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10834569)\|[Code](https://github.com/Rapisurazurite/CamoDiffusion)
| AIR<br><sup>2025</sup>  | <sup>`PCNet`</sup> | PlantCamo: Plant Camouflage Detection  <sub>![Static Badge](https://img.shields.io/badge/PlantCamo-grey)</sub>  <br> <sup><sub>*Jinyu Yang and Qingwei Wang and Feng Zheng and Peng Chen and Aleš Leonardis and Deng-Ping Fan*</sub></sup>  | [Paper](https://arxiv.org/abs/2410.17598)\|[Code](https://github.com/yjybuaa/PlantCamo)   
| SCIS<br><sup>2025</sup>  | <sup>`COMPrompter`</sup> | COMPrompter: Reconceptualized Segment Anything Model with Multiprompt Network for Camouflaged Object Detection <br> <sup><sub>*Xiaoqin Zhang, Zhenni Yu, Li Zhao, Deng-Ping Fan, Guobao Xiao*</sub></sup>  | [Paper](https://arxiv.org/abs/2411.18858)\|[Code](https://github.com/guobaoxiao/COMPrompter) 
| NeuCom<br><sup>2025</sup> | <sup>`EFNet`</sup> | Promoting camouflaged object detection through novel edge–target interaction and frequency-spatial fusion    <br> <sup><sub>*Juwei Guan, Weiqi Qian, Tongxin Zhu, Xiaolin Fang*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231224018356)\|Code 
| EAAI<br><sup>2025</sup>  | <sup>`CLAD`</sup> | Enhancing camouflaged object detection through contrastive learning and data augmentation techniques <br> <sup><sub>*Cunhan Guo, Heyan Huang*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S095219762401861X)\|Code




### 2024

<!---->

| **Pub.** | **Model** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |  
| NeurIPS<br><sup>2024</sup>  | <sup>`ProMaC`</sup> | Leveraging Hallucinations to Reduce Manual Prompt Dependency in Promptable Segmentation <br> <sup><sub>*Jian Hu, Jiayi Lin, Junchi Yan, Shaogang Gong*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.15205)\|[Code](https://github.com/lwpyh/ProMaC_code)  
| TPAMI<br><sup>2024</sup>  | <sup>`ZoomNeXt`</sup> | ZoomNeXt: A Unified Collaborative Pyramid Network for Camouflaged Object Detection   <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup>  | [Offl.](https://ieeexplore.ieee.org/document/10568374)\|[arXiv](https://arxiv.org/abs/2310.20208)\|<br>[Code](https://github.com/lartpang/ZoomNeXt)  
| ECCV<br><sup>2024</sup> | <sup>`WSSCOD`</sup> | Learning Camouflaged Object Detection from Noisy Pseudo Label  `WSS COD`  <br> <sup><sub>*Jin Zhang, Ruiheng Zhang, Yanjiao Shi, Zhe Cao, Nian Liu, Fahad Shahbaz Khan*</sub></sup>  | [Paper](https://arxiv.org/abs/2407.13157)\|Code 
| ECCV<br><sup>2024</sup> | <sup>`CamoTeacher`</sup> | CamoTeacher: Dual-Rotation Consistency Learning for Semi-Supervised Camouflaged Object Detection `WSS COD`  <br> <sup><sub>*Xunfa Lai, Zhiyu Yang, Jie Hu, Shengchuan Zhang, Liujuan Cao, Guannan Jiang, Zhiyu Wang, Songan Zhang, Rongrong Ji*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.08050)\|Code 
| ECCV<br><sup>2024</sup> | <sup>`SAM-COD`</sup> | SAM-COD: SAM-guided Unified Framework for Weakly-Supervised Camouflaged Object Detection     <br> <sup><sub>*Huafeng Chen, Pengxu Wei, Guangqian Guo, Shan Gao*</sub></sup>  | [Paper](https://www.arxiv.org/abs/2408.10760)\|[Code](https://github.com/2231122/SAM-COD)
| ECCV<br><sup>2024</sup> | <sup>`PSCOD`</sup> | Just a Hint: Point-Supervised Camouflaged Object Detection  <sub>![Static Badge](https://img.shields.io/badge/P--COD-grey)</sub>   <br> <sup><sub>*Huafeng Chen, Dian Shao, Guangqian Guo, Shan Gao*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.10777v1)\|[Code](https://github.com/2231122/PCOD) 
| ECCV<br><sup>2024</sup> | <sup>`ACUMEN`</sup> | Unlocking Attributes' Contribution to Successful Camouflage: A Combined Textual and Visual Analysis Strategy <sub>![Static Badge](https://img.shields.io/badge/COD--TAX-grey)</sub>   <br> <sup><sub>*Hong Zhang, Yixuan Lyu, Qian Yu, Hanyang Liu, Huimin Ma, Ding Yuan, Yifan Yang*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.12086)\|[Code](https://github.com/lyu-yx/ACUMEN) 
| ECCV<br><sup>2024</sup> | <small><sup>`OVCoser`</sup></small> | Open-Vocabulary Camouflaged Object Segmentation    <sub>![Static Badge](https://img.shields.io/badge/OVCamo-grey)</sub>    <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Jiaming Zuo, Lihe Zhang, Huchuan Lu*</sub></sup>   | [Paper](https://arxiv.org/abs/2311.11241)\|[Code](https://github.com/lartpang/OVCamo)
| ECCV<br><sup>2024</sup>  | <small><sup>`FSEL`</sup></small> | Frequency-Spatial Entanglement Learning for Camouflaged Object Detection   <br> <sup><sub>*Yanguang Sun, Chunyan Xu, Jian Yang, Hanyu Xuan, Lei Luo*</sub></sup>  | [Paper](https://arxiv.org/abs/2409.01686)\|[Code](https://github.com/CSYSI/FSEL) 
| ECCV<br><sup>2024</sup>  | <small><sup>`FocusDiffuser`</sup></small> |	FocusDiffuser: Perceiving Local Disparities for Camouflaged Object Detection   <br> <sup><sub>*Jianwei Zhao, Xin Li, Fan Yang, Qiang Zhai, Ao Luo, Zicheng Jiao, Hong Cheng*</sub></sup>  | [Paper](https://arxiv.org/abs/2407.13133)\|[Code](https://github.com/JWZhao-uestc/FocusDiffuser) 
| MM<br><sup>2024</sup> | <sup>`DSAM`</sup> | Exploring Deeper! Segment Anything Model with Depth Perception for Camouflaged Object Detection   <br> <sup><sub>*Zhenni Yu, Xiaoqin Zhang, Li Zhao, Yi Bin, Guobao Xiao*</sub></sup>  | [Paper](https://arxiv.org/abs/2407.12339)\|[Code](https://github.com/guobaoxiao/DSAM)  
| MM<br><sup>2024</sup> | <sup>`MMCPF`</sup> | Chain of Visual Perception: Harnessing Multimodal Large Language Models for Zero-shot Camouflaged Object Detection  `ZS COD`   <br> <sup><sub>*Lv Tang, Peng-Tao Jiang, Zhihao Shen, Hao Zhang, Jinwei Chen, Bo Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.11273)\|[Code](https://github.com/luckybird1994/MMCPF)  
| MM<br><sup>2024</sup> | <sup>`TPNet`</sup> | Text-prompt Camouflaged Instance Segmentation with Graduated Camouflage Learning  <br> <sup><sub>*Zhentao He, Changqun Xia, Shengye Qiao, Jia Li*</sub></sup>  | Paper\|Code
| MM<br><sup>2024</sup> | <sup>`MiNet`</sup> | MiNet: Weakly-Supervised Camouflaged Object Detection through Mutual Interaction between Region and Edge Cues   <br> <sup><sub>*Yuzhen Niu, Lifen Yang, Rui Xu, Yuezhou Li, Yuzhong Chen*</sub></sup>  | [Paper](https://dl.acm.org/doi/10.1145/3664647.3680891)\|Code
| MM<br><sup>2024</sup> | <sup>`-`</sup> | Semi-supervised Camouflaged Object Detection from Noisy Data   <br> <sup><sub>*Yuanbin Fu, Jie Ying, Houlei Lv, Xiaojie Guo*</sub></sup>  | [Paper](https://dl.acm.org/doi/abs/10.1145/3664647.3680645)\|Code
| ICML<br><sup>2024</sup> |  <sup>`Spider`</sup>  | Spider: A Unified Framework for Context-dependent Concept Understanding    <br> <sup><sub>*Xiaoqi Zhao, Youwei Pang, Wei Ji, Baicheng Sheng, Jiaming Zuo, Lihe Zhang, Huchuan Lu*</sub></sup>  | [Paper](https://arxiv.org/abs/2405.01002)\|[Code](https://github.com/Xiaoqi-Zhao-DLUT/Spider-UniCDSeg) 
| CVPR<br><sup>2024</sup> |  <sup>`LAKE-RED`</sup>  | LAKE-RED: Camouflaged Images Generation by Latent Background Knowledge Retrieval-Augmented Diffusion `Gen`   <br> <sup><sub>*Pancheng Zhao, Peng Xu, Pengda Qin, Deng-Ping Fan, Zhicheng Zhang, Guoli Jia, Bowen Zhou, Jufeng Yang*</sub></sup>  | [Paper](https://arxiv.org/abs/2404.00292)\|[Code](https://github.com/PanchengZhao/LAKE-RED)
| CVPR<br><sup>2024</sup> |  <sup>`VSCode`</sup>  | VSCode: General Visual Salient and Camouflaged Object Detection with 2D Prompt Learning   <br> <sup><sub>*Ziyang Luo, Nian Liu, Wangbo Zhao, Xuguang Yang, Dingwen Zhang, Deng-Ping Fan, Fahad Khan, Junwei Han*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.15011)\|[Code](https://github.com/Sssssuperior/VSCode) 
| CVPR<br><sup>2024</sup> | <sup>`RISNet`</sup> | Depth-Aware Concealed Crop Detection in Dense Agricultural Scenes   <sub>![Static Badge](https://img.shields.io/badge/ACOD--12K-grey)</sub>    <br> <sup><sub>*Liqiong Wang, Jinyu Yang, Yanfu Zhang, Fangyi Wang, Feng Zheng*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Depth-Aware_Concealed_Crop_Detection_in_Dense_Agricultural_Scenes_CVPR_2024_paper.html)\|[Code](https://github.com/Kki2Eve/RISNet) 
| ICLR<br><sup>2024</sup> |  <sup>`ICEG`</sup>  | Strategic Preys Make Acute Predators: Enhancing Camouflaged Object Detectors by Generating Camouflaged Objects   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Yulun Zhang, Zhenhua Guo, Xiu Li, Martin Danelljan, Fisher Yu*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.03166)\|[Code](https://github.com/ChunmingHe/Camouflageator) 
| ICASSP<br><sup>2024</sup> | <sup>`EANet`</sup> | Edge Attention Learning for Efficient Camouflaged Object Detection   <br> <sup><sub>*Zijian Liu; Ping Jiang; Lixin Lin; Xiaoheng Deng*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10448139)\|Code 
| AAAI<br><sup>2024</sup> | <sup>`Camo`<br>`Diffusion`</sup> | CamoDiffusion: Camouflaged Object Detection via Conditional Diffusion Models   <br> <sup><sub>*Chen, Zhongxi and Sun, Ke and Lin, Xianming and Ji, Rongrong*</sub></sup>  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27890)\|[Code](https://github.com/Rapisurazurite/CamoDiffusion) 
| AAAI<br><sup>2024</sup> |  <sup>`GenSAM`</sup>  | Relax Image-Specific Prompt Requirement in SAM: A Single Generic Prompt for Segmenting Camouflaged Objects   <br> <sup><sub>*Jian Hu, Jiayi Lin, Weitong Cai, Shaogang Gong*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.07374)\|[Proj](https://lwpyh.github.io/GenSAM/)\|<br>[Code](https://github.com/jyLin8100/GenSAM) 
| WACV<br><sup>2024</sup> |  <sup>`CamoFocus`</sup>   | CamoFocus: Enhancing Camouflage Object Detection With Split-Feature Focal Modulation and Context Refinement   <br> <sup><sub>*Abbas Khan, Mustaqeem Khan, Wail Gueaieb, Abdulmotaleb El Saddik, Giulia De Masi, Fakhri Karray*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Khan_CamoFocus_Enhancing_Camouflage_Object_Detection_With_Split-Feature_Focal_Modulation_and_WACV_2024_paper.html)\|Code 
| --  | -- | -- | -- | 
| TPAMI<br><sup>2024</sup> | <sup>`CamoFormer`</sup> | CamoFormer: Masked Separable Attention for Camouflaged Object Detection   <br> <sup><sub>*Bowen Yin; Xuying Zhang; Deng-Ping Fan; Shaohui Jiao; Ming-Ming Cheng; Luc Van Gool; Qibin Hou*</sub></sup> | [Offl.](https://ieeexplore.ieee.org/document/10623294)\|[arXiv](https://arxiv.org/abs/2212.06570)\|<br>[Code](https://github.com/HVision-NKU/CamoFormer) 
| TIP<br><sup>2024</sup> | <sup>`HGINet`</sup> | Hierarchical Graph Interaction Transformer with Dynamic Token Clustering for Camouflaged Object Detection     <br> <sup><sub>*Siyuan Yao, Hao Sun, Tian-Zhu Xiang, Xiao Wang, Xiaochun Cao*</sub></sup>  | [Offl.](https://ieeexplore.ieee.org/document/10719619)\|[arXiv](https://arxiv.org/abs/2408.15020)\|<br>[Code](https://github.com/Garyson1204/HGINet)
| TIP<br><sup>2024</sup> |  <sup>`IdeNet`</sup> | IdeNet: Making Neural Network Identify Camouflaged Objects Like Creatures  <br> <sup><sub>*Juwei Guan; Xiaolin Fang; Tongxin Zhu; Zhipeng Cai; Zhen Ling; Ming Yang; Junzhou Luo*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10661228)\|[Code](https://github.com/whyandbecause/IdeNet) 
| IJCV<br><sup>2024</sup> |  <sup>`GateNetv2`</sup> | Towards Diverse Binary Segmentation via A Simple yet General Gated Network   <br> <sup><sub>*Xiaoqi Zhao, Youwei Pang, Lihe Zhang, Huchuan Lu, Lei Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.10396)\|[Code](https://github.com/Xiaoqi-Zhao-DLUT/GateNet-RGB-Saliency)\|<br>[Res.](https://github.com/Xiaoqi-Zhao-DLUT/Awesome-Unified-Context-dependent-Concept-Segmentation) 
| TNNLS<br><sup>2024</sup> | <sup>`GLCONet`</sup> | GLCONet: Learning Multi-source Perception Representation for Camouflaged Object Detection   <br> <sup><sub>*Yanguang Sun, Hanyu Xuan, Jian Yang, Lei Luo*</sub></sup>  | [Paper](https://arxiv.org/abs/2409.09588)\|[Code](https://github.com/CSYSI/GLCONet)
| TMM<br><sup>2024</sup> | <sup>`DINet`</sup> | Decoupling and Integration Network for Camouflaged Object Detection  <br> <sup><sub>*Xiaofei Zhou; Zhicong Wu; Runmin Cong*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10417767)\|Code 
| TMM<br><sup>2024</sup> | <sup>`FGSA-Net`</sup> |    Frequency-Guided Spatial Adaptation for Camouflaged Object Detection     <br> <sup><sub>*Shizhou Zhang, Dexuan Kong, Yinghui Xing, Yue Lu, Lingyan Ran, Guoqiang Liang, Hexu Wang, Yanning Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2409.12421)\|Code
| PR<br><sup>2024</sup> | <sup>`DSNet`</sup> | Camouflaged Object Detection via Dual-branch Fusion and Dual Self-similarity constraints     <br> <sup><sub>*Haozhe Yang, Yuan Zhu, Ke Sun, Haoyang Ding, Xianming Lin*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320324006460)\|Code 
| IF<br><sup>2024</sup> | <sup>`MAM-FFC`</sup> | Multidimensional fusion of frequency and spatial domain information for enhanced camouflaged object detection     <br> <sup><sub>*Tingran Wang, Zaiyang Yu, Jianwei Fang, Jinlong Xie, Feng Yang, et al.*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1566253524006493)\|[Code](https://github.com/CHANTILLY2023/MAMIFNet) 
| KBS<br><sup>2024</sup> | <sup>`SDRNet`</sup>  | SDRNet: Camouflaged object detection with independent reconstruction of structure and detail   <br> <sup><sub>*Juwei Guan, Xiaolin Fang, Tongxin Zhu, Weiqi Qian*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705124006853)\|[Code](https://github.com/whyandbecause/SDRNet/)
| ESWA<br><sup>2024</sup> | <sup>`BiDiCOS`</sup>  | BiDiCOS: Camouflaged object segmentation via bilateral diffusion model    <br> <sup><sub>*Xinhao Jiang, Wei Cai, Yao Ding, Xin Wang, Danfeng Hong, Xingyu Di, Weijie Gao*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417424016142)\|[Code](https://github.com/jiangxinhao2020/BiDiCOS)
| TCSVT<br><sup>2024</sup> | <sup>`MVGNet`</sup> |   A Universal Multi-View Guided Network for Salient Object and Camouflaged Object Detection  <br> <sup><sub>*Xiaogang Song; Pengfei Zhang; Xiaofeng Lu; Xinhong Hei; Rongrong Liu*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10568109)\|[Code](https://github.com/1900zpf/MVGNet)
| TCSVT<br><sup>2024</sup> | <sup>`DRFNet`</sup> |  Learning Discriminative Representations From Cross-Scale Features for Camouflaged Object Detection   <br> <sup><sub>*Yongchao Wang; Xiuli Bi; Bo Liu; Yang Wei; Weisheng Li; Bin Xiao*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10616011)\|Code
| TCSVT<br><sup>2024</sup> | <sup>`CoNet`</sup> | CoNet: A Consistency-Oriented Network for Camouflaged Object Segmentation   <br> <sup><sub>*Fei Wu; Jun Yin; Xiaochuan Li; Jianfeng Wu; Da Jin; Jiamin Yang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10681598)\|Code
| TCSVT<br><sup>2024</sup> | <sup>`FDRNet`</sup> | Edge Perception Camouflaged Object Detection under Frequency Domain Reconstruction   <br> <sup><sub>*Zijian Liu; Xiaoheng Deng; Ping Jiang; Conghao Lv; Geyong Min; Xin Wang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/10536093)\|Code 
| TCSVT<br><sup>2024</sup> | <sup>`PRNet`</sup> | Efficient Camouflaged Object Detection Network Based on Global Localization Perception and Local Guidance Refinement     <br> <sup><sub>*Xihang Hu; Xiaoli Zhang; Fasheng Wang; Jing Sun; Fuming Sun*</sub></sup>    | [Paper](https://ieeexplore.ieee.org/abstract/document/10379651)\|[Code](https://github.com/hu-xh/PRNet) 
| TCSVT<br><sup>2024</sup> | <sup>`CMNet`</sup> | Finding Camouflaged Objects Along the Camouflage Mechanisms   <br> <sup><sub>*Yang Yang; Qiang Zhang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10231131)\|Code 
| CVIU<br><sup>2024</sup> | <sup>`DCPNet`</sup> | Dual cross perception network with texture and boundary guidance for camouflaged object detection   <br> <sup><sub>*Yaming Wang, Jiatong Chen, Xian Fang, Mingfeng Jiang, Jianhua Ma*</sub></sup>    | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1077314224002121)\|Code
| CVIU<br><sup>2024</sup> | <sup>`PGTNet`</sup> | Camouflaged object segmentation with prior via two-stage training   <br> <sup><sub>*Rui Wang, Caijuan Shi, Changyu Duan, Weixiang Gao, Hongli Zhu, Yunchao Wei, Meiqin Liu*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1077314224001425)\|[Code](https://github.com/Ray3417/PGT)
| NeuCom<br><sup>2024</sup> | <sup>`MCA-SAM`</sup> | Multi-scale contrastive adaptor learning for segmenting anything in underperformed scenes    <br> <sup><sub>*Ke Zhou, Zhongwei Qiu, Dongmei Fu*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.05936)\|Code 
| ApplInt<br><sup>2024</sup> | <sup>`TJNet`</sup> | Two guidance joint network based on coarse map and edge map for camouflaged object detection    <br> <sup><sub>*Zhe Tang, Jing Tang, Dengpeng Zou, Junyi Rao & Fang Qi*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s10489-024-05559-y)\|[Code](https://github.com/Huah2019/TJNet)
| ApplInt<br><sup>2024</sup> | <sup>`CCSNet`</sup> | Detecting camouflaged objects via cross-level context supplement   <br> <sup><sub>*Qing Zhang, Weiqi Yan, Rui Zhao, Yanjiao Shi & Jian Zeng*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s10489-024-05694-6)\|Code  
| MIR<br><sup>2024</sup>  | <sup>`-`</sup> | Segment Anything Is Not Always Perfect: An Investigation of SAM on Different Real-world Applications   <br> <sup><sub>*Wei Ji, Jingjing Li, Qi Bi, Tingwei Liu, Wenbo Li, Li Cheng*</sub></sup>  | [Offl.](https://link.springer.com/article/10.1007/s11633-023-1385-0)\|[arXiv](https://arxiv.org/abs/2304.05750)\|<br>[Code](https://github.com/LiuTingWed/SAM-Not-Perfect)
| TII<br><sup>2024</sup> | <sup>`VSSNet`</sup> |  Camouflaged Object Detection via Complementary Information-Selected Network Based on Visual and Semantic Separation   <br> <sup><sub>*Chao Yin; Kequan Yang; Jide Li; Xiaoqiang Li; Yifan Wu*</sub></sup>    | [Paper](https://ieeexplore.ieee.org/abstract/document/10609401)\|Code
| TIM<br><sup>2024</sup> | <sup>`DPSNet`</sup> |  DPSNet: A Detail Perception Synergistic Network for Camouflaged Object Detection   <br> <sup><sub>*Xiaofei Li; Sheng Long; Jiaxin Yang; Jun Lei; Shuohao Li; Jun Zhang*</sub></sup>    | [Paper](https://ieeexplore.ieee.org/abstract/document/10771944)\|[Code](https://github.com/fxle/DPSNet) 
| TCE<br><sup>2024</sup> | <sup>`SAE`</sup> |  Shrink and Expose: Locate Edge Coarse-to-Fine for Camouflaged Object Detection   <br> <sup><sub>*Kejun Kang; Yixiu Liu; Yaoqi Sun; Shangdong Zhu; Fawei Ge; Wei Wang*</sub></sup>    | [Paper](https://ieeexplore.ieee.org/abstract/document/10772193)\|[Code](https://github.com/creamm-kk/SAE)  
| COMPAG<br><sup>2024</sup>  | <sup>`TEAVit`</sup> | Green fruit detection methods: Innovative application of camouflage object detection and multilevel feature mining    <br> <sup><sub>*Yuting Zhai, Zongmei Gao, Yang Zhou, Jian Li, Yuqi Zhang, Yanlei Xu*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0168169924007476)\|Code
| ECOINF<br><sup>2024</sup>  | <sup>`YOLOv8-SIM`</sup> | Camouflage detection: Optimization-based computer vision for Alligator sinensis with low detectability in complex wild environments   `BBox`      <br> <sup><sub>*Yantong Liu, Sai Che, Liwei Ai, Chuanxiang Song, Zheyu Zhang, Yongkang Zhou, Xiao Yang, Chen Xian*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/pii/S1574954124003443)\|[Code](https://github.com/Ap1rate/yolov8-SIM)
| ACCESS<br><sup>2024</sup> | <sup>`FS-CDIS`</sup> | The Art of Camouflage: Few-shot Learning for Animal Detection and Segmentation  <sub>![Static Badge](https://img.shields.io/badge/CAMO--FS-grey)</sub>  <br> <sup><sub>*Thanh-Danh Nguyen, Anh-Khoa Nguyen Vu, Nhat-Duy Nguyen, Vinh-Tiep Nguyen, Thanh Duc Ngo, et al.*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10608133)\|[Code](https://github.com/danhntd/FS-CDIS)    


<!--| ApplSci<br><sup>2024</sup> | <sup>`CCGNet`</sup> | Camouflaged Object Detection That Does Not Require Additional Priors   <br> <sup><sub>*Yuchen Dong, Heng Zhou, Chengyang Li, Junjie Xie, Yongqiang Xie, and Zhongbo Li*</sub></sup>  | [Paper](https://www.mdpi.com/2076-3417/14/6/2621)\|Code
-->


### 2023

| **Pub.** | **Model** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| NeurIPS<br><sup>2023</sup>  | <sup>`WS-SAM`</sup> | Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.11003)\|[Code](https://github.com/ChunmingHe/WS-SAM)
| MM<br><sup>2023</sup>  | <sup>`UQFormer`</sup>  | A Unified Query-based Paradigm for Camouflaged Instance Segmentation  <br> <sup><sub>*Do Dong, Jialun Pei, Rongrong Gao, Tian-Zhu Xiang, Shuo Wang, Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.07392)\|[Code](https://github.com/dongbo811/UQFormer) 
| MM<br><sup>2023</sup> | <sup>`FPNet`</sup> | Frequency Perception Network for Camouflaged Object Detection  <br> <sup><sub>*Runmin Cong, Mengyao Sun, Sanyi Zhang, Xiaofei Zhou, Wei Zhang, Yao Zhao*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.08924)\|[Code](https://github.com/rmcong/FPNet_ACMMM23) 
| MM<br><sup>2023</sup> | <sup>`FRINet`</sup> | Frequency Representation Integration for Camouflaged Object Detection  <br> <sup><sub>*Chenxi Xie, Changqun Xia, Tianshu Yu, Jia Li*</sub></sup> | [Paper](https://dl.acm.org/doi/10.1145/3581783.3611773)\|[Code](https://github.com/iCVTEAM/FRINet) 
| MM<br><sup>2023</sup>  | <sup>`DaCOD`</sup> | Depth-aided Camouflaged Object Detection  <br> <sup><sub>*Qingwei Wang, Jinyu Yang, Xiaosheng Yu, Fangyi Wang, Peng Chen, Feng Zheng*</sub></sup> | [Paper](https://dl.acm.org/doi/10.1145/3581783.3611874)\|[Code](https://github.com/qingwei-wang/DaCOD)  
| MM<br><sup>2023</sup>  | <sup>`XMSNet`</sup> | Object Segmentation by Mining Cross-Modal Semantics <br> <sup><sub>*Zongwei Wu, Jingjing Wang, Zhuyun Zhou, Zhaochong An, Qiuping Jiang, Cédric Demonceaux, Guolei Sun, Radu Timofte*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.10469)\|[Code](https://github.com/Zongwei97/XMSNet) 
| IJCAI<br><sup>2023</sup>  | <sup>`PENet`</sup> | Locate, Refine and Restore: A Progressive Enhancement Network for Camouflaged Object Detection   <br> <sup><sub>*Xiaofei Li, Jiaxin Yang, Shuohao Li, Jun Lei, Jun Zhang, Dong Chen*</sub></sup>  | [Paper](https://www.ijcai.org/proceedings/2023/124)\|Code 
| ICCV<br><sup>2023</sup>  | <sup>`PopNet`</sup> | Source-free Depth for Object Pop-out  <br> <sup><sub>*Zongwei Wu, Danda Pani Paudel, Deng-Ping Fan, Jingjing Wang, Shuo Wang, Cedric Demonceaux, Radu Timofte, Luc Van Gool*</sub></sup>  | [Paper](https://arxiv.org/abs/2212.05370)\|[Code](https://github.com/Zongwei97/PopNet) 
| ICCV<br><sup>2023</sup>  | <sup>`-`</sup> | The Making and Breaking of Camouflage    <br> <sup><sub>*Hala Lamdouar, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://arxiv.org/abs/2309.03899)\|[Code](https://github.com/hlamdouar/CAMEVAL) 
| ICCVW<br><sup>2023</sup>  | <sup>`SAM-Adapter`</sup> | SAM-Adapter: Adapting Segment Anything in Underperformed Scenes   <br> <sup><sub>*Tianrun Chen, Lanyun Zhu, Chaotao Deng, Runlong Cao, Yan Wang, Shangzhan Zhang, Zejian Li, Lingyun Sun, Ying Zang, Papa Mao*</sub></sup> | [Offl.](https://openaccess.thecvf.com/content/ICCV2023W/VCL/html/Chen_SAM-Adapter_Adapting_Segment_Anything_in_Underperformed_Scenes_ICCVW_2023_paper.html)\|[arXiv](https://arxiv.org/abs/2304.09148)\|<br>[Code](https://github.com/tianrun-chen/SAM-Adapter-PyTorch) 
| CVPR<br><sup>2023</sup>  | <sup>`FSPNet`</sup> | Feature Shrinkage Pyramid for Camouflaged Object Detection with Transformers  <br> <sup><sub>*Zhou Huang, Hang Dai, Tian-Zhu Xiang, Shuo Wang, Huai-Xin Chen, Jie Qin, and Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.14816)\|[Code](https://github.com/ZhouHuang23/FSPNet)
| CVPR<br><sup>2023</sup>  | <sup>`FEDER`</sup> | Camouflaged Object Detection with Feature Decomposition and Edge Reconstruction   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/He_Camouflaged_Object_Detection_With_Feature_Decomposition_and_Edge_Reconstruction_CVPR_2023_paper.html)\|[Code](https://github.com/ChunmingHe/FEDER)
| CVPR<br><sup>2023</sup>  | <sup>`EVP`</sup> | Explicit Visual Prompting for Low-Level Structure Segmentations  <br> <sup><sub>*Weihuang Liu, Xi Shen, Chi-Man Pun, Xiaodong Cun*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.10883)\|[Code](https://github.com/NiFangBaAGe/Explicit-Visual-Prompt)
| CVPR<br><sup>2023</sup>  | <sup>`IOCFormer`</sup> | Indiscernible Object Counting in Underwater Scenes    <sub>![Static Badge](https://img.shields.io/badge/IOCfish5K-grey)</sub>   <br> <sup><sub>*Guolei Sun, Zhaochong An, Yun Liu, Ce Liu, Christos Sakaridis, Deng-Ping Fan, Luc Van Gool*</sub></sup>  | [Paper](https://arxiv.org/abs/2304.11677)\|[Code](https://github.com/GuoleiSun/Indiscernible-Object-Counting)  
| AAAI<br><sup>2023</sup>  | <sup>`CRNet`</sup> | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations   <sub>![Static Badge](https://img.shields.io/badge/S--COD-grey)</sub>  <br> <sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.14083)\|[Code](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations)
| AAAI<br><sup>2023</sup>  |  <sup>`HitNet`</sup>  | High-resolution Iterative Feedback Network for Camouflaged Object Detection <br> <sup><sub>*Xiaobin Hu, Deng-Ping Fan, Xuebin Qin, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25167)\|[Code](https://github.com/HUuxiaobin/HitNet) 
| ECAI<br><sup>2023</sup> | <sup>`diffCOD`</sup> | Diffusion Model for Camouflaged Object Detection     <br> <sup><sub>*Zhennan Chen, Rongrong Gao, Tian-Zhu Xiang, Fan Lin*</sub></sup> | [Paper](https://arxiv.org/abs/2308.00303)\|[Code](https://github.com/ZNan-Chen/diffCOD)
| ICASSP<br><sup>2023</sup>  | <sup>`TinyCOD`</sup> | TINYCOD: Tiny and Effective Model for Camouflaged Object Detection <br> <sup><sub>*Haozhe Xing; Shuyong Gao; Hao Tang; Tsui Qin Mok; Yanlan Kang; Wenqiang Zhang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/10095226)\|[Code](https://github.com/Haozhe-Xing/TinyCOD)
| ICME<br><sup>2023</sup>  | <sup>`EAMNet`</sup> | Edge-Aware Mirror Network for Camouflaged Object Detection  <br> <sup><sub>*Dongyue Sun, Shiyao Jiang, Lin Qi*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.03932)\|[Code](https://github.com/sdy1999/EAMNet)
| ICME<br><sup>2023</sup>  | <sup>`FDNet`</sup> | Camouflaged Object Detection with Feature Grafting and Distractor Aware   <sub>![Static Badge](https://img.shields.io/badge/ACOD2K-grey)</sub>  <br> <sup><sub>*Yuxuan Song, Xinyue Li, Lin Qi*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.03943)\|[Code](https://github.com/syxvision/FDNet)
| ICME<br><sup>2023</sup>  | <sup>`OAFormer`</sup> | OAFormer: Occlusion Aware Transformer for Camouflaged Object Detection <br> <sup><sub>*Xin Yang, Hengliang Zhu, Guojun Mao, Shuli Xing*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10219627)\|[Code](https://github.com/xinyang920/OAFormer) 
| ICME<br><sup>2023</sup> | <sup>`CFANet`</sup> | CFANet: A Cross-layer Feature Aggregation Network for Camouflaged Object Detection   <br> <sup><sub>*Qing ZhangWeiqi Yan*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10219858)\|[Code](https://github.com/ZhangQing0329/CFANet)
| WACV<br><sup>2023</sup>  | <sup>`MFFN`</sup> | MFFN: Multi-view Feature Fusion Network for Camouflaged Object Detection   <br> <sup><sub>*Dehua Zheng, Xiaochen Zheng, Laurence T. Yang, Yuan Gao, Chenlu Zhu, Yiheng Ruan*</sub></sup> | [Paper](https://arxiv.org/abs/2210.06361)\|[Code](https://github.com/dwardzheng/MFFN_COD)  
| --  | -- | -- | -- | 
| IJCV<br><sup>2023</sup> | <sup>`OPNet`</sup> | Camouflaged Object Segmentation with Omni Perception   <br> <sup><sub>*Haiyang Mei, Ke Xu, Yunduo Zhou, Yang Wang, Haiyin Piao, Xiaopeng Wei, Xin Yang*</sub></sup> | [Paper](https://www.researchgate.net/publication/372312626_Camouflaged_Object_Segmentation_with_Omni_Perception)\|[Code](https://github.com/Mhaiyang/2023_IJCV_OPNet)  
| TIP<br><sup>2023</sup> | <sup>`SAT`</sup> | Nowhere to Disguise: Spot Camouflaged Objects via Saliency Attribute Transfer   <br> <sup><sub>*Wenda Zhao; Shigeng Xie; Fan Zhao; You He; Huchuan Lu*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10132418)\|[Code](https://github.com/wdzhao123/SAT) 
| TIP<br><sup>2023</sup> | <sup>`PUENet`</sup>  | Predictive Uncertainty Estimation for Camouflaged Object Detection <br> <sup><sub>*Yi Zhang, Jing Zhang, Wassim Hamidouche, Olivier Deforges*</sub></sup> | [Paper](https://hal.science/hal-04142929/)\|[Code](https://github.com/Jun-Pu/PUENet)
| TIP<br><sup>2023</sup> | <sup>`FSNet`</sup> | FSNet: Focus Scanning Network for Camouflaged Object Detection  <br> <sup><sub>*Ze Song; Xudong Kang; Xiaohui Wei; Haibo Liu; Renwei Dian; Shutao Li*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/10103836)\|[Code](https://github.com/SongZeHNU/FSNet) 
| TIP<br><sup>2023</sup> | <sup>`ZSCOD`</sup> | Zero-Shot Camouflaged Object Detection `ZS COD`    <br> <sup><sub>*Haoran Li; Chun-Mei Feng; Yong Xu; Tao Zhou; Lina Yao; Xiaojun Chang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10234216)\|Code 
| TNNLS<br><sup>2023</sup> | <sup>`BBNet`</sup> | Collaborative Camouflaged Object Detection: A Large-Scale Dataset and Benchmark  <sub>![Static Badge](https://img.shields.io/badge/CoCOD8K-grey)</sub>   <br> <sup><sub>*Cong Zhang, Hongbo Bi, Tian-Zhu Xiang, Ranwan Wu, Jinghui Tong, Xiufang Wang*</sub></sup> | [Paper](https://arxiv.org/abs/2310.04253)\|[Code](https://github.com/zc199823/BBNet--CoCOD) 
| TNNLS<br><sup>2023</sup> | <sup>`MRR-Net`</sup> | Camouflaged Object Segmentation Based on Matching–Recognition–Refinement Network  <br> <sup><sub>*Xinyu Yan; Meijun Sun; Yahong Han; Zheng Wang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/10180211)\|[Code](https://github.com/XinyuYanTJU/MRR-Net)
| TNNLS<br><sup>2023</sup> | <sup>`PCPNet`</sup> | Pixel-Centric Context Perception Network for Camouflaged Object Detection   <br> <sup><sub>*Ze Song; Xudong Kang; Xiaohui Wei; Shutao Li*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10278183)\|Code 
| TMM<br><sup>2023</sup> | <sup>`UEDG`</sup> | UEDG: Uncertainty-Edge Dual Guided Camouflage Object Detection   <br> <sup><sub>*Lyu, Yixuan and Zhang, Hong and Li, Yan and Liu, Hanyang and Yang, Yifan and Yuan, Ding*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10183371)\|[Code](https://github.com/lyu-yx/UEDG) 
| PR<br><sup>2023</sup>   | <sup>`Bi-RRNet`</sup>  | Bi-RRNet: Bi-level recurrent refinement network for camouflaged object detection    <br> <sup><sub>*Yan Liu, Kaihua Zhang, Yaqian Zhao, Hu Chen, Qingshan Liu*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320323002145)\|Code 
| SCIS<br><sup>2023</sup>  | <sup>`-`</sup> | SAM Struggles in Concealed Scenes - Empirical Study on "Segment Anything"   <br> <sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Peng Xu, Bowen Zhou, Ming-Ming Cheng & Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2304.06022)\|Code 
| TCSVT<br><sup>2023</sup> | <sup>`LSR+`</sup> | Towards Deeper Understanding of Camouflaged Object Detection  <sub>![Static Badge](https://img.shields.io/badge/CAM--LDR-grey)</sub>   <br> <sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, Nick Barnes, Deng-Ping Fan*</sub></sup> | [Paper](https://arxiv.org/abs/2205.11333)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)
| TCSVT<br><sup>2023</sup> | <sup>`MSCAF-Net`</sup> | MSCAF-Net: A General Framework for Camouflaged Object Detection via Learning Multi-Scale Context-Aware Features  <br> <sup><sub>*Yu Liu; Haihang Li; Juan Cheng; Xun Chen*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10045692)\|[Code](https://github.com/yuliu316316/MSCAF-COD) 
| TCSVT<br><sup>2023</sup> | <sup>`SARNet`</sup> | Go Closer To See Better: Camouflaged Object Detection via Object Area Amplification and Figure-ground Conversion  <br> <sup><sub>*Haozhe Xing; Yan Wang; Xujun Wei; Hao Tang; Shuyong Gao; Wenqiang Zhang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10065514)/[Code](https://github.com/Haozhe-Xing/SARNet)
| TCSVT<br><sup>2023</sup> | <sup>`DCNet`</sup> | Dual-Constraint Coarse-to-Fine Network for Camouflaged Object Detection  <br> <sup><sub>*Guanghui Yue; Houlu Xiao; Hai Xie; Tianwei Zhou; Wei Zhou; Weiqing Yan; etc.*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10262011)\|Code 
| TCSVT<br><sup>2023</sup> |  <sup>`TANet`</sup>  | Deep Texture-Aware Features for Camouflaged Object Detection    <br><sup><sub>*Jingjing Ren, Xiaowei Hu, Lei Zhu, Xuemiao Xu, et al.*</sub></sup>  | [Paper](https://arxiv.org/pdf/2102.02996.pdf)\|Code 
| Neucom<br><sup>2023</sup>   | <sup>`CINet`</sup> |  Camouflaged object detection with counterfactual intervention    <br> <sup><sub>*Xiaofei Li, Hongying Li, Hao Zhou, Miaomiao Yu, Dong Chen, Shuohao Li, Jun Zhang*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223006537)\|Code 
| TIM<br><sup>2023</sup> | <sup>`JCNet`</sup> | Camouflaged Object Segmentation Based on Joint Salient Object for Contrastive Learning  <br> <sup><sub>*Jiang, Xinhao and Cai, Wei and Ding, Yao and Wang, Xin and Hong, Danfeng and Yang, Zhiyong and Gao, Weijie*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10224812)\|[Code](https://github.com/jiangxinhao2020/JCNet)  
| ApplInt<br><sup>2023</sup> | <sup>`TSFNet`</sup> | Ternary symmetric fusion network for camouflaged object detection  <br> <sup><sub>*Yangyang Deng, Jianxin Ma, Yajun Li, Min Zhang & Li Wang*</sub></sup> | [Paper](https://link.springer.com/article/10.1007/s10489-023-04898-6)\|Code





### 2022 

| **Pub.** | **Model** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- | 
|   NeurIPS<br><sup>2022</sup>   |  <sup>`FGA-Net`</sup> | Exploring Figure-Ground Assignment Mechanism in Perceptual Organization   <br> <sup><sub>*Wei Zhai, Yang Cao, Jing Zhang, Zheng-Jun Zha*</sub></sup> | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6cc31b44d88dce8380d36e81485cd07f-Abstract-Conference.html)\|[Code](https://openreview.net/forum?id=c3HrNgQE7d)
|   MM<br><sup>2022</sup>   |  <sup>`PreyNet`</sup> | PreyNet: Preying on camouflaged objects <br> <sup><sub>*M Zhang, S Xu, Yongri Piao, D Shi, S Lin, H Lu*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548178)\|[Code](https://github.com/sxu1997/PreyNet)
|   IJCAI<br><sup>2022</sup>   |  <sup>`BGNet`</sup>   | Boundary-Guided Camouflaged Object Detection <br> <sup><sub>*Yujia Sun, Shuo Wang, Chenglizhao Chen, Tian-Zhu Xiang*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2022/186)\|[Code](https://github.com/thograce/BGNet)
|   CVPR<br><sup>2022</sup>   |   <sup>`ZoomNet`</sup>   | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup> | [Paper](https://arxiv.org/abs/2203.02688)\|[Code](https://github.com/lartpang/ZoomNet)
|   CVPR<br><sup>2022</sup>   |   <sup>`SegMaR`</sup>   | Segment, Magnify and Reiterate: Detecting Camouflaged Objects the Hard Way <br> <sup><sub>*Qi Jia, S. Yao, Yu Liu, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Jia_Segment_Magnify_and_Reiterate_Detecting_Camouflaged_Objects_the_Hard_Way_CVPR_2022_paper.pdf)\|[Code](https://github.com/dlut-dimt/SegMaR) 
|   CVPR<br><sup>2022</sup>   |   <sup>`-`</sup>   | Detecting Camouflaged Object in Frequency Domain <br> <sup><sub>*Yijie Zhong, Bo Li, Lv Tang, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Detecting_Camouflaged_Object_in_Frequency_Domain_CVPR_2022_paper.pdf)\|[Code](https://github.com/VisibleShadow/Implementation-of-Detecting-Camouflaged-Object-in-Frequency-Domain) 
|   AAAI<br><sup>2022</sup>   |   <sup>`BSA-Net`</sup>  | I can find you! Boundary-guided Separated Attention Network for Camouflaged Object Detection <br><sup><sub>*Hongwei Zhu, Peng Li, Haoran Xie, Mingqiang Wei, et al.*</sub></sup> | [Paper](https://www.aaai.org/AAAI22Papers/AAAI-6565.ZhuH.pdf)\|[Code](https://github.com/WolfberryCoke/BSA-Net) | 
|   WACV<br><sup>2022</sup>   |   <sup>`OCENet`</sup>   | Modeling Aleatoric Uncertainty for Camouflaged Object Detection <br> <sup><sub>*Jiawei Liu, Jing Zhang, Nick Barnes*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Liu_Modeling_Aleatoric_Uncertainty_for_Camouflaged_Object_Detection_WACV_2022_paper.pdf)\|[Code](https://github.com/Carlisle-Liu/OCENet)
|  ICME<br><sup>2022</sup>    |  <sup>`PINet`</sup>   | Finding the Achilles Heel: Progressive Identification Network for Camouflaged Object Detection  <br> <sup><sub>*Mu-Chun Chou, Hung-Jen Chen, Hong-Han Shuai*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9859854)\|[Code](https://github.com/michael861227/PINet)
| --  | -- | -- | -- | 
|   TPAMI<br><sup>2022</sup>   |   <sup>`SINet-V2`</sup>   | Concealed Object Detection   <sub>![Static Badge](https://img.shields.io/badge/COD10K-grey)</sub>  <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Ming-Ming Cheng, Ling Shao*</sub></sup>        | [Paper](https://arxiv.org/abs/2102.10274)\|[Code](https://github.com/GewelsJI/SINet-V2)                                                   |
|   TIP<br><sup>2022</sup>   |  <sup>`FAPNet`</sup> | Feature Aggregation and Propagation Network for Camouflaged Object Detection <br> <sup><sub>*Tao Zhou, Yi Zhou, Chen Gong, Jian Yang, Yu Zhang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9940173)\|[Code](https://github.com/taozh2017/FAPNet)
|   TIP<br><sup>2022</sup>   |  <sup>`FindNet`</sup> | FindNet: Can You Find Me? Boundary-and-Texture Enhancement Network for Camouflaged Object Detection  `BSA-Net Ext` <br> <sup><sub>*Peng Li, Xuefeng Yan, Hongwei Zhu, Mingqiang Wei, Xiao-Ping Zhang, Jing Qin*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9923635/)\|Code
|   TIP<br><sup>2022</sup>   |  <sup>`MGL_v2`</sup> | MGL: Mutual Graph Learning for Camouflaged Object Detection   <br><sup><sub>*Qiang Zhai; Xin Li; Fan Yang; Zhicheng Jiao; Ping Luo; Hong Cheng; Zicheng Liu*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9962828)\|[Code](https://github.com/fanyang587/MGL) 
|   TMM<br><sup>2022</sup>   |  <sup>`DTC-Net`</sup>  | Deep Texton-Coherence Network for Camouflaged Object Detection <br> <sup><sub>*Wei Zhai, Yang Cao, HaiYong Xie, Zheng-Jun Zha*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9815160)\|Code 
|   KBS<br><sup>2022</sup>   |  <sup>`BgNet`</sup>  | Boundary-guided network for camouflage object detection <br> <sup><sub>*Tianyou Chen, Jin Xiao, Xiaoguang Hu, Guofeng Zhang, Shaojie Wang*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705122004294)\|[Code](https://github.com/clelouch/BgNet)
|   PR<br><sup>2022</sup>   |   <sup>`CubeNet`</sup>   | CubeNet: X-shape connection for camouflaged object detection <br> <sup><sub>*Mingchen Zhuge, Xiankai Lu, Yiyou Guo, Zhihua Cai, Shuhan Chen*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S003132032200125X?dgcid=raven_sd_recommender_email)\|[Code](https://github.com/mczhuge/CubeNet)
|   PR<br><sup>2022</sup>   |   <sup>`ERRNet`</sup>  | Fast Camouflaged Object Detection via Edge-based Reversible Re-calibration Network <br><sup><sub>*Ge-Peng Ji, Lei Zhu, Mingchen Zhuge, Keren Fu*</sub></sup> | [Paper](https://arxiv.org/abs/2111.03216)\|[Code](https://github.com/GewelsJI/ERRNet) 
|   TCSVT<br><sup>2022</sup>   | <sup>`C2FNet-V2`</sup> | Camouflaged Object Detection via Context-aware Cross-level Fusion  <br> <sup><sub>*Geng Chen, Si-Jie Liu, Yu-Jia Sun, Ge-Peng Ji, Ya-Feng Wu, Tao Zhou*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.13362)\|[Code](https://github.com/Ben57882/C2FNet-TSCVT) 
|   MIR<br><sup>2022</sup>   |  <sup>`DGNet`</sup> | Deep Gradient Learning for Efficient Camouflaged Object Detection <br> <sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Yu-Cheng Chou, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2205.12853)\|[Code](https://github.com/GewelsJI/DGNet)
|   TOMM<br><sup>2022</sup>   | <sup>`FBNet`</sup>  | Frequency-aware Camouflaged Object Detection <br> <sup><sub>*Jiaying Lin, Xin Tan, Ke Xu, Lizhuang Ma, Rynson W.H. Lau*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3545609)\|Code 



### 2021

| **Pub.** | **Model** | **Title**                                                   |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   ICCV<br><sup>2021</sup>   |  <sup>`UGTR`</sup>  | Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection <br><sup><sub>*Fan Yang, Qiang Zhai, Xin Li, Rui Huang, et al.*</sub></sup>        | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Uncertainty-Guided_Transformer_Reasoning_for_Camouflaged_Object_Detection_ICCV_2021_paper.pdf)\|[Code](https://github.com/fanyang587/UGTR)                                                   |
|   CVPR<br><sup>2021</sup>   |  <sup>`UJSCOD`</sup>  | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection    <br><sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Bowen Liu, Tong Zhang, Yuchao Dai*</sub></sup>       | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Uncertainty-Aware_Joint_Salient_Object_and_Camouflaged_Object_Detection_CVPR_2021_paper.html)\|[Code](https://github.com/JingZhang617/Joint_COD_SOD) |
|   CVPR<br><sup>2021</sup>   |  <sup>`LSR`</sup>  | Simultaneously Localize, Segment and Rank the Camouflaged Objects   <sub>![Static Badge](https://img.shields.io/badge/NC4K-grey)</sub>  <br><sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, et al.*</sub></sup>      | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf)\|[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)                                                   |
|   CVPR<br><sup>2021</sup>   |  <sup>`MGL`</sup> | Mutual Graph Learning for Camouflaged Object Detection    <br><sup><sub>*Qiang Zhai, Xin Li, Fan Yang, Chenglizhao Chen, Hong Cheng, Deng-Ping Fan*</sub></sup>    | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Mutual_Graph_Learning_for_Camouflaged_Object_Detection_CVPR_2021_paper.pdf)\|[Code](https://github.com/fanyang587/MGL)                                                   |
|   CVPR<br><sup>2021</sup>   |  <sup>`PFNet`</sup>  | Camouflaged Object Segmentation with Distraction Mining      <br><sup><sub>*Haiyang Mei, Ge-Peng Ji, Ziqi Wei, Xin Yang, Xiaopeng Wei, Deng-Ping Fan*</sub></sup>                               | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Camouflaged_Object_Segmentation_With_Distraction_Mining_CVPR_2021_paper.pdf)\|[Code](https://mhaiyang.github.io/CVPR2021_PFNet/index)                                                   |
|   IJCAI<br><sup>2021</sup>   |  <sup>`C2FNet`</sup>  | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup>          | [Paper](https://arxiv.org/abs/2105.12555)\|[Code](https://github.com/thograce/C2FNet) |
|   AAAI<br><sup>2021</sup>   |  <sup>`TINet`</sup>  | Inferring Camouflaged Objects by Texture-Aware Interactive Guidance Network     <br><sup><sub>*Jinchao Zhu, Xiaoyu Zhang, Shuo Zhang, Junnan Liu*</sub></sup>               | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16475)\|Code |
|   AAAI<br><sup>2021</sup> | <sup>`-`</sup> | CamouFinder: Finding Camouflaged Instances in Images `Demo` <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)/[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA)
|   TIFS<br><sup>2021</sup>   | <sup>`TSPORTNet`</sup> | Integrating Part-Object Relationship and Contrast for Camouflaged Object Detection  <br><sup><sub>*Yi Liu, Dingwen Zhang, Qiang Zhang, and Jungong Han*</sub></sup> | [Paper](https://www.researchgate.net/profile/Yi-Liu-35/publication/355923462_Integrating_Part-Object_Relationship_and_Contrast_for_Camouflaged_Object_Detection/links/625cb1221c096a380d0c8f91/Integrating-Part-Object-Relationship-and-Contrast-for-Camouflaged-Object-Detection.pdf)\|[Code](https://github.com/liuyi1989/TSPORTNet)
|   TIE<br><sup>2021</sup>   | <sup>`D2C-Net`</sup> | D2C-Net: A Dual-branch, Dual-guidance and Cross-refine Network for Camouflaged Object Detection <br><sup><sub>*Kang Wang, Hongbo Bi, Yi Zhang, Cong Zhang, Ziqi Liu, Shuang Zheng*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9430677)\|[Code](https://github.com/MS-KangWang/COD-D2Net) 
|   ACCESS<br><sup>2021</sup>   |  <sup>`MirrorNet`</sup> | MirrorNet: Bio-Inspired Camouflaged Object Segmentation     <br><sup><sub>*Jinnan Yan, Trung-Nghia Le, Khanh-Duy Nguyen, Minh-Triet Tran, Thanh-Toan Do, Tam V. Nguyen*</sub></sup>  | [Paper](https://arxiv.org/abs/2007.12881)\|[Proj](https://sites.google.com/view/ltnghia/research/camo)



### Before 2020 

| **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| CVPR<br><sup>2020</sup>   |   <sup>`SINet`</sup>   | **Camouflaged Object Detection**   <sub>![Static Badge](https://img.shields.io/badge/COD10K-grey)</sub>        <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Guolei Sun, Ming-Ming Cheng, Jianbing Shen, Ling Shao*</sub></sup>      | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf)\|[Code](https://github.com/DengPingFan/SINet) |
| CVIU<br><sup>2019</sup>   |  <sup>`ANet`</sup> | Anabranch network for camouflaged object segmentation  <sub>![Static Badge](https://img.shields.io/badge/CAMO-grey)</sub>    <br><sup><sub>*Trung-Nghia Le, Tam V. Nguyen, Zhongliang Nie, Minh-Triet Tran, Akihiro Sugimoto*</sub></sup>  | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf)\|[Code](https://sites.google.com/view/ltnghia/research/camo)
| SPL<br><sup>2019</sup>   |  <sup>`CPDDNet`</sup> | Detection of People With Camouflage Pattern Via Dense Deconvolution Network    <sub>![Static Badge](https://img.shields.io/badge/CPD1K-grey)</sub>  <br><sup><sub>*Yunfei Zheng, Xiongwei Zhang, Feng Wang, Tieyong Cao, Meng Sun, Xiaobing Wang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/8336933)\|[Code](https://github.com/xfflyer/Camouflaged-people-detection) 
| TIP<br><sup>2018</sup>   | <sup>`FWFC`</sup> | A Fusion Framework for Camouflaged Moving Foreground Detection in the Wavelet Domain  <sub>![Static Badge](https://img.shields.io/badge/CAMO_UOW-grey)</sub>    <br><sup><sub>*Shuai Li, Dinei Florencio, Wanqing Li, Yaqin Zhao, Chris Cook*</sub></sup>   | [Paper](https://arxiv.org/abs/1804.05984)\|[Code](https://sites.google.com/view/wanqingli/data-sets/uow-camo?authuser=0)    |
| IJCV<br><sup>2017</sup>   | <sup>`modiPNN`</sup> | Partially Camouflaged Object Tracking using Modified Probabilistic Neural Network and Fuzzy Energy based Active Contour    <br><sup><sub>*Ajoy Mondal, Susmita Ghosh, Ashish Ghosh*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s11263-016-0959-5)\|Code   |



## VCOD

| **Year** | **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | 
| 2024 | TPAMI  | <sup>`ZoomNeXt`</sup> | ZoomNeXt: A Unified Collaborative Pyramid Network for Camouflaged Object Detection   <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup>  | [Offl.](https://ieeexplore.ieee.org/document/10568374)\|[arXiv](https://arxiv.org/abs/2310.20208)\|<br>[Code](https://github.com/lartpang/ZoomNeXt)  
| 2024 | IJCV | <sup>`RCFF`</sup> | The Right Spin: Learning Object Motion from Rotation-Compensated Flow Fields     <br> <sup><sub>*Pia Bideau, Erik Learned-Miller, Cordelia Schmid, Karteek Alahari*</sub></sup> | [Offl.](https://link.springer.com/article/10.1007/s11263-023-01859-x)\|[arXiv](https://arxiv.org/abs/2203.00115)
| 2024 | TMM   | <sup>`IMEX`</sup> | Implicit-Explicit Motion Learning for Video Camouflaged Object Detection    <br> <sup><sub>*Wenjun Hui; Zhenfeng Zhu; Guanghua Gu; Meiqin Liu; Yao Zhao*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10430451)\|Code 
| 2024 | CVPR  | <sup>`TSP-SAM`</sup> | Endow SAM with Keen Eyes: Temporal-spatial Prompt Learning for Video Camouflaged Object Detection    <br> <sup><sub>*Wenjun Hui, Zhenfeng Zhu, Shuai Zheng, Yao Zhao*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Hui_Endow_SAM_with_Keen_Eyes_Temporal-spatial_Prompt_Learning_for_Video_CVPR_2024_paper.html)\|[Code](https://github.com/WenjunHui1/TSP-SAM)
| 2024 | CVPRW | <sup>`SAM-PM`</sup>| SAM-PM: Enhancing Video Camouflaged Object Detection using Spatio-Temporal Attention  <br> <sup><sub>*Muhammad Nawfal Meeran, Gokul Adethya T, Bhanu Pratyush Mantha*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2024W/PVUW/html/Meeran_SAM-PM_Enhancing_Video_Camouflaged_Object_Detection_using_Spatio-Temporal_Attention_CVPRW_2024_paper.html)\|[Code](https://github.com/SpiderNitt/SAM-PM) 
| 2024 | TCSVT |  <sup>`STM`</sup> | A Weakly-supervised Cross-domain Query Framework for Video Camouflage Object Detection  <br> <sup><sub>*Zelin Lu; Liang Xie; Xing Zhao; Binwei Xu; Haoran Liang; Ronghua Liang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10700777)\|Code 
| 2024 | ICASSP | <sup>`TMNet`</sup> | Tokenmotion: Motion-Guided Vision Transformer for Video Camouflaged Object Detection VIA Learnable Token Selection   <br> <sup><sub>*Zifan Yu; Erfan Bank Tavakoli; Meida Chen; Suya You; Raghuveer Rao; et al*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10447329)\|Code 
| 2023 | ICCV | <sup>`-`</sup> | The Making and Breaking of Camouflage    <br> <sup><sub>*Hala Lamdouar, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://arxiv.org/abs/2309.03899)\|[Code](https://github.com/hlamdouar/CAMEVAL) 
| 2022 | CVPR | <sup>`SLTNet`</sup> | Implicit Motion Handling for Video Camouflaged Object Detection    <sub>![Static Badge](https://img.shields.io/badge/MoCA--Mask-grey)</sub>   <br> <sup><sub>*Xuelian Cheng, Huan Xiong, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://dengpingfan.github.io/papers/[2022][CVPR]VCOD_MoCA-Mask.pdf)\|[Code](https://github.com/XuelianCheng/SLT-Net) 
| 2022 | CVPR | <sup>`QSDI`</sup> | A Deeper Dive Into What Deep Spatiotemporal Networks Encode: Quantifying Static vs. Dynamic Information      <br> <sup><sub>*Matthew Kowal, Mennatullah Siam, Md Amirul Islam, Neil D. B. Bruce, Richard P. Wildes, Konstantinos G. Derpanis*</sub></sup>  | [Offl.](https://openaccess.thecvf.com/content/CVPR2022/html/Kowal_A_Deeper_Dive_Into_What_Deep_Spatiotemporal_Networks_Encode_Quantifying_CVPR_2022_paper.html)\|[arXiv](https://arxiv.org/abs/2211.01783)\|<br>[Code](https://github.com/YorkUCVIL/Static-Dynamic-Interpretability/)\|[Proj](https://yorkucvil.github.io/Static-Dynamic-Interpretability/)  
| 2022 | NeurIPS | <sup>`OCLR`</sup> | Segmenting Moving Objects via an Object-Centric Layered Representation    <br> <sup><sub>*Junyu Xie, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/b37aa1d677970f2f56d0d17410c52b3b-Paper-Conference.pdf)\|[Code](https://github.com/Jyxarthur/OCLR_model)
| 2022 | TPAMI | <sup>`-`</sup> | EM-driven unsupervised learning for efficient motion segmentation      <br> <sup><sub>*Etienne Meunier, Anaïs Badoual, Patrick Bouthemy*</sub></sup> | [Paper](https://arxiv.org/abs/2201.02074)\|[Code](https://github.com/Etienne-Meunier-Inria/EM-Flow-Segmentation) 
| 2021 | ICCV | <sup>`MG`</sup> | Self-supervised Video Object Segmentation by Motion Grouping      <br> <sup><sub>*Charig Yang, Hala Lamdouar, Erika Lu, Andrew Zisserman, Weidi Xie*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Yang_Self-Supervised_Video_Object_Segmentation_by_Motion_Grouping_ICCV_2021_paper.html)\|[Code](https://charigyang.github.io/motiongroup/)\|<br>[Proj](https://charigyang.github.io/motiongroup/)  
| 2021 | BMVC | <sup>`SIMO`</sup> | Segmenting Invisible Moving Objects       <br> <sup><sub>*Hala Lamdouar, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://www.bmvc2021-virtualconference.com/assets/papers/0056.pdf)\|[Proj](https://www.robots.ox.ac.uk/~vgg/research/simo/)  
| 2020 | ACCV | <sup>`-`</sup> | Betrayed by Motion: Camouflaged Object Discovery via Motion Segmentation    <sub>![Static Badge](https://img.shields.io/badge/MoCA-grey)</sub>      <br> <sup><sub>*Hala Lamdouar, Charig Yang, Weidi Xie, Andrew Zisserman*</sub></sup>   | [Paper](https://arxiv.org/abs/2011.11630)\|[Code](https://github.com/hlamdouar/MoCA/)\|<br>[Data](https://www.robots.ox.ac.uk/~vgg/data/MoCA/)  
| 2018 | TIP | <sup>`FWFC`</sup> | A Fusion Framework for Camouflaged Moving Foreground Detection in the Wavelet Domain  <sub>![Static Badge](https://img.shields.io/badge/CAMO_UOW-grey)</sub>    <br><sup><sub>*Shuai Li, Dinei Florencio, Wanqing Li, Yaqin Zhao, Chris Cook*</sub></sup>   | [Paper](https://arxiv.org/abs/1804.05984)\|[Code](https://sites.google.com/view/wanqingli/data-sets/uow-camo?authuser=0)    |
| 2017 | IJCV | <sup>`modiPNN`</sup> | Partially Camouflaged Object Tracking using Modified Probabilistic Neural Network and Fuzzy Energy based Active Contour    <br><sup><sub>*Ajoy Mondal, Susmita Ghosh, Ashish Ghosh*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s11263-016-0959-5)\|Code   |
| 2016 | ECCV | <sup>`CMS`</sup> | It’s Moving! A Probabilistic Model for Causal Motion Segmentation in Moving Camera Videos     <sub>![Static Badge](https://img.shields.io/badge/Camouflaged--Animals--Dataset-grey)</sub>         <br> <sup><sub>*Pia Bideau, Erik Learned-Miller*</sub></sup>  | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_26)\|[Code](http://vis-www.cs.umass.edu/motionSegmentation/)


## CIS 

| **Year** | **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2024 | MM | <sup>`TPNet`</sup> | Text-prompt Camouflaged Instance Segmentation with Graduated Camouflage Learning  <br> <sup><sub>*Zhentao He, Changqun Xia, Shengye Qiao, Jia Li*</sub></sup>  | Paper\|Code
| 2024 | ApplInt | <sup>`MSPNet`</sup> | Multi-scale pooling learning for camouflaged instance segmentation   <br> <sup><sub>*Chen Li, Ge Jiao, Guowen Yue, Rong He & Jiayu Huang*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s10489-024-05369-2)\|[Code](https://github.com/another-u/MSPNet-main) 
| 2023 | MM | <sup>`UQFormer`</sup> | A Unified Query-based Paradigm for Camouflaged Instance Segmentation  <br> <sup><sub>*Do Dong, Jialun Pei, Rongrong Gao, Tian-Zhu Xiang, Shuo Wang, Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.07392)\|[Code](https://github.com/dongbo811/UQFormer)
| 2023 | CVPR | <sup>`DCNet`</sup> | Camouflaged Instance Segmentation via Explicit De-camouflaging  <br> <sup><sub>*Naisong Luo, Yuwen Pan, Rui Sun, Tianzhu Zhang, Zhiwei Xiong, Feng Wu*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Luo_Camouflaged_Instance_Segmentation_via_Explicit_De-Camouflaging_CVPR_2023_paper.pdf)\|[Code](https://github.com/USTCL/DCNet)
| 2023 | arXiv | <sup>`-`</sup> | Leveraging Open-Vocabulary Diffusion to Camouflaged Instance Segmentation  <br> <sup><sub>*Tuan-Anh Vu, Duc Thanh Nguyen, Qing Guo, Binh-Son Hua, Nhat Minh Chung, Ivor W. Tsang, Sai-Kit Yeung*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.17505)\|Code 
| 2022 | ECCV | <sup>`OSFormer`</sup> | OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers    <br> <sup><sub>*Jialun Pei, Tianyang Cheng, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2207.02255)\|[Code](https://github.com/PJLallen/OSFormer)
| 2022 | TIP  | <sup>`CFL`</sup> | Camouflaged Instance Segmentation In-The-Wild: Dataset, Method, and Benchmark Suite   <sub>![Static Badge](https://img.shields.io/badge/CAMO++-grey)</sub>     <br> <sup><sub>*Trung-Nghia Le, Yubo Cao, Tan-Cong Nguyen, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2103.17123)\|[Proj](https://sites.google.com/view/ltnghia/research/camo_plus_plus)  
| 2021 | AAAI | <sup>`-`</sup> | CamouFinder: Finding Camouflaged Instances in Images `Demo`    <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)\|[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA)



## WSCOD 

| **Year** | **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |  
| 2024 | MM<br><sup>2024</sup> | <sup>`MiNet`</sup> | MiNet: Weakly-Supervised Camouflaged Object Detection through Mutual Interaction between Region and Edge Cues   <br> <sup><sub>*Yuzhen Niu, Lifen Yang, Rui Xu, Yuezhou Li, Yuzhong Chen*</sub></sup>  | [Paper](https://dl.acm.org/doi/10.1145/3664647.3680891)\|Code
| 2024 | MM<br><sup>2024</sup> | <sup>`-`</sup> | Semi-supervised Camouflaged Object Detection from Noisy Data `SS COD`  <br> <sup><sub>*Yuanbin Fu, Jie Ying, Houlei Lv, Xiaojie Guo*</sub></sup>  | [Paper](https://dl.acm.org/doi/abs/10.1145/3664647.3680645)\|Code 
| 2024 | ECCV | <sup>`CamoTeacher`</sup> | CamoTeacher: Dual-Rotation Consistency Learning for Semi-Supervised Camouflaged Object Detection   `WSS COD`  <br> <sup><sub>*Xunfa Lai, Zhiyu Yang, Jie Hu, Shengchuan Zhang, Liujuan Cao, Guannan Jiang, Zhiyu Wang, Songan Zhang, Rongrong Ji*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.08050)\|Code
| 2024 | ECCV | <sup>`WSSCOD`</sup> | Learning Camouflaged Object Detection from Noisy Pseudo Label  `WSS COD`  <br> <sup><sub>*Jin Zhang, Ruiheng Zhang, Yanjiao Shi, Zhe Cao, Nian Liu, Fahad Shahbaz Khan*</sub></sup>  | [Paper](https://arxiv.org/abs/2407.13157)\|Code 
| 2024 | ECCV | <sup>`SAM-COD`</sup> | SAM-COD: SAM-guided Unified Framework for Weakly-Supervised Camouflaged Object Detection     <br> <sup><sub>*Huafeng Chen, Pengxu Wei, Guangqian Guo, Shan Gao*</sub></sup>  | [Paper](https://www.arxiv.org/abs/2408.10760)\|[Code](https://github.com/2231122/SAM-COD)
| 2024 | ECCV | <sup>`-`</sup> | Just a Hint: Point-Supervised Camouflaged Object Detection  `Point`  <sub>![Static Badge](https://img.shields.io/badge/P--COD-grey)</sub>   <br> <sup><sub>*Huafeng Chen, Dian Shao, Guangqian Guo, Shan Gao*</sub></sup>  | [Paper](https://arxiv.org/abs/2408.10777v1)\|[Code](https://github.com/2231122/PCOD) 
| 2023 | NeurIPS | <sup>`WS-SAM`</sup> | Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.11003)\|[Code](https://github.com/ChunmingHe/WS-SAM)
| 2023 | AAAI | <sup>`CRNet`</sup> | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations  `Scribble` <sub>![Static Badge](https://img.shields.io/badge/S--COD-grey)</sub> <br> <sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup>  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25156)\|[Code](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations)



## Zero-Shot COD

| **Year** | **Pub.** | **Model** | **Title**          | **Links**        |
| :------: | :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |  
| 2024 | MM | <sup>`MMCPF`</sup> | Chain of Visual Perception: Harnessing Multimodal Large Language Models for Zero-shot Camouflaged Object Detection    <br> <sup><sub>*Lv Tang, Peng-Tao Jiang, Zhihao Shen, Hao Zhang, Jinwei Chen, Bo Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.11273)\|[Code](https://github.com/luckybird1994/MMCPF) 
| 2023 | TIP | <sup>`ZSCOD`</sup> | Zero-Shot Camouflaged Object Detection     <br> <sup><sub>*Haoran Li; Chun-Mei Feng; Yong Xu; Tao Zhou; Lina Yao; Xiaojun Chang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10234216)\|Code  



## RefCOD

| **Year** | **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | 
| 2025  | TPAMI | <sup>`R2CNet`</sup> | Referring Camouflaged Object Detection  <sub>![Static Badge](https://img.shields.io/badge/R2C7K-grey)</sub>  <br> <sup><sub>*Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng*</sub></sup>  | [Paper](https://arxiv.org/abs/2306.07532)\|[Code](https://github.com/zhangxuying1004/RefCOD)
| 2024 | ICME | <sup>`RPMA`</sup> | Reference Prompted Model Adaptation for Referring Camouflaged Object Detection   <br> <sup><sub>*Xuewei Liu; Shaofei Huang; Ruipu Wu; Hengyuan Zhao; Duo Xu; Xiaoming Wei*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10687557)\|Code
| 2023  | arXiv | <sup>`MLKG`</sup> | Large Model Based Referring Camouflaged Object Detection   <br> <sup><sub>*Shupeng Cheng, Ge-Peng Ji, Pengda Qin, Deng-Ping Fan, Bowen Zhou, Peng Xu*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.17122)\|Code



## OVCOS

| **Year** | **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2024  | ECCV | <small><sup>`OVCoser`</sup></small> | Open-Vocabulary Camouflaged Object Segmentation    <sub>![Static Badge](https://img.shields.io/badge/OVCamo-grey)</sub>    <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Jiaming Zuo, Lihe Zhang, Huchuan Lu*</sub></sup>   | [Paper](https://arxiv.org/abs/2311.11241)\|[Code](https://github.com/lartpang/OVCamo)
| 2023  | arXiv | <small><sup>`-`</sup></small> | Leveraging Open-Vocabulary Diffusion to Camouflaged Instance Segmentation  <br> <sup><sub>*Tuan-Anh Vu, Duc Thanh Nguyen, Qing Guo, Binh-Son Hua, Nhat Minh Chung, Ivor W. Tsang, Sai-Kit Yeung*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.17505)\|Code 




## RGBP COS

| **Year** | **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2024 | EAAI | <small><sup>`IPNet`</sup></small> | IPNet: Polarization-based Camouflaged Object Detection via dual-flow network   <sub>![Static Badge](https://img.shields.io/badge/PCOD_1200-grey)</sub>   <br> <sup><sub>*Xin Wang, Jiajia Ding, Zhao Zhang, Junfeng Xu, Jun Gao*</sub></sup>   | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0952197623014872)\|[Code](https://github.com/CVhfut/PCOD_1200) 
| 2023 | PRL | <small><sup>`PolarNet`</sup></small> | Polarization-based Camouflaged Object Detection  <sub>![Static Badge](https://img.shields.io/badge/PCOD-grey)</sub>  <br> <sup><sub>*Xin Wang, Zhao Zhang, Jun Gao*</sub></sup>   | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865523002532)\|[Code](https://github.com/CVhfut/Polar-COD)



## Other Related 

| **Year** | **Pub.** | **Model** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | 
| 2024 | CVPR | <small><sup>`LAKE-RED`</sup></small> | LAKE-RED: Camouflaged Images Generation by Latent Background Knowledge Retrieval-Augmented Diffusion `Gen`   <br> <sup><sub>*Pancheng Zhao, Peng Xu, Pengda Qin, Deng-Ping Fan, Zhicheng Zhang, Guoli Jia, Bowen Zhou, Jufeng Yang*</sub></sup>  | [Paper](https://arxiv.org/abs/2404.00292)\|[Code](https://github.com/PanchengZhao/LAKE-RED) 
| 2023 | AIR | <small><sup>`CamDiff`</sup></small> | CamDiff: Camouflage Image Augmentation via Diffusion Model  `Gen`  <br> <sup><sub>*Xue-Jing Luo, Shuo Wang, Zongwei Wu, Christos Sakaridis, Yun Cheng, Deng-Ping Fan, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2304.05469)\|[Code](https://github.com/drlxj/CamDiff) 
| 2022 | CVPR | <small><sup>`GANmouflage`</sup></small> | GANmouflage: 3D Object Nondetection with Texture Fields   `Gen`   <br> <sup><sub>*Rui Guo, Jasmine Collins, Oscar de Lima, Andrew Owens*</sub></sup>  | [Paper](https://arxiv.org/abs/2201.07202)\|[Proj](https://rrrrrguo.github.io/ganmouflage/)
| 2022 | CVPR | <small><sup>`DTA`</sup></small> | DTA: Physical Camouflage Attacks using Differentiable Transformation Network     <br> <sup><sub>*Naufal Suryanto, Yongsu Kim, Hyoeun Kang, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2203.09831)\|Code
| 2022 | TMM | <small><sup>`LCG-Net`</sup></small> | Location-Free Camouflage Generation Network  `Gen`  <br> <sup><sub>*Yangyang Li, Wei Zhai, Yang Cao, Zheng-jun Zha*</sub></sup> | [Paper](https://arxiv.org/abs/2203.09845)\|[Code](https://github.com/Tale17/LCG-Net) 
| 2020 | AAAI |   <small><sup>`-`</sup></small>   | Deep Camouflage Images  `Gen`      <br><sup><sub>*Qing Zhang, Gelin Yin, Yongwei Nie, Wei-Shi Zheng*</sub></sup>       | [Paper](https://ojs.aaai.org//index.php/AAAI/article/view/6981)\|[Code](https://github.com/hirokic5/Pytorch_CamouflageImages) |



## Datasets

| **Name** | **Year** | **Pub.** | **Links** | **Type** | **#Annot. Img.(Cam./Non)** | **Bbox** | **Obj. Mask** | **Ins. Mask** | **Comments**
| :------: | :------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
[CAMO++](https://sites.google.com/view/ltnghia/research/camo_plus_plus?authuser=0) | 2021 | TIP | [Paper](https://arxiv.org/abs/2103.17123) | Image | 2,700/2,800 | &check; | &check; | &check; | 
[NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) | 2021 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf) | Image | 4,121 | &check; | &check; | &check; |
[COD10K](http://dpfan.net/camouflage/) | 2020 | CVPR | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf) | Image | 5,066/4,934 | &check; | &check; | &check; |
[CAMO](https://sites.google.com/view/ltnghia/research/camo) | 2019 | CVIU | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf) | Image | 1,250/1,250 | &cross; | &check; | &cross; |
[CPD1K](https://github.com/xfflyer/Camouflaged-people-detection) | 2018 | SPL | [Paper](https://ieeexplore.ieee.org/document/8336933)  | Image | 1,000 | &cross; | &check; | &cross; | 
[CHAMELEON](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | 2017 | — | [Webpage](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | Image | 76 | &cross; | &check; | &cross; | 
|  |  |  |  |  |  |  |  |  |
[MoCA-Mask](https://xueliancheng.github.io/SLT-Net-project/) | 2022 | CVPR | [Paper](https://arxiv.org/abs/2203.07363) | Video | 4,691 | &check; | &check; | &cross; | <!--87 clips, 22,939 images-->
[MoCA](https://www.robots.ox.ac.uk/~vgg/data/MoCA/) | 2020 | ACCV | [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.html) | Video | 7,617 | &check; | &cross; | &cross; | <!--141 clips, 37K images-->
[CamoAnimals](http://vis-www.cs.umass.edu/motionSegmentation/) | 2016 | ECCV | [Paper](http://vis-www.cs.umass.edu/motionSegmentation/) | Video | 181 | &cross; | &check; | &check; |  <!--9 clips, 839 images-->  



## Appendix

- [Awesome List for Camouflaged Object Detection](https://github.com/GewelsJI/SINet-V2/blob/main/AWESOME_COD_LIST.md)




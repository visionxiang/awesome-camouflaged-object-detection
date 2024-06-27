
# Awesome Camouflaged Object Detection <a href="https://github.com/sindresorhus/awesome"><img src="figs/awesome.png" alt="Awesome" style="max-width: 100%;" width="100"></a>

A curated list of awesome resources for **Camouflaged Object Detection (COD)**, including: 
- Camouflaged/Concealed Object Detection (COD)  
- Camouflaged/Concealed Object Segmentation (COS)  
- Camouflaged/Concealed Scene Understanding (CSU)
  
We commit to maintaining regular updates to ensure the continuous enhancement of this resource.

:heavy_exclamation_mark: [04/2024] Update CVPR2024 papers.  
:heavy_exclamation_mark: [01/2024] Update ICLR2024, WACV2024 papers.   
:heavy_exclamation_mark: [12/2023] Update NeurIPS2023, AAAI2024 papers.   
:heavy_exclamation_mark: [08/2023] Update ICCV2023, MM2023, etc. papers for COD and CIS.   
:heavy_exclamation_mark: [04/2023] Update CVPR2023 papers for COD and CIS.


--------------------------------------------------------------------------------------

<!--TOC-->

## Content:
<!-- - [Overview](#Overview) -->
- [Camouflaged Object Detection (COD)](#COD)
- [Video Camouflaged Object Detection (VCOD)](#VCOD)
- [Camouflaged Instance Segmentation (CIS)](#CIS)
- [Weakly-supervised COD](#WSCOD)
- [Referring COD](#RefCOD)
- [Open-Vocabulary COS](#OVCOS)
- [Other Related](#Other-Related)
- [Datasets](#Datasets)
- [Appendix](#Appendix)

--------------------------------------------------------------------------------------



## COD 

<!--Transformer for COD:
  1) [COD] Boosting COD with Boosting Camouflaged Object Detection with Dual-Task Interactive Transformer, ICPR
  2) [COD] High-resolution Iterative Feedback Network for Camouflaged Object Detection, arXiv
  3) [COD] Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection, ICCV21
  4) [CIS] OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers, ECCV22
  5) [COD] Generative Transformer for Accurate and Reliable Salient Object Detection, arXiv
-->


### Preprint

| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| --    | arXiv | Adaptive Guidance Learning for Camouflaged Object Detection      <br> <sup><sub>*Zhennan Chen, Xuying Zhang, Tian-Zhu Xiang, Ying Tai*</sub></sup>  | [Paper](https://arxiv.org/abs/2405.02824)/[Code](https://github.com/ZNan-Chen/AGLNet)
| --    | arXiv | The Art of Camouflage: Few-shot Learning for Animal Detection and Segmentation  <br> <sup><sub>*Thanh-Danh Nguyen, Anh-Khoa Nguyen Vu, Nhat-Duy Nguyen, Vinh-Tiep Nguyen, Thanh Duc Ngo, et al.*</sub></sup>  | [Paper](https://arxiv.org/abs/2304.07444)/Code
| --     | arXiv | Leveraging Open-Vocabulary Diffusion to Camouflaged Instance Segmentation   <br> <sup><sub>*Tuan-Anh Vu, Duc Thanh Nguyen, Qing Guo, Binh-Son Hua, Nhat Minh Chung, Ivor W. Tsang, Sai-Kit Yeung*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.17505)/Code 
| --     | arXiv | Pre-train, Adapt and Detect: Multi-Task Adapter Tuning for Camouflaged Object Detection    <br> <sup><sub>*Yinghui Xing, Dexuan Kong, Shizhou Zhang, Geng Chen, Lingyan Ran, Peng Wang, Yanning Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.10685)/Code
| --     | arXiv | Joint Salient Object Detection and Camouflaged Object Detection via Uncertainty-aware Learning   <br> <sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Tong Zhang, Yiran Zhong, Mingyi He, Yuchao Dai*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.04651)/[Code](https://npucvr.github.io/UJSCOD/)
| --     | arXiv | Referring Camouflaged Object Detection   <br> <sup><sub>*Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng*</sub></sup>  | [Paper](https://arxiv.org/abs/2306.07532)/[Code](https://github.com/zhangxuying1004/RefCOD)
| --     | arXiv | DQnet: Cross-Model Detail Querying for Camouflaged Object Detection <br> <sup><sub>*Wei Sun, Chengao Liu, Linyan Zhang, Yu Li, Pengxu Wei, Chang Liu, Jialing Zou, Jianbin Jiao, Qixiang Ye*</sub></sup> | [Paper](https://arxiv.org/abs/2212.08296)/[Code](https://github.com/CVPR23/DQnet)
| --     | arXiv | CamoFormer: Masked Separable Attention for Camouflaged Object Detection   <br> <sup><sub>*Bowen Yin, Xuying Zhang, Qibin Hou, Bo-Yuan Sun, Deng-Ping Fan, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2212.06570)/[Code](https://github.com/HVision-NKU/CamoFormer)
|   --   |  arXiv   | Transformer transforms salient object detection and camouflaged object detection <br> <sup><sub>*Yuxin Mao, Jing Zhang, Yuchao Dai, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2104.10127)/[Code](https://github.com/fupiao1998/TrasformerSOD)
|   --   |  arXiv   | Exploring Depth Contribution for Camouflaged Object Detection <br> <sup><sub>*Mochu Xiang, Jing Zhang, Yunqiu Lv, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2106.13217v3)/Code
|   --   |  arXiv   | Towards Accurate Camouflaged Object Detection with Mixture Convolution and Interactive Fusion <br> <sup><sub>*Bo Dong, Mingchen Zhuge, Yongxiong Wang, Hongbo Bi, Geng Chen*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.05687.pdf)/[Code](https://github.com/BigHeartDB/MCIFNet)  
|   --   |  arXiv   | Boundary-Aware Segmentation Network for Mobile and Web Applications <br> <sup><sub>*Xuebin Qin, Deng-Ping Fan, Chenyang Huang, et al.*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.04704.pdf)/[Code](https://github.com/xuebinqin/BASNet) 



### 2024

| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2024  | TPAMI | **ZoomNeXt: A Unified Collaborative Pyramid Network for Camouflaged Object Detection**   <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup>  | [Paper](https://arxiv.org/abs/2310.20208)/[Code](https://github.com/lartpang/ZoomNeXt)
| 2024 |  ICML  | Spider: A Unified Framework for Context-dependent Concept Understanding    <br> <sup><sub>*Xiaoqi Zhao, Youwei Pang, Wei Ji, Baicheng Sheng, Jiaming Zuo, Lihe Zhang, Huchuan Lu*</sub></sup>  | [Paper](https://arxiv.org/abs/2405.01002)/[Code](https://github.com/Xiaoqi-Zhao-DLUT/Spider-UniCDSeg)
| 2024 |  CVPR  | LAKE-RED: Camouflaged Images Generation by Latent Background Knowledge Retrieval-Augmented Diffusion   <br> <sup><sub>*Pancheng Zhao, Peng Xu, Pengda Qin, Deng-Ping Fan, Zhicheng Zhang, Guoli Jia, Bowen Zhou, Jufeng Yang*</sub></sup>  | [Paper](https://arxiv.org/abs/2404.00292)/[Code]()
| 2024 |  CVPR  | VSCode: General Visual Salient and Camouflaged Object Detection with 2D Prompt Learning   <br> <sup><sub>*Ziyang Luo, Nian Liu, Wangbo Zhao, Xuguang Yang, Dingwen Zhang, Deng-Ping Fan, Fahad Khan, Junwei Han*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.15011)/[Code](https://github.com/Sssssuperior/VSCode)
| 2024 | CVPR | Depth-Aware Concealed Crop Detection in Dense Agricultural Scenes   ``ACOD-12K``    <br> <sup><sub>*Liqiong Wang, Jinyu Yang, Yanfu Zhang, Fangyi Wang, Feng Zheng*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Depth-Aware_Concealed_Crop_Detection_in_Dense_Agricultural_Scenes_CVPR_2024_paper.html)/[Code](https://github.com/Kki2Eve/RISNet)
| 2024 |  ICLR  | Strategic Preys Make Acute Predators: Enhancing Camouflaged Object Detectors by Generating Camouflaged Objects   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Yulun Zhang, Zhenhua Guo, Xiu Li, Martin Danelljan, Fisher Yu*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.03166)/[Code](https://github.com/ChunmingHe/Camouflageator) 
| 2024 | ICASSP | Edge Attention Learning for Efficient Camouflaged Object Detection   <br> <sup><sub>*Zijian Liu; Ping Jiang; Lixin Lin; Xiaoheng Deng*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10448139)/Code 
| 2024 | AAAI | CamoDiffusion: Camouflaged Object Detection via Conditional Diffusion Models   <br> <sup><sub>*Zhongxi Chen, Ke Sun, Xianming Lin*</sub></sup>  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27890)/[Code](https://github.com/Rapisurazurite/CamoDiffusion)
| 2024 |  AAAI  | Relax Image-Specific Prompt Requirement in SAM: A Single Generic Prompt for Segmenting Camouflaged Objects   <br> <sup><sub>*Jian Hu, Jiayi Lin, Weitong Cai, Shaogang Gong*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.07374)/[Proj](https://lwpyh.github.io/GenSAM/)/<br>[Code](https://github.com/jyLin8100/GenSAM)
| 2024 |  WACV  | CamoFocus: Enhancing Camouflage Object Detection With Split-Feature Focal Modulation and Context Refinement   <br> <sup><sub>*Abbas Khan, Mustaqeem Khan, Wail Gueaieb, Abdulmotaleb El Saddik, Giulia De Masi, Fakhri Karray*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Khan_CamoFocus_Enhancing_Camouflage_Object_Detection_With_Split-Feature_Focal_Modulation_and_WACV_2024_paper.html)/Code 
| --  | -- | -- | -- | 
| 2024 | IJCV  | Towards Diverse Binary Segmentation via A Simple yet General Gated Network   <br> <sup><sub>*Xiaoqi Zhao, Youwei Pang, Lihe Zhang, Huchuan Lu, Lei Zhang*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.10396)/Code  
| 2024 | TCSVT | Efficient Camouflaged Object Detection Network Based on Global Localization Perception and Local Guidance Refinement     <br> <sup><sub>*Xihang Hu; Xiaoli Zhang; Fasheng Wang; Jing Sun; Fuming Sun*</sub></sup>  <br><sup>`[PRNet]`</sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10379651)/[Code](https://github.com/hu-xh/PRNet)
| 2024 |  TMM | Decoupling and Integration Network for Camouflaged Object Detection  <br> <sup><sub>*Xiaofei Zhou; Zhicong Wu; Runmin Cong*</sub></sup>  <br><sup>`[DINet]`</sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10417767)/Code
| 2024 | TCSVT | Finding Camouflaged Objects Along the Camouflage Mechanisms   <br> <sup><sub>*Yang Yang; Qiang Zhang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10231131)/Code
| 2024 | AppInt | Two guidance joint network based on coarse map and edge map for camouflaged object detection    <br> <sup><sub>*Zhe Tang, Jing Tang, Dengpeng Zou, Junyi Rao & Fang Qi*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s10489-024-05559-y)/[Code](https://github.com/Huah2019/TJNet)
| 2024 | ApplSci | Camouflaged Object Detection That Does Not Require Additional Priors   <br> <sup><sub>*Yuchen Dong, Heng Zhou, Chengyang Li, Junjie Xie, Yongqiang Xie, and Zhongbo Li*</sub></sup>  | [Paper](https://www.mdpi.com/2076-3417/14/6/2621)/Code 
| 2024 | Neucom | A systematic review of image-level camouflaged object detection with deep learning  <br> <sup><sub>*Yanhua Liang, Guihe Qin, Minghui Sun, Xinchao Wang, Jie Yan, Zhonghan Zhang*</sub></sup>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223011736)/Code


### 2023

| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2023  | NeurIPS | Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.11003)/[Code](https://github.com/ChunmingHe/WS-SAM)
| 2023  | ACM MM | A Unified Query-based Paradigm for Camouflaged Instance Segmentation  <br> <sup><sub>*Do Dong, Jialun Pei, Rongrong Gao, Tian-Zhu Xiang, Shuo Wang, Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.07392)/[Code](https://github.com/dongbo811/UQFormer)
| 2023  | ACM MM | Frequency Perception Network for Camouflaged Object Detection  <br> <sup><sub>*Runmin Cong, Mengyao Sun, Sanyi Zhang, Xiaofei Zhou, Wei Zhang, Yao Zhao*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.08924)/[Code](https://github.com/rmcong/FPNet_ACMMM23)
| 2023  | ACM MM | Frequency Representation Integration for Camouflaged Object Detection  <br> <sup><sub>*Chenxi Xie, Changqun Xia, Tianshu Yu, Jia Li*</sub></sup> | [Paper](https://dl.acm.org/doi/10.1145/3581783.3611773)/Code
| 2023  | ACM MM | Depth-aided Camouflaged Object Detection  <br> <sup><sub>*Qingwei Wang, Jinyu Yang, Xiaosheng Yu, Fangyi Wang, Peng Chen, Feng Zheng*</sub></sup> | [Paper](https://dl.acm.org/doi/10.1145/3581783.3611874)/[Code](https://github.com/qingwei-wang/DaCOD) 
| 2023  | ACM MM | Object Segmentation by Mining Cross-Modal Semantics <br> <sup><sub>*Zongwei Wu, Jingjing Wang, Zhuyun Zhou, Zhaochong An, Qiuping Jiang, Cédric Demonceaux, Guolei Sun, Radu Timofte*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.10469)/[Code](https://github.com/Zongwei97/XMSNet)
| 2023  | IJCAI | Locate, Refine and Restore: A Progressive Enhancement Network for Camouflaged Object Detection   <br> <sup><sub>*Xiaofei Li, Jiaxin Yang, Shuohao Li, Jun Lei, Jun Zhang, Dong Chen*</sub></sup>  | [Paper](https://www.ijcai.org/proceedings/2023/124)/Code
| 2023  | ICCV | Source-free Depth for Object Pop-out  <br> <sup><sub>*Zongwei Wu, Danda Pani Paudel, Deng-Ping Fan, Jingjing Wang, Shuo Wang, Cedric Demonceaux, Radu Timofte, Luc Van Gool*</sub></sup>  | [Paper](https://arxiv.org/abs/2212.05370)/[Code](https://github.com/Zongwei97/PopNet)
| 2023  | ICCV | The Making and Breaking of Camouflage <br> <sup><sub>*Hala Lamdouar, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://arxiv.org/abs/2309.03899)/Code
| 2023  | ICCVW | SAM-Adapter: Adapting Segment Anything in Underperformed Scenes   <br> <sup><sub>*Tianrun Chen, Lanyun Zhu, Chaotao Deng, Runlong Cao, Yan Wang, Shangzhan Zhang, Zejian Li, Lingyun Sun, Ying Zang, Papa Mao*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/ICCV2023W/VCL/html/Chen_SAM-Adapter_Adapting_Segment_Anything_in_Underperformed_Scenes_ICCVW_2023_paper.html)/[arXiv](https://arxiv.org/abs/2304.09148)/[Code](https://github.com/tianrun-chen/SAM-Adapter-PyTorch)
| 2023  | CVPR | Feature Shrinkage Pyramid for Camouflaged Object Detection with Transformers  <br> <sup><sub>*Zhou Huang, Hang Dai, Tian-Zhu Xiang, Shuo Wang, Huai-Xin Chen, Jie Qin, and Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.14816)/[Code](https://github.com/ZhouHuang23/FSPNet)
| 2023  | CVPR | Camouflaged Object Detection with Feature Decomposition and Edge Reconstruction   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/He_Camouflaged_Object_Detection_With_Feature_Decomposition_and_Edge_Reconstruction_CVPR_2023_paper.html)/[Code](https://github.com/ChunmingHe/FEDER)
| 2023  | CVPR | Explicit Visual Prompting for Low-Level Structure Segmentations  <br> <sup><sub>*Weihuang Liu, Xi Shen, Chi-Man Pun, Xiaodong Cun*</sub></sup>  | [Paper](https://arxiv.org/abs/2303.10883)/[Code](https://github.com/NiFangBaAGe/Explicit-Visual-Prompt)
| 2023  | CVPR | Indiscernible Object Counting in Underwater Scenes `IOCfish5K`   <br> <sup><sub>*Guolei Sun, Zhaochong An, Yun Liu, Ce Liu, Christos Sakaridis, Deng-Ping Fan, Luc Van Gool*</sub></sup>  | [Paper](https://arxiv.org/abs/2304.11677)/[Code](https://github.com/GuoleiSun/Indiscernible-Object-Counting)
| 2023  | CVPRW | Segment Anything Is Not Always Perfect: An Investigation of SAM on Different Real-world Applications   <br> <sup><sub>*Wei Ji, Jingjing Li, Qi Bi, Tingwei Liu, Wenbo Li, Li Cheng*</sub></sup>  | [Paper](https://arxiv.org/abs/2304.05750)/[Code](https://github.com/LiuTingWed/SAM-Not-Perfect)
| 2023  | AAAI | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations `S-COD`  <br> <sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.14083)/[Code](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations)
| 2023  |  AAAI   | High-resolution Iterative Feedback Network for Camouflaged Object Detection <br> <sup><sub>*Xiaobin Hu, Deng-Ping Fan, Xuebin Qin, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25167)/[Code](https://github.com/HUuxiaobin/HitNet) 
| 2023 | ECAI | Diffusion Model for Camouflaged Object Detection     <br> <sup><sub>*Zhennan Chen, Rongrong Gao, Tian-Zhu Xiang, Fan Lin*</sub></sup> | [Paper](https://arxiv.org/abs/2308.00303)/[Code](https://github.com/ZNan-Chen/diffCOD)
| 2023  | ICASSP | TINYCOD: Tiny and Effective Model for Camouflaged Object Detection <br> <sup><sub>*Haozhe Xing; Shuyong Gao; Hao Tang; Tsui Qin Mok; Yanlan Kang; Wenqiang Zhang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/10095226)/[Code](https://github.com/Haozhe-Xing/TinyCOD)
| 2023  | ICME | Edge-Aware Mirror Network for Camouflaged Object Detection  <br> <sup><sub>*Dongyue Sun, Shiyao Jiang, Lin Qi*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.03932)/[Code](https://github.com/sdy1999/EAMNet)
| 2023  | ICME | Camouflaged Object Detection with Feature Grafting and Distractor Aware `ACOD2K` <br> <sup><sub>*Yuxuan Song, Xinyue Li, Lin Qi*</sub></sup>  | [Paper](https://arxiv.org/abs/2307.03943)/[Code](https://github.com/syxvision/FDNet)
| 2023  | ICME | OAFormer: Occlusion Aware Transformer for Camouflaged Object Detection <br> <sup><sub>*Xin Yang, Hengliang Zhu, Guojun Mao, Shuli Xing*</sub></sup>  | Paper/Code
| 2023 | ICME | CFANet: A Cross-layer Feature Aggregation Network for Camouflaged Object Detection   <br> <sup><sub>*Qing ZhangWeiqi Yan*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10219858)/[Code](https://github.com/ZhangQing0329/CFANet)
| 2023  | WACV | MFFN: Multi-view Feature Fusion Network for Camouflaged Object Detection   <br> <sup><sub>*Dehua Zheng, Xiaochen Zheng, Laurence T. Yang, Yuan Gao, Chenlu Zhu, Yiheng Ruan*</sub></sup> | [Paper](https://arxiv.org/abs/2210.06361)/[Code](https://github.com/dwardzheng/MFFN_COD)
| --  | -- | -- | -- | 
| 2023 | TNNLS | Collaborative Camouflaged Object Detection: A Large-Scale Dataset and Benchmark  **`[CoCOD8K]`**   <br> <sup><sub>*Cong Zhang, Hongbo Bi, Tian-Zhu Xiang, Ranwan Wu, Jinghui Tong, Xiufang Wang*</sub></sup> | [Paper](https://arxiv.org/abs/2310.04253)/[Code](https://github.com/zc199823/BBNet--CoCOD)
| 2023 | TNNLS | Camouflaged Object Segmentation Based on Matching–Recognition–Refinement Network  <br> <sup><sub>*Xinyu Yan; Meijun Sun; Yahong Han; Zheng Wang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/10180211)/[Code](https://github.com/XinyuYanTJU/MRR-Net)
| 2023 | TNNLS | Pixel-Centric Context Perception Network for Camouflaged Object Detection   <br> <sup><sub>*Ze Song; Xudong Kang; Xiaohui Wei; Shutao Li*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10278183)/Code 
| 2023 | IJCV | Camouflaged Object Segmentation with Omni Perception   <br> <sup><sub>*Haiyang Mei, Ke Xu, Yunduo Zhou, Yang Wang, Haiyin Piao, Xiaopeng Wei, Xin Yang*</sub></sup> | [Paper](https://www.researchgate.net/publication/372312626_Camouflaged_Object_Segmentation_with_Omni_Perception)/Code
| 2023 | TMM | UEDG: Uncertainty-Edge Dual Guided Camouflage Object Detection   <br> <sup><sub>*Lyu, Yixuan and Zhang, Hong and Li, Yan and Liu, Hanyang and Yang, Yifan and Yuan, Ding*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10183371)/[Code](https://github.com/lyu-yx/UEDG) 
| 2023 | TIP | Zero-Shot Camouflaged Object Detection    <br> <sup><sub>*Haoran Li; Chun-Mei Feng; Yong Xu; Tao Zhou; Lina Yao; Xiaojun Chang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10234216)/Code 
| 2023 | TIP | Nowhere to Disguise: Spot Camouflaged Objects via Saliency Attribute Transfer   <br> <sup><sub>*Wenda Zhao; Shigeng Xie; Fan Zhao; You He; Huchuan Lu*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10132418)/[Code](https://github.com/wdzhao123/SAT) 
| 2023 | TIP | FSNet: Focus Scanning Network for Camouflaged Object Detection  <br> <sup><sub>*Ze Song; Xudong Kang; Xiaohui Wei; Haibo Liu; Renwei Dian; Shutao Li*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/10103836)/[Code](https://github.com/SongZeHNU/FSNet) 
| 2023 | TIP  | Predictive Uncertainty Estimation for Camouflaged Object Detection <br> <sup><sub>*Yi Zhang, Jing Zhang, Wassim Hamidouche, Olivier Deforges*</sub></sup> | [Paper](https://hal.science/hal-04142929/)/[Code](https://github.com/Jun-Pu/PUENet)
2023   | PR  | Bi-RRNet: Bi-level recurrent refinement network for camouflaged object detection    <br> <sup><sub>*Yan Liu, Kaihua Zhang, Yaqian Zhao, Hu Chen, Qingshan Liu*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320323002145)/Code
2023  | SCIS | SAM Struggles in Concealed Scenes - Empirical Study on "Segment Anything"   <br> <sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Peng Xu, Bowen Zhou, Ming-Ming Cheng & Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2304.06022)/Code
2023   | Neucom |  Camouflaged object detection with counterfactual intervention    <br> <sup><sub>*Xiaofei Li, Hongying Li, Hao Zhou, Miaomiao Yu, Dong Chen, Shuohao Li, Jun Zhang*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223006537)/Code 
| 2023 | TIM | Camouflaged Object Segmentation Based on Joint Salient Object for Contrastive Learning  <br> <sup><sub>*Jiang, Xinhao and Cai, Wei and Ding, Yao and Wang, Xin and Hong, Danfeng and Yang, Zhiyong and Gao, Weijie*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10224812)/Code
| 2023 | TCSVT | Dual-Constraint Coarse-to-Fine Network for Camouflaged Object Detection  <br> <sup><sub>*Guanghui Yue; Houlu Xiao; Hai Xie; Tianwei Zhou; Wei Zhou; Weiqing Yan; etc.*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10262011)/Code 
| 2023 | TCSVT | Finding Camouflaged Objects along the Camouflage Mechanisms <br> <sup><sub>*Yang Yang; Qiang Zhang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10231131)/Code
| 2023 | TCSVT | MSCAF-Net: A General Framework for Camouflaged Object Detection via Learning Multi-Scale Context-Aware Features  <br> <sup><sub>*Yu Liu; Haihang Li; Juan Cheng; Xun Chen*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10045692)/[Code](https://github.com/yuliu316316/MSCAF-COD) 
| 2023 | TCSVT | Go Closer To See Better: Camouflaged Object Detection via Object Area Amplification and Figure-ground Conversion  <br> <sup><sub>*Haozhe Xing; Yan Wang; Xujun Wei; Hao Tang; Shuyong Gao; Wenqiang Zhang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/abstract/document/10065514)/[Code](https://github.com/Haozhe-Xing/SARNet)
| 2023 | TCSVT | Towards Deeper Understanding of Camouflaged Object Detection `CVPR21 (LSR) extension` `CAM-LDR` <br> <sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, Nick Barnes, Deng-Ping Fan*</sub></sup> | [Paper](https://arxiv.org/abs/2205.11333)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)
| 2023 | AppInt | Ternary symmetric fusion network for camouflaged object detection  <br> <sup><sub>*Yangyang Deng, Jianxin Ma, Yajun Li, Min Zhang & Li Wang*</sub></sup> | [Paper](https://link.springer.com/article/10.1007/s10489-023-04898-6)/Code
| 2023 | VI | Advances in Deep Concealed Scene Understanding   <br> <sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Peng Xu, Ming-Ming Cheng, Christos Sakaridis, Luc Van Gool*</sub></sup> | [Paper](https://link.springer.com/article/10.1007/s44267-023-00019-6#article-info)/[Project](https://github.com/DengPingFan/CSU)





### 2022 

| **Year** | **Pub.** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2022   |  NeurIPS | Exploring Figure-Ground Assignment Mechanism in Perceptual Organization   <br> <sup><sub>*Wei Zhai, Yang Cao, Jing Zhang, Zheng-Jun Zha*</sub></sup> | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6cc31b44d88dce8380d36e81485cd07f-Abstract-Conference.html)/[Code](https://openreview.net/forum?id=c3HrNgQE7d)
|   2022   |   MM     | PreyNet: Preying on camouflaged objects <br> <sup><sub>*M Zhang, S Xu, Yongri Piao, D Shi, S Lin, H Lu*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548178)/[Code](https://github.com/sxu1997/PreyNet)
|   2022   |  IJCAI   | Boundary-Guided Camouflaged Object Detection <br> <sup><sub>*Yujia Sun, Shuo Wang, Chenglizhao Chen, Tian-Zhu Xiang*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2022/186)/[Code](https://github.com/thograce/BGNet)
|   2022   |   CVPR   | Segment, Magnify and Reiterate: Detecting Camouflaged Objects the Hard Way <br> <sup><sub>*Qi Jia, S. Yao, Yu Liu, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Jia_Segment_Magnify_and_Reiterate_Detecting_Camouflaged_Objects_the_Hard_Way_CVPR_2022_paper.pdf)/[Code](https://github.com/dlut-dimt/SegMaR) 
|   2022   |   CVPR   | Detecting Camouflaged Object in Frequency Domain <br> <sup><sub>*Yijie Zhong, Bo Li, Lv Tang, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Detecting_Camouflaged_Object_in_Frequency_Domain_CVPR_2022_paper.pdf)/Code
|   2022   |   CVPR   | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup> | [Paper](https://arxiv.org/abs/2203.02688)/[Code](https://github.com/lartpang/ZoomNet) |
|   2022   |  AAAI    | I can find you! Boundary-guided Separated Attention Network for Camouflaged Object Detection <br><sup><sub>*Hongwei Zhu, Peng Li, Haoran Xie, Mingqiang Wei, et al.*</sub></sup> | [Paper](https://www.aaai.org/AAAI22Papers/AAAI-6565.ZhuH.pdf)/[Code](https://github.com/WolfberryCoke/BSA-Net) | 
|   2022   |  WACV    | Modeling Aleatoric Uncertainty for Camouflaged Object Detection <br> <sup><sub>*Jiawei Liu, Jing Zhang, Nick Barnes*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Liu_Modeling_Aleatoric_Uncertainty_for_Camouflaged_Object_Detection_WACV_2022_paper.pdf)/[Code](https://github.com/Carlisle-Liu/OCENet)
|  2022    |  ICME   | Finding the Achilles Heel: Progressive Identification Network for Camouflaged Object Detection  <br> <sup><sub>*Mu-Chun Chou, Hung-Jen Chen, Hong-Han Shuai*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9859854)/[Code](https://github.com/michael861227/PINet)
| --  | -- | -- | -- | 
|   2022   |   TPAMI   | **Concealed Object Detection** `COD10K`  <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Ming-Ming Cheng, Ling Shao*</sub></sup>           | [Paper](https://arxiv.org/abs/2102.10274)/[Code](https://github.com/GewelsJI/SINet-V2)                                                   |
|   2022   |  TIP | Feature Aggregation and Propagation Network for Camouflaged Object Detection <br> <sup><sub>*Tao Zhou, Yi Zhou, Chen Gong, Jian Yang, Yu Zhang*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9940173)/[Code](https://github.com/taozh2017/FAPNet)
|   2022   |  TIP | FindNet: Can You Find Me? Boundary-and-Texture Enhancement Network for Camouflaged Object Detection  `AAAI22 (BSANet) extension` <br> <sup><sub>*Peng Li, Xuefeng Yan, Hongwei Zhu, Mingqiang Wei, Xiao-Ping Zhang, Jing Qin*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9923635/)/Code
|   2022   |  TIP | MGL: Mutual Graph Learning for Camouflaged Object Detection `CVPR2021 extension`   <br><sup><sub>*Qiang Zhai; Xin Li; Fan Yang; Zhicheng Jiao; Ping Luo; Hong Cheng; Zicheng Liu*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9962828)/[Code](https://github.com/fanyang587/MGL) 
|   2022   | MIR  | Deep Gradient Learning for Efficient Camouflaged Object Detection <br> <sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Yu-Cheng Chou, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2205.12853)/[Code](https://github.com/GewelsJI/DGNet)
|   2022   | TCSVT | Camouflaged Object Detection via Context-aware Cross-level Fusion `C2FNet Extension`  <br> <sup><sub>*Geng Chen, Si-Jie Liu, Yu-Jia Sun, Ge-Peng Ji, Ya-Feng Wu, Tao Zhou*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.13362)/[Code](https://github.com/Ben57882/C2FNet-TSCVT)
|   2022   |  TMM  | Deep Texton-Coherence Network for Camouflaged Object Detection <br> <sup><sub>*Wei Zhai, Yang Cao, HaiYong Xie, Zheng-Jun Zha*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9815160)/Code
|   2022   |  KBS     | Boundary-guided network for camouflage object detection <br> <sup><sub>*Tianyou Chen, Jin Xiao, Xiaoguang Hu, Guofeng Zhang, Shaojie Wang*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705122004294)/[Code](https://github.com/clelouch/BgNet)
|   2022   |  PR      | CubeNet: X-shape connection for camouflaged object detection <br> <sup><sub>*Mingchen Zhuge, Xiankai Lu, Yiyou Guo, Zhihua Cai, Shuhan Chen*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S003132032200125X?dgcid=raven_sd_recommender_email)/[Code](https://github.com/mczhuge/CubeNet)
|   2022   |  PR      | Fast Camouflaged Object Detection via Edge-based Reversible Re-calibration Network <br><sup><sub>*Ge-Peng Ji, Lei Zhu, Mingchen Zhuge, Keren Fu*</sub></sup> | [Paper](https://arxiv.org/abs/2111.03216)/[Code](https://github.com/GewelsJI/ERRNet) 
|   2022   |  TOMM | Frequency-aware Camouflaged Object Detection <br> <sup><sub>*Jiaying Lin, Xin Tan, Ke Xu, Lizhuang Ma, Rynson W.H. Lau*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3545609)/Code 



### 2021

| **Year** | **Pub.** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2021   |   ICCV   | Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection <br><sup><sub>*Fan Yang, Qiang Zhai, Xin Li, Rui Huang, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Uncertainty-Guided_Transformer_Reasoning_for_Camouflaged_Object_Detection_ICCV_2021_paper.pdf)/[Code](https://github.com/fanyang587/UGTR)                                                   |
|   2021   |   CVPR   | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection <br><sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Bowen Liu, Tong Zhang, Yuchao Dai*</sub></sup>                     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Uncertainty-Aware_Joint_Salient_Object_and_Camouflaged_Object_Detection_CVPR_2021_paper.html)/[Code](https://github.com/JingZhang617/Joint_COD_SOD) |
|   2021   |   CVPR   | Simultaneously Localize, Segment and Rank the Camouflaged Objects `NC4K`  <br><sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)                                                   |
|   2021   |   CVPR   | Mutual Graph Learning for Camouflaged Object Detection       <br><sup><sub>*Qiang Zhai, Xin Li, Fan Yang, Chenglizhao Chen, Hong Cheng, Deng-Ping Fan*</sub></sup>                                   | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Mutual_Graph_Learning_for_Camouflaged_Object_Detection_CVPR_2021_paper.pdf)/[Code](https://github.com/fanyang587/MGL)                                                   |
|   2021   |   CVPR   | Camouflaged Object Segmentation with Distraction Mining      <br><sup><sub>*Haiyang Mei, Ge-Peng Ji, Ziqi Wei, Xin Yang, Xiaopeng Wei, Deng-Ping Fan*</sub></sup>                               | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Camouflaged_Object_Segmentation_With_Distraction_Mining_CVPR_2021_paper.pdf)/[Code](https://mhaiyang.github.io/CVPR2021_PFNet/index)                                                   |
|   2021   |  IJCAI   | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup>                                  | [Paper](https://arxiv.org/abs/2105.12555)/[Code](https://github.com/thograce/C2FNet) |
|   2021   |   AAAI   | Inferring Camouflaged Objects by Texture-Aware Interactive Guidance Network <br><sup><sub>*Jinchao Zhu, Xiaoyu Zhang, Shuo Zhang, Junnan Liu*</sub></sup>                                           | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16475)/Code |
| 2021 | AAAI | CamouFinder: Finding Camouflaged Instances in Images `Demo` <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)/[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA)
|   2021   | TIFS | Integrating Part-Object Relationship and Contrast for Camouflaged Object Detection  <br><sup><sub>*Yi Liu, Dingwen Zhang, Qiang Zhang, and Jungong Han*</sub></sup> | [Paper](https://www.researchgate.net/profile/Yi-Liu-35/publication/355923462_Integrating_Part-Object_Relationship_and_Contrast_for_Camouflaged_Object_Detection/links/625cb1221c096a380d0c8f91/Integrating-Part-Object-Relationship-and-Contrast-for-Camouflaged-Object-Detection.pdf)/[Code](https://github.com/liuyi1989/TSPORTNet)
|   2021   | TIE | D2C-Net: A Dual-branch, Dual-guidance and Cross-refine Network for Camouflaged Object Detection <br><sup><sub>*Kang Wang, Hongbo Bi, Yi Zhang, Cong Zhang, Ziqi Liu, Shuang Zheng*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9430677)/[Code](https://github.com/MS-KangWang/COD-D2Net)
|   2021   |  TCSVT   | Deep Texture-Aware Features for Camouflaged Object Detection <br><sup><sub>*Jingjing Ren, Xiaowei Hu, Lei Zhu, Xuemiao Xu, et al.*</sub></sup>  | [Paper](https://arxiv.org/pdf/2102.02996.pdf)/Code 
|  2021   |  TCSVT  | Rethinking Camouflaged Object Detection: Models and Datasets <br><sup><sub>*Hongbo Bi, Cong Zhang, Kang Wang, Jinghui Tong, Feng Zheng*</sub></sup>   | [Paper](https://ieeexplore.ieee.org/document/9598866)/Code
|   2021   |   Access | MirrorNet: Bio-Inspired Camouflaged Object Segmentation <br><sup><sub>*Jinnan Yan, Trung-Nghia Le, Khanh-Duy Nguyen, Minh-Triet Tran, Thanh-Toan Do, Tam V. Nguyen*</sub></sup>  | [Paper](https://arxiv.org/abs/2007.12881)/[Proj](https://sites.google.com/view/ltnghia/research/camo)


### Before 2020 

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2020   |   CVPR   | **Camouflaged Object Detection** `COD10K`                            <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Guolei Sun, Ming-Ming Cheng, Jianbing Shen, Ling Shao*</sub></sup>                                         | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf)/[Code](https://github.com/DengPingFan/SINet)           |
|   2020   |   AAAI   | Deep Camouflage Images                                       <br><sup><sub>*Qing Zhang, Gelin Yin, Yongwei Nie, Wei-Shi Zheng*</sub></sup>                             | [Paper](https://ojs.aaai.org//index.php/AAAI/article/view/6981)/Code |
|   2019   |   CVIU   | Anabranch network for camouflaged object segmentation `CAMO` <br><sup><sub>*Trung-Nghia Le, Tam V. Nguyen, Zhongliang Nie, Minh-Triet Tran, Akihiro Sugimoto*</sub></sup>  | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf)/[Code](https://sites.google.com/view/ltnghia/research/camo)
|   2019   |   SPL    | Detection of People With Camouflage Pattern Via Dense Deconvolution Network `CPD1K` <br><sup><sub>*Yunfei Zheng, Xiongwei Zhang, Feng Wang, Tieyong Cao, Meng Sun, Xiaobing Wang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/8336933)/Code
|   2018   |   TIP    | A Fusion Framework for Camouflaged Moving Foreground Detection in the Wavelet Domain <br><sup><sub>*Shuai Li, Dinei Florencio, Wanqing Li, Yaqin Zhao, Chris Cook*</sub></sup>                                              | [Paper](https://arxiv.org/abs/1804.05984)/Code                                                   |
|   2016   |   IJCV   | <span style="white-space:nowrap;">Partially Camouflaged Object Tracking using Modified Probabilistic Neural Network and Fuzzy Energy based Active Contour&emsp;&emsp;&emsp;</span> <br><sup><sub>*Ajoy Mondal, Susmita Ghosh, Ashish Ghosh*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s11263-016-0959-5)/Code                                                   |



## VCOD

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|  2024     | TPAMI | ZoomNeXt: A Unified Collaborative Pyramid Network for Camouflaged Object Detection   <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup>  | [Paper](https://arxiv.org/abs/2310.20208)/[Code](https://github.com/lartpang/ZoomNeXt)
|   2024   |   CVPR   | Endow SAM with Keen Eyes: Temporal-spatial Prompt Learning for Video Camouflaged Object Detection    <br> <sup><sub>*Wenjun Hui, Zhenfeng Zhu, Shuai Zheng, Yao Zhao*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Hui_Endow_SAM_with_Keen_Eyes_Temporal-spatial_Prompt_Learning_for_Video_CVPR_2024_paper.html)/Code
|   2024   |  CVPRW  | SAM-PM: Enhancing Video Camouflaged Object Detection using Spatio-Temporal Attention  <br> <sup><sub>*Muhammad Nawfal Meeran, Gokul Adethya T, Bhanu Pratyush Mantha*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2024W/PVUW/html/Meeran_SAM-PM_Enhancing_Video_Camouflaged_Object_Detection_using_Spatio-Temporal_Attention_CVPRW_2024_paper.html)/[Code](https://github.com/SpiderNitt/SAM-PM)
|   2024   |  TMM | Implicit-Explicit Motion Learning for Video Camouflaged Object Detection    <br> <sup><sub>*Wenjun Hui; Zhenfeng Zhu; Guanghua Gu; Meiqin Liu; Yao Zhao*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/10430451)/Code
|   2024 | ICASSP | Tokenmotion: Motion-Guided Vision Transformer for Video Camouflaged Object Detection VIA Learnable Token Selection   <br> <sup><sub>*Zifan Yu; Erfan Bank Tavakoli; Meida Chen; Suya You; Raghuveer Rao; et al*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/10447329)/Code 
|   2022   |   CVPR   | Implicit Motion Handling for Video Camouflaged Object Detection `MoCA-Mask` <br> <sup><sub>*Xuelian Cheng, Huan Xiong, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://dengpingfan.github.io/papers/[2022][CVPR]VCOD_MoCA-Mask.pdf)/[Code](https://github.com/XuelianCheng/SLT-Net)
|   2022   |   CVPR   | A Deeper Dive Into What Deep Spatiotemporal Networks Encode: Quantifying Static vs. Dynamic Information <br> <sup><sub>*Matthew Kowal, Mennatullah Siam, Md Amirul Islam, Neil D. B. Bruce, Richard P. Wildes, Konstantinos G. Derpanis*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Kowal_A_Deeper_Dive_Into_What_Deep_Spatiotemporal_Networks_Encode_Quantifying_CVPR_2022_paper.html)/[Code](https://github.com/YorkUCVIL/Static-Dynamic-Interpretability/)/<br>[Journal](https://arxiv.org/abs/2211.01783)
|   2022   |   TPAMI   | EM-driven unsupervised learning for efficient motion segmentation <br> <sup><sub>*Etienne Meunier, Anaïs Badoual, Patrick Bouthemy*</sub></sup> | [Paper](https://arxiv.org/abs/2201.02074)/[Code](https://github.com/Etienne-Meunier-Inria/EM-Flow-Segmentation)
|   2021   |   ICCV   | Self-supervised Video Object Segmentation by Motion Grouping <br> <sup><sub>*Charig Yang, Hala Lamdouar, Erika Lu, Andrew Zisserman, Weidi Xie*</sub></sup>  | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Yang_Self-Supervised_Video_Object_Segmentation_by_Motion_Grouping_ICCV_2021_paper.html)/[Code](https://charigyang.github.io/motiongroup/)
|   2021   |   BMVC   | Segmenting Invisible Moving Objects <br> <sup><sub>*Hala Lamdouar, Weidi Xie, Andrew Zisserman*</sub></sup> | [Paper](https://www.bmvc2021-virtualconference.com/assets/papers/0056.pdf)/[Proj](https://www.robots.ox.ac.uk/~vgg/research/simo/)
|   2020	 |   ACCV	  | Betrayed by Motion: Camouflaged Object Discovery via Motion Segmentation <br> <sup><sub>*Hala Lamdouar, Charig Yang, Weidi Xie, Andrew Zisserman*</sub></sup>  <br><sup>`[MoCA]`</sup> | [Paper](https://arxiv.org/abs/2011.11630)/[Code](https://www.robots.ox.ac.uk/~vgg/data/MoCA/)
|   2016   |  ECCV   | It’s Moving! A Probabilistic Model for Causal Motion Segmentation in Moving Camera Videos <br> <sup><sub>*Pia Bideau, Erik Learned-Miller*</sub></sup>  | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_26)/[Code](http://vis-www.cs.umass.edu/motionSegmentation/)


## CIS 

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2024  | ApplIntell | Multi-scale pooling learning for camouflaged instance segmentation   <br> <sup><sub>*Chen Li, Ge Jiao, Guowen Yue, Rong He & Jiayu Huang*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s10489-024-05369-2)/[Code](https://github.com/another-u/MSPNet-main)
| 2023  | arXiv | Leveraging Open-Vocabulary Diffusion to Camouflaged Instance Segmentation  <br> <sup><sub>*Tuan-Anh Vu, Duc Thanh Nguyen, Qing Guo, Binh-Son Hua, Nhat Minh Chung, Ivor W. Tsang, Sai-Kit Yeung*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.17505)/Code 
| 2023     | ACM MM   | A Unified Query-based Paradigm for Camouflaged Instance Segmentation  <br> <sup><sub>*Do Dong, Jialun Pei, Rongrong Gao, Tian-Zhu Xiang, Shuo Wang, Huan Xiong*</sub></sup>  | [Paper](https://arxiv.org/abs/2308.07392)/[Code](https://github.com/dongbo811/UQFormer)
| 2023     | CVPR     | Camouflaged Instance Segmentation via Explicit De-camouflaging  <br> <sup><sub>*Naisong Luo, Yuwen Pan, Rui Sun, Tianzhu Zhang, Zhiwei Xiong, Feng Wu*</sub></sup>  | Paper/Code
|   2022   |  ECCV    | OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers <br> <sup><sub>*Jialun Pei, Tianyang Cheng, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2207.02255)/[Code](https://github.com/PJLallen/OSFormer)
|   2022   |  TIP     | Camouflaged Instance Segmentation In-The-Wild: Dataset, Method, and Benchmark Suite <br> <sup><sub>*Trung-Nghia Le, Yubo Cao, Tan-Cong Nguyen, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2103.17123)/[Proj](https://sites.google.com/view/ltnghia/research/camo_plus_plus)
| 2021     | AAAI     | CamouFinder: Finding Camouflaged Instances in Images `Demo` <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)/[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA)



## WSCOD 

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2023  | NeurIPS | Weakly-Supervised Concealed Object Segmentation with SAM-based Pseudo Labeling and Multi-scale Feature Grouping   <br> <sup><sub>*Chunming He, Kai Li, Yachao Zhang, Guoxia Xu, Longxiang Tang, Yulun Zhang, Zhenhua Guo, Xiu Li*</sub></sup>  | [Paper](https://arxiv.org/abs/2305.11003)/[Code](https://github.com/ChunmingHe/WS-SAM)
| 2023  | AAAI | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations  <br> <sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup>  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25156)/[Code](https://github.com/dddraxxx/Weakly-Supervised-Camouflaged-Object-Detection-with-Scribble-Annotations)


## RefCOD

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2023  | arXiv | Large Model Based Referring Camouflaged Object Detection   <br> <sup><sub>*Shupeng Cheng, Ge-Peng Ji, Pengda Qin, Deng-Ping Fan, Bowen Zhou, Peng Xu*</sub></sup>  | [Paper](https://arxiv.org/abs/2311.17122)/Code
| 2023  | arXiv | Referring Camouflaged Object Detection   <br> <sup><sub>*Xuying Zhang, Bowen Yin, Zheng Lin, Qibin Hou, Deng-Ping Fan, Ming-Ming Cheng*</sub></sup>  <br><sup>`[R2C7K dataset]`</sup> | [Paper](https://arxiv.org/abs/2306.07532)/[Code]([https://github.com/ChunmingHe/WS-SAM](https://github.com/zhangxuying1004/RefCOD))



## OVCOS

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2023  | arXiv | Open-Vocabulary Camouflaged Object Segmentation   <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Jiaming Zuo, Lihe Zhang, Huchuan Lu*</sub></sup>  <br><sup>`[OVCamo dataset]`</sup>  | [Paper](https://arxiv.org/abs/2311.11241)/Code
| 2023  | arXiv | Leveraging Open-Vocabulary Diffusion to Camouflaged Instance Segmentation  <br> <sup><sub>*Tuan-Anh Vu, Duc Thanh Nguyen, Qing Guo, Binh-Son Hua, Nhat Minh Chung, Ivor W. Tsang, Sai-Kit Yeung*</sub></sup>  | [Paper](https://arxiv.org/abs/2312.17505)/Code 







## Other Related 
| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| 2024 |  CVPR  | LAKE-RED: Camouflaged Images Generation by Latent Background Knowledge Retrieval-Augmented Diffusion   <br> <sup><sub>*Pancheng Zhao, Peng Xu, Pengda Qin, Deng-Ping Fan, Zhicheng Zhang, Guoli Jia, Bowen Zhou, Jufeng Yang*</sub></sup>  | Paper/Code
|   2023   |   AIR  | CamDiff: Camouflage Image Augmentation via Diffusion Model  <br> <sup><sub>*Xue-Jing Luo, Shuo Wang, Zongwei Wu, Christos Sakaridis, Yun Cheng, Deng-Ping Fan, Luc Van Gool*</sub></sup> | [Paper](https://arxiv.org/abs/2304.05469)/[Code](https://github.com/drlxj/CamDiff) 
|   2022   |  CVPR   | GANmouflage: 3D Object Nondetection with Texture Fields <br> <sup><sub>*Rui Guo, Jasmine Collins, Oscar de Lima, Andrew Owens*</sub></sup>  | [Paper](https://arxiv.org/abs/2201.07202)/[Proj](https://rrrrrguo.github.io/ganmouflage/)
|   2022   |  CVPR   | DTA: Physical Camouflage Attacks using Differentiable Transformation Network <br> <sup><sub>*Naufal Suryanto, Yongsu Kim, Hyoeun Kang, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2203.09831)/Code
|   2022   |  TMM    | Location-Free Camouflage Generation Network <br> <sup><sub>*Yangyang Li, Wei Zhai, Yang Cao, Zheng-jun Zha*</sub></sup> | [Paper](https://arxiv.org/abs/2203.09845)/[Code](https://github.com/Tale17/LCG-Net) 





## Datasets

| **Name** | **Year** | **Pub.** | **Links** | **Type** | **#Annot. Img.(Cam./Non)** | **Bbox** | **Obj. Mask** | **Ins. Mask** | **Comments**
| :------: | :------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
[CAMO++](https://sites.google.com/view/ltnghia/research/camo_plus_plus?authuser=0) | 2021 | TIP | [Paper](https://arxiv.org/abs/2103.17123) | Image | 2,700/2,800 | &check; | &check; | &check; | <small>Not Open</small>
[NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) | 2021 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf) | Image | 4,121 | &check; | &check; | &check; |
[COD10K](http://dpfan.net/camouflage/) | 2020 | CVPR | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf) | Image | 5,066/4,934 | &check; | &check; | &check; |
[CAMO](https://sites.google.com/view/ltnghia/research/camo) | 2019 | CVIU | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf) | Image | 1,250/1,250 | &cross; | &check; | &cross; |
[CPD1K](https://github.com/xfflyer/Camouflaged-people-detection) | 2018 | SPL | [Paper](https://ieeexplore.ieee.org/document/8336933)  | Image | 1,000 | &cross; | &check; | &cross; | 
[CHAMELEON](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | 2017 | —— | [Webpage](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | Image | 76 | &cross; | &check; | &cross; | 
|  |  |  |  |  |  |  |  |  |
[MoCA-Mask](https://xueliancheng.github.io/SLT-Net-project/) | 2022 | CVPR | [Paper](https://arxiv.org/abs/2203.07363) | Video | 4,691 | &check; | &check; | &cross; | <!--87 clips, 22,939 images-->
[MoCA](https://www.robots.ox.ac.uk/~vgg/data/MoCA/) | 2020 | ACCV | [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.html) | Video | 7,617 | &check; | &cross; | &cross; | <!--141 clips, 37K images-->
[CamouflagedAnimals](http://vis-www.cs.umass.edu/motionSegmentation/) | 2016 | ECCV | [Paper](http://vis-www.cs.umass.edu/motionSegmentation/) | Video | 181 | &cross; | &check; | &check; |  <!--9 clips, 839 images-->  



## Appendix

- [Awesome List for Camouflaged Object Detection](https://github.com/GewelsJI/SINet-V2/blob/main/AWESOME_COD_LIST.md)


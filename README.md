# Papers with UnrealCV
> A curated list of papers using [UnrealCV](unrealcv.org).

This is a list of papers that use [UnrealCV](unrealcv.org), an open source project to help researchers build virtual worlds using [Unreal Engine 4](www.unrealengine.com). 
The papers are categorized by their applications, such as semantic understanding, 3D vision, embodied vision, etc.

The following labels are used to indicate the usage of UnrealCV in each paper:

- 📊`Dataset`: generate synthetic dataset for training.
- 🔍`Diagnosis`: control the factor for model diagnosis.
- 🏃`Interaction`: train/test agent(s) by interacting with the virtual worlds (e.g., RL).

## Table of Content
* [Semantic Understanding](#semantic)
  * [Segmentation](#segmentation)
  * [Text Detection](#text-detection)
  * [Person Re-identification](#person-reid)
  * [Activity Recognition](#activity)
* [3D Vision](#3d-vision)
  * [Depth Estimation](#depth)
  * [Scene Reconstruction](#reconstruction)
  * [Pose Estimation](#pose)
* [Embodied Vision](#embodied-vision)
  * [Visual Navigation](#visual-navigation)
  * [Active Object Tracking](#active-tracking)
  * [Multi-agent Cooperation](#multi-agent)

## <a name="contributing"></a> Contributing
If you find any papers that used UnrealCV but are not included in this list, please feel free to send a PR or open an issue.

When sending PRs, please put the new paper at the correct chronological position as the following format: <br>

```
- Usage Tags(📊🔍🏃) 
  **Paper Title** 
  *Author(s)* 
  Conference/Journal Year. [[Paper](link)] [[code](link)] [[Website](link)]
```

## <a name="semantic"></a> Semantic Understanding

### <a name="segmentation"></a> Object Segmentation and Detection
- 📊 **ScaleNet: Guiding Object Proposal Generation in Supermarkets and Beyond**.
   *Siyuan Qiao, Wei Shen, Weichao Qiu, Chenxi Liu, Alan Yuille*. 
   ICCV 2017. [[paper](https://arxiv.org/abs/1704.06752)] [[code](https://github.com/joe-siyuan-qiao/SupermarketPlugin-AutoShuffleWindow)]
   
- 📊
  **Semantic Part Detection via Matching: Learning to Generalize to Novel Viewpoints from Limited Training Data**.
  *Yutong Bai, Qing Liu, Lingxi Xie, Weichao Qiu, Yan Zheng, Alan Yuille*.
  ICCV 2019. [[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Bai_Semantic_Part_Detection_via_Matching_Learning_to_Generalize_to_Novel_ICCV_2019_paper.pdf)]

- 📊
  **AugPOD: Augmentation-oriented Probabilistic Object Detection**.
  *Chuan-Wei Wang\*, Chin-An Cheng\*, Ching-Ju Cheng\*, Hou-Ning Hu, Hung-Kuo Chu, Min Sun*.
  CVPR 2019 Workshop. [[paper](https://nikosuenderhauf.github.io/roboticvisionchallenges/assets/papers/CVPR19/rvc_1.pdf)]

- 📊 
  **OmniSCV: An Omnidirectional Synthetic Image Generator for Computer Vision**. 
  *Berenguel-Baeta, Bruno, Jesus Bermudez-Cameo, and Jose J. Guerrero*. Sensors 2020. [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7181225/)]

### <a name="text-detection"></a> Text Detection and Recognition
- 📊
  **UnrealText: Synthesizing Realistic Scene Text Images from the Unreal World**.
  *Minghui Liao, Guan Pang, Jing Huang, Tal Hassner, Xiang Bai*.
  CVPR 2020. [[paper](https://arxiv.org/abs/2003.10608)] [[code](https://github.com/Jyouhou/UnrealText)]

- 📊 
 **Synthetic-to-Real Unsupervised Domain Adaptation for Scene Text Detection in the Wild**.
 *Weijia Wu, Ning Lu, Enze Xie, Yuxing Wang, Wenwen Yu, Cheng Yang, Hong Zhou*.
 ACCV 2020. [[paper](https://openaccess.thecvf.com/content/ACCV2020/papers/Wu_Synthetic-to-Real_Unsupervised_Domain_Adaptation_for_Scene_Text_Detection_in_the_ACCV_2020_paper.pdf)] [[code](https://github.com/weijiawu/SyntoReal_STD)

### <a name="person-reid"></a> Person Re-identification
- 📊
  **UnrealPerson: An Adaptive Pipeline for Costless Person Re-identification**.
  *Tianyu Zhang, Lingxi Xie, Longhui Wei, Zijie Zhuang, Yongfei Zhang, Bo Li, Qi Tian*.
  CVPR 2021. [[paper](https://arxiv.org/abs/2012.04268v2)] [[code](https://github.com/FlyHighest/UnrealPerson)]

### <a name="activity"></a> Activity Recognition
- 🔍
  **Identity Preserve Transform: Understand What Activity Classification Models Have Learnt**.
  *Jialing Lyu, Weichao Qiu, Xinyue Wei, Yi Zhang, Alan Yuille, Zheng-Jun Zha*.
  CVPR 2020 Workshop. [[paper](https://arxiv.org/abs/1912.06314)]


## <a name="3d-vision"></a> 3D Vision

### <a name="depth"></a> Depth Estimation
- 🔍
  **Unrealstereo: Controlling hazardous factors to analyze stereo vision**.
  *Yi Zhang, Weichao Qiu, Qi Chen, Xiaolin Hu, Alan Yuille*.
  3DV 2018. [[paper](https://arxiv.org/abs/1612.04647)] [[code](https://github.com/edz-o/unreal-stereo-evaluation)]

- 📊 🏃
  **Enhancing optical-flow-based control by learning visual appearance cues for flying robots**.
  *G. C. H. E. de Croon, C. De Wagter, T. Seidl*.
  Nature Machine Intelligence 2021. [[paper](https://www.nature.com/articles/s42256-020-00279-7)]

### <a name="reconstruction"></a> Scene Reconstruction
- 📊
  **Submodular Trajectory Optimization for Aerial 3D Scanning**.
  *Mike Roberts, Debadeepta Dey, Anh Truong, Sudipta Sinha, Shital Shah, Ashish Kapoor, Pat Hanrahan, Neel Joshi*.
  ICCV 2017. [[paper](https://arxiv.org/abs/1705.00703)] [[project](http://graphics.stanford.edu/papers/aerial_scanning/)]
- 🏃
  **Next-Best View Policy for 3D Reconstruction**.
  *Peralta, D., Casimiro, J., Nilles, A.M., Aguilar, J.A., Atienza, R., and Cajote, R*.
  ECCV Workshops 2020. [[paper](https://arxiv.org/abs/2008.12664)] [[code](https://github.com/darylperalta/ScanRL)]
- 🏃
  **Path Planning for Active V-Slam Based on Reinforcement Learning**.
  *Borui Li, Fuchun Sun, Huaping Liu, Bin Fang*.
  International Conference on Cognitive Systems and Signal Processing 2019. [[paper](https://link.springer.com/chapter/10.1007/978-981-13-7986-4_42)]

### <a name="pose"></a> Pose Estimation
- 📊
  **A Unified Framework for Multi-View Multi-Class Object Pose Estimation**.
 *Chi Li, Jin Bai, Gregory D. Hager*.
  ECCV 2018. [[paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Chi_Li_A_Unified_Framework_ECCV_2018_paper.pdf)]

- 📊 
  🏃
  **CRAVES: Controlling Robotic Arm with a Vision-based, Economic System**.
 *Yiming Zuo\*, Weichao Qiu\*, Lingxi Xie, Fangwei Zhong, Yizhou Wang, Alan Yuille*.
  CVPR 2019. [[paper](https://arxiv.org/abs/1812.00725)] [[code](https://github.com/zuoym15/craves.ai)]

- 📊 
  **Learning from Synthetic Animals**.
  *Jiteng Mu\*, Weichao Qiu\*, Gregory Hager, Alan Yuille*.
  CVPR 2020 (Oral). [[paper](https://arxiv.org/abs/1912.08265)] [[code](https://github.com/JitengMu/Learning-from-Synthetic-Animals)]

- 📊 
 **AdaFuse: Adaptive Multiview Fusion for Accurate Human Pose Estimation in the Wild**.
 *Zhe Zhang, Chunyu Wang, Weichao Qiu, Wenhu Qin, Wenjun Zeng*.
 IJCV 2020. [[paper](https://arxiv.org/pdf/2010.13302.pdf)] [[code](https://github.com/zhezh/adafuse-3d-human-pose)]

- 📊 
  **Deep Learning for Spacecraft Pose Estimation from Photorealistic Rendering**.
  *Pedro F. Proença, Yang Gao*.
  ICRA 2020. [[paper](https://ieeexplore.ieee.org/abstract/document/9197244)] [[project](https://pedropro.github.io/project/urso/)]
- 📊 
 **Learning From Synthetic Vehicles**.
 *Tae Soo Kim, Bohoon Shim, Michael Peven, Weichao Qiu, Alan Yuille, Gregory D. Hager*.
 WACV 2022. [[paper](https://openaccess.thecvf.com/content/WACV2022W/RWS/papers/Kim_Learning_From_Synthetic_Vehicles_WACVW_2022_paper.pdf)] [[dataset](https://archive.org/details/saved-v-1)]

- 🏃
  **Proactive Multi-Camera Collaboration for 3D Human Pose Estimation**.
  *Hai Ci\*, Mickel Liu\*, Xuehai Pan\*, Fangwei Zhong, Yizhou Wang*.
  ICLR 2023. [[paper](https://openreview.net/pdf?id=CPIy9TWFYBG)] [[project](https://sites.google.com/view/active3dpose)]

## <a name="embodied-vision"></a> Embodied Vision

## <a name="visual-navigation"></a> Visual Navigation

- 🏃
  **An Improved Method Based on Deep Reinforcement Learning for Target Searching**.
  *Xiao Long Wei, Xiang Lin Huang, Tao Lu, Ge Ge Song*.
  International Conference on Robotics and Automation Engineering (ICRAE) 2019. [[paper](https://ieeexplore.ieee.org/abstract/document/9043821)]
- 🏃
  **Training an Agent to Find and Reach an Object in Different Environments using Visual Reinforcement Learning and Transfer Learning**.
 *Evelyn Conceição Santos Batista, Wouter Caarls, Leonardo A. Forero, Marco Aurélio C. Pacheco*.
 ICAART 2021. [[paper](https://www.scitepress.org/PublishedPapers/2021/102368/102368.pdf)]
- 📊
  🏃
  **Enhancing optical-flow-based control by learning visual appearance cues for flying robots**.
  *G. C. H. E. de Croon, C. De Wagter, T. Seidl*.
  Nature Machine Intelligence 2021. [[paper](https://www.nature.com/articles/s42256-020-00279-7)]

## <a name="active-tracking"></a> Active Object Tracking
- 🏃 
 **End-to-end Active Object Tracking via Reinforcement Learning**.
 *Wenhan Luo\*, Peng Sun\*, Fangwei Zhong, Wei Liu, Tong Zhang, Yizhou Wang*. 
  ICML 2018. [[paper](http://proceedings.mlr.press/v80/luo18a/luo18a.pdf)] [[project](https://sites.google.com/site/whluoimperial/active_tracking_icml2018)]

- 🏃 
  **End-to-end Active Object Tracking and Its Real-world Deployment via Reinforcement Learning**. 
  *Wenhan Luo\*, Peng Sun\*, Fangwei Zhong\*, Wei Liu, Tong Zhang, Yizhou Wang*.
  IEEE TPAMI 2019. [[paper](https://arxiv.org/pdf/1808.03405.pdf)] [[project](https://sites.google.com/site/whluoimperial/active_tracking_icml2018)]

- 🏃 
  **AD-VAT: An Asymmetric Dueling mechanism for learning Visual Active Tracking**.
  *Fangwei Zhong, Wenhan Luo, Peng Sun, Tingyun Yan, Yizhou Wang*.
  ICLR 2019. [[paper](https://openreview.net/pdf?id=HkgYmhR9KX)] [[code](https://github.com/zfw1226/active_tracking_rl)]

- 🏃
  🔍
  **AD-VAT+: An Asymmetric Dueling Mechanism for Learning and Understanding Visual Active Tracking**.
  *Fangwei Zhong, Wenhan Luo, Peng Sun, Tingyun Yan, Yizhou Wang*.
  IEEE TPAMI 2019. [[paper](https://ieeexplore.ieee.org/abstract/document/8896000)] [[code](https://github.com/zfw1226/active_tracking_rl)]

- 🏃
  **Pose-Assisted Multi-Camera Collaboration for Active Object Tracking**.
  *Jing Li\*, Jing Xu\*, Fangwei Zhong\*, Xiangyu Kong, Yu Qiao, Yizhou Wang*.
  AAAI 2020. [[paper](https://arxiv.org/pdf/2001.05161.pdf)] [[code](https://github.com/LilJing/pose-assisted-collaboration)]

- 🏃
  🔍
  **Towards Distraction-Robust Active Visual Tracking**.
  *Fangwei Zhong, Wenhan Luo, Peng Sun, Tingyun Yan, Yizhou Wang*.
  ICML 2021. [[paper](https://arxiv.org/abs/2106.10110)] [[code](https://github.com/zfw1226/active_tracking_rl/tree/distractor)] [[project](https://sites.google.com/view/distraction-robust-avt)]

- 🏃
  **Anti-Distractor Active Object Tracking in 3D Environments**.
  *Mao Xi, Yun Zhou, Zheng Chen, Wengang Zhou, Houqiang Li*.
  IEEE TCSVT 2022. [[paper](https://ieeexplore.ieee.org/abstract/document/9521193)]

- 🏃
  **RSPT: Reconstruct Surroundings and Predict Trajectories for Generalizable Active Object Tracking**.
  *Fangwei Zhong\*, Xiao Bi\*, Yudi Zhang, Wei Zhang, Yizhou Wang*.
  AAAI 2023. [[paper](https://arxiv.org/pdf/2304.03623v1.pdf)] [[project](https://sites.google.com/view/aot-rspt)]

## <a name="multi-agent"></a> Multi-Agent Cooperation
- 🏃
  **Pose-Assisted Multi-Camera Collaboration for Active Object Tracking**.
  *Jing Li\*, Jing Xu\*, Fangwei Zhong\*, Xiangyu Kong, Yu Qiao, Yizhou Wang*.
  AAAI 2020. [[paper](https://arxiv.org/pdf/2001.05161.pdf)] [[code](https://github.com/LilJing/pose-assisted-collaboration)]

- 🏃
  **Proactive Multi-Camera Collaboration for 3D Human Pose Estimation**.
  *Hai Ci\*, Mickel Liu\*, Xuehai Pan\*, Fangwei Zhong, Yizhou Wang*.
  ICLR 2023. [[paper](https://openreview.net/pdf?id=CPIy9TWFYBG)] [[project](https://sites.google.com/view/active3dpose)]

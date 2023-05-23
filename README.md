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

- 📊 **A Framework for Self-Training Perceptual Agents in Simulated Photorealistic Environments**.
   *Patrick Mania, Michael Beetz*. 
   ICRA 2019. [[paper](https://ai.uni-bremen.de/papers/mania19scenarios.pdf)] [[code](https://github.com/code-iai/ROSIntegration)]
   
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
 ACCV 2020. [[paper](https://openaccess.thecvf.com/content/ACCV2020/papers/Wu_Synthetic-to-Real_Unsupervised_Domain_Adaptation_for_Scene_Text_Detection_in_the_ACCV_2020_paper.pdf)] [[code](https://github.com/weijiawu/SyntoReal_STD)]

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

- 📊
  **ESIM: an Open Event Camera Simulator**.
  *Henri Rebecq, Daniel Gehrig, Davide Scaramuzza*.
  CoRL 2018. [[paper](https://rpg.ifi.uzh.ch/docs/CORL18_Rebecq.pdf)][[code](https://github.com/uzh-rpg/rpg_esim)]

- 📊
  **Coupled Real-Synthetic Domain Adaptation for Real-World Deep Depth Enhancement**.
  *Xiao Gu, Yao Guo, Fani Deligianni, Guang-Zhong Yang*.
  IEEE Transactions on Image Processing (TIP) 2020. [[paper](https://eprints.gla.ac.uk/214086/1/214086.pdf?ref=https://githubhelp.com)]

- 📊 🏃
  **Enhancing optical-flow-based control by learning visual appearance cues for flying robots**.
  *G. C. H. E. de Croon, C. De Wagter, T. Seidl*.
  Nature Machine Intelligence 2021. [[paper](https://www.nature.com/articles/s42256-020-00279-7)]

- 📊
  **SMD-Nets: Stereo Mixture Density Networks**.
  *Fabio Tosi, Yiyi Liao, Carolin Schmitt, Andreas Geiger*.
  CVPR 2021. [[paper](https://arxiv.org/abs/2104.03866)][[code](https://github.com/fabiotosi92/SMD-Nets)]

### <a name="reconstruction"></a> Scene Reconstruction
- 📊
  **Submodular Trajectory Optimization for Aerial 3D Scanning**.
  *Mike Roberts, Debadeepta Dey, Anh Truong, Sudipta Sinha, Shital Shah, Ashish Kapoor, Pat Hanrahan, Neel Joshi*.
  ICCV 2017. [[paper](https://arxiv.org/abs/1705.00703)] [[project](http://graphics.stanford.edu/papers/aerial_scanning/)]
- 📊
  **GEN-SLAM: Generative Modeling for Monocular Simultaneous Localization and Mapping**.
  *Punarjay Chakravarty, Praveen Narayanan, Tom Roussel*.
  ICRA 2019. [[paper](https://arxiv.org/abs/1902.02086)]
- 📊
  **QuadricSLAM: Dual Quadrics from Object Detections as Landmarks in Object-oriented SLAM**.
  *Lachlan Nicholson, Michael Milford, Niko Sünderhauf*.
  IEEE Robotics and Automation Letters (RA-L) 2019. [[paper](https://arxiv.org/abs/1804.04011)]
- 🏃
  **Path Planning for Active V-Slam Based on Reinforcement Learning**.
  *Borui Li, Fuchun Sun, Huaping Liu, Bin Fang*.
  International Conference on Cognitive Systems and Signal Processing 2019. [[paper](https://link.springer.com/chapter/10.1007/978-981-13-7986-4_42)]
- 📊
  **UnrealNavigation: Simulation Software for testing SLAM in Virtual Reality**.
  *Anne M. Bettens, Benjamin Morrell, Mauricio Coen, Neil McHenry, Xiaofeng Wu, Peter Gibbens, Gregory Chamitoff*.
  AIAA Scitech 2020 Forum. [[paper](https://d1wqtxts1xzle7.cloudfront.net/64442367/SciTechpublishedPDF-libre.pdf?1600216186=&response-content-disposition=inline%3B+filename%3DUnrealNavigation_Simulation_Software_for.pdf&Expires=1684754646&Signature=Y52JIICq~fwtHAk25SSf1PJTEee3WsdJqNp6yjk-iTydirZA9bfc3PHZnEdkzXc3CyIdcmarkkOVDsVQIpR6uuDEgeBRXyXHYfr6pkTguzggdajUaF8PFx3EFA1M3LlnL6LvbzLP5TV9Mzm3mX1eOdA52r7tYz94Z7-9isMiKnWBbHpbxF8Yq7v444NEZjbbz1aZFN1I0fvtcJerWHtn-Sqz5lpL6jjx0PP3S2PX4t96XCXjFBOhrgTMs~7-K4HTZceOw2it5hULEPy92ar6Nt5~6fwHmH73BFuo1tj1OypaWmK125z5~duOCK~G~EYmKxK0Xp8EtfzteJ0XBmHXJg__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)] [[code](https://github.com/maucoen/UnrealNavigation)]
- 📊
  **An Efficient Sampling-based Method for Online Informative Path Planning in Unknown Environments**.
  *Lukas Schmid, Michael Pantic, Raghav Khanna, Lionel Ott, Roland Siegwart, Juan Nieto*.
  IEEE Robotics and Automation Letters (RA-L) 2020. [[paper](https://arxiv.org/abs/1909.09548)] [[code](https://github.com/ethz-asl/mav_active_3d_planning)]
- 🏃
  **Next-Best View Policy for 3D Reconstruction**.
  *Peralta, D., Casimiro, J., Nilles, A.M., Aguilar, J.A., Atienza, R., and Cajote, R*.
  ECCV Workshops 2020. [[paper](https://arxiv.org/abs/2008.12664)] [[code](https://github.com/darylperalta/ScanRL)]
- 📊
  **Flight Planning for Survey-Grade 3D Reconstruction of Truss Bridges**.
  *Zhexiong Shang, Zhigang Shen*.
  Remote Sens. 2022. [[paper](https://www.mdpi.com/2072-4292/14/13/3200)]

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
  
### <a name="pose"></a> Data Generation
- 📊
  **Local Light Field Fusion: Practical View Synthesis with Prescriptive Sampling Guidelines**.
 *Ben Mildenhall, Pratul P. Srinivasan, Rodrigo Ortiz-Cayon, Nima Khademi Kalantari, Ravi Ramamoorthi, Ren Ng, Abhishek Kar*.
  SIGGRAPH 2019. [[paper](https://arxiv.org/pdf/1905.00889.pdf)] [[project](https://bmild.github.io/llff/)]

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

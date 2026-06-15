# Papers with UnrealCV
> A curated list of papers using [UnrealCV](unrealcv.org).

This is a list of papers that use [UnrealCV](unrealcv.org), an open source project to help researchers build virtual worlds using [Unreal Engine 4/5](www.unrealengine.com). 
The papers are categorized by their applications, such as semantic understanding, 3D vision, embodied vision, etc.

The following labels are used to indicate the usage of UnrealCV in each paper:

- 📊`Dataset`: generate synthetic dataset for training.
- 🔍`Diagnosis`: control the factor for model diagnosis.
- 🏃`Interaction`: train/test agent(s) by interacting with the virtual worlds (e.g., RL).

## Table of Contentc
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
  * [General Simulation/Datasets](#general-simulation)
  * [Visual Navigation](#visual-navigation)
  * [Active Object Tracking](#active-tracking)
  * [Multi-agent Cooperation](#multi-agent)
  * [Applications](#application)

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

- 📊 **Falling Things: A Synthetic Dataset for 3D Object Detection and Pose Estimation**.
   *Tremblay, Jonathan, Thang To, and Stan Birchfield*. 
   CVPR 2018 Workshop. [[paper](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w40/Tremblay_Falling_Things_A_CVPR_2018_paper.pdf)] [[code](https://research.nvidia.com/publication/2018-06_falling-things-synthetic-dataset-3d-object-detection-and-pose-estimation)]

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

- 📊
  **UR-MAT: A Multimodal, Material-Aware Synthetic Dataset of Urban Scenarios**.
  *Debora Russo, Nicola Mazzocca, Valeria Vittorini*.
  ACM Multimedia 2025. [[paper](https://dl.acm.org/doi/10.1145/3746027.3758314)]

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

- 📊
  **Robust Person Re-Identification with Wireless Signals**
  *Xi, Dong, Wengang Zhou, and Houqiang Li*. ICME 2023. [[paper](https://ieeexplore.ieee.org/abstract/document/10219732)]

- 📊
  **InfinitePerson: Innovating Synthetic Data Creation for Generalization Person Re-Identification**.
  *YingGuoqing Zhang; Jin Li; Yuhui Zheng; Ruili Wang*.
   IEEE Transactions on Circuits and Systems for Video Technology. [[paper](https://ieeexplore.ieee.org/abstract/document/10764763)] [[code](https://github.com/zhguoqing/InfinitePerson)]

### <a name="activity"></a> Activity Recognition
- 🔍
  **Identity Preserve Transform: Understand What Activity Classification Models Have Learnt**.
  *Jialing Lyu, Weichao Qiu, Xinyue Wei, Yi Zhang, Alan Yuille, Zheng-Jun Zha*.
  CVPR 2020 Workshop. [[paper](https://arxiv.org/abs/1912.06314)]
- 📊
  **Active shooter detection and robust tracking utilizing supplemental synthetic data**.
  *Joshua R. Waite, Jiale Feng, Riley Tavassoli, Laura Harris, Sin Yong Tan, Subhadeep Chakraborty, Soumik Sarkar*.
  Arxiv 2023. [[paper](https://arxiv.org/abs/2309.03381)]
## <a name="3d-vision"></a> 3D Vision

### <a name="depth"></a> Depth Estimation
- 🔍
  **Unrealstereo: Controlling hazardous factors to analyze stereo vision**.
  *Yi Zhang, Weichao Qiu, Qi Chen, Xiaolin Hu, Alan Yuille*.
  3DV 2018. [[paper](https://arxiv.org/abs/1612.04647)] [[code](https://github.com/edz-o/unreal-stereo-evaluation)]

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

- 📊
  **G2-MonoDepth: A General Framework of Generalized Depth Inference from Monocular RGB+ X Data**.
  *Haotian Wang, Meng Yang, Nanning Zheng*.
  IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI) 2023. [[paper](https://ieeexplore.ieee.org/document/10373158)]

- 📊 
  **Learning Occluded Branch Depth Maps in Forest Environments Using RGB-D Images**
  *Geckeler, C., Aucone, E., Schnider, Y., Simeon, A., von Bassewitz, J. P., Zhu, Y., & Mintchev, S.*
    IEEE Robotics and Automation Letters (RA-L) 2024. [[paper](https://ieeexplore.ieee.org/document/10403997]

- 📊
  **Real-World Depth Recovery via Structure Uncertainty Modeling and Inaccurate GT Depth Fitting**.
  *Delong Suzhang, Meng Yang*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2504.11820)]

### <a name="reconstruction"></a> Scene Reconstruction
- 📊
  **Submodular Trajectory Optimization for Aerial 3D Scanning**.
  *Mike Roberts, Debadeepta Dey, Anh Truong, Sudipta Sinha, Shital Shah, Ashish Kapoor, Pat Hanrahan, Neel Joshi*.
  ICCV 2017. [[paper](https://arxiv.org/abs/1705.00703) ] [[project](http://graphics.stanford.edu/papers/aerial_scanning/)]
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
  AIAA Scitech 2020 Forum. [[paper](https://www.researchgate.net/profile/Neil-Mchenry/publication/338398825_UnrealNavigation_Simulation_Software_for_testing_SLAM_in_Virtual_Reality/links/5f1b359f299bf1720d625b28/UnrealNavigation-Simulation-Software-for-testing-SLAM-in-Virtual-Reality.pdf)] [[code](https://github.com/maucoen/UnrealNavigation)]
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
- 📊
  **View Planning Using Discrete Optimization for 3D Reconstruction of Row Crops**.
  *Athanasios Bacharis, Henry J. Nelson and Nikolaos Papanikolopoulos*.
  IROS 2022. [[paper](https://ieeexplore.ieee.org/abstract/document/9981209)]
- 📊
  **YOWO: You Only Walk Once to Jointly Map an Indoor Scene and Register Ceiling-Mounted Cameras**.
  *Fan Yang, Sosuke Yamao, Ikuo Kusajima, Atsunori Moteki, Shoichi Masui, Shan Jiang*
  IEEE Transactions on Circuits and Systems for Video Technology, 2025. [[paper](https://ieeexplore.ieee.org/abstract/document/10663468)]
- 📊🏃
  **Semantic-Driven Informed Planning and 3D Reconstruction for the Quadrotor Unmanned Aerial Vehicle**.
  *Xiaotian Xu; Xuetao Zhang; Yisha Liu; Hanzhang Wang; Xuebo Zhang; Yan Zhuang*.
   IEEE Transactions on Vehicular Technology, 2025. [[paper](https://ieeexplore.ieee.org/document/10740306)]
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

- 📊
  **SPADES: A Realistic Spacecraft Pose Estimation Dataset using Event Sensing**.
  *Arunkumar Rathinam, Haytam Qadadri, Djamila Aouada*.
  ICRA 2024. [[paper](https://ieeexplore.ieee.org/document/10611231)] [[code](https://github.com/ArunkumarRathinam/SPADES)]

- 📊
  **Monocular 3D Human Pose Estimation for Sports Broadcasts using Partial Sports Field Registration**.
  *Tobias Baumgartner, Stefanie Klatt*. CVPR-W 2023. [[paper](https://openaccess.thecvf.com/content/CVPR2023W/CVSports/papers/Baumgartner_Monocular_3D_Human_Pose_Estimation_for_Sports_Broadcasts_Using_Partial_CVPRW_2023_paper.pdf) ] 
  [[code](https://github.com/tobibaum/PartialSportsFieldReg_3DHPE)]

- 📊 
  **Hardware-accelerated Mars Sample Localization via Deep Transfer Learning from Photorealistic Simulations**
  *R. Castilla-Arquillo, C. J. P ́erez-del-Pulgar, G. J. Paz-Delgado and L. Gerdes*
  IEEE Robotics and Automation Letters 2022. [[paper](https://arxiv.org/abs/2206.02622)] [[code](https://github.com/spaceuma/MarsSampleLocalization)]

### <a name="view"></a> View Synthesis
- 📊
  **Local Light Field Fusion: Practical View Synthesis with Prescriptive Sampling Guidelines**.
 *Ben Mildenhall, Pratul P. Srinivasan, Rodrigo Ortiz-Cayon, Nima Khademi Kalantari, Ravi Ramamoorthi, Ren Ng, Abhishek Kar*.
  SIGGRAPH 2019. [[paper](https://arxiv.org/pdf/1905.00889.pdf)][[project](https://bmild.github.io/llff/)]

- 📊
  **5D Light Field Synthesis from a Monocular Video**.
  *Kyuho Bae, Andre Ivan, Hajime Nagahara, In Kyu Park*.
  Arxiv 2019. [[paper](https://arxiv.org/abs/1912.10687)]

### <a name="event"></a> Event Camera
- 📊
  **ESIM: an Open Event Camera Simulator**.
  *Henri Rebecq, Daniel Gehrig, Davide Scaramuzza*.
  CoRL 2018. [[paper](https://rpg.ifi.uzh.ch/docs/CORL18_Rebecq.pdf)][[code](https://github.com/uzh-rpg/rpg_esim)]

- 📊
  **Insights into Batch Selection for Event-Camera Motion Estimation**.
  *Valerdi, Juan L., Chiara Bartolozzi, and Arren Glover*.
  Sensors 2023. [[paper](https://www.mdpi.com/1424-8220/23/7/3699)]


## <a name="embodied-vision"></a> Embodied Vision

### <a name="general-simulation"></a> General Simulation/Datasets
- 🏃 📊 🔍 
  **UnrealZoo: Enriching Photo-realistic Virtual Worlds for Embodied AI**.
  *Fangwei Zhong, Kui Wu, Churan Wang, Hao Chen, Hai Ci, Zhoujun Li, Yizhou Wang*.
  ICCV 2025. [[paper](https://arxiv.org/abs/2412.20977)] [[project](http://unrealzoo.site/)]
- 📊 🏃
  **EmbRACE-3K: Embodied Reasoning and Action in Complex Environments**.
  *Mingxian Lin, Wei Huang, Yitang Li, Chengjie Jiang, Kui Wu, Fangwei Zhong, Shengju Qian, Xin Wang, Xiaojuan Qi*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2507.10548)]

- 📊 🏃
  **SimWorld: An Open-ended Realistic Simulator for Autonomous Agents in Physical and Social Worlds**.
  *Jiawei Ren, Xiaokang Ye, Lingjun Mao, Xuhong He, Jianzhi Shen, Yiming Liang, Ruixuan Zhang, Tianai Yue, Yiqing Yang, Ryan Wu, Kevin Benavente, Rajiv Mandya Nagaraju, Muhammad Faayez, Xiyan Zhang, Dhruv Vivek Sharma, Xianrui Zhong, Ziqiao Ma, Tianmin Shu, Zhiting Hu, Lianhui Qin*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2512.01078)] [[project](https://simworld.org/)] [[code](https://github.com/SimWorld-AI/SimWorld)]

- 📊 🏃
  **SimWorld-Robotics: Synthesizing Photorealistic and Dynamic Urban Environments for Multimodal Robot Navigation and Collaboration**.
  *Jiawei Ren, Yiming Liang, Xiaokang Ye, Lingjun Mao, Xuhong He, Tianai Yue, Yiqing Yang, Ryan Wu, Zhiting Hu, Lianhui Qin*.
  NeurIPS 2025. [[paper](https://arxiv.org/abs/2512.10046)] [[project](https://sites.google.com/view/simworld-robotics)]

- 📊 🏃 🔍
  **LychSim: A Controllable and Interactive Simulation Framework for Vision Research**.
  *Wufei Ma, Chloe Wang, Siyi Chen, Jiawei Peng, Patrick Li, Alan Yuille*.
  Arxiv 2026. [[paper](https://arxiv.org/abs/2605.12449)] [[project](https://lychsim.github.io/)] [[code](https://github.com/wufeim/LychSim)]

- 📊 🏃 🔍
  **RescueBench: Can Embodied Agents Save Lives in the Wild ?**.
  *Kui Wu, Beiyu Guo, Hao Chen, ShuHang Xu, Yuling Li, Yongdan Zeng, Zhoujun Li, Yizhou Wang, Fangwei Zhong*.
  Arxiv 2026. [[paper](https://arxiv.org/abs/2606.01848)] [[code](https://github.com/UnrealZoo/RescueBench)]

### <a name="visual-navigation"></a> Visual Navigation

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
- 📊 🏃
  **Simultaneous localization and mapping architecture for small bodies and space exploration.**.
  *Bettens, A., Morrell, B., Coen, M., Wu, X., Gibbens, P., & Chamitoff, G.*.
  Advances in Space Research 2024, 73(1), 1185-1197. [[paper](https://www.sciencedirect.com/science/article/pii/S0273117723008682)]
- 📊 🏃
  **OpenFly: A Versatile Toolchain and Large-scale Benchmark for Aerial Vision-Language Navigation**.
  *Yunpeng Gao, Chenhui Li, Zhongrui You, Junli Liu, Zhen Li, ..., Bin Zhao, Xuelong Li*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2502.18041)] [[project](https://shailab-ipec.github.io/openfly/)]
- 📊 🏃
  **UAV-Flow Colosseo: A Real-World Benchmark for Flying-on-a-Word UAV Imitation Learning**.
  *Xiangyu Wang, Donglin Yang, Yue Liao, Wenhao Zheng, wenjun wu, Bin Dai, Hongsheng Li, Si Liu*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2505.15725)]
- 📊 🏃
  **DeliveryBench: Can Agents Earn Profit in Real World?**.
  *Lingjun Mao, Jiawei Ren, Kun Zhou, Jixuan Chen, Ziqiao Ma, Lianhui Qin*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2512.19234)] [[project](https://deliverybench.github.io/)] [[code](https://github.com/SimWorld-AI/DeliveryBench)]
- 📊 🏃
  **Scalable Multi-Task Reinforcement Learning for Generalizable Spatial Intelligence in Visuomotor Agents**.
  *Shaofei Cai, Zhancun Mu, Haiwen Xia, Bowei Zhang, Anji Liu, Yitao Liang*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2507.23698)]

- 🏃 🔍
  **WorldVLN: Autoregressive World Action Model for Aerial Vision-Language Navigation**.
  *Baining Zhao, Jiacheng Xu, Weicheng Feng, Xin Zhang, Zhaolu Wang, Haoyang Wang, Shilong Ji, Ziyou Wang, Jianjie Fang, Zhiheng Zheng, Weichen Zhang, Yu Shang, Wei Wu, Chen Gao, Xinlei Chen, Yong Li*.
  Arxiv 2026. [[paper](https://arxiv.org/abs/2605.15964)] [[code](https://github.com/EmbodiedCity/WorldVLN.code)] [[project](https://embodiedcity.github.io/WorldVLN/)]

### <a name="active-tracking"></a> Active Object Tracking
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
- 📊🏃
  **Empowering Embodied Visual Tracking with Visual Foundation Models and Offline RL**.
  *Fangwei Zhong, Kui Wu*, Hai Ci, Churan Wang, Hao Chen*.
  ECCV 2024. [[paper](https://arxiv.org/pdf/2404.09857)] [[code](https://github.com/UnrealTracking/Offline_RL_Active_Tracking)]

- 🏃
  **VLM Can Be a Good Assistant: Enhancing Embodied Visual Tracking with Self-Improving Vision-Language Models**.
  *Kui Wu, Shuhang Xu, Hao Chen, Churan Wang, Zhoujun Li, Yizhou Wang, Fangwei Zhong*.
  IROS 2025. [[paper](https://arxiv.org/abs/2505.20718)]

- 🏃
  **TrackVLA: Embodied Visual Tracking in the Wild**.
  *Shaoan Wang, Jiazhao Zhang, Minghan Li, Jiahang Liu, Anqi Li, Kui Wu, Fangwei Zhong, Junzhi Yu, Zhizheng Zhang, He Wang*.
  CoRL 2025. [[paper](https://arxiv.org/abs/2505.23189)]

- 🏃📊
  **Hierarchical Instruction-aware Embodied Visual Tracking**.
  *Kui Wu, Hao Chen, Churan Wang, Fakhri Karray, Zhoujun Li, Yizhou Wang, Fangwei Zhong*.
  Arxiv 2025. [[paper](https://arxiv.org/abs/2505.20710)]

- 🏃
  **AdaTracker: Learning Adaptive In-Context Policy for Cross-Embodiment Active Visual Tracking**.
  *Kui Wu, Hao Chen, Jinzhu Han, Haijun Liu, Churan Wang, Yizhou Wang, Zhoujun Li, Si Liu, Fangwei Zhong*.
  IEEE RA-L 2026. [[paper](https://arxiv.org/abs/2604.20305)]

- 🏃
  **Instance-level Visual Active Tracking with Occlusion-Aware Planning**.
  *Haowei Sun, Kai Zhou, Hao Gao, Shiteng Zhang, Jinwu Hu, Xutao Wen, Qixiang Ye, Mingkui Tan*.
  CVPR 2026 Poster. [[paper](https://arxiv.org/abs/2604.21453)] [[code](https://github.com/SHWplus/OA-VAT)]

- 🏃📊
  **TrackVLA++: Unleashing Reasoning and Memory Capabilities in VLA Models for Embodied Visual Tracking**.
  *Shaoan Wang, Jiazhao Zhang, Minghan Li, Jiahang Liu, Anqi Li, Kui Wu, Fangwei Zhong, Junzhi Yu, Zhizheng Zhang, He Wang*.
  ICRA 2026. [[paper](https://arxiv.org/abs/2510.07134)] [[project](https://pku-epic.github.io/TrackVLA-plus-plus-Web)]

### <a name="multi-agent"></a> Multi-Agent Cooperation
- 🏃
  **Pose-Assisted Multi-Camera Collaboration for Active Object Tracking**.
  *Jing Li\*, Jing Xu\*, Fangwei Zhong\*, Xiangyu Kong, Yu Qiao, Yizhou Wang*.
  AAAI 2020. [[paper](https://arxiv.org/pdf/2001.05161.pdf)] [[code](https://github.com/LilJing/pose-assisted-collaboration)]

- 🏃
  **Proactive Multi-Camera Collaboration for 3D Human Pose Estimation**.
  *Hai Ci\*, Mickel Liu\*, Xuehai Pan\*, Fangwei Zhong, Yizhou Wang*.
  ICLR 2023. [[paper](https://openreview.net/pdf?id=CPIy9TWFYBG)] [[project](https://sites.google.com/view/active3dpose)]

### <a name="Applications"></a> Applications
- 🏃
  **iFANnpp: Nuclear Power Plant Digital Twin for Robots and Autonomous Intelligence**.
  *Youndo Do, Marc Zebrowitz, Jackson Stahl, Fan Zhang*.
  Arxiv 2024. [[paper](https://arxiv.org/abs/2410.09213)]

- 📊
  **A scalable pipeline to create synthetic datasets from functional–structural plant models for deep learning**.
  *Dirk Norbert Baker, Felix Maximilian Bauer, Mona Giraud, Andrea Schnepf, Jens Henrik Göbbert, Hanno Scharr, Ebba Hvannberg, Morris Riedel*.
  in silico Plants, 6(1), diad022. [[paper](https://academic.oup.com/insilicoplants/article/6/1/diad022/7462759)]
- 📊
  **A Hybrid Co-Finetuning Approach for Visual Bug Detection in Video Games**.
  *Faliu Yi, Sherif Abdelfattah, Wei Huang, A. J. Brown*.
  AIIDE 2025. [[paper](https://ojs.aaai.org/index.php/AIIDE/article/view/36820)]
- 📊
  **Adapting Agricultural Virtual Environments in Game Engines to Improve HPC Accessibility**.
  *Dirk Norbert Baker, Felix Bauer, Andrea Schnepf, Hanno Scharr, Morris Riedel, Jens Henrik Göbbert, Ebba Hvannberg*.
  [[paper](https://opinvisindi.is/bitstream/handle/20.500.11815/4936/submission.pdf?sequence=1&isAllowed=y)]

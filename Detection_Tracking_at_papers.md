

# Detection and Track Adversarial Attack
----
1.[Object_Detection_Adversarial_Example_Attack](#jump1)   

2.[Track_Adversarial_Example_Attack](#jump2)  

---
## <span id="jump1">Object_Detectio_Adversarial_Example_Attack</span>


### arxiv 2023

+ T-SEA: Transfer-based Self-Ensemble Attack on Object Detection   
YHao Huang, Ziyan Chen, Huanran Chen  
[[paper](https://arxiv.org/pdf/2211.09773.pdf)] [[code](https://github.com/VDIGPKU/T-SEA)]
  <details>
    <summary>Notes</summary>
     we focus on the single-model transfer-based black-box attack on object detection, utilizing only one model to achieve a high-transferability adversarial attack on multiple black-box detectors. Specifically, we first make observations on the patch optimization process of the existing method and propose an enhanced attack framework by slightly adjusting its training strategies. Then, we analogize patch optimization with regular model optimization, proposing a series of self-ensemble approaches on the input data, the attacked model, and the adversarial patch to efficiently make use of the limited information and prevent the patch from overfitting.
    </details>




### arxiv 2022

+ Transferable Physical Attack against Object Detection with Separable Attention  
Yu Zhang, Zhiqiang Gong, Yichuang Zhang, YongQian Li, Kangcheng Bin, Jiahao Qi, Wei Xue, Ping Zhong  
[[paper](https://arxiv.org/pdf/2205.09592.pdf)]  

+ Focused Adversarial Attacks  
Thomas Cilloni, Charles Walter, Charles Fleming  
[[paper](https://arxiv.org/pdf/2205.09624.pdf)] [[code]()]
  <details>
    <summary>Notes</summary>
    
    </details>

+ Defending Against Person Hiding Adversarial Patch Attack with a Universal White Frame   
Youngjoon Yu, Hong Joo Lee, Hakmin Lee, Yong Man Ro  
[[paper](https://arxiv.org/pdf/2204.13004.pdf)] [[code]()]  

+ Using Frequency Attention to Make Adversarial Patch Powerful Against Person Detector   
Xiaochun Lei, Chang Lu, Zetao Jiang, Zhaoting Gong, Xiang Cai, Linjun Lu  
[[paper](https://arxiv.org/pdf/2205.04638.pdf)] [[code]()]

+ Deepfake Video Detection with Spatiotemporal Dropout Transformer(Defense)   
Daichi Zhang, Fanzhao Lin, Yingying Hua, Pengju Wang, Dan Zeng, Shiming Ge    
[[paper](https://arxiv.org/pdf/2207.06612)] [[code]()]


+ GLOW: Global Layout Aware Attacks for Object Detection  
Jun Bao, Buyu Liu, Jianping Fan, Jun Yu    
[[paper](https://arxiv.org/pdf/2302.14166v1.pdf)] [[code]()]



### WACV 2022

+ ADC: Adversarial attacks against object Detection that evade Context consistency checks  
Mingjun Yin, Shasha Li, Chengyu Song, M. Salman Asif, Amit K. Roy-Chowdhury, Srikanth V. Krishnamurthy  
[[paper](https://openaccess.thecvf.com/content/WACV2022/papers/Yin_ADC_Adversarial_Attacks_Against_Object_Detection_That_Evade_Context_Consistency_WACV_2022_paper.pdf)] [[code]()] 
  <details>
    <summary>Notes</summary>
    In this paper, we show that even context consistency checks can be brittle to properly crafted adversarial examples and to the best of our knowledge, we are the first to do so. Specifically, we propose an adaptive framework to generate examples that subvert such defenses, namely, Adversarial attacks against object Detection that evade Context consistency checks (ADC). In ADC, we formulate a joint optimization problem which has two attack goals, viz., (i) fooling the object detector and (ii) evading the context consistency check system, at the same time. Experiments on both PASCAL VOC and MS COCO datasets show that examples generated with ADC fool the object detector with a success rate of over 85% in most cases, and at the same time evade the recently proposed context consistency checks, with a bypassing rate of over 80% in most cases. Our results suggest that how to robustly model context and check its consistency, is still an open problem.
    </details>

+ Physical Adversarial Attacks on an Aerial Imagery Object Detector  
YAndrew Du, Bo Chen, Tat-Jun Chin, Yee Wei Law, Michele Sasdelli, Ramesh Rajasegaran, Dillon Campbell  
[[paper](https://openaccess.thecvf.com/content/WACV2022/papers/Du_Physical_Adversarial_Attacks_on_an_Aerial_Imagery_Object_Detector_WACV_2022_paper.pdf)]  

### ECCV 2022

+ Adversarially-Aware Robust Object Detector(Defense)    
Ziyi Dong, Pengxu Wei, Liang Lin    
[[paper](https://arxiv.org/abs/2207.06202)] [[code](https://github.com/7eu7d7/robustdet)]  


### CVPR 2022

+ Adversarial Texture for Fooling Person Detectors in the Physical World  
Zhanhao Hu, Siyuan Huang, Xiaopei Zhu, Xiaolin Hu, Fuchun Sun, Bo Zhang  
[[paper](https://arxiv.org/pdf/2203.03373.pdf)] [[code]()]  

+ Target-aware Dual Adversarial Learning and a Multi-scenario Multi-Modality Benchmark to Fuse Infrared and Visible for Object Detection  
Jinyuan Liu, Xin Fan, Zhanbo Huang, Guanyao Wu, Risheng Liu, Wei Zhong, Zhongxuan Luo  
[[paper](https://arxiv.org/pdf/2203.16220.pdf)] [[code](https://github.com/dlut-dimt/tardal)] 

+ Cross-Modal Transferable Adversarial Attacks from Images to Videos  
Zhipeng Wei, Jingjing Chen, Zuxuan Wu, Yu-Gang Jiang    
[[paper](https://arxiv.org/abs/2112.05379.pdf)] [[code](https://github.com/dlut-dimt/tardal)] 

+ Segment and Complete: Defending Object Detectors against Adversarial Patch Attacks with Robust Patch Detection  
Jiang Liu, Alexander Levine, Chun Pong Lau, Rama Chellappa, Soheil Feizi    
[[paper](https://arxiv.org/pdf/2112.04532)] [[code]()]  

+ Zero-Query Transfer Attacks on Context-Aware Object Detectors  
Zikui Cai, Shantanu Rane, Alejandro E. Brito, Chengyu Song, Srikanth V. Krishnamurthy, Amit K. Roy-Chowdhury, M. Salman Asif   
[[paper](https://arxiv.org/abs/2203.15230)] [[code]()] 
  <details>
    <summary>Notes</summary>
    We present the first approach for generating context-consistent adversarial attacks that can evade the context-consistency check of black-box object detectors operating on complex, natural scenes. Unlike many black-box attacks that perform repeated attempts and open themselves to detection, we assume a “zero-query” setting, where the attacker has no knowledge of the classification decisions of the victim system. First, we derive multiple attack plans that assign incorrect labels to victim objects in a context-consistent manner. Then we design and use a novel data structure that we call the perturbation success probability matrix, which enables us to filter the attack plans and choose the one most likely to succeed. This final attack plan is implemented using a perturbation-bounded adversarial attack algorithm. We compare our zero-query attack against a few-query scheme that repeatedly checks if the victim system is fooled. We also compare against state-of-the-art context-agnostic attacks. Against a context-aware defense, the fooling rate of our zero-query approach is significantly higher than context-agnostic approaches and higher than that achievable with up to three rounds of the fewquery scheme.
    </details>

### AAAI 2022

+ Context-Aware Transfer Attacks for Object Detection  
Zikui Cai, Xinxin Xie, Shasha Li, Mingjun Yin, Chengyu Song, Srikanth V. Krishnamurthy, Amit K. Roy-Chowdhury, M. Salman Asif  
[[paper](https://arxiv.org/pdf/2112.03223.pdf)] [[code](https://github.com/WhoTHU/Adversarial_Texture)]  

### AAAI 2021

+ Fooling thermal infrared pedestrian detectors in real world using small bulbs  
Xiaopei Zhu, Xiao Li, Jianmin Li, Zheyao Wang, Xiaolin Hu  
[[paper](https://arxiv.org/pdf/2101.08154.pdf)] [[code]()]  

### ICCV 2021

+ Parallel Rectangle Flip Attack: A Query-based Black-box Attack against Object Detection  
Siyuan Liang, Baoyuan Wu, Yanbo Fan, Xingxing Wei, Xiaochun Cao  
[[paper](https://arxiv.org/pdf/2201.08970.pdf)] [[code](https://github.com/LiangSiyuan21/Parallel-Rectangle-Flip-Attack-A-Query-based-Black-box-Attack-against-Object-Detection)]  

+ Exploiting Multi-Object Relationships for Detecting Adversarial Attacks in Complex Scenes (Defense)
Mingjun Yin, Shasha Li, Zikui Cai, Chengyu Song  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yin_Exploiting_Multi-Object_Relationships_for_Detecting_Adversarial_Attacks_in_Complex_Scenes_ICCV_2021_paper.pdf)] [[code]()]  
  <details>
    <summary>Notes</summary>
    Motivated by the observation that language descriptions of natural scene images have already captured the object co-occurrence relationships that can be learned by a language model, we develop a novel approach to perform context consistency checks using such language models. The distinguishing aspect of our approach is that it is independent of the deployed object detector and yet offers very high accuracy in terms of detecting adversarial examples in practical scenes with multiple objects. Experiments on the PASCAL VOC and MS COCO datasets show that our method can outperform state-of-the-art methods in detecting adversarial attacks.
    </details>


+ Naturalistic Physical Adversarial Patch for Object Detectors  
Hu Yu-Chih-Tuan, Kung Bo-Han, Tan Daniel Stanley, Chen Jun-Cheng, Hua Kai-Lung, Cheng Wen-Huang  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_Naturalistic_Physical_Adversarial_Patch_for_Object_Detectors_ICCV_2021_paper.pdf)] [[code](https://github.com/aiiu-lab/Naturalistic-Adversarial-Patch)]  

+ Data-free Universal Adversarial Perturbation and Black-box Attack  
Chaoning Zhang, Philipp Benz, Adil Karjauv, In So Kweon  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_Data-Free_Universal_Adversarial_Perturbation_and_Black-Box_Attack_ICCV_2021_paper.pdf)] [[code](https://bit.ly/3y0ZTIC)]  

+ Multi-Expert Adversarial Attack Detection in Person Re-identification Using Context Inconsistency  
Xueping Wang, Shasha Li, Min Liu, Yaonan Wang, Amit K. Roy-Chowdhury  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Multi-Expert_Adversarial_Attack_Detection_in_Person_Re-Identification_Using_Context_Inconsistency_ICCV_2021_paper.pdf)] [[code]()]  
  <details>
    <summary>Notes</summary>
    In this work, we propose a Multi-Expert Adversarial Attack Detection (MEAAD) approach to achieve this goal by checking context inconsistency, which is suitable for any DNN-based ReID systems. Specifically, three kinds of context inconsistencies caused by adversarial attacks are employed to learn a detector for distinguishing the perturbed examples, i.e., a) the embedding distances between a perturbed query person image and its top-K retrievals are generally larger than those between a benign query image and its top-K retrievals, b) the embedding distances among the top-K retrievals of a perturbed query image are larger than those of a benign query image, c) the top-K retrievals of a benign query image obtained with multiple expert ReID models tend to be consistent, which is not preserved when attacks are present. Extensive experiments on the Market1501 and DukeMTMC-ReID datasets show that, as the first adversarial attack detection approach for ReID, MEAAD effectively detects various adversarial attacks and achieves high ROC-AUC (over 97.5%).
    </details>

### IEEE Transactions on Cybernetics 2021 （Q1）

+ Daedalus: Breaking Nonmaximum Suppression in Object Detection via Adversarial Examples  
Derui Wang, Chaoran Li, Sheng Wen, Qing-Long Han, Surya Nepal, Xiangyu Zhang, Yang Xiang  
[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9313033)] [[code](https://github.com/NeuralSec/Daedalus-attack)]  

### ICME 2021

+ RPATTACK: Refined Patch Attack on General Object Detectors  
Hao Huang, Yongtao Wang, Zhaoyu Chen, Zhi Tang, Wenqiang Zhang, Kai-Kuang Ma  
[[paper](https://arxiv.org/pdf/2103.12469.pdf)] [[code](https://github.com/VDIGPKU/RPAttack)]  

+ Transferable Adversarial Examples for Anchor Free Object Detection  
Quanyu Liao, Xin Wang, Bin Kong, Siwei Lyu, Bin Zhu, Youbing Yin, Qi Song, Xi Wu  
[[paper](https://arxiv.org/pdf/2106.01618.pdf)] [[code]()] 

### ACM MM 2021

+ Efficient Sparse Attacks on Videos using Reinforcement Learning  
Huanqian Yan, Xingxing Wei  
[[paper](https://dl.acm.org/doi/pdf/10.1145/3474085.3475395)] [[code](https://github.com/FenHua/EARL)]  

+ Dual Attention Suppression Attack: Generate Adversarial Camouflage in Physical World  
Jiakai Wang, Aishan Liu, Zixin Yin, Shunchang Liu, Shiyu Tang, Xianglong Liu  
[[paper](https://arxiv.org/pdf/2103.01050.pdf)] [[code](https://github.com/nlsde-safety-team/DualAttentionAttack)]  

+ The Translucent Patch: A Physical and Universal Attack on Object Detectors   
Alon Zolfi, Moshe Kravchik, Yuval Elovici, Asaf Shabtai  
[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zolfi_The_Translucent_Patch_A_Physical_and_Universal_Attack_on_Object_CVPR_2021_paper.pdf)] [[code]()]  

+ VideoMoCo: Contrastive Video Representation Learning with Temporally Adversarial Examples  
Tian Pan, Yibing Song, Tianyu Yang, Wenhao Jiang, Wei Liu   
[[paper](https://arxiv.org/pdf/2103.05905)] [[code](https://github.com/tinapan-pt/VideoMoCo)]

### ICASSP 2021

+ Detecting Adversarial Attacks On Audiovisual Speech Recognition  
Pingchuan Ma, Stavros Petridis, Maja Pantic  
[[paper](https://arxiv.org/abs/1912.08639)] [[code]()]  

### CVPR 2020 

+ Role of Spatial Context in Adversarial Robustness for Object Detection    
BAniruddha Saha, Akshayvarun Subramanya, Koninika Patil, Hamed Pirsiavash  
[[paper](https://arxiv.org/pdf/1910.00068.pdf)] [[code](https://github.com/UMBCvision/Contextual-Adversarial-Patches)] 
  <details>
    <summary>Notes</summary>
    In this paper, we examine this problem and design category speciﬁc adversarial patches which make a widely used object detector like YOLO blind to an attacker chosen object category. We also show that limiting the use of spatial context during object detector training improves robustness to such adversaries. We believe the existence of context based adversarial attacks is concerning since the adversarial patch can affect predictions without being in vicinity of any objects of interest. Hence, defending against such attacks becomes challenging and we urge the research community to give attention to this vulnerability.
    </details>
### ECCV 2020   

+ Sparse Adversarial Attack via Perturbation Factorization  
Yanbo Fan, Baoyuan Wu, Tuanhui Li, Yong Zhang, Mingyang Li, Zhifeng Li, Yujiu Yang  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670035.pdf)] [[code](https://github.com/wubaoyuan/Sparse-Adversarial-Attack)]  

+ Indirect Local Attacks for Context-aware Semantic Segmentation Networks  
Krishna Kanth Nakka, Mathieu Salzmann  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500596.pdf)] [[code](https://github.com/krishnakanthnakka/Indirectlocalattacks/)]  

+ Connecting the Dots: Detecting Adversarial Perturbations Using Context Inconsistency  
Shasha Li, Shitong Zhu, Sudipta Paul  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680392.pdf)] [[code]()]
  <details>
    <summary>Notes</summary>
    we are the ﬁrst to propose using context inconsistency to detect adversarial perturbations in object classiﬁcation tasks. We design and realize a DNN-based adversarial detection system that automatically extracts context for each region, and checks its consistency with a learned context distribution of the corresponding category. We conduct extensive experiments on both digital and physical perturbation attacks with three diﬀerent adversarial targets on two large-scale datasets - PASCAL VOC and Microsoft COCO.
    </details>


+ APRICOT: A Dataset of Physical Adversarial Attacks on Object Detection  
A. Braunegg, Amartya Chakraborty, Michael Krumdick, Nicole Lape  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660035.pdf)] [[code](https://apricot.mitre.org/)]  

+ Design and Interpretation of Universal Adversarial Patches in Face Detection  
Xiao Yang, Fangyun Wei,  Hongyang Zhang, Jun Zhu   
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620171.pdf)] [[code]()]

+ Classes Matter: A Fine-grained Adversarial Approach to Cross-domain Semantic Segmentation  
Haoran Wang, Tong Shen, Wei Zhang, Lingyu Duan, Tao Mei     
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590630.pdf)] [[code](https://github.com/JDAI-CV/FADA)]

+ Making an Invisibility Cloak: Real World Adversarial Attacks on Object Detectors  
Zuxuan Wu, Ser-Nam Lim, Larry S. Davis, Tom Goldstein     
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490001.pdf)] [[code](https://github.com/JDAI-CV/FADA)]

### ICME 2020

+ Contextual Adversarial Attacks For Object Detection  
Hantao Zhang; Wengang Zhou; Houqiang Li  
[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9102805)] [[code](https://github.com/VDIGPKU/RPAttack)]  

### AAAI 2020

+ Heuristic Black-Box Adversarial Attacks on Video Recognition Models  
Zhipeng Wei, Jingjing Chen, Xingxing Wei, Linxi Jiang, Tat-Seng Chua, Fengfeng Zhou, Yu-Gang Jiang  
[[paper](https://arxiv.org/pdf/1911.09449.pdf)] [[code](https://github.com/zhipeng-wei/Heuristic_black_box_adversarial_attack_on_video_recognition_models)]

### AAAI 2019

+ Sparse Adversarial Perturbations for Videos  
Xingxing Wei, Jun Zhu, Hang Su  
[[paper](https://arxiv.org/pdf/2203.06616.pdf)] [[code](https://github.com/yanhui002/video_adv)]

+ DPatch: An Adversarial Patch Attack on Object Detectors  
Xin Liu, Huanrui Yang, Ziwei Liu, Linghao Song, Hai Li, Yiran Chen    
[[paper](https://arxiv.org/pdf/1806.02299.pdf)] [[code](https://github.com/veralauee/DPatch)]

### IJCAI 2019

+ Transferable Adversarial Attacks for Image and Video Object Detection  
Xingxing Wei, Siyuan Liang, Ning Chen, Xiaochun Cao  
[[paper](https://arxiv.org/pdf/1811.12641.pdf)] [[code](https://github.com/yanhui002/UEA)]

### CVPR 2019

+ Fooling automated surveillance cameras: adversarial patches to attack person detection  
Simen Thys, Wiebe Van Ranst, Toon Goedemé  
[[paper](https://arxiv.org/pdf/1904.08653.pdf)] [[code](https://gitlab.com/EAVISE/adversarial-yolo)]  

### ICCV 2019

+ AdvIT: Adversarial Frames Identifier Based on Temporal Consistency in Videos  
  Chaowei Xiao, Ruizhi Deng, Bo Li, Taesung Lee, Benjamin Edwards, Jinfeng Yi, Dawn Song, Mingyan Liu, Ian M. Molloy  
[[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xiao_AdvIT_Adversarial_Frames_Identifier_Based_on_Temporal_Consistency_in_Videos_ICCV_2019_paper.pdf)] [[code]()]  

### BMVC 2019

+ Exploring the Vulnerability of Single Shot Module in Object Detectors via Imperceptible Background Patches  
Yuezun Li, Xiao Bian, Ming-ching Chang, Siwei Lyu1  
[[paper](https://cse.buffalo.edu/~siweilyu/papers/bmvc19.pdf)] [[code](https://gitlab.com/EAVISE/adversarial-yolo)]  

### ICML 2019

+ On Physical Adversarial Patches for Object Detection  
Mark Lee, Zico Kolter  
[[paper](https://arxiv.org/pdf/1906.11897.pdf)] [[code]()]  

### arxiv 2019  

+ On Physical Adversarial Patches for Object Detection  
Mark Lee, Zico Kolter  
[[paper](https://arxiv.org/pdf/1906.11897.pdf)] [[code](https://github.com/erasaur/adversarial-patch-object-detection)]  

+ Identifying and Resisting Adversarial Videos Using Temporal Consistency  
Xiaojun Jia, Xingxing Wei, Xiaochun Cao  
[[paper](https://arxiv.org/abs/1909.04837)] [[code](h)]  
  <details>
    <summary>Notes</summary>
    In this paper, we propose an effective defense framework to characterize and defend adversarial videos. The proposed method contains two phases: (1) adversarial video detection using temporal consistency between adjacent frames, and (2) adversarial perturbation reduction via denoisers in the spatial and temporal domains respectively. Specifically, because of the linear nature of DNNs, the imperceptible perturbations will enlarge with the increasing of DNNs depth, which leads to the inconsistency of DNNs output between adjacent frames. However, the benign video frames often have the same outputs with their neighbor frames owing to the slight changes. Based on this observation, we can distinguish between adversarial videos and benign videos. After that, we utilize different defense strategies against different attacks. We propose the temporal defense, which reconstructs the polluted frames with their temporally neighbor clean frames, to deal with the adversarial videos with sparse polluted frames. For the videos with dense polluted frames, we use an efficient adversarial denoiser to process each frame in the spatial domain, and thus purify the perturbations (we call it as spatial defense). A series of experiments conducted on the UCF-101 dataset demonstrate that the proposed method significantly improves the robustness of video classifiers against adversarial attacks.
    </details>

### USENIX Security 2018

+ Physical Adversarial Examples for Object Detectors  
Kevin Eykholt, Ivan Evtimov, Earlence Fernandes, Bo Li, Amir Rahmati, Florian Tramer, Atul Prakash1, Tadayoshi Kohno, Dawn Song  
[[paper](https://arxiv.org/pdf/1807.07769.pdf)] [[code](https://gitlab.com/EAVISE/adversarial-yolo)]

### CVPR 2018

+ Robust Physical-World Attacks on Deep Learning Models  
Kevin Eykholt, Ivan Evtimov, Earlence Fernandes, Bo Li, Amir Rahmati, Chaowei Xiao, Atul Prakash, Tadayoshi Kohno, Dawn Song  
[[paper](https://arxiv.org/pdf/1707.08945.pdf)] [[code](https://gitlab.com/EAVISE/adversarial-yolo)]  

### ECCV 2018

+ Characterizing Adversarial Examples Based on Spatial Consistency Information for Semantic Segmentation  
Chaowei Xiao, Ruizhi Deng, Bo Li, Fisher Yu, Mingyan Liu, Dawn Song  
[[paper](https://arxiv.org/abs/1810.05162.pdf)] [[code](https://gitlab.com/EAVISE/adversarial-yolo)]  

### ECML-PKDD 2018（CCF B）

+ ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector  
Shang-Tse Chen, Cory Cornelius, Jason Martin, Duen Horng Chau  
[[paper](https://arxiv.org/pdf/1804.05810.pdf)] [[code](https://github.com/shangtse/robust-physical-attack)]  

### arxiv 2017

+ Adversarial Examples that Fool Detectors  
Jiajun Lu, Hussein Sibai, Evan Fabry  
[[paper](https://arxiv.org/pdf/1712.02494.pdf)] 

### ICCV 2017

+ Adversarial Examples for Semantic Segmentation and Object Detection  
Cihang Xie, Jianyu Wang, Zhishuai Zhang, Yuyin Zhou, Lingxi Xie, Alan Yuille  
[[paper](https://arxiv.org/pdf/1703.08603.pdf)] [[code](https://github.com/cihangxie/DAG)]

## <span id="jump2">Track_Adversarial_Example_Attack</span>

### ICRA 2022

+ Ad2 Attack: Adaptive Adversarial Attack on Real-Time UAV Tracking  
Changhong Fu, Sihang Li, Xinnan Yuan, Junjie Ye, Ziang Cao, Fangqiang Ding  
[[paper](https://arxiv.org/abs/2203.01516)] [[code](github.com/vision4robotics/Ad2Attack)]  


### arxiv 2022

+ SkeleVision: Towards Adversarial Resiliency of Person Tracking with Multi-Task Learning   
YNilaksh Das, Sheng-Yun Peng, Duen Horng Chau  
[[paper](https://arxiv.org/pdf/2204.00734.pdf)] [[code](https://github.com/nilakshdas/skelevision)]  

### ICLR 2022

+ Few-Shot Backdoor Attacks on Visual Object Tracking  
Yiming Li, Haoxiang Zhong, Xingjun Ma, Yong Jiang, Shu-Tao Xia  
[[paper](https://arxiv.org/pdf/2201.13178.pdf)] [[code](https://github.com/hxzhong1997/fsba)]  
  <details>
    <summary>Notes</summary>
    提出一种只对少量样本植入后门攻击（Backdoor Attack）基于孪生网络（Siamese Network）的目标跟踪模型的后门攻击方法，现有的方法在攻击的时候效果不好的原因在于良性帧与对抗帧特征空间上距离较近，导致攻击效果不佳，作者改进思路将该任务看作是一种多任务学习，学习的目标是最小化标准跟踪损失和最大化良性和对抗模版（Temple）、良性搜索区域（Region）与对抗搜索区域的特征损失，减少计算量同时保证攻击性能，通过指标精确率、AUC等展示实验结果。
    </details>

### ICASSP 2022

+ Efficient universal shuffle attack for visual object tracking  
Siao Liu, Zhaoyu Chen, Wei Li, Jiwei Zhu, Jiafeng Wang, Wenqiang Zhang, Zhongxue Gan  
[[paper](https://arxiv.org/pdf/2203.06898.pdf)] [[code]()]  

### ICCV 2021

+ Learning to Adversarially Blur Visual Object Tracking    
Qing Guo, Ziyi Cheng, Felix Juefei-Xu, Lei Ma, Xiaofei Xie, Yang Liu, Jianjun Zhao  
[[paper](https://arxiv.org/abs/2107.12085.pdf)] [[code](https://github.com/tsingqguo/ABA)]  

### CVPR 2021

+ IoU Attack: Towards Temporally Coherent Black-Box Adversarial Attack for Visual Object Tracking  
Shuai Jia, Yibing Song, Chao Ma, Xiaokang Yang  
[[paper](https://arxiv.org/pdf/2103.14938.pdf)] [[code](https://github.com/VISION-SJTU/IoUattack)]  


### AAAI 2021

+ Towards Universal Physical Attacks on Single Object Tracking  
Li Ding, Yongwei Wang, Kaiwen Yuan, Minyang Jiang, Ping Wang, Hua Huang, Z. Jane Wang  
[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16211/16018)] [[code]()]

### CVPR 2020

+ One-Shot Adversarial Attacks on Visual Tracking With Dual Attention  
Xuesong Chen, Xiyu Yan, Feng Zheng, Yong Jiang, Shu-Tao Xia, Yong Zhao, Rongrong Ji  
[[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_One-Shot_Adversarial_Attacks_on_Visual_Tracking_With_Dual_Attention_CVPR_2020_paper.pdf)] [[code](https://github.com/LiangSiyuan21/Parallel-Rectangle-Flip-Attack-A-Query-based-Black-box-Attack-against-Object-Detection)] 

+ Cooling-Shrinking Attack: Blinding the Tracker with Imperceptible Noises    
Bin Yan, Dong Wang, Huchuan Lu, Xiaoyun Yang  
[[paper](https://arxiv.org/pdf/2003.09595.pdf)] [[code](https://github.com/MasterBin-IIAU/CSA)]   
  <details>
    <summary>Notes</summary>
    提出一种冷却-收缩对抗攻击方法攻击基于Siamese的跟踪模型，该方法通过设计冷却收缩损失函数，训练一个扰动生成器网络，能够冷却目标存在的热力图区域以及收缩预测的bounding box，使目标隐形。
    </details> 

### ICLR 2020  

+ Fooling Detection Alone is Not Enough: First Adversarial Attack against Multiple Object Tracking  
  Yunhan Jia, Yantao Lu, Junjie Shen, Qi Alfred Chen, Zhenyu Zhong, Tao Wei  
[[paper](https://www.ics.uci.edu/~alfchen/jack_iclr20.pdf)] [[code](https://github.com/anonymousjack/hijacking)]  

### ECCV 2020

+ Efficient Adversarial Attacks for Visual Object Tracking  
Siyuan Liang, Xingxing Wei, Siyuan Yao, Xiaochun Cao  
[[paper](https://arxiv.org/pdf/2008.00217.pdf)] [[code](https://github.com/LiangSiyuan21/Parallel-Rectangle-Flip-Attack-A-Query-based-Black-box-Attack-against-Object-Detection)]  

+ SPARK: Spatial-aware Online Incremental Attack Against Visual Tracking    
Qing Guo, Xiaofei Xie, Felix Juefei-Xu, Lei Ma, Zhongguo Li, Wanli Xue, Wei Feng, Yang Liu  
[[paper](https://arxiv.org/pdf/1910.08681v4.pdf)] [[code](https://github.com/tsingqguo/AttackTracker)]  

+ Robust Tracking against Adversarial Attacks  
Shuai Jia, Chao Ma, Yibing Song, Xiaokang Yang  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640069.pdf)] [[code](https://github.com/joshuajss/RTAA)]  

### AAAI 2020

+ A Unified Multi-Scenario Attacking Network for Visual Object Tracking  
Xuesong Chen, Canmiao Fu, Feng Zheng, Yong Zhao, Hongsheng Li, Ping Luo, Guo-Jun Qi  
[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16195/16002)] [[code]()]


## Datasets



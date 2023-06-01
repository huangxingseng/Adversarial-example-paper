

# Image Adversarial Attack
----
1.[Image_Adversarial_Example_Attack](#jump1)  
2.[Image_Adversarial_Patch_Attack](#jump2)  
3.[Image_Backdoor_Attack](#jump3)  
4.[Image_Adversarial_Survey](#jump4) 


---


## <span id="jump1">Image_Adversarial_Example_Attack</span>


### ArXiv 2023

+ Going Further: Flatness at the Rescue of Early Stopping for Adversarial Example Transferability  
Martin Gubri, Maxime Cordy, Yves Le Traon  
[[paper](https://arxiv.org/abs/2304.02688)] [[code]()]  


### CVPR 2023

+ StyLess: Boosting the Transferability of Adversarial Examples  
Kaisheng Liang, Bin Xiao   
[[paper](https://web.comp.polyu.edu.hk/csbxiao/paper/2023/11004_styless_boosting_the_transfera-Camera-ready%20PDF.pdf)] [[code](https://github.com/uhiu/StyLess)]  
  <details>
    <summary>Notes</summary>
    CNN-based: We find that existing transferable attacks do not distinguish between style and content features during optimization, limiting their attack transferability. To improve attack transferability, we propose a novel attack method called style-less perturbation (StyLess). Specifically, instead of using a vanilla network as the surrogate model, we advocate using stylized networks, which encode different style features by perturbing an adaptive instance normalization. Our method can prevent adversarial examples from using non-robust style features and help generate transferable perturbations.
    </details>

+ Improving the Transferability of Adversarial Samples by Path-Augmented Method    
Jianping Zhang, Jen-tse Huang, Wenxuan Wang, Yichen Li, Weibin Wu, Xiaosen Wang, Yuxin Su, Michael R. Lyu   
[[paper](https://arxiv.org/abs/2303.15735)] [[code](https://github.com/uhiu/StyLess)]  
  <details>
    <summary>Notes</summary>
    CNN-based: we propose the Path-Augmented Method (PAM). Specifically, PAM first constructs a candidate augmentation path pool. It then settles the employed augmentation paths during adversarial sample generation with greedy search. Furthermore, to avoid augmenting semantics-inconsistent images, we train a Semantics Predictor (SP) to constrain the length of the augmentation path.
    </details>


+ Sensitive Region-Aware Black-box Adversarial Attacks    
Chenhao Lina, Sicong Hana, Jiongli Zhub, Qian Lia, Chao Shena, Youwei    
[[paper](https://pdf.sciencedirectassets.com/271625/AIP/1-s2.0-S0020025523004978/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQCN1ZoPF9p9FvjL03t%2F%2FgnxINk600bf7qSehigg6k4dmQIhAJ2usana3QQuA0NyzRDyZz%2FiVbqhXffBwLVeTkmYaza8KrMFCGoQBRoMMDU5MDAzNTQ2ODY1Igy9I7KEU8MeL4%2BhA8sqkAWqL6yNZLyRuhhLtNzVDUp9Bk1hqnY2%2FvuoHlitmnYpzKt%2Baozeh%2BCfEH7qpRsFW4P365eeuG3HGmniewDchDKShe2hXoYX9oPxy0awGhQrQcCn7A7PGs9nPDzqTLph2v6r5VNf65cRGy7gwb0vzpg%2BvattEay8p%2F%2Fj7KrNSFkRfNxbtxvHdA3PkXDscr1Uf%2FHLOeMMUnQGraVGZzU519iXS8gk6t6yitIn%2BD2Kkemy3aIxgkxm%2Bkb5tSXaJ0ncN8TnaBjSWo%2F2KuOFIUFm0yaY4f9%2BzjVXkIanBR22FhBXQaegdDFG%2FywFbxp21I6cQCL0vaadU%2Bx2g4sF2SurjGD5Zve45v0indfeW3FKBwcNv2wX3CvU5v4PVF1mUpUH2Yh7SGPe15t3n%2F34yddAFu6lwuDD17dRYOabmrzOqGXCrJgGjMJKf1XJdTt1gX9%2BWriBIXJmNWKVfWWCWvGMHyD%2Fr4zhpBGiwA4owef8rXrKUFMk1j4KpUngafwq24Q63aHcMn6GFH24mFe4WRjxSZ50uV%2B%2B%2B2WfsDzc%2BVvdR%2BHhSBgK7QWDMdCa%2Ft1Ezch0C4srv%2Bs0ErIlgVYkBBORrCpCIXBdf%2BPKn%2FfVx1IQtG81mggK462UlIByd%2B4MBzBsd%2FFo%2FXc3y9cOQ6dU%2BEMjqZqgvkHo6%2FHtQiYZ5oi2yg%2FNQeRAQOZMa%2BsZmArvBAj8%2F3uBsMl7GRQpcixRR288vpCF%2Fi9Z4FPVvAiMnnWSkPwNr%2FI7xxYBVGiSAb0h8FWMsSD4CR1cvcyOebAyxN2wyYuULVVUl0tmnhdDkvIDLFlCt1x0zs3eYsckqcdQKbHUOXbM98QgraQEh6Aok9tr9wKPNCW6TcV5p%2FJxpp5yjueUTTC%2FlcihBjqwAeBscyL17kLJUM4NHnwpYHA%2BORQZpv3Lax7t%2FFGAR1uzxzxBfJRfo%2BwsO4jhuV6pb4RKO4wwxj9byVZVGL7x0Nq0wiu6wdRpGk0f4zuHICPkF9PxvCVg8%2BdrDCcvGST5kUNGyGvlaPns6qZ39jWdvo%2B9yp%2FQBdnRptYeZApyQnYJLxf0O9vvdUyn7zTOTwbDEZqM%2F6p8oLL7AGfGRhkb9VxJJLA4IzhfOEfVVDKJP75K&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230409T023658Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYUUI5UQNQ%2F20230409%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=d71e13cd2a5449f0b7db54b40ad85a14a4d5f437f7b5463aa2f80d6e90620262&hash=91932458acb47b035a1b11c84f996758b3284f5823526988bae6516757507e63&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0020025523004978&tid=spdf-bff35929-be72-43a2-891d-2959656fe404&sid=3d51b3c08cc3064b0b2aea36718a5a497861gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=190855055108560056025f&rr=7b4f5d8e8f762362&cc=cn)] [[code](https://github.com/uhiu/StyLess)]  
  <details>
    <summary>Notes</summary>
    This paper proposes a novel plug-in framework called Sensitive RegionAware Attack (SRA) to generate soft-label black-box adversarial examples using the sensitivity map and evolution strategies. First, a transferable blackbox sensitivity map generation approach is proposed for identifying the sensitive regions of input images. To perform SRA with a limited amount of perturbed pixels, a dynamic l0 and l∞ adjustment strategy is introduced. Furthermore, an adaptive evolution strategy is employed to optimize the selection of generated sensitive regions, allowing for the execution of effective and imperceptible attacks.
    </details>


+ Towards Compositional Adversarial Robustness: Generalizing Adversarial Training to Composite Semantic Perturbations    
Lei Hsiung, Yun-Yun Tsai, Pin-Yu Chen, Tsung-Yi Ho 
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Hsiung_Towards_Compositional_Adversarial_Robustness_Generalizing_Adversarial_Training_to_Composite_Semantic_CVPR_2023_paper.pdf)] [[code](https://hsiung.cc/CARBEN/)]  


+ Revisiting Residual Networks for Adversarial Robustness     
Shihua Huang, Zhichao Lu, Kalyanmoy Deb, Vishnu Naresh Boddeti 
[[paper](http://arxiv.org/abs/2212.11005)] [[code]()]  



+ CFA: Class-Wise Calibrated Fair Adversarial Training      
Zeming Wei, Yifei Wang, Yiwen Guo, Yisen Wang  
[[paper](http://arxiv.org/abs/2303.14460)] [[code]()]  



+ Jedi: Entropy-Based Localization and Removal of Adversarial Patches   
Bilel Tarchoun, Anouar Ben Khalifa, Mohamed Ali Mahjoub, Nael Abu-Ghazaleh, Ihsen Alouani
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Tarchoun_Jedi_Entropy-Based_Localization_and_Removal_of_Adversarial_Patches_CVPR_2023_paper.pdf)] [[code]()]  


+ Sibling-Attack: Rethinking Transferable Adversarial Attacks Against Face Recognition    
Zexin Li, Bangjie Yin, Taiping Yao, Junfeng Guo, Shouhong Ding, Simin Chen, Cong Liu  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Sibling-Attack_Rethinking_Transferable_Adversarial_Attacks_Against_Face_Recognition_CVPR_2023_paper.pdf)] [[code]()]  



+ Physically Adversarial Infrared Patches With Learnable Shapes and Locations 
Xingxing Wei, Jie Yu, Yao Huang  
[[paper](http://arxiv.org/abs/2303.13868)] [[code]()]  



+ TWINS: A Fine-Tuning Framework for Improved Transferability of Adversarial Robustness and Generalization  
Ziquan Liu, Yi Xu, Xiangyang Ji, Antoni B. Chan  
[[paper](http://arxiv.org/abs/2303.11135)] [[code]()]  




+ Adversarial Counterfactual Visual Explanations  
Guillaume Jeanneret, Loïc Simon, Frédéric Jurie    
[[paper](http://arxiv.org/abs/2303.09962)] [[code]()]  


+ The Enemy of My Enemy Is My Friend: Exploring Inverse Adversaries for Improving Adversarial Training  
Junhao Dong, Seyed-Mohsen Moosavi-Dezfooli, Jianhuang Lai, Xiaohua Xie  
[[paper](http://arxiv.org/abs/2211.00525)] [[code]()]  


+ Towards Transferable Targeted Adversarial Examples  
Zhibo Wang, Hongshan Yang, Yunhe Feng, Peng Sun, Hengchang Guo, Zhifei Zhang, Kui Ren  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Towards_Transferable_Targeted_Adversarial_Examples_CVPR_2023_paper.pdf)] [[code]()]  


+ Discrete Point-Wise Attack Is Not Enough: Generalized Manifold Adversarial Attack for Face Recognition  
Qian Li, Yuxiao Hu, Ye Liu, Dongxiao Zhang, Xin Jin, Yuntian Chen  
[[paper](http://arxiv.org/abs/2301.06083)] [[code]()]  


+ Robust Single Image Reflection Removal Against Adversarial Attacks  
Zhenbo Song, Zhenyuan Zhang, Kaihao Zhang, Wenhan Luo, Zhaoxin Fan, Wenqi Ren, Jianfeng Lu  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Song_Robust_Single_Image_Reflection_Removal_Against_Adversarial_Attacks_CVPR_2023_paper.pdf)] [[code]()]  


+ Privacy-Preserving Adversarial Facial Features  
Zhibo Wang, He Wang, Shuaifan Jin, Wenwen Zhang, Jiahui Hu, Yan Wang, Peng Sun, Wei Yuan, Kaixin Liu, Kui Ren  
[[paper](http://arxiv.org/abs/2305.05391)] [[code]()]  


+ Boosting Accuracy and Robustness of Student Models via Adaptive Adversarial Distillation  
Bo Huang, Mingyang Chen, Yi Wang, Junda Lu, Minhao Cheng, Wei Wang  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Boosting_Accuracy_and_Robustness_of_Student_Models_via_Adaptive_Adversarial_CVPR_2023_paper.pdf)] [[code]()]  



+ Randomized Adversarial Training via Taylor Expansion  
Gaojie Jin, Xinping Yi, Dengyu Wu, Ronghui Mu, Xiaowei Huang  
[[paper](http://arxiv.org/abs/2303.10653)] [[code]()]  



+ Edges to Shapes to Concepts: Adversarial Augmentation for Robust Vision  
Aditay Tripathi, Rishubh Singh, Anirban Chakraborty, Pradeep Shenoy  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Tripathi_Edges_to_Shapes_to_Concepts_Adversarial_Augmentation_for_Robust_Vision_CVPR_2023_paper.pdf)] [[code]()]  


+ Feature Separation and Recalibration for Adversarial Robustness   
Woo Jae Kim, Yoonki Cho, Junsik Jung, Sung-Eui Yoon  
[[paper](http://arxiv.org/abs/2303.13846)] [[code]()]  
  


+ Towards Benchmarking and Assessing Visual Naturalness of Physical World Adversarial Attacks  
Simin Li, Shuning Zhang, Gujun Chen, Dong Wang, Pu Feng, Jiakai Wang, Aishan Liu, Xin Yi, Xianglong Liu  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Towards_Benchmarking_and_Assessing_Visual_Naturalness_of_Physical_World_Adversarial_CVPR_2023_paper.pdf)] [[code]()]  



+ BiasAdv: Bias-Adversarial Augmentation for Model Debiasing  
Jongin Lim, Youngdong Kim, Byungjai Kim, Chanho Ahn, Jinwoo Shin, Eunho Yang, Seungju Han  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Lim_BiasAdv_Bias-Adversarial_Augmentation_for_Model_Debiasing_CVPR_2023_paper.pdf)] [[code]()]  


+ Adversarial Robustness via Random Projection Filters  
Minjing Dong, Chang Xu  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Dong_Adversarial_Robustness_via_Random_Projection_Filters_CVPR_2023_paper.pdf)] [[code]()]  


+ The Best Defense Is a Good Offense: Adversarial Augmentation Against Adversarial Attacks  
Iuri Frosio, Jan Kautz  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Frosio_The_Best_Defense_Is_a_Good_Offense_Adversarial_Augmentation_Against_CVPR_2023_paper.pdf)] [[code]()]  


+ Seasoning Model Soups for Robustness to Adversarial and Natural Distribution Shifts  
Francesco Croce, Sylvestre-Alvise Rebuffi, Evan Shelhamer, Sven Gowal  
[[paper](http://arxiv.org/abs/2302.10164)] [[code]()]  



+ Introducing Competition To Boost the Transferability of Targeted Adversarial Examples Through Clean Feature Mixup  
Junyoung Byun, Myung-Joon Kwon, Seungju Cho, Yoonji Kim, Changick Kim  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Byun_Introducing_Competition_To_Boost_the_Transferability_of_Targeted_Adversarial_Examples_CVPR_2023_paper.pdf)] [[code]()]  


+ StyleAdv: Meta Style Adversarial Training for Cross-Domain Few-Shot Learning  
Yuqian Fu, Yu Xie, Yanwei Fu, Yu-Gang Jiang  
[[paper](http://arxiv.org/abs/2302.09309)] [[code]()]  



+ AGAIN: Adversarial Training With Attribution Span Enlargement and Hybrid Feature Fusion  
Shenglin Yin, Kelu Yao, Sheng Shi, Yangzhou Du, Zhen Xiao  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Yin_AGAIN_Adversarial_Training_With_Attribution_Span_Enlargement_and_Hybrid_Feature_CVPR_2023_paper.pdf)] [[code]()]  


+ Adversarial Normalization: I Can Visualize Everything (ICE)  
Hoyoung Choi, Seungwan Jin, Kyungsik Han  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Choi_Adversarial_Normalization_I_Can_Visualize_Everything_ICE_CVPR_2023_paper.pdf)] [[code]()]  


+ Minimizing Maximum Model Discrepancy for Transferable Black-Box Targeted Attacks  
HAnqi Zhao, Tong Chu, Yahao Liu, Wen Li, Jingjing Li, Lixin Duan  
[[paper](http://arxiv.org/abs/2212.09035)] [[code]()]  



+ Efficient Loss Function by Minimizing the Detrimental Effect of Floating-Point Errors on Gradient-Based Attacks  
Yunrui Yu, Cheng-Zhong Xu  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_Efficient_Loss_Function_by_Minimizing_the_Detrimental_Effect_of_Floating-Point_CVPR_2023_paper.pdf)] [[code]()]  


+ Effective Ambiguity Attack Against Passport-Based DNN Intellectual Property Protection Schemes Through Fully Connected Layer Substitution  
Yiming Chen, Jinyu Tian, Xiangyu Chen, Jiantao Zhou  
[[paper](http://arxiv.org/abs/2303.11595)] [[code]()]  


+ Enhancing the Self-Universality for Transferable Targeted Attacks  
Zhipeng Wei, Jingjing Chen, Zuxuan Wu, Yu-Gang Jiang  
[[paper](http://arxiv.org/abs/2209.03716)] [[code]()]  


+ Ensemble-Based Blackbox Attacks on Dense Prediction  
Zikui Cai, Yaoteng Tan, M. Salman Asif  
[[paper](http://arxiv.org/abs/2303.14304)] [[code]()]  


+ 
Dynamic Generative Targeted Attacks With Pattern Injection  
Weiwei Feng, Nanqing Xu, Tianzhu Zhang, Yongdong Zhang  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Feng_Dynamic_Generative_Targeted_Attacks_With_Pattern_Injection_CVPR_2023_paper.pdf)] [[code]()]  


### ArXiv 2022

+ Fast Gradient Non-sign Methods  
Yaya Cheng, Jingkuan Song, Xiaosu Zhu, Qilong Zhang, Lianli Gao, Heng Tao Shen  
[[paper](https://arxiv.org/pdf/2110.12734.pdf)] [[code](https://github.com/yaya-cheng/FGNM)]  

+ Improving the Transferability of Adversarial Examples with Restructure Embedded Patches  
Huipeng Zhou, Yu-an Tan, Yajie Wang, Haoran Lyu, Shangbo Wu, Yuanzhang Li  
[[paper](https://arxiv.org/pdf/2204.12680.pdf)] [[code]()]  

+ Improving Adversarial Transferability with Spatial Momentum  
Guoqiu Wang, Xingxing Wei, Huanqian Yan  
[[paper](https://arxiv.org/pdf/2203.13479.pdf)] [[code](https://github.com/yaya-cheng/FGNM)]  

+ Optimizing One-pixel Black-box Adversarial Attacks    
Tianxun Zhou, Shubhankar Agrawal, Prateek Manocha  
[[paper](https://arxiv.org/pdf/2205.02116.pdf)] [[code]()]  

### ECCV 2022

+ Frequency Domain Model Augmentation for Adversarial Attack  
Yuyang Long, Qilong Zhang, Boheng Zeng, Lianli Gao, Xianglong Liu, Jian Zhang, Jingkuan Song  
[[paper](https://arxiv.org/abs/2207.05382)] [[code](https://github.com/yuyang-long/SSA)]  

+ Susceptibility of Continual Learning Against Adversarial Attacks  
Hikmat Khan, Pir Masoom Shah, Syed Farhan Alam Zaidi, Saif ul Islam    
[[paper](https://arxiv.org/abs/2207.05225?context=cs)] [[code]()]

### ICLR 2022

+ Patch-Fool: Are Vision Transformers Always Robust Against Adversarial Perturbations?  
Yonggan Fu, Shunyao Zhang, Shang Wu, Cheng Wan, Yingyan Lin  
[[paper](https://arxiv.org/pdf/2203.08392.pdf)] [[code](https://github.com/rice-eic/patch-fool)]

+ ON IMPROVING ADVERSARIAL TRANSFERABILITY OF VISION TRANSFORMERS  
Muzammal Naseer, Kanchana Ranasinghe, Salman Khan, Fahad Shahbaz Khan, Fatih Porikli  
[[paper](https://openreview.net/pdf?id=D6nH3719vZy)] [[code](https://t.ly/hBbW)]  


+ BAG OF TRICKS FOR ADVERSARIAL TRAINING  
Tianyu Pang, Xiao Yang, Yinpeng Dong, Hang Su, Jun Zhu    
[[paper](https://openreview.net/pdf?id=Xb8xvrtB8Ce)] [[code](https://github.com/P2333/Bag-of-Tricks-for-AT)]


+ Perceptual Adversarial Robustness: Defense Against Unseen Threat Models  
Laidlaw, Cassidy and Singla, Sahil and Feizi, Soheil    
[[paper](https://arxiv.org/pdf/2006.12655)] [[code](https://github.com/cassidylaidlaw/perceptual-advex)]

+ A UNIFIED APPROACH TO INTERPRETING AND BOOSTING ADVERSARIAL TRANSFERABILITY  
Xin Wang, Jie Ren, Shuyun Lin, Xiangming Zhu, Yisen Wang, Quanshi Zhang    
[[paper](https://arxiv.org/abs/2010.04055)] [[code](https://github.com/xherdan76/A-Unified-Approach-to-Interpreting-and-Boosting-Adversarial-Transferability)]

+ RETHINKING ADVERSARIAL TRANSFERABILITY FROM A DATA DISTRIBUTION PERSPECTIVE  
Yao Zhu, Jiacheng Sun2, Zhenguo L     
[[paper](https://openreview.net/pdf?id=gVRhIEajG1k)] [[code]()]
  <details>
    <summary>Notes</summary>
    In this paper, we rethink adversarial transferability from a data distribution perspective and further enhance transferability by score matching based optimization. We identify that some samples with injecting small Gaussian noise can fool different target models, and their adversarial examples under different source models have much stronger transferability. We hypothesize that these samples are in the low-density region of the ground truth distribution where models are not well trained. To improve the attack success rate of adversarial examples, we match the adversarial attacks with the directions which effectively decrease the ground truth density. We propose Intrinsic Adversarial Attack (IAA), which smooths the activation function and decreases the impact of the later layers of a given normal model, to increase the alignment of adversarial attack and the gradient of joint data distribution.
    </details>


### CVPR 2022

+ LAS-AT: Adversarial Training with Learnable Attack Strategy  
Xiaojun Jia, Yong Zhang, Baoyuan Wu, Ke Ma, Jue Wang, Xiaochun Cao  
[[paper](https://arxiv.org/pdf/2203.06616.pdf)] [[code](https://github.com/jiaxiaojunQAQ/LAS-AT)]

+ Boosting Black-Box Attack with Partially Transferred Conditional Adversarial Distribution  
Yan Feng, Baoyuan Wu, Yanbo Fan, Li Liu, Zhifeng Li, Shutao Xia  
[[paper](https://arxiv.org/pdf/2203.06616.pdf)] [[code](https://github.com/Kira0096/CGATTACK)]

+ Stochastic Variance Reduced Ensemble Adversarial Attack for Boosting the Adversarial Transferability  
Yifeng Xiong, Jiadong Lin, Min Zhang, John E. Hopcroft, Kun He  
[[paper](https://arxiv.org/pdf/2111.10752.pdf)] [[code](https://github.com/jhl-hust/svre)]  

+ Towards Practical Certifiable Patch Defense with Vision Transformer  
Zhaoyu Chen, Bo Li, Jianghe Xu, Shuang Wu, Shouhong Ding, Wenqiang Zhang  
[[paper](https://arxiv.org/pdf/2203.08519.pdf)] [[code]()]  

+ Improving the Transferability of Targeted Adversarial Examples through Object-Based Diverse Input  
Junyoung Byun, Seungju Cho, Myung-Joon Kwon, Hee-Seon Kim, Changick Kim  
[[paper](https://arxiv.org/pdf/2203.09123.pdf)] [[code](https://github.com/dreamflake/odi)]

+ Understanding and Increasing Efficiency of Frank-Wolfe Adversarial Training(Defense)  
Theodoros Tsiligkaridis, Jay Roberts  
[[paper](https://arxiv.org/pdf/2012.12368.pdf)] [[code](https://github.com/TheoT1/FW-AT-Adapt)]

+ Exploring Frequency Adversarial Attacks for Face Forgery Detection  
Shuai Jia, Chao Ma, Taiping Yao, Bangjie Yin, Shouhong Ding, Xiaokang Yang  
[[paper](https://arxiv.org/pdf/2203.15674.pdf)] [[code]()]  

+ Subspace Adversarial Training(Defense) 
Tao Li, Yingwen Wu, Sizhe Chen, Kun Fang, Xiaolin Huang    
[[paper](https://arxiv.org/abs/2111.12229.pdf)] [[code](https://github.com/nblt/sub-at)]  

+ Pyramid Adversarial Training Improves ViT Performance(Defense) 
Charles Herrmann, Kyle Sargent, Lu Jiang, Ramin Zabih, Huiwen Chang, Ce Liu, Dilip Krishnan, Deqing Sun    
[[paper](https://arxiv.org/abs/2111.15121.pdf)] [[code]()]  

+ Transferable Sparse Adversarial Attack  
Ziwen He, Wei Wang, Jing Dong, Tieniu Tan  
[[paper](https://arxiv.org/pdf/2105.14727.pdf)] [[code](https://github.com/shaguopohuaizhe/TSAA)]  


+ Practical Evaluation of Adversarial Robustness via Adaptive Auto Attack  
Ye Liu, Yaya Cheng, Lianli Gao, Xianglong Liu, Qilong Zhang, Jingkuan Song  
[[paper](https://arxiv.org/abs/2203.05154.pdf)] [[code](https://github.com/liuye6666/adaptive_auto_attack)]  

+ Bounded Adversarial Attack on Deep Content Features  
Qiuling Xu, Guanhong Tao, Xiangyu Zhang  
[[paper](https://www.cs.purdue.edu/homes/taog/docs/CVPR22_Xu.pdf)] [[code](https://github.com/qiulingxu/D2B)]  

+ Give Me Your Attention: Dot-Product Attention Considered Harmful for Adversarial Patch Robustness  
Giulio Lovisotto, Nicole Finnie, Mauricio Munoz, Chaithanya Kumar Mummadi, Jan Hendrik Metzen  
[[paper](https://arxiv.org/pdf/2203.13639.pdf)] [[code]()]  

+ Adversarial Eigen Attack on Black-Box Models  
Linjun Zhou, Peng Cui, Yinan Jiang, Shiqiang Yang  
[[paper](https://arxiv.org/pdf/2009.00097.pdf)] [[code]()]  

+ Enhancing Adversarial Training with Second-Order Statistics of Weights  
Gaojie Jin, Xinping Yi, Wei Huang, Sven Schewe, Xiaowei Huang  
[[paper](https://arxiv.org/pdf/2203.06020.pdf)] [[code]()]  

+ Frequency-driven Imperceptible Adversarial Attack on Semantic Similarity  
Cheng Luo, Qinliang Lin, Weicheng Xie, Bizhu Wu, Jinheng Xie, Linlin Shen  
[[paper](https://arxiv.org/pdf/2203.05151.pdf)] [[code](https://github.com/LinQinLiang/SSAH-adversarial-attack)]  

+ Shadows can be Dangerous: Stealthy and Effective Physical-world Adversarial Attack by Natural Phenomenon   
Yiqi Zhong, Xianming Liu, Deming Zhai, Junjun Jiang, Xiangyang Ji  
[[paper](https://arxiv.org/pdf/2203.03818.pdf)] [[code](https://github.com/hncszyq/ShadowAttack)]  


### CVPR 2021

+ Improving the Transferability of Adversarial Samples With Adversarial Transformations  
Weibin Wu, Yuxin Su, Michael R. Lyu, Irwin King  
[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Improving_the_Transferability_of_Adversarial_Samples_With_Adversarial_Transformations_CVPR_2021_paper.pdf)] [[code](https://github.com/sarathknv/adversarial-examples-pytorch/tree/master/one_pixel_attack)]

+ Enhancing the Transferability of Adversarial Attacks through Variance Tuning  
Xiaosen Wang, Kun He  
[[paper](https://arxiv.org/pdf/2103.15571.pdf)] [[code](https://github.com/JHL-HUST/VT)]

+ SurFree: a fast surrogate-free black-box attack  
Thibault Maho, Teddy Furon, Erwan Le Merrer  
[[paper](https://arxiv.org/pdf/2011.12807v1.pdf)] [[code](https://github.com/t-maho/SurFree)]

+ Natural Adversarial Examples  
Dan Hendrycks, Kevin Zhao, Steven Basart, Jacob Steinhardt, Dawn Song  
[[paper](https://arxiv.org/pdf/1907.07174.pdf)] [[code](https://github.com/hendrycks/natural-adv-examples)]  

+ Delving into Data: Effectively Substitute Training for Black-box Attack  
Wenxuan Wang, Bangjie Yin, Taiping Yao, Li Zhang, Yanwei Fu, Shouhong Ding, Jilin Li, Feiyue Huang, Xiangyang Xue  
[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Delving_into_Data_Effectively_Substitute_Training_for_Black-box_Attack_CVPR_2021_paper.pdf)] [[code](https://github.com/hendrycks/natural-adv-examples)]  

+ You See What I Want You to See: Exploring Targeted Black-Box Transferability Attack for Hash-based Image Retrieval Systems  
Yanru Xiao and Cong Wang  
[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Xiao_You_See_What_I_Want_You_To_See_Exploring_Targeted_CVPR_2021_paper.pdf)] [[code](https://github.com/hendrycks/natural-adv-examples)]  

+ Adversarial Laser Beam: Effective Physical-World Attack to DNNs in a Blink  
Ranjie Duan, Xiaofeng Mao, A. K. Qin, Yun Yang, Yuefeng Chen, Shaokai Ye, Yuan He  
[[paper](https://arxiv.org/pdf/2103.06504)] [[code](https://github.com/RjDuan/Advlight)]  

+ Adversarial Robustness Across Representation Spaces  
Pranjal Awasthi, George Yu, Chun-Sung Ferng, Andrew Tomkins, Da-Cheng Juan  
[[paper](https://arxiv.org/pdf/2012.00802)] [[code](https://github.com/tensorflow/neural-structured-learning/tree/master/research/multi_representation_adversary)] 

+ Robust and Accurate Object Detection via Adversarial Learning  
Xiangning Chen, Cihang Xie, Mingxing Tan, Li Zhang, Cho-Jui Hsieh, Boqing Gong  
[[paper](https://arxiv.org/pdf/2103.13886)] [[code](https://github.com/google/automl)] 

### IJCAI 2021

+ Demiguise Attack: Crafting Invisible Semantic Adversarial Perturbations with Perceptual Similarity  
Yajie Wang,Shangbo Wu,Wenyi Jiang,Shengang Hao,Yu-an Tan,Quanxin Zhang  
[[paper](https://www.ijcai.org/proceedings/2021/0430.pdf)] [[code]()]

### ICCV 2021

+ Attack Agnostic Detection of Adversarial Examples via Random Subspace Analysis (Defense)  
Nathan Drenkow, Neil Fendley, Philippe Burlina  
[[paper](https://arxiv.org/pdf/2012.06405.pdf)] [[code]()]  

+ Reliably fast adversarial training via latent adversarial perturbation (Defense)  
Geon Yeong Park Sang Wan Lee  
[[paper](Park_Reliably_Fast_Adversarial_Training_via_Latent_Adversarial_Perturbation_ICCV_2021_paper)] [[code]()]  

+ AGKD-BML: Defense Against Adversarial Attack by Attention Guided Knowledge Distillation and Bi-directional Metric Learning  
Hong Wang, Yuefan Deng, Shinjae Yoo, Haibin Ling, Yuewei Lin    
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_AGKD-BML_Defense_Against_Adversarial_Attack_by_Attention_Guided_Knowledge_Distillation_ICCV_2021_paper.pdf)] [[code](https://github.com/hongw579/AGKD-BML)]

+ AdvDrop: Adversarial Attack to DNNs by Dropping Information  
Ranjie DuanYuefeng Chen Dantong Niu Yun Yang A. K. Qin Yuan He  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Duan_AdvDrop_Adversarial_Attack_to_DNNs_by_Dropping_Information_ICCV_2021_paper.pdf)] [[code]()]

+ Admix: Enhancing the Transferability of Adversarial Attacks  
Xiaosen Wang Xuanran He Jingdong Wang Kun He  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Admix_Enhancing_the_Transferability_of_Adversarial_Attacks_ICCV_2021_paper.pdf)] [[code](https://github.com/JHL-HUST/Admix)]

+ TkML-AP: Adversarial Attacks to Top-k Multi-Label Learning  
Shu Hu, Lipeng Ke, Xin Wang, Siwei Lyu  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_TkML-AP_Adversarial_Attacks_to_Top-k_Multi-Label_Learning_ICCV_2021_paper.pdf)] [[code](https://github.com/discovershu/TKML-AP)]

+ Adversarial Example Detection Using Latent Neighborhood Graph (Defense)  
Ahmed Abusnaina, Yuhang Wu, Sunpreet Arora, Yizhen Wang, Fei Wang, Hao Yang, David Mohaisen  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Abusnaina_Adversarial_Example_Detection_Using_Latent_Neighborhood_Graph_ICCV_2021_paper.pdf)] [[code]()]

+ Feature Importance-aware Transferable Adversarial Attacks  
Zhibo Wang, Hengchang Guo, Zhifei Zhang, Wenxin Liu, Zhan Qin, Kui Ren  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Feature_Importance-Aware_Transferable_Adversarial_Attacks_ICCV_2021_paper.pdf)] [[code](https://github.com/hcguoO0/FIA)]


### ECCV 2020

+ Manifold Projection for Adversarial Defense on Face Recognition (Defense)  
Jianli Zhou, Chao Liang, Jun Chen  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750290.pdf)] [[code](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750290.pdf)]

+ Defense Against Adversarial Attacks via Controlling Gradient Leaking on Embedded Manifolds (Defense)  
Yueru Li, Shuyu Cheng, Hang Su, Jun Zhu  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730749.pdf)] [[code]()]

+ Improving Adversarial Robustness by Enforcing Local and Global Compactness (Defense)  
Anh Bui, Trung Le, He Zhao, Paul Montague, Olivier deVel, Tamas Abraham, Dinh Phung  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123720205.pdf)] [[code]()]

+ Improving Query Efficiency of Black-box Adversarial Attack  
Yang Bai, Yuyuan Zeng, Yong Jiang, Yisen Wang, Shu-Tao Xia, Weiwei Guo  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700103.pdf)] [[code](https://github.com/Sandy-Zeng/NPAttack)]

+ Adversarial Training with Bi-directional Likelihood Regularization for Visual Classification  
Weitao Wan, Jiansheng Chen, Ming-Hsuan Yang  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690766.pdf)] [[code]()]

+ Square Attack: a query-efficient black-box adversarial attack via random search  
Maksym Andriushchenko, Francesco Croce  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680477.pdf)] [[code](https://github.com/max-andr/square-attack)]

+ Context-Aware RCNN: A Baseline for Action Detection in Videos  
Jianchao Wu, Zhanghui Kuang, Limin Wang, Wayne Zhang, Gangshan Wu  
[[paper](https://arxiv.org/abs/2007.09861)] [[code](https://github.com/MCG-NJU/CRCNN-Action)]

+ Open-set Adversarial Defense (Defense)  
Rui Shao, Pramuditha Perera, Pong C. Yuen, Vishal M. Patel  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123620664.pdf)] [[code](https://github.com/rshaojimmy/ECCV2020-OSAD)]

+ Boosting Decision-based Black-box Adversarial Attacks with Random Sign Flip  
Weilun Chen, Zhaoxiang Zhang, Xiaolin Hu, Baoyuan Wu  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600273.pdf)] [[code]()]

+ Bias-based Universal Adversarial Patch Attack for Automatic Check-out  
Aishan Liu, Jiakai Wang, Xianglong Liu, Bowen Cao, Chongzhi Zhang, Hang Yu  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580392.pdf)] [[code]()]

+ Improved Adversarial Training via Learned Optimizer (Defense)  
Yuanhao Xiong, Cho-Jui Hsieh 
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123530086.pdf)] [[code]()]

### ICLR 2020

+ NESTEROV ACCELERATED GRADIENT AND SCALE INVARIANCE FOR ADVERSARIAL ATTACKS  
Jiadong Lin, Chuanbiao Song, Kun He, Liwei Wang, John E. Hopcroft  
[[paper](https://arxiv.org/pdf/1908.06281.pdf)] [[code](https://github.com/JHL-HUST/SI-NI-FGSM)]

+ Skip Connections Matter: On the Transferability of Adversarial Examples Generated with ResNets  
Dongxian Wu, Yisen Wang, Shu-Tao Xia, James Bailey, Xingjun Ma  
[[paper](https://arxiv.org/pdf/2002.05990v1.pdf)] [[code](https://github.com/csdongxian/skip-connections-matter)]

### NIPS 2019

+ Adversarial Examples Are Not Bugs, They Are Features  
Andrew Ilyas, Shibani Santurkar, Dimitris Tsipras, Logan Engstrom, Brandon Tran, Aleksander Madry  
[[paper](https://arxiv.org/pdf/1905.02175.pdf)]

### CVPR 2019

+ One pixel attack for fooling deep neural networks (One_Pixel_Attack)  
Jiawei Su, Danilo Vasconcellos Vargas, Sakurai Kouichi  
[[paper](https://arxiv.org/pdf/1710.08864.pdf)] [[code](https://github.com/sarathknv/adversarial-examples-pytorch/tree/master/one_pixel_attack)]

+ Improving Transferability of Adversarial Examples with Input Diversity (DI-FGSM)  
Cihang Xie, Zhishuai Zhang, Yuyin Zhou, Song Bai, Jianyu Wang, Zhou Ren, Alan Yuille  
[[paper](https://arxiv.org/pdf/1803.06978.pdf)] [[code](https://github.com/cihangxie/DI-2-FGSM)]  

+ Evading Defenses to Transferable Adversarial Examples by Translation-Invariant Attacks (TI-FGSM)  
Yinpeng Dong, Tianyu Pang, Hang Su, Jun Zhu  
[[paper](https://arxiv.org/pdf/1904.02884.pdf)] [[code](https://github.com/dongyp13/Translation-Invariant-Attacks)]

+ SparseFool: a few pixels make a big difference (SparseFool)  
Apostolos Modas, Seyed-Mohsen Moosavi-Dezfooli, Pascal Frossard Ecole Polytechnique Federale de Lausanne  
[[paper](https://arxiv.org/pdf/1811.02248.pdf)] [[code](https://github.com/LTS4/SparseFool)]

+ Improving the Transferability of Adversarial Examples with Resized-Diverse-Inputs, Diversity-Ensemble and Region Fitting  
Junhua Zou, Zhisong Pan, Junyang Qiu, Xin Liu, Ting Rui, Wei Li  
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670562.pdf)] [[code](https://github.com/LTS4/SparseFool)]

+ Sparse Adversarial Attack via Perturbation Factorization  
Yanbo Fan, Baoyuan Wu, Tuanhui Li, Yong Zhang, Mingyang Li, Zhifeng Li, Yujiu Yang   
[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670035.pdf)] [[code](https://github.com/wubaoyuan/Sparse-Adversarial-Attack)]

### CVPR 2018

+ Boosting Adversarial Attacks with Momentum (MI-FGSM)  
Yinpeng Dong, Fangzhou Liao, Tianyu Pang, Hang Su, Jun Zhu, Xiaolin Hu, Jianguo Li  
[[paper](https://arxiv.org/pdf/1705.07204.pdf)] [[code](https://github.com/dongyp13/Non-Targeted-Adversarial-Attacks)]  

### ICLR 2018

+ Ensemble Adversarial Training: Attacks and Defenses  
Florian Tramèr, Alexey Kurakin, Nicolas Papernot, Ian Goodfellow, Dan Boneh, Patrick McDaniel  
[[paper](https://arxiv.org/pdf/1705.07204.pdf)] [[code](https://adversarial-attacks-pytorch.readthedocs.io/en/latest/attacks.html#module-torchattacks.attacks.rfgsm)]

+ Towards Deep Learning Models Resistant to Adversarial Attacks (PGD)  
Aleksander Madry, Aleksandar Makelov, Ludwig Schmidt, Dimitris Tsipras, Adrian Vladu  
[[paper](https://arxiv.org/pdf/1706.06083.pdf)] [[code](https://adversarial-attacks-pytorch.readthedocs.io/en/latest/attacks.html#module-torchattacks.attacks.pgd)]  
+ Countering Adversarial Images using Input Transformations  
Chuan Guo, Mayank Rana, Moustapha Cisse, Laurens van der Maaten  
[[paper](https://arxiv.org/pdf/1711.00117.pdf)] [[code](https://github.com/facebookarchive/adversarial_image_defenses)]

### ICLR 2017

+ ADVERSARIAL EXAMPLES IN THE PHYSICAL WORLD (BIM)  
Alexey Kurakin, Ian Goodfellow, Samy Bengio  
[[paper](https://arxiv.org/pdf/1607.02533.pdf)] [[code](https://adversarial-attacks-pytorch.readthedocs.io/en/latest/attacks.html#module-torchattacks.attacks.bim)]

### S&P 2017

+ Towards Evaluating the Robustness of Neural Networks (C&W)  
Nicholas Carlini, David Wagner  
[[paper](https://arxiv.org/pdf/1608.04644.pdf)] [[code](https://github.com/carlini/nn_robust_attacks)]

### CVPR 2017

+ Universal adversarial perturbations (UAP)  
S. Moosavi-Dezfooli*, A. Fawzi*, O. Fawzi, P. Frossard  
[[paper](https://arxiv.org/pdf/1610.08401.pdf)] [[code](https://github.com/LTS4/universal)]

### CVPR 2016

+ DeepFool: a simple and accurate method to fool deep neural networks (Deepfool)  
Seyed-Mohsen Moosavi-Dezfooli, Alhussein Fawzi, Pascal Frossard  
[[paper](https://arxiv.org/pdf/1511.04599.pdf)] [[code](https://github.com/lts4/deepfool)]

### S&P 2016

+ The limitations of deep learning in adversarial settings (JSMA)  
Papernot, Nicolas, Patrick McDaniel, Somesh Jha, Matt Fredrikson, Z. Berkay Celik, and Ananthram Swami  
[[paper](https://arxiv.org/pdf/1511.07528.pdf)]

### ICLR 2015

+ EXPLAINING AND HARNESSING ADVERSARIAL EXAMPLES (FGSM)  
Ian J. Goodfellow, Jonathon Shlens & Christian Szegedy  
[[paper](https://arxiv.org/pdf/1412.6572.pdf)] [[code](https://adversarial-attacks-pytorch.readthedocs.io/en/latest/attacks.html#module-torchattacks.attacks.fgsm)]

### ICLR 2014

+ Intriguing properties of neural networks (L-bfgs)  
Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow, Rob Fergus  
[[paper](https://arxiv.org/pdf/1312.6199.pdf)]



---
## <span id="jump2">Image_Adversarial_Patch_Attack</span>


### ICCV 2021

+ Defending against Universal Adversarial Patches by Clipping Feature Norms (Defense)  
Cheng Yu, Jiansheng Chen, Youze Xue, Yuyang Liu, Weitao Wan, Jiayu Bao, Huimin Ma  
[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_Defending_Against_Universal_Adversarial_Patches_by_Clipping_Feature_Norms_ICCV_2021_paper.pdf)] [[code](https://github.com/jiaxiaojunQAQ/Adv-watermark)] 

### ACM MM 2020

+ Adv-watermark: A Novel Watermark Perturbation for Adversarial Examples  
Xiaojun Jia, Xingxing Wei, Xiaochun Cao, Xiaoguang Han  
[[paper](https://arxiv.org/pdf/2008.01919.pdf)] [[code](https://github.com/jiaxiaojunQAQ/Adv-watermark)] 


### ECCV 2020

+ Adversarial Training against Location-Optimized Adversarial Patches  
Sukrut Rao, David Stutz, Bernt Schiele  
[[paper](https://arxiv.org/pdf/2005.02313.pdf)] [[code](https://github.com/sukrutrao/Adversarial-Patch-Training)]  

### ICML 2018

+ LaVAN: Localized and Visible Adversarial Noise  
Danny Karmon, Daniel Zoran, Yoav Goldberg  
[[paper](https://arxiv.org/pdf/1801.02608.pdf)] [[code]()]  

### NIPS 2017

+ Adversarial Patch  
Tom B. Brown, Dandelion Mané, , Aurko Roy, Martín Abadi, Justin Gilmer  
[[paper](https://arxiv.org/pdf/1712.09665.pdf)] [[code]()]  


## <span id="jump3">Image_Backdoor_Attack</span>

### Arxiv 2023 

+ Backdoor Cleansing with Unlabeled Data    
TLu Pang, Tao Sun, Haibin Ling, Chao Chen  
[[paper](https://arxiv.org/pdf/2211.12044.pdf)] [[code]()]  


+ Defending Against Patch-based Backdoor Attacks on Self-Supervised Learning    
Ajinkya Tejankar, Maziar Sanjabi, Qifan Wang  
[[paper](https://arxiv.org/pdf/2304.01482.pdf)] [[code](https://github.com/UCDvision/PatchSearch)]  



### CVPR 2023 

+ Progressive Backdoor Erasing via Connecting Backdoor and Adversarial Attacks  
Bingxu Mu, Zhenxing Niu, Le Wang, Xue Wang, Qiguang Miao, Rong Jin, Gang Hua  
[[paper](http://arxiv.org/abs/2202.06312)] [[code]()]  


+ Color Backdoor: A Robust Poisoning Attack in Color Space  
Wenbo Jiang, Hongwei Li, Guowen Xu, Tianwei Zhang  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_Color_Backdoor_A_Robust_Poisoning_Attack_in_Color_Space_CVPR_2023_paper.pdf)] [[code]()]  


+ Defending Against Patch-Based Backdoor Attacks on Self-Supervised Learning  
Ajinkya Tejankar, Maziar Sanjabi, Qifan Wang, Sinong Wang, Hamed Firooz, Hamed Pirsiavash, Liang Tan  
[[paper](http://arxiv.org/abs/2304.01482)] [[code]()]  


+ How to Backdoor Diffusion Models?  
Sheng-Yen Chou, Pin-Yu Chen, Tsung-Yi Ho  
[[paper](http://arxiv.org/abs/2212.05400)] [[code]()]  


+ Backdoor Defense via Deconfounded Representation Learning  
Zaixi Zhang, Qi Liu, Zhicai Wang, Zepu Lu, Qingyong Hu  
[[paper](http://arxiv.org/abs/2303.06818)] [[code]()]  


+ Backdoor Cleansing With Unlabeled Data  
Lu Pang, Tao Sun, Haibin Ling, Chao Chen  
[[paper](http://arxiv.org/abs/2211.12044)] [[code]()]  


+ MEDIC: Remove Model Backdoors via Importance Driven Cloning  
Qiuling Xu, Guanhong Tao, Jean Honorio, Yingqi Liu, Shengwei An, Guangyu Shen, Siyuan Cheng, Xiangyu Zhang  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_MEDIC_Remove_Model_Backdoors_via_Importance_Driven_Cloning_CVPR_2023_paper.pdf)] [[code]()]   


+ Architectural Backdoors in Neural Networks  
Mikel Bober-Irizar, Ilia Shumailov, Yiren Zhao, Robert Mullins, Nicolas Papernot  
[[paper](http://arxiv.org/abs/2206.07840)] [[code]()] 


+ Detecting Backdoors in Pre-Trained Encoders  
Shiwei Feng, Guanhong Tao, Siyuan Cheng, Guangyu Shen, Xiangzhe Xu, Yingqi Liu, Kaiyuan Zhang, Shiqing Ma, Xiangyu Zhang  
[[paper](http://arxiv.org/abs/2303.15180)] [[code]()] 


+ The Dark Side of Dynamic Routing Neural Networks: Towards Efficiency Backdoor Injection  
Simin Chen, Hanlin Chen, Mirazul Haque, Cong Liu, Wei Yang  
[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_The_Dark_Side_of_Dynamic_Routing_Neural_Networks_Towards_Efficiency_CVPR_2023_paper.pdf)] [[code]()] 


+ Backdoor Defense via Adaptively Splitting Poisoned Dataset  
Kuofeng Gao, Yang Bai, Jindong Gu, Yong Yang, Shu-Tao Xia  
[[paper](http://arxiv.org/abs/2303.12993)] [[code]()] 


+ Detecting Backdoors During the Inference Stage Based on Corruption Robustness Consistency  
Xiaogeng Liu, Minghui Li, Haoyu Wang, Shengshan Hu, Dengpan Ye, Hai Jin, Libing Wu, Chaowei Xiao  
[[paper](http://arxiv.org/abs/2303.18191)] [[code]()] 



### NIPS 2022

+ BackdoorBench: A Comprehensive Benchmark of Backdoor Learning         
Wu, Baoyuan and Chen, Hongrui and Zhang, Mingda and Zhu, Zihao and Wei, Shaokui and Yuan, Danni and Shen, Chao and Zha, Hongyuan      
[[paper]()] [[code](https://github.com/SCLBD/BackdoorBench)] 

+ Effective Backdoor Defense by Exploiting Sensitivity of Poisoned Samples       
Chen, Weixin and Wu, Baoyuan and Wang, Haoqian      
[[paper]()] [[code](https://github.com/SCLBD/BackdoorBench)] 

### IEEE TRANSACTIONS ON RELIABILITY 2022

+ Model Agnostic Defence against Backdoor Attacks in Machine Learning  
Sakshi Udeshi, Shanshan Peng, Gerald Woo, Lionell Loh, Louth Rawshan, Sudipta Chattopadhyay        
[[paper](https://arxiv.org/pdf/1908.02203.pdf)] [[code]()] 
  <details>
    <summary>Notes</summary>
    In this work, we present NEO, a model agnostic framework to detect and mitigate such backdoor attacks in image classification ML models. For a given image classification model, our approach analyses the inputs it receives and determines if the model is backdoored. In addition to this feature, we also mitigate these attacks by determining the correct predictions of the poisoned images.
    </details>



### ICLR 2022

+ Backdoor Defense via Decoupling the Training Process     
Huang, Kunzhe and Li, Yiming and Wu, Baoyuan and Qin, Zhan and Ren, Kui    
[[paper]()] [[code](https://github.com/SCLBD/BackdoorBench)] 


### ICCV 2021

+ Invisible backdoor attack with sample-specific triggers    
Li, Yuezun and Li, Yiming and Wu, Baoyuan and Li, Longkang and He, Ran and Lyu, Siwei  
[[paper]()] [[code](https://github.com/SCLBD/BackdoorBench)] 


### EMNLP 2021

+ Backdoor Attacks on Pre-trained Models by Layerwise Weight Poisoning    
Linyang Li, Demin Song, Xiaonan Li, Jiehang Zeng, Ruotian Ma, Xipeng Qiu  
[[paper](https://arxiv.org/abs/2108.13888)] [[code]()] 


### CCS 2021

+ Backdoor Pre-trained Models Can Transfer to All    
Lujia Shen, Shouling Ji, Xuhong Zhang  
[[paper](https://dl.acm.org/doi/pdf/10.1145/3460120.3485370)] [[code]()] 

### CVPR 2021

+ Black-box Detection of Backdoor Attacks with Limited Information and Data      
Yinpeng Dong, Xiao Yang, Zhijie Deng, Tianyu Pang, Zihao Xiao, Hang Su, Jun Zhu    
[[paper](https://arxiv.org/abs/2103.13127#)] [[code]()] 


### IEEE Access 2019

+ BadNets: Evaluating Backdooring Attacks on Deep Neural Networks      
TIANYU GU, KANG LIU, BRENDAN DOLAN-GAVITT, SIDDHARTH GARG    
[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8685687)] [[code](https://github.com/verazuo/badnets-pytorch)] 



## <span id="jump4">Image_Adversarial_Survey</span>

### Arxiv 2023

+ It Is All About Data: A Survey on the Effects of Data on Adversarial Robustness  
PEIYU XIONG, MICHAEL TEGEGN, JASKEERAT SINGH SARIN, SHUBHRANEEL PAL, JULIA RUBIN  
[[paper](https://arxiv.org/pdf/2303.09767.pdf)] [[code]()] 





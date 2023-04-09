

# Image Adversarial Attack
----
1.[Image_Adversarial_Example_Attack](#jump1)  
2.[Image_Adversarial_Patch_Attack](#jump2)  
3.[Image_Backdoor_Attack](#jump3)  
4.[Image_Adversarial_Survey](#jump4) 


---


## <span id="jump1">Image_Adversarial_Example_Attack</span>

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




## <span id="jump4">Image_Adversarial_Survey</span>

### Arxiv 2023

+ It Is All About Data: A Survey on the Effects of Data on Adversarial Robustness  
PEIYU XIONG, MICHAEL TEGEGN, JASKEERAT SINGH SARIN, SHUBHRANEEL PAL, JULIA RUBIN  
[[paper](https://arxiv.org/pdf/2303.09767.pdf)] [[code]()] 






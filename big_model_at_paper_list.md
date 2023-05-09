

# Big model Adversarial Attack
----
1.[White-box-Attack](#jump1)   

2.[Black-box-Attack](#jump2)  

---
## <span id="jump1">White-box-Attack</span>


### arxiv 2022

+ On the Adversarial Robustness of Vision Transformers   
Rulin Shao, Zhouxing Shi, Jinfeng Yi, Pin-Yu Chen, Cho-Jui Hsieh  
[[paper](https://arxiv.org/abs/2103.15670)]  [[code](https://github.com/RulinShao/on-the-adversarial-robustness-of-visual-transformer)]


### ICCV 2021

+ Understanding robustness of transformers for image classiﬁcation  
Srinadh Bhojanapalli, Ayan Chakrabarti, Daniel Glasner, Daliang Li, Thomas Unterthiner, Andreas Veit
[[paper](https://arxiv.org/abs/2103.14586)] [[code]()]
  <details>
    <summary>Notes</summary>
    test
    </details>





## <span id="jump2">Black-box-Attack</span>


### CVPR 2023

+ Transferable Adversarial Attacks on Vision Transformers with Token Gradient Regularization  
Jianping Zhang, Yizhan Huang, Weibin Wu, Michael R. Lyu  
[[paper](https://arxiv.org/pdf/2303.15754.pdf)] [[code]()]  



### arxiv 2022

+ Decision-based Black-box Attack Against Vision Transformers via Patch-wise Adversarial Removal
Yucheng Shi, Yahong Han, Yu-an Tan, Xiaohui Kuang  
[[paper](https://arxiv.org/abs/2112.03492)] [[code](https://github.com/shiyuchengTJU/PAR/blob/main/par_main.py)]  


+ Towards Transferable Adversarial Attacks on Vision Transformers  
Zhipeng Wei, Jingjing Chen, Micah Goldblum, Zuxuan Wu, Tom Goldstein, Yu-Gang Jiang  
[[paper](https://arxiv.org/abs/2109.04176)] [[code](https://github.com/shiyuchengTJU/PAR/blob/main/par_main.py)]  


+ On Improving Adversarial Transferability of Vision Transformers  
Muzammal Naseer, Kanchana Ranasinghe, Salman Khan, Fahad Shahbaz Khan, Fatih Porikli  
[[paper](https://arxiv.org/abs/2106.04169)] [[code](https://t.ly/hBbW)]  


### CVPR 2022

+ A Comprehensive Study of Image Classification Model Sensitivity to Foregrounds, Backgrounds, and Visual Attributes  
Mazda Moayeri, Phillip Pope, Yogesh Balaji  
[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Moayeri_A_Comprehensive_Study_of_Image_Classification_Model_Sensitivity_to_Foregrounds_CVPR_2022_paper.pdf)] [[code]()]  
  <details>
    <summary>Notes</summary>
    In our analysis, we consider diverse state-of-the-art architectures (ResNets, Transformers) and training procedures (CLIP, SimCLR, DeiT, Adversarial Training). We find that, somewhat surprisingly, in ResNets, adversarial training makes models more sensitive to the background compared to foreground than standard training. Similarly, contrastively-trained models also have lower relative foreground sensitivity in both transformers and ResNets. Lastly, we observe intriguing adaptive abilities of transformers to increase relative foreground sensitivity as corruption level increases. Using saliency methods, we automatically discover spurious features that drive the background sensitivity of models and assess alignment of saliency maps with foregrounds
    </details>



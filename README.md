# Adversarial-machine-learning

## Introduction

An image with a non-random noisy **imperceptible** to human can make machines' predictions **incorrectly**.

![](https://github.com/VVillQian/Adversarial-machine-learning/blob/main/images/adex.PNG)

It is often formulated as an optimiation problem:
![](https://latex.codecogs.com/svg.latex?x^*=\\mathop{argmax}_{x}Dist(x,x_0)+c\\mathcal{L}(x))
,where Dist and ![](https://latex.codecogs.com/svg.latex?\\mathcal{L}) capture "imperceptible" and "incorrectly" respectively.

## Trends
![](https://nicholas.carlini.com/writing/2019/advex_plot.png)

[source](https://nicholas.carlini.com/writing/2019/all-adversarial-example-papers.html)

## Contests
- [NIPS 2017: Targeted Adversarial Attack](https://www.kaggle.com/c/nips-2017-targeted-adversarial-attack)
- [NIPS 2018: Adversarial Vision Challenge](https://www.crowdai.org/challenges/adversarial-vision-challenge)
- [IJCAI 2019: Alibaba Adversarial AI Challenge](https://tianchi.aliyun.com/markets/tianchi/ijcai19_en)
- [CIKM 2020: Adversarial Challenge on Object Detection](https://tianchi.aliyun.com/competition/entrance/531806/introduction?spm=5176.12281949.1003.15.5cea24485KbbDJ)
- [ACM MM2021: Robust defense competition for e-commerce logo detection](https://tianchi.aliyun.com/competition/entrance/531888/introduction?spm=5176.12281957.1004.7.38b0244818wKWp)

## Selected Papers

### Attack

Number | Method| Title | Reference | Code 
------ | ----- | ----- | --------- | ---- 
01|L-BFGS-B|Intriguing Properties of Neural Networks|[ICLR 2014](https://arxiv.org/abs/1312.6199)|[code](http://goo.gl/huaGPb)
02|FGSM|Explaining and Harnessing Adversarial Examples|[ICLR 2015](https://arxiv.org/abs/1412.6572)
03|C&W|Towards Evaluating the Robustness of Neural Networks|[S&P 2017](https://ieeexplore.ieee.org/document/7958570/)|[code](http://nicholas.carlini.com/code/nn_robust_attacks)
04|Boundary Attack|Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models|[ICLR 2018](https://openreview.net/forum?id=SyZI0GWCZ)|[code](https://github.com/bethgelab/foolbox)
05||Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples|[ICML 2018](http://proceedings.mlr.press/v80/athalye18a.html)|[code](https://github.com/anishathalye/obfuscated-gradients)
06|1Pixel|One Pixel Attack for Fooling Deep Neural Networks|[TEC 2019](https://ieeexplore.ieee.org/document/8601309)|[code](https://github.com/Hyperparticle/one-pixel-attack-keras)
07|ReColorAdv|Functional Adversarial Attacks|[NIPS 2019](https://proceedings.neurips.cc/paper/2019/hash/6e923226e43cd6fac7cfe1e13ad000ac-Abstract.html)|[code]( https://github.com/cassidylaidlaw/ReColorAdv)
08|Opt-attack|Query-Efficient Hard-label Black-box Attack: An Optimization-based Approach|[ICLR 2019](https://openreview.net/forum?id=rJlk6iRqKX)|[code](https://github.com/LeMinhThong/blackbox-attack)
09|SignHunter|Sign Bits Are All You Need for Black-Box Attacks|[ICLR 2020](https://openreview.net/forum?id=SygW0TEFwH)|[code](https://bit.ly/3acIHoQ)
10|RayS|RayS: A Ray Searching Method for Hard-label Adversarial Attack|[KDD 2020](https://dl.acm.org/doi/10.1145/3394486.3403225)|[code](https://github.com/uclaml/RayS)
11|PerC-C&W|Towards Large yet Imperceptible Adversarial Image Perturbations with Perceptual Color Distance|[CVPR 2020](https://ieeexplore.ieee.org/document/9157804/)|[code](https://github.com/ZhengyuZhao/PerC-Adversarial)


### Defence

Number | Method| Title | Reference | Code 
------ | ----- | ----- | --------- | ---- 
01|Adversarial Training|Towards Deep Learning Models Resistant to Adversarial Attacks|[ICLR 2018](https://openreview.net/forum?id=rJzIBfZAb)|[code](https://github.com/MadryLab)
02|TRADES|Theoretically Principled Trade-off between Robustness and Accuracy|[ICML 2019](http://proceedings.mlr.press/v97/zhang19p.html)|[code](https://github.com/yaodongyu/TRADES)
03|Randomized smoothing|Certified Adversarial Robustness via Randomized Smoothing|[ICML 2019](http://proceedings.mlr.press/v97/cohen19c.html)|[code](http://github.com/locuslab/smoothing)
04|DMAT|Dual Manifold Adversarial Robustness: Defense against Lp and non-Lp Adversarial Attacks|[NIPS 2020](https://proceedings.neurips.cc/paper/2020/hash/23937b42f9273974570fb5a56a6652ee-Abstract.html)|[code]()



### Metric

Number | Title | Reference | Code 
------ | ----- | --------- | ---- 

### Mechanism

Number | Title | Reference 
------ | ----- | --------- 
01|Intriguing Properties of Neural Networks|[ICLR 2014](https://arxiv.org/abs/1312.6199)|[code](http://goo.gl/huaGPb)
02|Explaining and Harnessing Adversarial Examples|[ICLR 2015](https://arxiv.org/abs/1412.6572)
03|Adversarial Examples are not Bugs, they are Features|[NIPS 2019](https://proceedings.neurips.cc/paper/2019/hash/e2c420d928d4bf8ce0ff2ec19b371514-Abstract.html)|[code](http://git.io/adv-datasets)


## Recommended Blogs
Number | Link
------ | ----
01|[gradient science](http://gradientscience.org)

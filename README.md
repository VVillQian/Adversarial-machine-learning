# Adversarial-machine-learning

## Introduction

An image with a non-random noisy **imperceptible** to human can make machines' predictions **incorrectly**.

## Trends
![trends](https://nicholas.carlini.com/writing/2019/advex_plot.png)

[image source](https://nicholas.carlini.com/writing/2019/all-adversarial-example-papers.html)

## Contests
- [NIPS 2017: Targeted Adversarial Attack](https://www.kaggle.com/c/nips-2017-targeted-adversarial-attack)
- [NIPS 2018: Adversarial Vision Challenge](https://www.crowdai.org/challenges/adversarial-vision-challenge)
- [IJCAI 2019: Alibaba Adversarial AI Challenge](https://tianchi.aliyun.com/markets/tianchi/ijcai19_en)
- [CIKM 2020: Adversarial Challenge on Object Detection](https://tianchi.aliyun.com/competition/entrance/531806/introduction?spm=5176.12281949.1003.15.5cea24485KbbDJ)
- [ACM MM2021: Robust defense competition for e-commerce logo detection](https://tianchi.aliyun.com/competition/entrance/531888/introduction?spm=5176.12281957.1004.7.38b0244818wKWp)

## Selected Papers

### Attack

Number | Method| Title | Reference | Code | Sparkle
------ | ----- | ----- | --------- | ---- | -------
01|L-BFGS-B|Intriguing Properties of Neural Networks|[ICLR 2014](https://arxiv.org/abs/1312.6199)|[code](http://goo.gl/huaGPb)|Definition
02|FGSM|Explaining and Harnessing Adversarial Examples|[ICLR 2015](https://arxiv.org/abs/1412.6572)
03|C&W|Towards Evaluating the Robustness of Neural Networks|[S&P 2017](https://ieeexplore.ieee.org/document/7958570/)|[code](http://nicholas.carlini.com/code/nn_robust_attacks)
04||Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models|[ICLR 2018](https://openreview.net/forum?id=SyZI0GWCZ)|[code](https://github.com/bethgelab/foolbox)|black box

### Defence

Number | Method| Title | Reference | Code | Sparkle
------ | ----- | ----- | --------- | ---- | -------
01|AT|Towards Deep Learning Models Resistant to Adversarial Attacks|[ICLR 2018](https://openreview.net/forum?id=rJzIBfZAb)|[code](https://github.com/MadryLab)|min-max formulation;loss surface
02|TRADES|Theoretically Principled Trade-off between Robustness and Accuracy|[ICML 2019](http://proceedings.mlr.press/v97/zhang19p.html)|[code](https://github.com/yaodongyu/TRADES)|theoretical analysis;lower bound



### Metric

Number | Title | Reference | Code | Sparkle
------ | ----- | --------- | ---- | -------


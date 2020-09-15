# Awesome One Class Classification

A curated list of awesome resources dedicated to One Class Classification.

**Contributing**: Please feel free to make *[pull requests](https://github.com/tim5go/awesome-one-class-classification/pulls)*.

## Contents
* [Research Trends and Surveys](#research-trends-and-surveys)
* [Papers](#papers)
	* [SVM Approaches](#svm-approaches)
	* [Deep Learning Approaches](#deep-learning-approaches)
* [Datasets](#datasets)


## Research Trends and Surveys
* [One-class classification: Concept-learning in the absence of counter-examples](http://homepage.tudelft.nl/n9d04/thesis.pdf) (DMJ Tax, 2001)
* [One-class classification: taxonomy of study and review of techniques](https://arxiv.org/abs/1312.0049) (Shehroz S.Khan, Michael G.Madden, 2014)
* [Rethinking Assumptions in Deep Anomaly Detection](https://arxiv.org/abs/2006.00339) (Lukas Ruff, Robert A. Vandermeulen, Billy Joe Franks, Klaus-Robert Müller, Marius Kloft, 2020)


## Papers

### SVM Approaches
#### Support Vector Domain Description
* Support vector domain description [[paper]](http://rduin.nl/papers/prl_99_svdd.pdf)
	* David M.J. Tax, Robert P.W. Duin
	* Pattern Recognition Letters 20 (1999)
#### Support Vector Mapping Convergence
* Text Classification from Positive and Unlabeled Documents [[paper]](http://sifaka.cs.uiuc.edu/czhai/pub/cikm03-svm.pdf)
	* Hwanjo Yu, ChengXiang Zhai, Jiawei Han
	* CIKM 2003
#### Center-Based Similarity Space Learning
* Breaking the Closed World Assumption in Text Classification [[paper]](https://www.aclweb.org/anthology/N16-1061/)
	* Geli Fei, Bing Liu
	* NAACL 2016
#### Cumulative Learning
* Learning Cumulatively to Become More Knowledgeable [[paper]](https://www.kdd.org/kdd2016/papers/files/rpp0426-feiA.pdf)
	* Geli Fei, Shuai Wang and Bing Liu
	* KDD 2016

### Deep Learning Approaches
#### OpenMax
* Towards Open Set Deep Networks [[paper]](https://arxiv.org/abs/1511.06233)
	* Abhijit Bendale, Terrance Boult
	* CVPR 2016
#### Deep Open Classification (DOC)
* DOC: Deep Open Classification of Text Documents [[paper]](https://arxiv.org/abs/1709.08716)
	* Lei Shu, Hu Xu, Bing Liu
	* EMNLP 2017
#### Deep Support Vector Data Description
* Deep One-Class Classification [[paper]](http://proceedings.mlr.press/v80/ruff18a.html)
	* Lukas Ruff, Robert Vandermeulen, Nico Goernitz, Lucas Deecke, Shoaib Ahmed Siddiqui, Alexander Binder, Emmanuel Müller, Marius Kloft
	* PMLR 2018
#### GAN
* Out-of-domain Detection based on Generative Adversarial Network [[paper]](https://www.aclweb.org/anthology/D18-1077/)
	* Seonghan Ryu, Sangjun Koo, Hwanjo Yu, Gary Geunbae Lee
	* EMNLP 2018
#### Mahalanobis distance-based
* A Simple Unified Framework for Detecting Out-of-Distribution Samples and Adversarial Attacks [[paper]](https://arxiv.org/abs/1807.03888)
	* Kimin Lee, Kibok Lee, Honglak Lee, Jinwoo Shin
	* NIPS 2018
* Rethinking Softmax Cross-Entropy Loss for Adversarial Robustness [[paper]](https://arxiv.org/abs/1905.10626)
	* Tianyu Pang, Kun Xu, Yinpeng Dong, Chao Du, Ning Chen, Jun Zhu
	* ICLR 2020
#### Margin Loss
* Deep Unknown Intent Detection with Margin Loss [[paper]](https://www.aclweb.org/anthology/P19-1548/)
	* Ting-En Lin, Hua Xu
	* ACL 2019
#### KL Divergence
* KLOOS: KL Divergence-based Out-of-Scope Intent Detection in Human-to-Machine Conversations [[paper]](https://dl.acm.org/doi/abs/10.1145/3397271.3401318)
	* Eyup Halit Yilmaz, Cagri Toraman
	* SIGIR 2020
#### Pseudo OOD Sample Generation (POG)
* Out-of-domain Detection for Natural Language Understanding in Dialog Systems [[paper]](https://arxiv.org/abs/1909.03862)
	* Yinhe Zheng, Guanyi Chen, Minlie Huang
	* TALSP 2020

[Back to Top](#contents)


## Datasets
* Intent Classification and Out-of-Scope Prediction Dataset [[paper]](https://arxiv.org/abs/1909.02027)
	* This dataset dataset covers 150 intent classes over 10 domains, capturing the breadth that a production taskoriented agent must handle. It also includes queries that are out-of-scope i.e., queries that do not fall into any of the system’s supported intents. 

[Back to Top](#contents)
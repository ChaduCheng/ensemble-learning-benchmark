# ensemble-learning-benchmark
The purpose of our project is to design a new ensemble learning models with some better metric value, like accuracy, robustness, etc. 
This repository will present some interesting papers bout the current work of ensemble learning and other related information. Also, we will put some good results on ensemble learning and other things to this repository. This repository will keep being updated. 

## Ensemble learning method and some other methods similar to ensemble learning:

### model-base:  

#### modify the network structure or congregate models:  


* [Revisiting Ensemble in Adversarial Context: Improving natural accuracy](https://arxiv.org/pdf/2002.11572.pdf)  
(ICLR workshop 2020)  
(Aditya Saligrama et al)  
**content**: Design an ensemble learning system could improve natural accuracy. This paper executes ensemble learning based on composite models.  
* [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770)  
(ICLR 2017)  
(Yanpei Liu et al)  
**contents**: The ensemble learning method proposed in this paper is based on adding all pre-trained models together and train them. This paper claims that they are the first one to study this topic over large models and a large scale dataset. And the first paper to study non-targeted attack and targeted attack in this area.  
* [Enhance certified radius via a Deep Model Ensemble](https://arxiv.org/pdf/1910.14655.pdf)  
(arXiv 31 oct 2019)  
(Huan Zhang et al)  
**content**: This paper proposes an algorithm to enhance certified robustness of a deep model ensemble by optimally weighting each base model.  
* [Ensemble the adv and certified training](https://openreview.net/forum?id=SJxSDxrKDr)  
(ICLR 2020)  
(Mislav Balunovic et al)  
**content** This paper present COLT, a new method to train neural networks based on a novel combination of adversarial training and provable defense.  

#### modify loss function:    

* Meta-learning Enabled Adversarial Training  
(Yiyi Tao, Bo Li et al)
**content**: First meta-learning based adversarial training approach. Execute ensemble leraning by modifying the models' parameters.  
* [Provable robustness against all adversarial](https://arxiv.org/pdf/1905.11213.pdf)  
(arXiv 27 May 2019)  
(Francesco Groce et al)  
**content**: This paper propse a new regularization scheme for ReLU networks which enforces robustness and show how that leads to provably robust models.

### data augments:

* [Ensemble Adversarial Training: Attacks and Defenses](https://arxiv.org/abs/1705.07204)  
(ICLR 2019)  
(Florian Tramer et al)  
[(ftramer_code)](https://github.com/ftramer/ensemble-adv-training)
**contents**: This paper propose ensemble learning mainly by using data augments. It seems that the first paper to study ensemble learning.  
* [**Adversarial Training and Robustness for Multiple Perturbations**](https://arxiv.org/pdf/1904.13000.pdf) 
(arXiv 18 Oct 2019)  
(Florian Tramer et al)  
**content**: This paper's aim is to understand the reasons underlying the robustness trade-off, and to train models that are simultaneously robust to multiple perturbation types.
* [n-ML: Mitigating Adversarial Examples via Ensembles of Topologically Manipulated Classifiers](https://arxiv.org/pdf/1912.09059.pdf)  
(arXiv 19 Dec 2019)  
(Mahmood Sharif et al)  
**contents**: This paper propose a new defense called n-ML against adv examples. inputs crefted by perturbing benign inputs by small amounts to induce misclassifications by classifiers. 
* [Testing Robustness Against Unforeseen Adversarial](https://arxiv.org/abs/1908.08016)  
(arXiv 19 Aug 2019)  
(Daniel Kang et al)  
[(code and perturbation data)](https://github.com/ddkang/advex-uar)
**contents**: This paper propose a methodology for evaluating a defense against a diverse range of distrotion types and also use a summary metric UAR to measure the unforeseen attack robustness against distortion. 

## Improving the performance of ensemble learning:
* [Improving Adversarial Robustness via Promoting Ensemble Diversity](https://arxiv.org/pdf/1901.08846.pdf)  
(arXiv 29 May 2019)  
(Tianyu Pang et al)  
**content**: This paper presents a method that explores the interaction among individual networks to improve robustness for ensemble modles. They define a new notion of ensemble diversity.  
* [**Improving Adversarial Robustness of Ensembles with Diversity Training**](https://arxiv.org/pdf/1901.09981.pdf)  
(arXiv 28 Jan 2019)  
(Sanjay Kariyappa)  
**content**: This paper propose *Diversity Training*, a novel method to train an ensemble of models with uncorrelated loss functions.This method focuses on modifying loss function.They try to improve the robustness by reduce adversarial subspace.



## Some new discoveries of adversarial training's characteristics:  
* [loss of invariance: Fundamental Tradeoffs between Invariance and Sensitivity to Adversarial Perturbations](https://arxiv.org/pdf/2002.04599.pdf)  
(arXiv 11 Feb 2020)  
(Florian Tramer et al)  
**Content**: Instead of studying sensitivity-based adversarial examples, this paper studies invariance-based adv examples, which introduce minimal semantic changes that modify an input's true label yet preserve the model's prediction.  
* [Sensitivity: On the sensitivity of adversarial robustness to input data distributions](https://openreview.net/pdf?id=S1xNEhR9KX)  
(ICLR 2019)  
(Gavin Weiguang Ding et al)  
**Content**: there are existing relationship between adversarial robustness and the input data distribution.  

## Different Metrics:   
* [Robustness May Be at Odds with Accuracy](https://openreview.net/forum?id=SyxAb30cY7)  
(ICLR 2019)  
(Dimitris Tsipras et al)  
**contents**: There are existing inherent tension between the goal of adv robustness and that of generalization. The trade-off between the standard accuracy of a model and its robustness to adv perturbations provably exists even in a fairly simple an natural setting.  
* [Fundamental Tradeoffs between Invariance and Sensitivity to Adversarial Perturbations](https://arxiv.org/pdf/2002.04599.pdf)
(arXiv 11 Feb 2020)  
(Florian Tramer et al)  
**contents**: There are existing trade-off between invariance-based adv examples and sensitivity-based adv examples.  
* [Are Adversarial Robustness and Common Perturbation Robustness Independant Attributes ?](http://openaccess.thecvf.com/content_ICCVW_2019/papers/RLQ/Laugros_Are_Adversarial_Robustness_and_Common_Perturbation_Robustness_Independant_Attributes__ICCVW_2019_paper.pdf)  
(ICCV workshop 2019)  
(Alfred Laugros et al)
**contents**: This paper talks about the relationship between the adversarial robustness and common perturbations. This paper wants to talk about the question about what extent the adversarial robutsness is related to the global robustness. 

## Some methods that are helpful to our problems:  
* [self-supervised: Adversarial Robustness: From Self-Supervised Pre-Training to Fine-Tuning](https://arxiv.org/pdf/2003.12862.pdf)   
(arXiv 28 March 2020)    
(Tianlong Chen et al)  
**Contents**: Introduce adversarial training into self-supervision, to provide general-purpose robust pretrained models for the first time.  
* [ResNets Ensemble via the Feynman-Kac Formalism to Improve Natural and Robust Accuracies](https://papers.nips.cc/paper/8443-resnets-ensemble-via-the-feynman-kac-formalism-to-improve-natural-and-robust-accuracies.pdf)  
(NIPS 2019)  
(Bao Wang et al)  
* [Towards A Unified Min-Max Framework for Adversarial Exploration and Robustness](https://www.researchgate.net/profile/Jiacen_Xu2/publication/333679480_Beyond_Adversarial_Training_Min-Max_Optimization_in_Adversarial_Attack_and_Defense/links/5dbfb886a6fdcc212800a8ef/Beyond-Adversarial-Training-Min-Max-Optimization-in-Adversarial-Attack-and-Defense.pdf)  
(arXiv 29 Sep 2019)  
(Jingkang Wang et al)  
* [Improving the affordability of robustness training for DNNs](https://arxiv.org/pdf/2002.04237.pdf)  
(arXiv 11 Feb 2020)  
(Sidharth Gupta et al)  



Last updated: April 27, 2020

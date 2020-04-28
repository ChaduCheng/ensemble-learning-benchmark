# ensemble-learning-benchmark
The purpose of our project is to design a new ensemble learning models with some better metric value, like accuracy, robustness, etc. 
This repository will present some interesting papers bout the current work of ensemble learning and other related information. Also, we will put some good results on ensemble learning and other things to this repository. This repository will keep being updated. 

## Drawbacks on exisiing adversarial and certified training techniques with single DNN:  
* [loss of invariance](https://arxiv.org/pdf/2002.04599.pdf)  
(arXiv 11 Feb 2020)  
(Florian Tramer et al)  
* [On the ensitivity of adversarial robustness to input data distributions](https://openreview.net/pdf?id=S1xNEhR9KX)  
(ICLR 2019)  
(Gavin Weiguang Ding et al)  
**Content**: there are existing relationship between adversarial robustness and the input data distribution.  

## Ensemble learning method and some other methods similar to ensemble learning:

### model-base:  
#### modify the network structure or congregate models:  
[ftramer_code](https://github.com/ftramer/ensemble-adv-training)
* [Revisiting Ensemble in Adversarial Context: Improving natural accuracy](https://arxiv.org/pdf/2002.11572.pdf)  
(ICLR workshop 2020)  
(Aditya Saligrama et al)  
**content**: Desin an ensemble learning system could improve natural accuracy. This paper executes ensemble learning based on composite models.  
* [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770)  
(ICLR 2017)  
(Yanpei Liu et al)  
**contents**: The ensemble learning method proposed in this paper is based on adding all pre-trained models together and train them. This paper claims that they are the first one to study this topic over large models and a large scale dataset. And the first paper to study non-targeted attack and targeted attack in this area. 
#### modify loss function:    
* Meta-learning Enabled Adversarial Training  
(Yiyi Tao, Bo Li et al)
**content**: First meta-learning based adversarial training approach. Execute ensemble leraning by modifying the models' parameters.  
### data augments:
* [Ensemble Adversarial Training: Attacks and Defenses](https://arxiv.org/abs/1705.07204)  
(ICLR 2019)  
(Florian Tramer et al)  
**contents**: This paper propose ensemble learning mainly by using data augments. It seems that the first paper to study ensemble learning.  


* [Enhance certified radius via a Deep Model Ensemble](https://arxiv.org/pdf/1910.14655.pdf)  
(arXiv 31 oct 2019)  
(Huan Zhang et al)  
* [Improving Adversarial Robustness via Promoting Ensemble Diversity](https://arxiv.org/pdf/1901.08846.pdf)  
(arXiv 29 May 2019)  
(Tianyu Pang et al)  
* [Improving Adversarial Robustness of Ensembles with Diversity Training](https://arxiv.org/pdf/1901.09981.pdf)  
(arXiv 28 Jan 2019)  
(Sanjay Kariyappa)  
* [n-ML: Mitigating Adversarial Examples via Ensembles of Topologically Manipulated Classifiers](https://arxiv.org/pdf/1912.09059.pdf)  
(arXiv 19 Dec 2019)  
(Mahmood Sharif et al)  
* [Ensemble the adv and certified training](https://openreview.net/forum?id=SJxSDxrKDr)  
(ICLR 2020)  
(Mislav Balunovic et al)  

## Different Metrics:   
* [Robustness May Be at Odds with Accuracy](https://openreview.net/forum?id=SyxAb30cY7)  
(ICLR 2019)  
(Dimitris Tsipras et al)  
* [Fundamental Tradeoffs between Invariance and Sensitivity to Adversarial Perturbations](https://arxiv.org/pdf/2002.04599.pdf)
(arXiv 11 Feb 2020)  
(Florian Tramer et al)  
* [Are Adversarial Robustness and Common Perturbation Robustness Independant Attributes ?](http://openaccess.thecvf.com/content_ICCVW_2019/papers/RLQ/Laugros_Are_Adversarial_Robustness_and_Common_Perturbation_Robustness_Independant_Attributes__ICCVW_2019_paper.pdf)  
(ICCV workshop 2019)  
(Alfred Laugros et al)


## Some naive solutions of our problem:  
* [self-supervised](https://arxiv.org/pdf/2003.12862.pdf)   
(arXiv 28 March 2020)    
(Tianlong Chen et al)  
* [ResNets Ensemble via the Feynman-Kac Formalism to Improve Natural and Robust Accuracies](https://papers.nips.cc/paper/8443-resnets-ensemble-via-the-feynman-kac-formalism-to-improve-natural-and-robust-accuracies.pdf)  
(NIPS 2019)  
(Bao Wang et al)  
* [Towards A Unified Min-Max Framework for Adversarial Exploration and Robustness](https://www.researchgate.net/profile/Jiacen_Xu2/publication/333679480_Beyond_Adversarial_Training_Min-Max_Optimization_in_Adversarial_Attack_and_Defense/links/5dbfb886a6fdcc212800a8ef/Beyond-Adversarial-Training-Min-Max-Optimization-in-Adversarial-Attack-and-Defense.pdf)  
(arXiv 29 Sep 2019)  
(Jingkang Wang et al)  
* [Improving the affordability of robustness training for DNNs](https://arxiv.org/pdf/2002.04237.pdf)  
(arXiv 11 Feb 2020)  
(Sidharth Gupta et al)  



## Designing models robust on multiple perturbations:  
* [Adversarial Training and Robustness for Multiple Perturbations](https://arxiv.org/pdf/1904.13000.pdf)  
(arXiv 18 Oct 2019)  
(Florian Tramer et al)  
* [Provable robustness against all adversarial](https://arxiv.org/pdf/1905.11213.pdf)  
(arXiv 27 May 2019)  
(Francesco Groce et al)  


Last updated: April 25, 2020

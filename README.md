# RGB-D Salient Object Detection: A Survey

![alt text](./Fig0.jpg)


RGB-D Salient Object Detection: A Survey

Contributed by  [*Tao Zhou*](https://taozh2017.github.io), [*Deng-Ping Fan*](https://dpfan.net/).

--- *Last updated: 2020/07/26* --- 


------


## Content:

1. <a href="#survey"> Related Reviews and Surveys to SOD </a>
2. <a href="#RGBDmodels"> RGB-D SOD Models </a>
3. <a href="#LFmodels">  Light Field SOD Models </a>
4. <a href="#datasets"> RGB-D SOD Datasets </a>
5. <a href="#evaluation"> Evaluation </a>
    1. <a href="#technical_CT">  Overall Evaluation: </a>
    1. <a href="#technical_CXR">  Attribute-based Evaluation: </a>


------

## Related Reviews and Surveys to SOD:  <a id="survey" class="anchor" href="#survey" aria-hidden="true"><span class="octicon octicon-link"></span></a>  

**No.** | **Year** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-: | :-  | :-: 
01 | 2015 | IEEE TIP   |  Salientobject detection: A benchmark | [Paper](https://arxiv.org/pdf/1501.02741.pdf)/Project
02 | 2018 | IEEE TCSVT |  Review of visual saliency detectionwith comprehensive information | [Paper](https://arxiv.org/pdf/1803.03391.pdf)/Project
03 | 2018 | ACM TIST   |  A review of co-saliency detection algorithms: Fundamentals,applications, and challenges | [Paper](https://arxiv.org/pdf/1604.07090.pdf)/Project
04 | 2018 | IEEE TSP   |  Advanced deep-learning techniques for salient andcategory-specific object detection: A survey| [Paper](https://ieeexplore.ieee.org/document/8253582)/Project
05 | 2018 | IJCV       |  Attentivesystems: A survey | [Paper](https://link.springer.com/article/10.1007/s11263-017-1042-6)/Project
06 | 2019 | CVM        |  Salient object detection: A survey | [Paper](https://link.springer.com/content/pdf/10.1007/s41095-019-0149-9.pdf)/Project
07 | 2019 | IEEE TNNLS |  Object detection with deep learning: Areview | [Paper](https://arxiv.org/pdf/1807.05511.pdf)/Project
08 | 2019 | arXiv      |  Salient Object Detection in the Deep Learning Era-An In-Depth Survey | [Paper](https://arxiv.org/pdf/1904.09146.pdf)/[Project](https://github.com/wenguanwang/SODsurvey) 


------

## RGB-D SOD Models:  <a id="RGBDmodels" class="anchor" href="#RGBDmodels" aria-hidden="true"><span class="octicon octicon-link"></span></a>  

**No.** | **Year** | **Model** |**Pub.** | **Title** | **Links** 
:-: | :-: | :-: | :-  | :-  | :-: 
01 | 2012 | DM    | ECCV    | Depth matters: Influence of depth cues on visual saliency        | [Paper](https://link.springer.com/content/pdf/10.1007/978-3-642-33709-3_8.pdf)/Project 
02 | 2012 | RCM   | ICCSE  | Depth combined saliency detection based on region contrast model | [Paper](https://ieeexplore.ieee.org/document/6295184)/Project 
03 | 2013 | LS    | BMVC   | An In Depth View of Saliency                                     | [Paper](http://www.cs.utah.edu/~thermans/papers/ciptadi-bmvc2013.pdf)/Project 
04 | 2013 | RC    | BMVC   | Depth really Matters: Improving Visual Salient Region Detection with Depth | [Paper](http://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/ConferencePapers/2013/cv_deepth-really.pdf)/Project 
05 | 2013 | SOS   | Neurocomputing | Depth really Matters: Improving Visual Salient Region Detection with Depth | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231213002981)/Project 
06 | 2014 | SRDS  | ICDSP          | Salient region detection for stereoscopic images | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6900706)/Project 
07 | 2014 | LHM   | ECCV           | RGBD Salient Object Detection: A Benchmark and Algorithms | [Paper](http://dpfan.net/wp-content/uploads/NLPR_dataset_ECCV14.pdf)/[Project](https://sites.google.com/site/rgbdsaliency/code)
08 | 2014 | DESM  | ICIMCS         | Depth Enhanced Saliency Detection Method | [Paper](http://dpfan.net/wp-content/uploads/DES_dataset_ICIMCS14.pdf)/Project
09 | 2014 | ACSD  | ICIP           | Depth saliency based on anisotropic center-surround difference | [Paper](https://projet.liris.cnrs.fr/imagine/pub/proceedings/ICIP-2014/Papers/1569913831.pdf)/[Project](https://github.com/HzFu/DES_code)
10 | 2015 | GP    | CVPRW          | Exploiting global priors for RGB-D saliency detection | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_workshops_2015/W14/papers/Ren_Exploiting_Global_Priors_2015_CVPR_paper.pdf)/[Project](https://github.com/JianqiangRen/Global_Priors_RGBD_Saliency_Detection)
11 | 2015 | SFP   | ICIMCS         | Salient object detection in RGB-D image based on saliency fusion and propagation | [Paper](https://dl.acm.org/doi/10.1145/2808492.2808551)/Project
12 | 2015 | DIC   | TVC            | Depth incorporating with color improves salient object detection | [Paper](https://link.springer.com/article/10.1007/s00371-014-1059-6)/Project
13 | 2015 | SRD   | ICRA           | Salient Regions Detection for Indoor Robots using RGB-D Data | [Paper](http://www.cogsys.cs.uni-tuebingen.de/publikationen/2015/Jiang_ICRA15.pdf)/Project
14 | 2015 | MGMR  | ICIP           | RGB-D saliency detection via mutual guided manifold ranking | [Paper](https://ieeexplore.ieee.org/document/7350882)/Project
15 | 2015 | SF    | CAC            | Selective features for RGB-D saliency | [Paper](https://ieeexplore.ieee.org/document/7382554)/Project
16 | 2016 | PRC   | Access         | Improving RGBD Saliency Detection Using Progressive Region Classification and Saliency Fusion| [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7762806)/Project






------

## Light Field SOD Models:  <a id="LFmodels" class="anchor" href="#LFmodels" aria-hidden="true"><span class="octicon octicon-link"></span></a>  



------

## RGB-D SOD Datasets:  <a id="datasets" class="anchor" href="#datasets" aria-hidden="true"><span class="octicon octicon-link"></span></a>  




------

## Evaluation:  <a id="evaluation" class="anchor" href="#evaluation" aria-hidden="true"><span class="octicon octicon-link"></span></a>  

 
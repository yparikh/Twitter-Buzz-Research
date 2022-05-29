# Twitter-Buzz-Research
## About

https://ieeexplore.ieee.org/document/8993082

This paper investigates six machine-learning models to determine which algorithm would effectively predict buzz on Twitter. Different classifiers are applied such as Stochastic Gradient Descent, Support Vector Machines, Logistic Regression, Deep Neural Networks, Random Forests and Extra Trees on a Twitter dataset. This dataset contains features with users and author engagement over a certain period. After tests conducted on all the algorithms, we concluded that Extra Trees model outperforms the other models.

## Dependencies
* [scikit-learn](http://scikit-learn.org/stable/)
* [numpy](http://www.numpy.org/)
* pandas
* seaborn
* Matplotlib.pyplot

## Installation & Usage

 Open the terminal:
 ```
 $ cd \<required-path>
 $ git clone https://github.com/yparikh/Twitter-Buzz-Research.git
 $ jupyter notebook
 ```
 - Once Jupyter Notebook is running, go to Twitter-Buzz-Research Directory
 - Open Twitter-Research.ipynb & Run 

## Heatmaps

<img src="/Readme/Heatmap_All.png" align="top"
width="200" hspace="10" vspace="10">
<img src="/Readme/Heatmap_SGD.png" align="top"
width="200" hspace="10" vspace="10">
<img src="/Readme/Heatmap_RandomForest.png" align="top"
width="200" hspace="10" vspace="10">
<img src="/Readme/Heatmap_ExtaTrees.png" align="top"
width="200" hspace="10" vspace="10">
<img src="/Readme/Heatmap_LR.png" align="top"
width="200" hspace="10" vspace="10">

## ROC Graphs

<img src="/Readme/ROC_SGD.png" align="top"
width="200" hspace="10" vspace="10">
<img src="/Readme/ROC_RandomForest.png" align="top"
width="200" hspace="10" vspace="10">
<img src="/Readme/ROC_ExtraTrees.png" align="top"
width="200" hspace="10" vspace="10">
<img src="/Readme/ROC_LR.png" align="top"
width="200" hspace="10" vspace="10">

 
# Citation
If you use this software in academic research, please, cite it using the following BibTeX:
```latex
@misc{YashParikh2019,
author = {Yash Parikh, Eman Abdelfattah},
title = {Comparison of Machine Learning Models to Predict Twitter Buzz},
year = {2019},
publisher = {IEEE},
journal = {2019 IEEE 10th Annual Ubiquitous Computing, Electronics & Mobile Communication Conference (UEMCON)},
howpublished = {\url{https://ieeexplore.ieee.org/document/8993082}},
}
```

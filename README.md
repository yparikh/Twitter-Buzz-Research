# Twitter-Buzz-Research
## About

[Link to the Paper](https://ieeexplore.ieee.org/document/8993082)

This paper investigates six machine-learning models to determine which algorithm would effectively predict buzz on Twitter. Different classifiers are applied such as Stochastic Gradient Descent, Support Vector Machines, Logistic Regression, Deep Neural Networks, Random Forests and Extra Trees on a Twitter dataset. After tests conducted on all the algorithms, we concluded that Extra Trees model outperforms the other models.

## Dataset

[Link to the Dataset](https://archive.ics.uci.edu/ml/datasets/Buzz+in+social+media+#)

The dataset used in this research is the Twitter Absolute Dataset provided by Francois et. al. The dataset includes 140,707 instances with 77 attributes. The abbreviations, supplied by the authors, are translated from French and may differ from the feature name. These attributes are divided into 11 primary features which will be used for the models. These primary features utilize various measurements for user and author engagements such as Number of Created Discussions, Attention Level, Author Interactions, Average Discussions Length, etc.

## Dependencies
* [scikit-learn](http://scikit-learn.org/stable/)
* [numpy](http://www.numpy.org/)
* [pandas](https://pandas.pydata.org/) 
* [seaborn](https://seaborn.pydata.org/)
* [Matplotlib.pyplot](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.html)

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

The heat maps presented below display the precision score (correct positive predictions), the recall score (correct positive predictions out of all positive cases), and the F1 score (Balance of both precision and recall scores). 

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

ROC (Reciever Operating Characteristic) Graphs are tools used to predict probability of a binary outcome. It has a True Positive Rate on the y-axis and a False Positive Rate on the x-axis. Utilizing this graph demonstrates how the model performs at predicting the correct positive class. 

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

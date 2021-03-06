---
title       : Other prediction algorithms
subtitle    : 
author      : Jeffrey Leek, Assistant Professor of Biostatistics 
job         : Johns Hopkins Bloomberg School of Public Health
logo        : bloomberg_shield.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow   # 
url:
  lib: ../../libraries
  assets: ../../assets
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---





## There are a ton of prediction algorithms 

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/lotsamodels.png height=450>

[http://caret.r-forge.r-project.org/modelList.html](http://caret.r-forge.r-project.org/modelList.html)

---

## Don't forget this

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/illusion.png height=100>

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/illusiontable.png height=300>

[http://arxiv.org/pdf/math/0606441.pdf](http://arxiv.org/pdf/math/0606441.pdf)


---

## Support vector machines

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/svm.png height=450>

[http://en.wikipedia.org/wiki/Support_vector_machine](http://en.wikipedia.org/wiki/Support_vector_machine)

---

## Naive Bayes

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/naivebayes1.png height=75>

</br></br>

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/naivebayes2.png height=225>

[http://en.wikipedia.org/wiki/Naive_Bayes_classifier](http://en.wikipedia.org/wiki/Naive_Bayes_classifier)

_(Used often for document classification, spam filtering,...)_

---

## Neural networks

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/neuralnet.jpg height=450>

[http://www.learnartificialneuralnetworks.com/images/bneuronmodel.jpg](http://www.learnartificialneuralnetworks.com/images/bneuronmodel.jpg)

_(The basis for "deep learning" among other things)_


---

## Bias variance tradeoff

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/biasvariance.png height=450>

[http://www.willamette.edu/~gorr/classes/cs449/overfitting.html](http://www.willamette.edu/~gorr/classes/cs449/overfitting.html)


---

## Lasso

Linear regression minimizes: 

$$ \sum_{i=1}^n \left(Y_i - \sum_{k=1}^K \beta_k X_{ik}\right)^2$$

Lasso minimizes

<center>
$\sum_{i=1}^n \left(Y_i - \sum_{k=1}^K \beta_k X_{ik}\right)^2$ where $\sum_{k=1}^K |\beta_k| < t$
</center>


---

## Makes some coefficients zero

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/lasso.png height=450>

[http://statweb.stanford.edu/~tibs/lasso.html](http://statweb.stanford.edu/~tibs/lasso.html)


---

## Nearest neighbors

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/knn.png height=450>

[http://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm](http://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)


---

## Notes and further resources

* [Introduction to statistical learning](http://www-bcf.usc.edu/~gareth/ISL/)
* [Elements of Statistical Learning](http://www-stat.stanford.edu/~tibs/ElemStatLearn/)
* Also check out [Machine Learning on Coursera](https://www.coursera.org/course/ml)



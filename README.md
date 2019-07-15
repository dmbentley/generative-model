# generative-model

In this notebook, a machine learning model is constructed that can classify a series of wine bottles to one of three wineries of origin. The most sophisticated model that is contructed in these notebooks can correctly classify 98% of wine bottles. The dataset that is used comes from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml) and contains 13 numerical indicators for 178 wine bottles. The numerical indicators include the alcohol content and magnesium content, as two examples, for each of the 178 wine bottles.

The machine learning model that is chosen is a *Gaussian generative model*. This type of model fits a Gaussian distribution to each of the three wineries in an attempt to form a profile of each of them. When an unknown wine bottle needs to be classified, the generative model considers a Bayesian approach that weighs up the answers to:

* Which of the three Gaussian distributions for the wineries accommodates this unknown wine bottle the best?
* Of the previously seen wine bottles, which winery was the most frequently occurring? 

This repository contains two notebooks:

* [1-univariate-generative-model.ipynb](1-univariate-generative-model.ipynb)
* [2-multivariate-generative-model.ipynb](2-multivariate-generative-model.ipynb)


![Alt text](./images/alcohol-content-histogram.png?raw=true "Title")

![Alt text](./images/alcohol-density.png?raw=true "Title")

![Alt text](./images/accuracy-scores.png?raw=true "Title")

![Alt text](./images/flavanoids-density.png?raw=true "Title")

![Alt text](./images/alcalinity-of-ash-density.png?raw=true "Title")

![](./images/ash-vs-alcohol.png)

![](./images/winery-1.png)

![](./images/winery-2.png)

![](./images/winery-3.png)

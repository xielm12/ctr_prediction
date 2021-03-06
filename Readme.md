# Click Through Rate Prediction

### Computational Advertising Related Terminology
* [CTR, CPC, CPA, CR](http://www.regalix.com/by_regalix/insights/blogs/four-cs-ppc-ctr-cpc-cpa-cr/)
* How is the sponsored ad rank decided? (TBD)
* How to predict CTR? (TBD)
* HOw to decide price according to predicted CTR? (TBD)


### Usual Methodology
* Kaggle
  * [Avazu Competition](https://www.kaggle.com/c/avazu-ctr-prediction)
  * [Outbrain Competition](https://www.kaggle.com/c/outbrain-click-prediction)
     * [pyspark for data processing](https://github.com/gabrielspmoreira/static_resources/blob/gh-pages/Kaggle-Outbrain-PageViews_EventsAnalytics.ipynb)
* Kaggle methodology summary
  * [link 1](http://mlwave.com/predicting-click-through-rates-with-online-machine-learning/)
  * [link 2](./ref/ClickThroughRate2015.pdf)
  * [winning solution](https://github.com/guestwalk/kaggle-avazu) 
* deep learning in CTR prediction
    * Prof Zhang's [work](https://github.com/wnzhang/deep-ctr)
    * [Text Regression](https://blog.deepomatic.com/text-regression-for-click-through-rate-prediction-using-convnet-9f43971e12c#.9yarc7hbb)
    * [Deep CTR Prediction in Display Advertising](./ref/Deep_CTR.pdf)
* hands on
  * [logistic regression](https://turi.com/learn/gallery/notebooks/click_through_rate_prediction_intro.html)
  * [Avazu competition](https://github.com/owenzhang/kaggle-avazu)
* class
  * Stanford [Computational Advertising](http://web.stanford.edu/class/msande239/)
  * CMU

### Methodology for rare/new ads
* [multi-armed bandit](http://yelp.github.io/MOE/bandit.html)
* [Bayesian](http://www.marketingdistillery.com/2014/09/24/bayesian-modeling-of-click-through-rate-for-small-data/)

### Model performance matrix
Classification error measurement
* AUC
* Somer’s D 
* Logloss
* MSE
* recall
* precision
Regression error measurement
* RMSE 
Variance-based error and Bias-based error 
* [Understanding Bias-Variance trade-off](http://scott.fortmann-roe.com/docs/BiasVariance.html) 
* [wiki](https://en.wikipedia.org/wiki/Bias%E2%80%93variance_tradeoff) 

### Design (A/B) Tests
* [different design and test scheme](./) (TBD) 

### Pandas
* [Official Tutorial](http://pandas.pydata.org/pandas-docs/stable/tutorials.html)
* [Time Series Analysis with Pandas](https://www.analyticsvidhya.com/blog/2016/02/time-series-forecasting-codes-python/)
* [sklearn tutorial(NLP)](http://scikit-learn.org/stable/tutorial/) 

### Python visualization
* [simple CTR analysis](https://github.com/jfraj/click-through)
* [visualization tool](./ref/EECS-2016-64.pdf)

### Python useful packages
* Collections - [Counter class](http://pymbook.readthedocs.io/en/latest/collections.html) 
* [re - python regular expressions](https://developers.google.com/edu/python/regular-expressions) 

### Python Cheatsheet
* [common methods and data structures](https://github.com/kishkaru/Programming-Cheatsheets/blob/master/python%20cheatsheet.py) 

### Python Algorithm
https://github.com/bmanturner/CS303-python

### Spark
* [Application Frame 1](./ref/Spark在计算广告领域的应用实践.pdf)

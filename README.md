# A Machine Learning Framework to predict the customer churn rate


This project demonstrates applying a 3 step general purpose framework to solve problems with machine learning. The purpose of the framework is to provide a scaffolding for rapidly developing machine learning solutions across industries and datasets. 

The end outcome is the business decisioning to address the customer churn with a reduction in the cost involving in the marketing campaign and give insight on the areas the business has to focus. 

# Framework Steps: 

1. __Prediction Engineering__
  * State business needs
  * Translate business requirment into machine learning task by specifying problem parameters
  * Develop set of labels along with cut off times for supervised machine learning modelss. 
2. __Feature Engineering__
  * Create features - predictor variables - out of raw data
  * Use cutoff times to make valid features for each label
  * Apply automated feature engineering to automatically make hundreds of relevant, valid features
3. __Modelling__
  * Train a machine learning model to predict labels from freatures
  * Use a pre-built solution with common libraries
  * Optimize model in line with business objectives
  
  
  # Details about the repository
  
  The notebooks in this repository document a step by step application of the framework to a real world use case and dataset prediction. The data set is extracted from the KKbox, Asia's largest music streaming service, and can be downloaded [here](https://www.kaggle.com/c/kkbox-churn-prediction-challenge/data). 
  
Within the overall scaffolding, several standard data science toolboxes are used to solve the problem:

* [Featuretools](https://docs.featuretools.com/#): automated feature engineering
* [Pandas](https://pandas.pydata.org): data munging and engineering
* [Scikit-Learn](http://scikit-learn.org/stable/documentation.html): standard machine learning algorithms
* [Apache Spark](https://spark.apache.org/documentation.html) with [PySpark](https://spark.apache.org/docs/latest/api/python/index.html): Running comptutations in parallel
* [TPOT (Tree-based Pipeline Optimization Tool)](https://github.com/EpistasisLab/tpot): model selection optimization using genetic algorithms



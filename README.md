## Credit card approval prediction algorithm

The purpose of this is to try out different ML classification algorithms to determine if a credit card application should be approved or recjected. The implementations are: **Logistic Regression**, **Random Forest**, and **XGBoost**. 

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

---

### Requirements

`python3` `jupyter notebook` 

### Dependencies

`pandas` `numpy` `Scikit-learn` `XGBoost` `joblib`

---

### About

There are some traditional credit card approval systems that are inflexible and the features are taken into account individually and not in a combined way. So I came across this dataset with information from the 80's and tried to implement 3 ML models to see if it can be predicted accurately.

### Conclusion

Althouh the dataset is very small and the data is anonymized the implementations worked out very accurately how to determine whether a credit card should be approved or not. Between the three implementations, the one which worked best was the Random Forest Classificator, although probably with a bigger sample an XGBoost may be better. Both of these outpreformed the Logistic Regression which was the original solution proposed for the problem.

---

The dataset was published by [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/credit+approval) and was submitted by **quinlan '@' cs.su.oz.au**.

This notebook is based on [Sayak Paul's Datacamp Project](https://www.datacamp.com/projects/558).

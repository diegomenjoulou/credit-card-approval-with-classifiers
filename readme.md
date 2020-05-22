## Credit card approval prediction algorithm

The purpose of this is non comercial, just for trying out ML algorithms.

For the past 10 years I worked at a Bank where one of my duties was credit analysis and approval. Back in 2010 we did them manually on an excel spreadsheet and with the documentation printed out. In the last few years we implemented a software based on rules that discarded or approved the credit application, but it always seemed to me that it was an inflexible model, and the features were taken into account individually and not in a combined way. So I came across this dataset and tried to implement a ML model to see if it can be predicted accurately. 

Although te column names are available, the data was anonymized to protect the privacy.

The implementations are: **Logistic Regression**, **Random Forest**, and **XGBoost**. 

The dataset was published by [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/credit+approval) and was submitted by **quinlan '@' cs.su.oz.au**.

This notebook is based on [Sayak Paul's Datacamp Project](https://www.datacamp.com/projects/558).
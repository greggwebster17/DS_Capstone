# DS_Capstone
PySpark Capstone project as part of the Udacity Data Science Nanodegree 

Summary of Results and Analysis - using user data from a music streaming service, features are created and a Logistic regression model fitted in order to predict churn. The final model does not perform too well and further work is required to improve the preditive ability of the model.

Installations - no additional libraries are needed to be installed in order for the project code to run.

Dependencies - there a few packages used that the code needs. These are 
from pyspark.sql import SparkSession
from pyspark.ml import Pipeline
from pyspark.ml.classification import LogisticRegression
from pyspark.ml.evaluation import BinaryClassificationEvaluator, MulticlassClassificationEvaluator
from pyspark.ml.tuning import CrossValidator, ParamGridBuilder
import matplotlib.pyplot as plt
import pandas as pd

Project Motivation - in order to predict churn (cancellations) of users for a music streaming service. Project uses PySpark capabilities. Involves creating features, then fitting a Logistic Regression. The best model is chosen using Gini and AUC measures. 

File Descriptions - There is one Python notebook with the relevant code to conduct the data preparation, analysis and model fitting. 

How to Interact with your project - Python notebook has the code and results. A write up of the results can also be found here https://greggwebster17.medium.com/music-app-churn-prediction-using-logistic-regression-e0ac9f374f36

The link to the GitHub repository is https://github.com/greggwebster17/DS_Capstone.

Licensing, Authors, Acknowledgements, etc.- Credit to Udacity to supplying the data. There are no restrictions to the use of the code supplied here.

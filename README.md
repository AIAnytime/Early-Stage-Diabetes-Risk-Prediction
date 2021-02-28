# Early Stage Diabetes Risk Prediction

**End to End Machine Learning pipeline for early stage diabetes risk prediction model using several supervised machine learning algorithms like Decision Tree, Logistic Regression, and KNN**.


**Notebook contains all the steps of a Data Science Life Cycle that looks like:**

<a href="https://ibb.co/jvmyGLW"><img src="https://i.ibb.co/SXbt0Kd/tdsp-lifecycle2.png" alt="tdsp-lifecycle2" border="0"></a>

## Data 👇

**The data is available at UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.**

## Steps performed in the Notebook: 👇

+ **Exploratory Data Analysis** : Basic Data Analysis and Visualization with Preprocessing.
+ **Feature Engineering** : Finding the best features using several technqiues like SelectKBest, Recursive Elimination, and Ranking Mechanism.  I also did some Outlier removal steps.
+ **Machine Learning Models** : I have used Logistic Regression, Decision Tree Classifier, and KNN to find the best model among them using several evaluation techniques.
+ **Evaluation and Interpretation**: Evaluation of models using Confusion Matrix, Classification Report, etc.
+ **Interpretation**: Used Lime (amazing for Iterpretation of models), Eli5, etc.

**Open the Notebook in the Jupyter Notebook, Jupyter Lab, or Google Colab's Notebook to execute all the steps and re-train the models for your purpose.**

## Evaluation and Interpretation👇

All the models have performed well but **Decision Tree** leads to a better accuracy and shows promising result in evaluation steps as well. **The Decision Tree Classifier has given 94% accuracy ahead of Logistic Regression (90%) and KNN (88%). But in Decision Tree, it seems to overfit and "Age" has strong correlation with Target. I have used Logistic Regression ahead of Decision Tree for this task.**

<a href="https://ibb.co/8MmFXqN"><img src="https://i.ibb.co/LS04vmY/decision-tree-plot.png" alt="decision-tree-plot" border="0"></a>

See the **Confusion Matrix and Classification Report** below:
<a href="https://imgbb.com/"><img src="https://i.ibb.co/rv7v2KJ/download.png" alt="download" border="0"></a>

<a href="https://ibb.co/qg53CDM"><img src="https://i.ibb.co/vdY6hcx/Early-Stage-Diabetes-Risk-Prediction-early-stage-diabetes-prediction-ipynb-at-main-sonucr7-Early-Sta.png" alt="Early-Stage-Diabetes-Risk-Prediction-early-stage-diabetes-prediction-ipynb-at-main-sonucr7-Early-Sta" border="0"></a>



## Deployment 👇

**I built an awesome application, find it here: http://predict-smart.herokuapp.com**

You can use saved models which are in the pickel files to build any kind of application i.e. Web, Serverless Rest APIs, Mobile Apps, etc. Connect me for more on it...............................


## Find me here 👇

If you have any feedback, please connect:
+ sonu1000raw@gmail.com
+ LinkedIn: https://www.linkedin.com/in/sonucr7/


Thanks 😇












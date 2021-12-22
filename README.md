# Turkish-Divorce-Survey
# UVA MSDS Bayesian Machine Learning Project
## Ryan Pindale & Anna Landi

Project Name: Bayes Semester Project: Turkish Divorce Prediction

Authors: Anna Landi and Ryan Pindale

Project Description and Goals:

• We applied a Bayesian Logistic Regression and built a Variational Autoencoder (VAE) to
predict divorce among Turkish couples.

• We implemented these Bayesian methods to analyze the "Divorce Predictors" data set
from the UCI Machine Learning Repository.

• Our goals are two-fold: 
1. to know the probability of correct classification of couples as
being either divorced or married, and 
2. to find the likelihood of the importance of the
various predictors as they relate to the outcome.

- Yöntem et al., (2019) originally conducted a research study to find divorce prediction
through correlation based feature selection and artificial neural networks among Turkish couples (we are using their data).

- The participants completed the Divorce Predictors Scale (DPS), which consists of 54 survey questions asked on a 0 to 4 Likert scale (0 = strongly agree; 4 = strongly disagree).
- 
- The survey questions are modeled after Gottman’s Couples Therapy - divorce prediction can be reduced to four major tenets: criticism, contempt, stonewalling, and defensiveness.
- 
Data Set Source: divorce.xlsx (https://archive.ics.uci.edu/ml/datasets/Divorce+Predictors+data+set)

Data Overview:
• Data are cleaned and standardized with no missing values.
• About half of the 170 couples reported being divorced.
• Of the married couples, roughly 43% married for love, while the remaining couples had
arranged marriages.
• Researchers included only happily married couples (i.e. those who had no intention of
getting divorced) in their study.
• Researchers claimed to have discovered the six most important DPS survey questions
for divorce prediction - we explore these six features in detail.

Instructions: Run all lines of code in the order that they appear in the notebook (we wrote the code in jupyterlab Version 2.1.5).

Required Python Packages:
• import numpy as np
• import pandas as pd
• import pymc3 as pm
• import arviz as az
• import seaborn as sns
• import scipy.stats as stats
• import matplotlib.pyplot as plt
• import statistics
• from scipy.stats import norm
• az.style.use("arviz-darkgrid")

References:
• https://archive.ics.uci.edu/ml/datasets/Divorce+Predictors+data+set
• https://dergipark.org.tr/en/download/article-file/748448
• https://www.kaggle.com/alperenclk/for-beginner-divorce-prediction-whit-ann
• https://www.gottman.com/about/the-gottman-method/
• https://blog.keras.io/building-autoencoders-in-keras.html
• https://www.cdc.gov/nchs/data/dvs/national-marriage-divorce-rates-00-19.pdf
• Yöntem, M , Adem, K , İlhan, T , Kılıçarslan, S. (2019). DIVORCE PREDICTION USING
CORRELATION BASED FEATURE SELECTION AND ARTIFICIAL NEURAL NETWORKS. Nevşehir Hacı Bektaş Veli Üniversitesi SBE Dergisi, 9 (1), 259-273. Retrieved from https://dergipark.org.tr/en/pub/nevsosbilen/issue/46568/549416.


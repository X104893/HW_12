Project Title: Credit Risk Classification

Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. I use various techniques to train and evaluate models with imbalanced classes. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Technologies The code is written in Py 3.0. We used Colab to run the program

Installation Guide

import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced
from sklearn.linear_model import LogisticRegression
from imblearn.over_sampling import RandomOverSampler
import warnings
warnings.filterwarnings('ignore')
from sklearn.model_selection import train_test_split

I Split Data into Training and Testing Sets

Created a Logistic Regression Model with the Original Data

Predicted a Logistic Regression Model with Resampled Training Data

Wrote a Credit Risk Analysis Report

 Contributors In addtion to me the GW Bootcamp TA, LA, and tutors help me create this project

License The Source code is for educational purposes only and should not be used to make any professional recomendations. Feel free to use for any educational needs
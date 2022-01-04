# Credit Risk Prediction

How to run my program?
I have used Jupyter Notebooks for implementing this assignment. Thus the output folder is a “ipynb” file.

Steps to Run:
1. Open Jupyter Notebooks
2. Click on this file to open
3. Go to Cells in the options above and select “Run All”

I have used the following liabraries:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.preprocessing import OneHotEncoder
from sklearn.compose import make_column_transformer
from sklearn.preprocessing import StandardScaler
from xgboost import XGBClassifier
import xgboost as xgb
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn import metrics
from sklearn.pipeline import make_pipeline
from sklearn.model_selection import cross_val_score
from sklearn.ensemble import RandomForestClassifier
from sklearn.datasets import make_classification
from sklearn.model_selection import train_test_split
from imblearn.under_sampling import NearMiss
from collections import Counter
from imblearn.over_sampling import RandomOverSampler
from imblearn.combine import SMOTETomek

Note: The program should run perfectly fine having installed all the libraries of python installed in the system.

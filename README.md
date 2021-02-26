# CA_03_Assignment

## Overview 
This assignment was aimed to learn more about the Decision Tree algorithm. We used a dataset that was obtained from the Census Bureau and it shows the salaries of people along with 7 variables: Age, Capital Gain/Loss, Education, Hours Per Week, Marriage Status, Occupation and Race/Sex. 
## Operating Instructions 
To run this code properly this ipynb file needs to be uploaded into Google Colab. The census data file also needs to be uploaded into Colab. 
## Package Requirements
import numpy as np
import pandas as pd 
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier
from sklearn.preprocessing import LabelEncoder
from six import StringIO  
from IPython.display import Image  
from sklearn.tree import export_graphviz
import pydotplus
from sklearn import metrics
from sklearn.metrics import confusion_matrix
from sklearn.metrics import accuracy_score, recall_score, precision_score, f1_score, plot_roc_curve, roc_auc_score, roc_curve, auc
## Contact Information 
Melyssa Moore
## Credits and Acknowledgements 
My professor created the template for this assignment and provided the data file.  
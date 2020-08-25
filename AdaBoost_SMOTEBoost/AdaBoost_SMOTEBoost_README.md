# IEEE-CIS FRAUD DETECTION
## AdaBoost + SMOTEBoost Implementation

This is one attempt in tackling the IEEE-CIS Fraud Detection problem using AdaBoost and SMOTEBoost algorithms. 

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine.

### Prerequisites

Sklearn's AdaBoostClassifier library to implement the algorithm
```
pip install sklearn
```
```
from sklearn.ensemble import AdaBoostClassifier
```
Sklearn's train_test_split library to perform splitting on train dataset
```
from sklearn.model_selection import train_test_split
```
Sklearn's confusion_matrix library to help plot our model's confusion matrix
```
from sklearn.metrics import confusion_matrix
```
Sklearn's label encoder preprocessing library to help us label encode the features
```
from sklearn import preprocessing
```
Standard libraries to import
```
pip install pandas
pip install numpy
pip install matplotlib
```
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

## Built With

* [Google Colab](https://colab.research.google.com) - The web framework used

## Authors

* **Stephanie Audrey Susanto** 
* **Gabriella Benedicta Christianti**


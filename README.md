# Data Analytics Tutorial with Pandas

This tutorials will process the E-Commerce Shipping dataset into data ready for modelling

## Prerequisites
1. Download the dataset from [ECommerce Shipping](https://www.kaggle.com/datasets/prachi13/customer-analytics/download?datasetVersionNumber=1)
2. Install the package for visualization:
   ```code
   import pandas as pd
   import numpy as np
   import matplotlib.pyplot as plt
   import seaborn as sns
   ``` 
3. Do EDA, data cleaning, data preprocessing and splitting data as usual

### Dataset Spliting
```code
x_train, x_test, y_train, y_test = train_test_split(
```
       
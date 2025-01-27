# Name: Muhammad Umar
# Roll Nob:057


# Project Overview

This README file provides an overview of the contents and purpose of the Jupyter Notebook titled 'Project.ipynb'.

### Code Example
```python
import pandas as pd
```

### Code Example
```python
import numpy as np
```

### Code Example
```python
df= pd.read_csv("fashion_products.csv")
```

### Code Example
```python
df.sample(5)
```

### Code Example
```python
df.shape
```

### Code Example
```python
df.sample
```

### Code Example
```python
df.describe()
```

### Code Example
```python
df.columns
```

### Code Example
```python
df.select_dtypes
```

## ***Data Cleaning***

### Code Example
```python
df.dropna()
```

### Code Example
```python
df.dropna(inplace=True)
```

### Code Example
```python
df.fillna(90,inplace=True)
```

### Code Example
```python
df.isnull()
```

## ***Data Processing***

### Code Example
```python
df.info
```

### Code Example
```python
df.describe(include="all").loc[["min","max"]]
```

### Code Example
```python
df["Category"].value_counts()
```

### Code Example
```python
df["Color"]
```

### Code Example
```python
a=df["Size"]
print(a)
```

## ***Data Aggregation***

### Code Example
```python
df["Brand"].value_counts().plot(kind='bar')
```

### Code Example
```python
df["Size"].value_counts().plot(kind="kde")
```

### Code Example
```python
df["Product Name"].max()
```

### Code Example
```python
df["Product Name"].min()
```

### Code Example
```python
df["Product ID"].mode()
```

### Code Example
```python
df["Color"].value_counts().plot(kind="pie")
```

### Code Example
```python
df["Product ID"].sum()
```

### Code Example
```python
df["Category"].mode()
```

### Code Example
```python
df["Product ID"].sum()
```

### Code Example
```python
df["User ID"].mode()
```

### Code Example
```python
df["Product ID"].sum()
```

### Code Example
```python
df.describe(include="all").iloc[[0,10]]
```

### Code Example
```python
df["Rating"].median()
```

### Code Example
```python
df.groupby("Color").describe()
```

### Code Example
```python
df.fillna(method="bfill")
```

## Instructions

To use this project, follow the steps below:

1. Install the required dependencies.
2. Run the notebook cells in sequence.

## Dependencies

This project may require the following Python libraries:
- numpy
- pandas
- matplotlib


# Roches Point Weather

C:\Users\phumi\Downloads\Roches Point Weather\hly1075.csv

## Table of Contents


## About the Project

## How to get started.

To  explore this dataset you need to download 
python, which can be installed through [anaconda]
(https://www.anaconda.com/download), and a 
notebook editor such as Jupiter notebooks, which 
can be found in [Visual Studio Code](https://code.
visualstudio.com/).

## Analysis

 Imported Python libraries to anlyse the data.

```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns
import sys
```

- Pandas - for data manipulation and analysis. I
allows us to investigate CSV files, amongst othe
features.

- Matplotlib - for data visualisation and 
graphical plotting.

- Seaborn - complements matplotlib and offers a 
simpler way to plot charts.

- Numpy - to perform  wide variety of 
mathematical operations on arrays.

- Sys - provides various functions and variables
that are used to manipulate Python runtime 
environment. We use stdout module to send the 
codes' output onto the 'summary text file'.

## Loading Data

 **pd.read_csv** reads in the dataset and store 
it as a Dataframe object in the variable..

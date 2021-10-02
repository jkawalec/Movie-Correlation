![Logo](https://static2.srcdn.com/wordpress/wp-content/uploads/2018/12/Highest-Grossing-Films-of-2018-Header-V3.jpg)
    
# Movie Correlation

In this project, We are going to look at what factors correlated most with the gross Revenue


## Authors

- [@jkawalec](https://www.github.com/jkawalec)

  
## Installation

Used Jupyter Notebook for this project

Download Anaconda: https://www.anaconda.com/products/individual#Downloads

Download Jupyter Project: https://github.com/jkawalec/Movie-Correlation/blob/main/Movie%20Correlation.ipynb

Download Movie Dataset: https://www.kaggle.com/danielgrijalvas/movies

Import the libriaries needed

```bash
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib
import matplotlib.pyplot as plt
plt.style.use('ggplot')
from matplotlib.pyplot import figure
```
    
## Usage

Use this project to explore different correlation impact on Gross Revenue for Movies. Use this project to first show your data cleaning techniques. Then, take a deeper dive on which variables have a high correlation with Gross Revenue for Movies

```javascript
df['budget'] = df['budget'].astype('Int64')

df['gross'] = df['gross'].astype('Int64')
```



```javascript
plt.scatter(x=df['budget'],y=df['gross'])
plt.title('Budget Vs Gross Earnings')
plt.xlabel('Budget')
plt.ylabel('Gross')
plt.show()
```

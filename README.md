# Sales Analysis using Machine learning Algorithm leinear Regression


## Dataset Overview
This dataset contains four columns: three feature columns representing TV, Radio, and Newspaper advertising spends, and one target column, Sales. The goal is to identify the relationship between the independent variables (advertising spends) and the dependent variable (Sales) to determine which medium has the strongest influence on sales.

## Key variabale and description

- TV: Advertising budget spent on TV.
- Radio: Advertising budget spent on Radio.
- Newspaper: Advertising budget spent on Newspapers
- Sales: The number of units sold (target variable), which we aim to predict based on the advertising budgets











## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

## Installation

This notebook runs on Google Colab. To use the necessary libraries, simply import them at the beginning of your notebook:

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression

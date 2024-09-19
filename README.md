
# Machine Learning with Coffe Shop Sales           
  
# Projenin Amacı
Projemiz kafenin satış mikarı ve toplam getirisinin çeşitli değişkenleri baz alarak analizini yapmak içşin yapılmıştır .

# Veri Seti
Veri setimiz toplamda 149116 satır ve 17 sütundan oluşuyor . 


**Sütun isimleri** :

-Transaction ID: Numerical (Unique identifier for each transaction)

-Transaction Date: Date (Date of the transaction)

-Transaction Time: Time (Time of the transaction)

-Store Number: Numerical (Identifier for the store location)

-Store Location: Text (Location of the store)

-Unit Number: Numerical (Unit number within the store)Product 

-Category: Text (Category of the product)

-Product Type: Text (Type of product within the category)

-Product Name: Text (Specific name of the product)

-Price: Numerical (Price of the product)

-Month: Numerical (Month of the transaction)

-Day: Numerical (Day of the month)

-Weekday: Text (Day of the week)

-Hour: Numerical (Hour of the day)



# Değişkenler

import random

import time

from sklearn.model_selection import train_test_split

import sklearn.preprocessing as LabelEndcoder 

import sklearn.preprocessing as PolynomialFeatures

import seaborn as sns

from xgboost import XGBRegressor

from sklearn import linear_model , tree

from sklearn.metrics import mean_squared_error , r2_score

from datetime import datetime 

from statsmodels.stats.outliers_influence import variance_inflation_factor

from joblib import Parallel , delayed

from sklearn.pipeline import Pipeline

mport plotly.express as px

import plotly.graph_objects as go

import plotly.figure_factory as ff

from plotly.subplots import make_subplots



# Model Seçimi
En iyi perfomansaı veren algoritma seçilir , hiperparametetre optimize edilir . 
Bu projede en iyi performansı veren modelin 








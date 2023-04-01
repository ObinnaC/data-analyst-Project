# final-oc47

# Lets dive into it.
Goal of the project:
Often times, we have power hungry country measuring their strenght with their ability to develop nuclear weapon, the amount of Olympia Gold metals won, Space Exploration, military numbers, currency exchange rates . It is time to see which country are actually ahead or should I say, 
which countries has broken through the built in social construct that deprive others of their unalienable rights. 

This Project looks at ...

 # Datasets source 
 1. https://data.oecd.org/inequality/women-in-politics.htm
 2. https://statusofwomendata.org/explore-the-data/download-the-data/
 3. https://data.worldbank.org/indicator/SG.GEN.PARL.ZS?most_recent_year_desc=true
 4. https://www.openicpsr.org/openicpsr/project/100918/version/V1/view

 # code source
 1. machine learning with python video 14 Polynomial Regression https://www.youtube.com/watch?v=2wzxzHoW-sg
 2. Creating Geographic Maps with plotly express https://www.youtube.com/watch?v=Oht6cf-Acl0&list=WL&index=52&t=917s
 3. Analysis of Variance (ANOVA) | https://www.youtube.com/watch?v=AhZ-hllEVxs&list=WL&index=57&t=396s
 4. pycountry-convert https://pypi.org/project/pycountry-convert/
 5. stackoverflow for data cleaning errors 
 # Importing Libraries
 import pandas as pd
 import numpy as np 
 import seaborn as sb
 import matplotlib.pyplot as plt
 import plotly
 import plotly.express as px
 import pycountry_convert as pc
 import statsmodels.api as sm
 from statsmodels.formula.api import ols
 from statsmodels.stats.anova import anova_lm 
 from sklearn import metrics 
 from sklearn.preprocessing import PolynomialFeatures
 from sklearn.model_selection import train_test_split
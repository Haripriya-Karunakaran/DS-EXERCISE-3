# DS-EXERCISE-3

#                                                 UNIVARIATE ANALYSIS 

## AIM: 

To perform Univariate Analysis on the given data. 

## ALGORITHM: 

 Step 1: Read the given data.
 
 Step 2: Get information from the data. 
 
 Step 3: Perform the Univariate Analysis. 
 
 Step 4: Save the clean data to the file.
 
## CODE:

## SuperStore.csv

import pandas as pd

import numpy as np

import seaborn as sns

df = pd.read_csv("/content/SuperStore.csv")

df.isnull().sum()

df.info()

df.dtypes

df['Sales'].value_counts()

df.describe()

sns.boxplot(x='Sales',data=df)

sns.countplot(x='Postal Code',data=df)

sns.displot(df["Postal Code"])

sns.histplot(x='Postal Code',data=df)

import pandas as pd

import seaborn as sns

df = pd.read_csv("/content/SuperStore.csv")

df.skew()

## diabetes.csv

import pandas as pd

import seaborn as sns

df = pd.read_csv("/content/diabetes.csv")

df.info()

df.dtypes

df['Insulin'].value_counts()

df.describe()

sns.boxplot(x='Insulin',data=df)

sns.countplot(x='Glucose',data=df)

sns.displot(df["Insulin"])

sns.histplot(x='Glucose',data=df)

import pandas as pd

import seaborn as sns

df=pd.read_csv("/content/diabetes.csv")

df.skew()

## RESULT:

Univariate Analysis is performed on given data and save

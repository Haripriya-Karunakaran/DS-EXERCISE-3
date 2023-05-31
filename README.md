# EXERCISE-3  UNIVARIATE ANALYSIS 

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

## OUTPUT:

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/61c5bb25-6968-4834-99ba-73e5af8129cb)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/72c02478-ac7b-4c64-90f0-349ce5e419b7)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/b4f8ae9e-31b5-4e86-8c54-3d8e683129a6)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/fb2e7ee4-2d0b-4d03-9f4c-cc295cbfe87b)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/2186ca5e-0601-4371-9494-87f948e10732)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/2bc7ba87-8851-42f2-aef5-8d5a2a3a0a87)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/776a1907-3a4d-4998-8388-952fec9e08b4)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/24de8068-6678-4c09-a361-bf612423f76e)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/5fa83276-d178-446e-a35f-78bb22edb478)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/e8f85912-a589-457c-b1e4-96163ffe90db)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/2942e8ee-7466-4c06-b000-d2bd13c0ada8)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/16510522-7e92-49b8-b41b-f9e9ccd2f5c2)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/dfe6919a-89d8-4127-b141-b0674cd8b955)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/45ce0bae-d1ca-4d7b-b502-dcece7de6fdc)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/7ce226c4-fb99-45cf-b8ed-530d24e1400a)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/2a257646-7315-4f55-ba2d-1be59b470302)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/f268c719-b480-47f8-a8e8-11e69928a7f5)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/05959f12-79b2-4ace-b383-43e74cc89c13)

![image](https://github.com/Haripriya-Karunakaran/DS-EXERCISE-3/assets/126390051/a6603d4e-356f-4341-bd91-a03d0f68a991)

## RESULT:

Thus,Univariate Analysis has been performed on given data.

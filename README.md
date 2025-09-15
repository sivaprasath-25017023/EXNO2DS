# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
        ```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv('titanic_dataset.csv')
df

<img width="734" height="479" alt="image" src="https://github.com/user-attachments/assets/06b6a58f-fabc-48fe-9f48-c205654705ab" />
<img width="1104" height="403" alt="image" src="https://github.com/user-attachments/assets/d2c441df-d94b-4991-a28b-f990d24f59f0" />
<img width="818" height="619" alt="image" src="https://github.com/user-attachments/assets/2ffe0795-3315-4f4b-a7fa-f8aef494dcf7" />
<img width="487" height="96" alt="image" src="https://github.com/user-attachments/assets/7b36a781-31e8-4af9-91a6-3356d6910695" />
<img width="1412" height="755" alt="image" src="https://github.com/user-attachments/assets/b2d703c7-690b-41bd-a79e-414ee2c47911" />
<img width="700" height="663" alt="image" src="https://github.com/user-attachments/assets/3f3ee357-1fe5-46f0-8ade-89ad997cb970" />
<img width="1414" height="711" alt="image" src="https://github.com/user-attachments/assets/6010e82c-1b11-49ff-878d-dd88f1fe07b7" />
<img width="707" height="591" alt="image" src="https://github.com/user-attachments/assets/af09234e-8efc-4c04-b391-17692d71a515" />
<img width="877" height="635" alt="image" src="https://github.com/user-attachments/assets/74b8ada5-1d3c-4f3e-a3b9-486af9af6632" />
<img width="1408" height="687" alt="image" src="https://github.com/user-attachments/assets/772d817b-c80c-43ec-a94f-8d8f1d565c2f" />
<img width="1418" height="725" alt="image" src="https://github.com/user-attachments/assets/33519e78-7113-4d7b-9bf3-c995bab15fce" />
<img width="884" height="667" alt="image" src="https://github.com/user-attachments/assets/98628c5a-70a5-447c-b0bc-ee8637c7d698" />
<img width="936" height="629" alt="image" src="https://github.com/user-attachments/assets/98e35876-eccf-4370-a28c-39a934717afc" />
<img width="974" height="619" alt="image" src="https://github.com/user-attachments/assets/95937672-7e6d-4109-a287-d721591a6bd6" />
<img width="1397" height="688" alt="image" src="https://github.com/user-attachments/assets/85fde9da-ba74-48d7-88af-96de0f89a7dc" />
<img width="936" height="643" alt="image" src="https://github.com/user-attachments/assets/b4118214-2fce-4a52-910e-6fad19436268" />
```









# RESULT
            Hence the program to perform Exploratory Data Analysis on the given data set has been done successfully.

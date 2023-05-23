# Ex-09-Data-Visualization-

## AIM
To Perform Data Visualization on a complex dataset and save the data to a file. 

# Explanation
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# ALGORITHM
### STEP 1
Read the given Data
### STEP 2
Clean the Data Set using Data Cleaning Process
### STEP 3
Apply Feature generation and selection techniques to all the features of the data set
### STEP 4
Apply data visualization techniques to identify the patterns of the data.


# CODE
# Data Preprocessing

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

from google.colab import files

uploaded = files.upload()

df = pd.read_csv("tips.csv")

df

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/67c08542-7107-46ab-a077-4dd38d6b050a)

df.isnull().sum()

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/7c3d5f83-519a-4e9d-8c47-964f6b7ba51a)

# Handling Outliers
![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/696fd9a7-47d5-4829-b989-7fb65eeb3d28)

# Removing Outliers
![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/21d06dbc-b16b-4604-b319-4e3d7d370125)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/aa53cbc7-2092-4ba8-930e-e3f0a5a96937)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/298e1c4a-7bc7-45e0-8d70-3f3d97bdaec8)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/1064c5d1-c8f7-48aa-a3f6-4813b3bb20d8)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/669578e4-9622-4ef2-870b-67d2d13ab14f)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/cd25e647-53b9-4972-a6ef-26def3096c7b)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/127a4759-b406-4302-a736-19f725d78996)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/8dbfa6d5-356f-4f7c-8ab2-d12e9b3a6f51)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/08bfca6c-5424-4e0a-b192-1e7404cff4a8)

![image](https://github.com/Rajasree-321/Ex-09-Data-Visualization_1/assets/96918911/dfeac11a-8670-4861-9aa7-5c82f6f09a09)



# RESULT
Thus, the Data Visualization for the given dataset had been executed successfully.

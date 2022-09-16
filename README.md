# Prevalence-of-brain-stroke

## Introduction
A stroke is a medical condition in which there is brain's cells death due to poor or lack of blood flow to the brain. There are two main types of stroke:  hemorrhagic, due to bleeding and ischemic, due to lack of blood flow, causing brain to stop functioning properly. Signs and symptoms of a stroke may include an inability to move or feel on one side of the body,loss of vision to one side,problems understanding or speaking and dizziness. If symptoms last less than one or two hours, the stroke is a transient ischemic attack (TIA), also called a mini-stroke. The symptoms of a stroke can be permanent, long-term complications may include pneumonia and loss of bladder control which may eventually lead to death.

## Data collection and transformation

The data used for this analysis was gotten from Kaggle, here is the link to the dataset https://www.kaggle.com/datasets/zzettrkalpakbal/full-filled-brain-stroke-dataset.

The file contains 11 columns and 4981 rows, there was a description on the page for each of the columns.



![Screenshot (154)](https://user-images.githubusercontent.com/109418747/190642296-4449513a-9257-4150-938f-c7270a073cd6.png)



The data was imported into Excel power query for cleaning and transformation to ease the analysis process. While going through the dataset, I realized I have to create new columns to substitute some of the provided columns to ensure proper exploration and analysis. For heart disease and hypertension columns which are represented with 0 and 1, I used conditional formatting to change it to hypertension/ no hypertension and heart disease/No heart disease. Patients ages were also grouped, categorized patients into diabetic and non-diabetic patients, using the BMI, patients were categorized based into various weight group. I also rename the colums to more descriptive titles.


![image](https://user-images.githubusercontent.com/109418747/190642032-fd1932d4-eb3d-40b8-83e0-fc5578880208.png)

## Visualization
 
 
 After cleaning and checking the quality of the data, I loaded the clean data into Microsoft Excel to build the dashbaord in order to gather insights from the data

 
![brain stroke](https://user-images.githubusercontent.com/109418747/190633822-2017a58e-a33a-4303-ae5a-79cfe2e5d14d.png)



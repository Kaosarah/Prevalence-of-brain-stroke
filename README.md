# Prevalence-of-brain-stroke

## Introduction

A stroke is a medical condition in which there is brain cell's death due to poor or lack of blood flow to the brain. There are two main types of stroke:  hemorrhagic, due to bleeding and ischemic, due to lack of blood flow, causing brain to stop functioning properly. Signs and symptoms of a stroke may include an inability to move or feel one side of the body,loss of vision on one side,problem with understanding or speaking and dizziness. If symptoms last less than one or two hours, the stroke is a transient ischemic attack (TIA), also called a mini-stroke. The symptoms of a stroke can be permanent, long-term complications may include pneumonia and loss of bladder control which may eventually lead to death.

## Data collection and transformation

The data used for this analysis was gotten from Kaggle, here is the link to the dataset 
https://www.kaggle.com/datasets/zzettrkalpakbal/full-filled-brain-stroke-dataset.

The file contains 11 columns and 4981 rows, there was a description on the web page for each of the columns.



![Screenshot (154)](https://user-images.githubusercontent.com/109418747/190642296-4449513a-9257-4150-938f-c7270a073cd6.png)



The data was imported into Excel power query for cleaning and transformation to ease the analysis process. While going through the dataset, I realized I have to create new columns to substitute some of the provided columns to ensure proper exploration and analysis. For heart disease and hypertension columns which are represented with 0 and 1, I used conditional formatting to change it to hypertension/ no hypertension and heart disease/No heart disease. Patients ages were also grouped, I also categorized the patients into diabetic and non-diabetic patients, using the BMI, patients were categorized into various weight group. I also renamed the columns for more descriptive titles.


![image](https://user-images.githubusercontent.com/109418747/190642032-fd1932d4-eb3d-40b8-83e0-fc5578880208.png)

## Visualization
 
 
 After cleaning and checking the quality of the data, I loaded the clean data into Microsoft Excel to build the dashbaord in order to gather insights from the data

 
 ![image](https://user-images.githubusercontent.com/109418747/190677965-8459ff2a-5480-47fa-a8dd-e6058e88b72e.png)


## Insights

According to the dataset presented, brain stroke is mostly seen in adult especially those that are above 60 years of age and rarely find in children.

There is no relationship between heart disease and Brain stroke 

Females are mostly affected with this condition than males.

Individuals with high glucose level (diabetic patients) are prone to brain stroke.

Obese patients are also of the risk of having brain stroke.

There is correlation between smoking and brain stroke as the percentage of patients who smokes and formerly smokes (45.17) are higher than those who do not smoke.

The prevelence of stroke in those living in the urban region(55.10%) is slightly higher than those in rural areas(44.89%).  



## Recommendations
 
All the above mentioned risk factors (smoking, low glucose level, obesity) should be prevented.

Regular checkup of cholesterol and glucose level.

Consistence exercise and diet high in vegetables ,fruits and food low in salt should be consumed.

Patients should report to the clinic immediately symptoms of the risk factors mentioned above or brain stroke are noticed for proper diagnosis and medications.

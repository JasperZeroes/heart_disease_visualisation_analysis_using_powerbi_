<h1>Personal Key Indicators of Heart Disease Analysis using Power BI <img width=125 align=right src="https://github.com/JasperZeroes/Data_visualisation/blob/master/dataset-cover.jpg"> </h1>

## Overview  
Heart diseases also known as Cardiovascular diseases (CVDs) are the leading cause of death globally, taking an estimated 17.9 million lives each year. In the USA alone, it is the causes of death for people of most races (African Americans, American Indians, Alaska Natives, and white people). About half of all Americans (47%) have at least 1 of 3 key risk factors for heart disease: high blood pressure, high cholesterol, and smoking.

The effects of behavioural risk factors may show up in individuals. Identifying those at highest risk of CVDs and ensuring they receive appropriate treatment can prevent premature deaths. [(WHO)](https://www.who.int/health-topics/cardiovascular-diseases)
   
In this project we will learn how the disease affects different patients with respect to features such as sex, age or race. We will see various interactive visuals of the data obtained from the diagnosis of the patients and if they have the disease or not.

These visuals can help medical professionals to determine prescribing various medical treatments and treatment measures to the patients comparing their diagnosis data with our analysed data. It will significantly reduce the time taken by the medical professional to determine the patients’ problems.

## Data Source
The dataset is part of the Behavioral Risk Factor Surveillance System (BRFSS) of the Centers for Disease Control and Prevention (CDC). BRFSS conducts annual telephone surveys to gather data on the health status of US residents. The dataset has undergone cleaning to include only the most relevant variables, reducing the original nearly 300 variables to about 18.

## About the dataset

The following are the features we'll use to determine the likelihood of our target variable (heart disease or no heart disease).
There are 18 attributes:
<details><summary><b>Click to know more </b></summary>   

1. **Heart disease**: coronary heart disease (CHD) or myocardial infarction (MI) 
2. **BMI**: Body Mass Index
3. **Smoking**: Smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] (Yes; No)
4. **AlcoholDrinking**: Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) (Yes; No)
5. **Stroke**: Ever told you had a stroke
6. **PhysicalHealth**: Physical illness and injury, during the past 30 days
7. **MentalHealth**: State of your mental health during the past 30 days
8. **DiffWalking**: Difficulty walking or climbing stairs?
9. **Sex**: Gender (Male; Female)
10. **AgeCategory**: Age (Years) 
11. **Race**: Ethnicity (Whites, Hispanic etc)
12. **Diabetic**: Ever told you had diabetes?
13. **PhysicalActivity**: Adults who reported doing physical activity or exercise during the past 30 days. 
14. **GenHealth**: General state of your health
15. **SleepTime**: On average, how many hours of sleep do you get in a 24-hour period? 
16. **Asthma**: Ever been diagnosed of Asthma?
17. **KidneyDisease**: Not including kidney stones, bladder infection or incontinence, were you ever told you had kidney disease?
18. **SkinCancer**: Ever told you had skin cancer?


</details>

  >Note: Names of the columns were changed while transforming the data in Power BI.

   
## Problem Statement

Heart disease is a leading cause of mortality in most races in the United States, with high blood pressure, high cholesterol and smoking being the key risk factors. The 2020 Annual CDC survey data of 300k adults related to their health status contains information on risks factors as well as other key indicator like diabetic status, obesity (high BMI), not getting enough physical activity or drinking too much alcohol.

The problem is how to utilize the CDC survey data to identify patterns for the likelihood of heart disease in people. Also, poor data visualization is one of the factors which creates one of the biggest overarching problems in the healthcare industry.
<br></br>

## Solution

Power BI is an interactive data visualization software that is responsible for creating, striking, engaging, and meaningful data visualizations that can help to break down even the most complex and convoluted healthcare problems into manageable component parts, giving providers a new level of insight into how to deliver the highest quality care to patients while succeeding with their strategic goals.
<br></br> 

## Description

Here, we’ve used the 2020 annual CDC survey data of 300k+ adults related to their Health status to identify the key factors responsible for heart disease.


<details><summary><b>Key Influencers</b></summary> 

   
   1. The key influencers tab should display the key factors affecting the value selected. In our case, the top factor that results in positive diagnosis of Heart Disease is [Name of feature/variable]. 
   2. On the other side, we may include a column chart or a scatter plot showing the distribution of the selected factor.
   

</details>
<details><summary><b>Top Segments</b></summary>
   
   1. The top segments tab may display the top segments that are identified by Power BI from the dataset for the metric selected. 
   2. It initially shows the overview of all the segments. These segments can be ranked by the heart disease detected (True/False) and the number of patients (population size). [Include image from dashboard]
   
</details>
   
- The visualizations are filtered between Heart Disease Detected to be True or False.
- Slicers are a way of filtering. They narrow the portion of the dataset that is shown in the other report visualizations. 
  So, we might have two slicers one for filtering from the range of age, and another for filtering from different gender or both. [Include image from dashboard]
<br></br>

## Conclusion
It was found, from the dataset, that males were 1.6x more likely than females to have heart disease, and is most common in the age ranging between 70-74 years. [Include image from dashboard]

Heart Disease diagnosis is most positively affected by the following factors:

   1. [Name of variable affecting heart disease], for [%age number of people affected] of the patients and this factor is [number of times] times more likely to cause the disease.

   Offer possible explanation for why (Look into Maryam's research) ! [Include image from dashboard]

   2. [Name of variable affecting heart disease], for [%age number of people affected] of the patients and this factor is [number of times] times more likely to cause the disease.

   Offer possible explanation for why (Look into Maryam's research)! [Include image from dashboard]

   3. [Name of variable affecting heart disease], for [%age number of people affected] of the patients and this factor is [number of times] times more likely to cause the disease.

   Offer possible explanation for why (Look into Maryam's research)! [Include image from dashboard]

   4. Other insights can come in here

   Offer possible explanation for why (Look into Maryam's research) ! [Include image from dashboard]




## Reference

 - Dataset factors explanation – [https://www.kaggle.com/onatto/predicting-heart-disease-a-detailed-guide](https://www.kaggle.com/onatto/predicting-heart-disease-a-detailed-guide)
(Kaggle)

 - Vector art - [https://www.freepik.com/vectors/people](https://www.freepik.com/vectors/people)
(People vector created by katemangostar - www.freepik.com)


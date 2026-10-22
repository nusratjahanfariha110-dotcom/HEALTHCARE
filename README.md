# 📊 Global Healthcare, Fitness & Lifestyle Analysis

This project analyzes the **Sleep Health and Lifestyle Dataset** using Microsoft Excel. It explores the relationships between sleep duration, sleep quality, stress level, physical activity, BMI, blood pressure, daily steps, and sleep disorders.

The project includes data cleaning, Pivot Tables, Pivot Charts, and an interactive Excel dashboard.


## 📁 Dataset

- Source: Kaggle :Sleep Health & Data Set
`  `https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset `
- **Records:** 374 individuals
- **Key columns:** Person ID, Gender, Age, Occupation, Sleep Duration, Quality of Sleep, Physical Activity Level, Stress Level, BMI Category, Systolic, Diastolic, Daily Steps, Sleep Disorder, and Age Group.

## 🛠️ Tools Used

- Microsoft Excel
- Data Cleaning
- Pivot Tables
- Pivot Charts
- Slicers
- Interactive Dashboard

##Data Cleaning
 1.Remove :Remove all the duplicates from the person ID
 2.Added:Added the aged group columb by using "if" fuction.
 3.Seperate & Convert:Seperate the Heart Rate & convert both names into "Systolic" & "Diastolic".
 4.Convert:Convert the "Normal weight " to "Normal".And convert "Obese" to "Over weight"
 5.Convert:Convert whole data into table
 
## 📈 Analysis Questions

1. **What is the average sleep duration and stress level by occupation?**  
   Engineers have the highest average sleep duration at 7.99 hours, while Sales Representatives have the highest average stress level at 8.0.

2. **How are sleep disorders distributed across BMI categories?**  
   Among overweight individuals, 68 people have Insomnia and 71 have Sleep Apnea. Most individuals with a Normal BMI do not have any sleep disorder.

3. **How do sleep quality and physical activity vary by age group?**  
   The Middle Aged group has the highest total physical activity level, while the Senior group shows relatively high total sleep quality.

4. **How do sleep, stress, and blood pressure differ by gender?**  
   Females have an average sleep duration of 7.23 hours, compared with 7.04 hours for males. Males have a higher average stress level of 6.08, compared with 4.68 for females.

5. **What is the average number of daily steps by sleep disorder?**  
   Individuals with Sleep Apnea have the highest average daily steps at 7,619, followed by those with no sleep disorder at 6,853 and those with Insomnia at 5,901.

## 🔍 Key Insights

- High stress levels and shorter sleep duration appear together in several occupations.
- Overweight individuals show a higher tendency toward Insomnia and Sleep Apnea.
- Individuals with a Normal BMI are less likely to have a sleep disorder.
- Daily step counts differ across sleep disorder categories.
- The dashboard allows users to explore insights by occupation, gender, age group, and BMI category.
##Dashboard
All the charts pictures are included with the file of excel
## Method
 1.We used pivot tables
 2.We turn the values into percentage 
 3.We used pivot charts


## 📌 Project Structure


global-healthcare-fitness-lifestyle-analysis/
│
├── Global-Healthcare-Fitness-Lifestyle-Analysis.xlsx
├── README.md
└── dashboard_screenshot.png
```
## Limitations

- The dataset contains only **374 records**, so the results may not be representative of the wider population.
- Some records appear similar or duplicated, which may affect the accuracy of the analysis.
- The dataset has no date or time information, so trends over time cannot be studied.
- Sleep, stress, and activity levels may be self-reported and may not be medically verified.
- The analysis identifies relationships but cannot prove cause and effect.
- The dataset covers limited occupations and age groups, reducing generalizability.
- Excel is suitable for dashboarding and exploratory analysis but is less suitable for advanced statistical modeling or large-scale data processing.

## 👤 Author

**Nusrat Jahan Fariha**  
Data Analyst | Excel | Dashboard Design | Data Visualization  

- GitHub:https://github.com/nusratjahanfariha110-dotcom
- LinkedIn: https://www.linkedin.com/in/nusrat-jahan-fariha-83a60a445/?isSelfProfile=true

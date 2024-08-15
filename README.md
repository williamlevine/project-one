<h1>Diabetes and Demographic Indicators in the United States</h1>

<h4>Contributors: Muad Rashid; William Levine; Chinna Maijala; Abigail Serpa; Sophia Seibure</h4>

![image](https://github.com/user-attachments/assets/ab3e9117-efeb-492d-8a02-b1b52855f8c6)
Photo by <a href="https://unsplash.com/@sweetlifediabetes?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Sweet Life</a> on <a href="https://unsplash.com/photos/a-plate-of-food-and-a-glucometer-on-a-table-iIDY3j_Gnjc?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
  

<h2>Project One for the University of Minnesota's Data Analytics and Visualization Bootcamp</h2>

<h3>Overview</h3>
This project seeks to analyze various demographic indicators and lifestyle behaviors as they relate to the incidence of diabetes in the United States. Diabetes research and data analysis is crucial as it addresses a global health crisis affecting millions of people; our project will focus on different outcomes in the U.S. Diabetes is a chronic condition that can lead to serious complications such as heart disease, kidney failure, blindness, and amputations. Understanding the disease's mechanisms, risk factors, and effective treatments along with lifestyle improvements is vital for improving patient outcomes, reducing healthcare costs, and preventing the onset of diabetes in at-risk populations. Research in this field also supports the development of new therapies, technologies, and public health strategies that can significantly improve quality of life and reduce the burden of diabetes on individuals and society.

<h3>Research Questions:</h3>

- Are the following general demographic indicators correlated with diabetes?
	- Income
	- Education
	- Age
- How are these demographic indicators correlated with the following lifestyle choices?
	- Fruit and vegetable consumption
	- Physical activity
	- Recent cholesterol check
	- BMI
	- Heavy alcohol consumption
- How is each lifestyle choice above correlated with diabetes outcome?

<h3>Data Exploration and Cleaning</h3>
The dataset used for this project was found on Kaggle, where it existed as a cleaned and trimmed version of the larger Behavioral Risk Factor Surveillance System (BRFSS), a survey conducted annually in the United States by the CDC. The original survey has responses from over 400,000 participants. The cleaned version we used has responses from over 250,000 people and is trimmed to only include selected demographic, lifestyle, and diabetes information. These results are from the year 2015.
<br/><br/>
As the dataset was already quite clean, most of our data cleaning involved ensuring the absence of null values, as well as reorganizing the data into usable data frames using groupby and related mathematical functions to calculate the counts and proportions of participants in each demographic or lifestyle group with a given outcome.


<h3>Results</h3> 

Overall, significant correlations were found between diabetes and income, education, and age, with the strength of those significances increasing in that order. Although a trend can be observed in the provided charts, income was found to not have a significant correlation across all categories, but when the highest and lowest categories were compared, a very low p-value was returned in the Chi-squared test. The charts demonstrate that as income increases, diabetes rate decreases; as education level increases, diabetes rate decreases; and as age increases, diabetes rate increases.

Neither fruit nor vegetable consumption was found to have a statistically significant correlation with diabetes outcome. Vegetable consumption was a bit more significant than fruit consumption (p-values of 0.5889 and 0.828, respectively), but the difference could still be attributed largely to chance in sampling. Although not statistically significant, the charts suggest that once-a-day or greater consumption of both fruits and vegetables could be correlated with lower rates of diabetes.
Income has a significant relationship with both fruit and vegetable consumption: fruit only when the highest and lowest groups are compared; vegetables both when all groups are compared and when the highest and lowest are compared. Both fruit and vegetable consumption increase as income increases.

Education has a significant relationship with both fruit and vegetable consumption, following the same pattern of significance as income. There is, however, a standout difference here compared to other charts: for both fruit and vegetables, those with no schooling have a higher rate of consumption than those whose highest level of completed education was either some grade school or some high school. Consumption rates, from there, increase as education increases.

Age has a significant relationship with both fruit and vegetable consumption, but for both fruit and vegetables, significance is only found when the highest and lowest groups are compared. Age thus appears to be the “least correlated” with fruit and vegetable consumption. In these charts, we can see another anomaly, which is that, although consumption of both fruit and vegetables tends to increase as age increases, there is another bump around age 30 to 40, which then dips off again and increases around age 50.

<p align="center">
<img width="400" alt="image" src="https://github.com/user-attachments/assets/7366eb72-570d-4c09-8d13-44f74ca722a6">
<img width="400" alt="image" src="https://github.com/user-attachments/assets/6d689e6a-e887-4a2f-bedc-93672df29083">
  
The analysis reveals that physical activity is influenced by several demographic factors: diabetes status, income, age, and education level. Individuals with diabetes are less active compared to those without diabetes or prediabetes. Higher income is associated with greater physical activity, while lower income correlates with more inactivity. Younger individuals are more active than older ones, who show higher inactivity rates. Additionally, higher education levels are linked to more physical activity, whereas lower education levels are associated with higher inactivity rates. These factors highlight the complex interplay of socio-economic and health-related variables on lifestyle behaviors.

An intriguing pattern emerged when examining the relationship between education level and physical activity. Specifically, individuals with lower education levels tend to have lower rates of engaging in physical exercise. This finding is noteworthy given that most educational systems mandate physical education (PE) classes or extracurricular activities that include sports.

It’s important to consider that while educational institutions do provide structured physical activities, they might not fully capture the broader lifestyle or personal engagement in exercise outside of school hours. Hence, the observed lower exercise rates among individuals with less education may reflect broader socio-economic factors or differences in lifestyle preferences and opportunities rather than the quality of physical education provided.

In all cases, the p-values are significantly less than 0.05, indicating strong evidence of associations between physical activity and each of the factors analyzed: diabetes status, income, age, and education. This suggests that physical activity is influenced by these demographic and health-related factors, with notable differences in engagement levels across different categories.
<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/1e235e1b-33c1-44fb-8e47-41a73d569fbb">

The youngest age cohort of 18-50 showed a high rate of cholesterol checks, but a slightly larger proportion of this group had not undergone a cholesterol check compared to older cohorts. The middle-age cohort, ages 51-64, exhibited a higher compliance rate for cholesterol checks, likely reflecting increased health awareness or medical advice as individuals approach retirement age. The oldest cohort, from age 65-84, had the highest proportion of individuals who had undergone cholesterol checks, which aligns with the increased health monitoring typically recommended for older adults.

Individuals with lower educational attainment, particularly those who never attended school or only completed elementary education, had the lowest rates of cholesterol checks. Respondents with higher education levels, especially those with college education, were significantly more likely to have undergone cholesterol checks. This suggests that higher education is associated with greater health awareness and access to healthcare services. The chi-square test indicated a statistically significant association between education level and cholesterol check status, reinforcing the importance of education in preventive healthcare.

Individuals in lower income brackets were less likely to have undergone cholesterol checks. This may be due to financial barriers, lack of access to healthcare, or lower health literacy. Those in higher income brackets had a significantly higher rate of cholesterol checks, suggesting that income positively influences access to healthcare services and the ability to afford preventive care. The analysis highlights the disparities in healthcare access and utilization based on income, with wealthier individuals being more proactive in managing their health through regular cholesterol checks.

The analysis of cholesterol checks across different demographic indicators—age, education, and income—reveals clear patterns of health behavior and access to preventive care. Older adults, those with higher educational attainment, and individuals with higher incomes are more likely to have undergone cholesterol checks. These findings underscore the critical role of socioeconomic factors in healthcare access and the importance of targeted public health interventions to increase preventive care among younger, less educated, and lower-income populations. By addressing these disparities, we can improve overall public health outcomes and reduce the risk of cardiovascular diseases associated with high cholesterol levels.

<p align="center">
<img width="400" alt="image" src="https://github.com/user-attachments/assets/25f8a429-0639-4af5-b7cf-1dcccbc9c7e8">

The analysis reveals a slight decrease in BMI as income increases, particularly in the highest income bracket ($75,000 or more). While individuals in lower income brackets generally have higher BMI distributions, those earning $75,000 or more show a slightly lower median BMI. This suggests that higher income may indeed provide some benefits in terms of healthier weight management, likely due to better access to health services.

Education is often considered a critical factor in shaping health outcomes, yet this study reveals that it has little impact on BMI. Whether individuals have never attended school or are college graduates, BMI remains consistent across education levels.

Age appears to have a more pronounced effect on BMI. The data indicates that younger individuals (ages 18-24) tend to have lower BMI scores, which gradually increase as individuals age. BMI stabilizes in older age groups (75+), suggesting that weight gain may be a natural part of the aging process.

One of the most striking findings is the strong correlation between BMI and diabetes outcomes. Individuals with higher BMI scores are significantly more likely to fall into pre-diabetes or diabetes categories. This connection underscores the critical role that weight management plays in preventing and managing diabetes. Public health initiatives should focus on promoting healthy eating, regular physical activity, and weight control as key strategies to combat the growing diabetes epidemic.

<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/70be6f3c-7157-4ea7-84c2-327227acf4e1">

Across all income groups, a low percentage of respondents claimed that they are heavy alcoholic consumers, with slight increases at higher income levels. This could be due to higher stress levels and more responsibility with high income jobs, being able to afford more alcohol, and compared to lower income individuals having more leisure time where one would have more opportunity to drink.

Like income, those who claimed heavy alcohol consumption is low across all education levels, and it slightly increases as education increases, with the highest percentage being college graduates. Higher education are places where drinking socially occurs often and those habits can continue after college.

When comparing heavy alcohol use with age, it seems as though the percentage of individuals that claimed heavy drinking decreased as age increased. The highest percentage being in the 18-24 age group, when individuals graduate high school and have more time and freedom to drink more, or they go to college where that environment is known for social drinking. The percentage of non heavy drinkers are consistently high though, and high alcoholic consumption decreases significantly with age.

When comparing the proportions of diabetes in the non heavy alcohol consumer group vs the heavy alcohol group, the results were not as expected. This data set shows that the greater proportion of those with diabetes are in the non heavy alcohol group. This might be due to the fact that less than 6% of individuals claimed heavy alcohol use (heavy alcohol use being more than 14 drinks/week if you are a man and more than 7/week if you are a woman) so the sample size is small. When doing the chi-squared test between diabetes status and heavy alcohol consumption, a p value of .1264 is calculated, which is greater than .05 meaning we fail to reject the null hypothesis and the two variables are not statistically significant.

<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/ace66240-909e-42cf-98b4-83ffa36a55a2">

<h3>Challenges:</h3>
	- Finding a dataset to analyze.
 
<h3>Successes:</h3>
	- Teamwork makes the dream work!
 
<h3>Tech Used:</h3>
	- Jupyter Notebook <br/>
 	- Visual Studio Code
 
<h3>Resources:</h3>
	- Original dataset: https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system<br/>
 	- Cleaned dataset: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset<br />
 	- Notebook for cleaning: https://www.kaggle.com/code/alexteboul/diabetes-health-indicators-dataset-notebook<br/>
  	- Codebook for interpreting variables: https://www.cdc.gov/brfss/annual_data/2015/pdf/codebook15_llcp.pdf<br/>
	- OpenAI GitHub: https://github.com/openai
 	
<h3>Slide Deck Presentation Link:</h3>
https://docs.google.com/presentation/d/1CTFlWn4W6MksoLJruzDwwsQURiYzW_03seefBXjptjI/edit?usp=sharing







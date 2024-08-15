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
	- Heavy alcohol consumption
	- Fruit and vegetable consumption 
	- Recent cholesterol check
	- Physical activity
	- BMI 
- How is each lifestyle choice above correlated with diabetes outcome?

<h3>Data Exploration and Cleaning</h3>
The dataset used for this project was found on Kaggle, where it existed as a cleaned and trimmed version of the larger Behavioral Risk Factor Surveillance System (BRFSS), a survey conducted annually in the United States by the CDC. The original survey has responses from over 400,000 participants. The cleaned version we used has responses from over 250,000 people and is trimmed to only include selected demographic, lifestyle, and diabetes information. These results are from the year 2015.
<br/><br/>
As the dataset was already quite clean, most of our data cleaning involved ensuring the absence of null values, as well as reorganizing the data into usable data frames using groupby and related mathematical functions to calculate the counts and proportions of participants in each demographic or lifestyle group with a given outcome.


<h3>Results</h3> 

- Overall, significant correlations were found between diabetes and income, education, and age, with the strength of those significances increasing in that order. Although a trend can be observed in the provided charts, income was found to not have a significant correlation across all categories, but when the highest and lowest categories were compared, a very low p-value was returned in the Chi-squared test. The charts demonstrate that as income increases, diabetes rate decreases; as education level increases, diabetes rate decreases; and as age increases, diabetes rate increases.

- Although fruit and vegetable consumption alone are not significantly correlated with diabetes outcome, they are significantly correlated with various demographic metrics which themselves are strongly correlated with diabetes. Fruit and vegetable consumption increases as income, education, and age increase. As diabetes outcome decreases when income and education increase, this could suggest a difference in lifestyle between groups which has an impact on diabetes outcome.
<p align="center">
<img width="400" alt="image" src="https://github.com/user-attachments/assets/7366eb72-570d-4c09-8d13-44f74ca722a6">
<img width="400" alt="image" src="https://github.com/user-attachments/assets/6d689e6a-e887-4a2f-bedc-93672df29083">
  
- The analysis reveals that physical activity is influenced by several demographic factors: diabetes status, income, age, and education level. Individuals with diabetes are less active compared to those without diabetes or prediabetes. Higher income is associated with greater physical activity, while lower income correlates with more inactivity. Younger individuals are more active than older ones, who show higher inactivity rates. Additionally, higher education levels are linked to more physical activity, whereas lower education levels are associated with higher inactivity rates. These factors highlight the complex interplay of socio-economic and health-related variables on lifestyle behaviors.
<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/1e235e1b-33c1-44fb-8e47-41a73d569fbb">

- Across all income and education levels, a low percentage of respondents reported heavy alcohol consumption, though there is a slight increase in heavy drinking among higher income earners and more educated individuals. In contrast, heavy alcohol consumption declines with age, with the highest percentage found among the 18-24 age group. Interestingly, the data reveals that a higher proportion of individuals with diabetes are in the non-heavy alcohol consumption group.
<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/ace66240-909e-42cf-98b4-83ffa36a55a2">

- The analysis of cholesterol checks across different demographic indicators—age, education, and income—reveals clear patterns of health behavior and access to preventive care. Older adults, those with higher educational attainment, and individuals with higher incomes are more likely to have undergone cholesterol checks. These findings underscore the critical role of socioeconomic factors in healthcare access and the importance of targeted public health interventions to increase preventive care among younger, less educated, and lower-income populations.
<p align="center">
<img width="400" alt="image" src="https://github.com/user-attachments/assets/25f8a429-0639-4af5-b7cf-1dcccbc9c7e8">

- The analysis shows that income and education have minimal impact on BMI, but age has a clear link, with BMI increasing as individuals age. Additionally, the strong correlation between BMI and diabetes highlights the need for targeted interventions to address both.
<p align="center">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/70be6f3c-7157-4ea7-84c2-327227acf4e1">

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







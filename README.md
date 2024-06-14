# Predicting Insurance Premiums

## Below is a comprehensive data analysis for individuals from the four regions of the United States, examining their characteristics including number of children, BMI, age, sex, smoking status, and insurance charges. This analysis is followed by the application of a Machine Learning Random Forest Regressor algorithm, incorporating feature engineering to enhance predictive performance.

1- **Correlation Heatmap for Numerical Features**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/60c2f101-bcc7-44bd-9fe3-b70db6399730)

## Conclusions from the above graph:
> 1. **There is a moderate positive correlation between age and charges. This suggests that as age increases, the charges also tend to increase, but the relationship is not very strong.**

> 2. **There is a weak positive correlation between BMI and charges. This indicates that higher BMI values are slightly associated with higher charges, but the relationship is not significant.**

> 3. **The correlation between the number of children and charges is very weak. This suggests that the number of children has little to no impact on the charges.**

> 4. **There is a weak positive correlation between age and BMI, indicating that older individuals tend to have slightly higher BMI values, but the relationship is not strong.**

> 5. **The correlation between age and the number of children is very weak, suggesting no significant relationship between these variables.**

> 6. **There is an almost negligible correlation between BMI and the number of children, indicating no meaningful relationship between these variables.**

2- **Histogram of Numarical Values**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/d6492679-aede-4bbe-8d96-ee19aa1bd0db)

## Conclustions from the above graph:
> 1. **The age distribution appears to be relatively uniform across the middle age ranges but has a significant peak at age 18-20. This indicates a higher number of younger individuals in the dataset. There are fewer individuals in the older age brackets compared to the younger ones.**

> 2. **The BMI distribution is approximately normal (bell-shaped), with the majority of individuals having a BMI between 25 and 35. There are fewer individuals with very low or very high BMI values.**

> 3. **The distribution of the number of children shows that the majority of individuals have zero children. The frequency decreases as the number of children increases, with very few individuals having more than three children.**

> 4. **The distribution of insurance charges is highly skewed to the right, indicating that most individuals have lower insurance charges, while a smaller number of individuals have significantly higher charges. This skewness suggests that a small number of high-cost claims are driving the overall charge distribution.**

3- **Sex&Smoke Distribution**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/4185ef48-340f-44f4-959d-697ba8ded957)

## Conclustions from the above graph:
> 1. **The distribution of males and females in the dataset is nearly equal, with both categories having around 700 individuals. This balanced distribution suggests that the dataset is not biased towards one sex, allowing for a fair analysis of other features in relation to sex.**

> 2. **There is a significant difference in the number of smokers and non-smokers in the dataset. The number of non-smokers (approximately 1060) is much higher than the number of smokers (approximately 270). This imbalance indicates that a larger portion of the dataset consists of non-smokers. This could affect analyses related to smoking and its impact on other variables like charges.**

4- **Scatter plots for numerical features vs charges**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/9069fdd4-b677-4480-b678-5fa0eddd14b4)

## Conclustions from the above graph:
> 1. **Age is a significant factor in insurance charges, likely due to increased health risks with age.**
> 2. **BMI has a slight impact on charges, but the relationship is not strong.**
> 3. **The number of children does not have a significant impact on charges.**

5- **BMI vs. Charges by Smoking Status**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/cdd436a1-d65a-483e-a338-32f5b66e89ff)

## Conclustions from the above graph:
> 1. **Smoking status significantly affects insurance charges, with smokers incurring higher costs.**
> 2. **This impact is consistent across different BMI levels, highlighting smoking as a major risk factor.**

6- **Charges by Sex and Smoking Status**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/27edd0ee-11df-42b6-aac6-3483557bff7b)

## Conclustions from the above graph:
> 1. **Both male and female smokers have higher insurance charges compared to their non-smoking counterparts.**
> 2. **The distribution of charges is broader for smokers, indicating more variability and potentially higher health risks.**

7- **Pair Plot by Smoking Status**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/b42e26ce-4498-4b3b-81f1-b72b444c5554)

## Conclustions from the above graph:
> 1. **The relationships between variables differ for smokers and non-smokers.**
> 2. **Charges increase with age and BMI more sharply for smokers, reinforcing the impact of smoking on health costs.**

8- **Charges by Region**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/b9a8119d-dd44-4552-8269-5191ea2b5c46)

## Conclustions from the above graph:
> 1. **Regional differences in charges suggest varying healthcare costs or health risks across regions.**
> 2. **Southeast stands out with higher charges, possibly indicating higher healthcare utilization or costs in that region.**

9- **Distribution of Charges by Region**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/1c60c570-85e0-4661-95f9-419fc67003a9)

## Conclustions from the above graph:
> 1. **The right-skewed distribution in all regions indicates that while most individuals have lower charges, a few have significantly higher costs.**
> 2. **Southeast has a noticeable peak in higher charge ranges, reinforcing the box plot findings.**

10- **Distribution of Children by Region**
![image](https://github.com/itsahmedmohamedamin/Predicting-Insurance-Premiums/assets/50253297/dd3e6ae1-1e16-4609-9357-7a7dbd7f1691)

## Conclustions from the above graph:
> 1. **The distribution is consistent across regions, with a majority having no or one child.**
> 2. **There is no significant regional difference in the number of children, indicating similar family sizes across regions.**


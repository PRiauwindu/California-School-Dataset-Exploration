# California School Dataset Exploration

GitHub Pages: https://priauwindu.github.io/California-School-Dataset-Exploration/

# Introduction

R Ecdat package is a dataset containing information on California public schools in 1998. The dataset includes information on 420 schools, with variables on student test scores, class sizes, teacher experience and education, and other school characteristics.

This dataset is often used in educational research to study the factors that influence student achievement, as well as to evaluate the effectiveness of different policies and interventions. It is also frequently used as a teaching tool in statistics and econometrics courses, as it provides a rich source of real-world data that can be used to illustrate various statistical and modeling techniques.

# Objective

Exploring the relationship between student test scores in California public schools with several factors using Multiple Linear Regression method.

# Analysis Result Summary

The analysis of the "caschool" dataset using multiple linear regression showed that several factors were significantly associated with student test scores in California public schools. Specifically, the model found that higher expenditures per student (expnstu) and higher average income in the school district (avginc) were positively associated with higher test scores. This suggests that investing more resources into education and addressing income-related issues in school districts could potentially improve student achievement in California.

In contrast, the model also found that several factors were negatively associated with student test scores. These include a higher percentage of students who do not receive free or reduced-price meals (mealpct), a higher student-teacher ratio (str), and a lower percentage of English learners (elpct) in the school. This suggests that addressing poverty-related issues such as access to free or reduced-price meals, reducing class sizes, and addressing language barriers for non-English learners could also help improve student achievement in California public schools.

Overall, our multiple linear regression model provides useful insights into the factors that influence student achievement in California public schools. By identifying these factors, policymakers and educators can work to address these issues and potentially improve student outcomes.

It is important to note that while the multiple linear regression analysis of the "caschool" dataset using the predictors of mealpct, expnstu, str, avginc, and elpct did reveal some significant associations with student test scores in California public schools, the model is limited by the available variables, range of the data value within the dataset, and potential confounding factors that were not included in our analysis. Furthermore, correlations do not necessarily imply causation, and it is important to consider other factors that may influence student achievement, such as student motivation and teacher quality. Therefore, our results should be interpreted with caution and further research is needed to fully understand the complex factors that impact student achievement in California public schools.

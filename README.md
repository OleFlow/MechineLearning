# MechineLearning-Income Determinations: Exploring Influential Factors in Annual Earnings (Adult Dataset)

## Description

Analyzing demographic and income-related information for various individuals.

## Data Table

This table presents information about individuals and various attributes related to their demographics and employment.

| Column Name       | Description                                                        |
|-------------------|--------------------------------------------------------------------|
| Age               | Age of the individual.                                             |
| Workclass         | The type of employment.                                            |
| Fnlwgt            | A weighting factor used in the calculation of the census results.  |
| Education         | Highest level of education achieved by the individual.             |
| Educational-num   | Numerical representation of education.                              |
| Marital-status    | Marital status of the individual.                                   |
| Occupation        | Type of occupation the individual is engaged in.                    |
| Relationship      | Relationship status of the individual.                              |
| Race              | Race of the individual.                                             |
| Gender            | Gender of the individual.                                           |
| Capital-gain      | Capital gains obtained by the individual.                            |
| Capital-loss      | Capital losses obtained by the individual.                           |
| Hours-per-week    | Hours worked per week by the individual.                             |
| Native-country    | Country of origin or native country of the individual.              |
| Income            | Income level, whether it's above or below $50K.                     |

## Stakeholders
### Employers or HR Departments:
Predicting income levels based on demographic and employment-related features can help employers understand the expected income range of potential employees. This can aid in decision-making during the hiring process and salary negotiations.
## Data visualization number 1
![Screenshot 2023-10-12 at 17 04 19](https://github.com/OleFlow/MechineLearning/assets/106384255/d51b45f1-789c-4555-a99e-be1561947cf7)
**Age vs. Working Class for <=50K (Red points):**

The red points are spread across various working classes, showing that individuals with income <=50K are employed across different sectors and age groups.

**Age vs. Working Class for >50K (Blue points):**

The blue points, representing individuals with income >50K, also come from various working classes, indicating a diversity of occupations within this income range.

## Data visualization number 2
![Screenshot 2023-10-12 at 17 08 29](https://github.com/OleFlow/MechineLearning/assets/106384255/ab4c959f-2bd0-4099-aad3-eb0b6eeb8788)

**Average Age:**

For both males and females, the average age is slightly higher for individuals with an income >50K compared to those with an income <=50K.
Among males, the average age for those with an income >50K is slightly higher than for females in the same income group.


**Average Hours per Week:**

For both males and females, the average hours per week are slightly higher for individuals with an income >50K compared to those with an income <=50K.
Among males, the average hours per week for those with an income >50K is slightly higher than for females in the same income group.


**Gender Differences:**

In both income groups, the average age and average hours per week are slightly higher for males compared to females.


**Income Differences:**
In both gender categories, individuals with an income >50K tend to have a slightly higher average age and work slightly more hours per week compared to those with an income <=50K.

## The metrics for your best model

I used the K-Nearest Neighbors (KNN)
Accuracy: 72% accuracy is a reasonable starting point

## Conclusion
**Understanding Demographic and Socioeconomic Factors:**

Analyze the scatter plot of age vs. hours per week to understand the distribution of working hours across different age groups. This can help in tailoring policies or interventions for specific age demographics, especially considering factors like productivity and employee satisfaction.

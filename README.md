# Descriptive Statistics with Python

## Table of Contents
1. [Section 1: Theoretical Questions](#section-1-theoretical-questions)
   - [Question 1](#question-1)
   - [Question 2](#question-2)
   - [Question 3](#question-3)
   - [Question 4](#question-4)
   - [Question 5](#question-5)
   - [Question 6](#question-6)
   - [Question 7](#question-7)
2. [Section 2: Practical Questions with Dataset](#section-2-practical-questions-with-dataset)
   - [Question 8](#question-8)
   - [Question 9](#question-9)
   - [Question 10](#question-10)
   - [Question 11](#question-11)
   - [Question 12](#question-12)
   - [Question 13](#question-13)
   - [Question 14](#question-14)
   - [Question 15](#question-15)
   - [Question 16](#question-16)
   - [Question 17](#question-17)
   - [Question 18](#question-18)
   - [Question 19](#question-19)
   - [Question 20](#question-20)
3. [Deliverables for Solution and Grading Rubric](#deliverables-for-solution-and-grading-rubric)

## Section 1: Theoretical Questions
### Question 1
A statistics test was conducted for 10 learners in a class. The mean of their score is 85 and the variance of the score is zero. What can you interpret about the score obtained by all learners?

- If the variance of the scores is zero, it implies that there is no variability in the scores. In other words, all scores are identical. Since the mean score is 85, it means that all 10 learners scored exactly 85 on the test.

### Question 2
In a residential locality, the mean size of the house is 2224 square feet and the median value of the house is 1500 square feet. What can you interpret about the skewness in the distribution of house size? Are there more bigger or smaller houses in the residential locality?

- The mean (2224 square feet) is greater than the median (1500 square feet), indicating that the distribution of house sizes is positively skewed, with a tail extending towards larger house sizes. Therefore, there are more smaller houses in the residential locality as indicated by the median value being less than the mean.

### Question 3
The following table shows the mean and variance of the expenditure for two groups of people. You want to compare the variability in expenditure for both groups with respect to their mean. Which statistical measure would you use to evaluate the variability in expenditure? Please provide an explanation for your answer.

| Expenditure | Group I | Group II |
|-------------|---------|----------|
| Mean        | $500,000| $40,000  |
| Std. Dev.   | $125,000| $10,000  |

- To compare the variability in expenditure for both groups with respect to their mean, you would use the coeff. of variation (CV).
Coefficient of variance (CV) = (Standard dev. / Mean)  * 100%
For
Group 1: CV = (125,000 / 500,000) * 100% = 25%
Group 2: CV = (10,000 / 40,000) * 100% = 25%
Both groups have the same coefficient of variation (25%), indicating that the variability in expenditure relative to the mean is consistent across both groups.

### Question 4
During the survey, the ages of 80 patients infected by COVID and admitted to one of the city hospitals were recorded and the collected data is represented in the less than cumulative frequency distribution table.

| Age (in yrs.) | No. of Patients |
|---------------|-----------------|
| 5 - 15        | 6               |
| 15 - 25       | 11              |
| 25 - 35       | 21              |
| 35 - 45       | 23              |
| 45 - 55       | 14              |
| 55 - 65       | 5               |

#### a. Which class interval has the highest frequency?  
The class interval with the highest frequency is "35-45 years," with 23 patients.

#### b. Which age was affected the least?  
As the age group “55-65 years” have only 5 patients. Therefore, this age range was affected the least among the patients admitted to the hospital.

#### c. How many patients of age 45 years and above were admitted?  
Since the interval spans 10 years (from 35 to 45), and assuming a uniform distribution, we can estimate that approximately 1/10th of the patients in this interval are exactly 45 years old.
So, for the "35 to 45 years" interval: Number of patients aged 45 = (1/10) * 23 = 2.3, rounding off 2
Total patients of age 45 years and above 14 (from "45 to 55 years") + 2 (estimated from "35 to 45 years") + 5 (from "55 to 65 years") = 21
So, there were approximately 21 patients of age 45 years and above admitted to the hospital.

#### d. Which is the modal class interval in the above dataset?
The modal class interval is the interval "35 to 45 years" because it has the highest frequency of 23 patients.

#### e. What is the median class interval of age?
To find the median class interval, we locate the class interval containing the median age, which is the interval where the cumulative frequency first exceeds (or equals) half of the total frequency.

Cumulative Frequency:
- 5 to 15 years: 6
- 15 to 25 years: 6 + 11 = 17
- 25 to 35 years: 17 + 21 = 38
- 35 to 45 years: 38 + 23 = 61
- 45 to 55 years: 61 + 14 = 75
- 55 to 65 years: 75 + 5 = 80

  Since the total frequency is 80, the median would be the 40th value. Looking at the cumulative frequencies, the interval "35 to 45 years" (from 38 to 61) contains the 40th value.
  So, the median class interval of age is "35 to 45 years."




# ICU Data Analysis
#### -- Project Status: [Completed]
## Project Intro/Objective
When a patient goes to the ICU, it is very important to understand their medical history in order to provide them with the correct medical assistance. Their likelihood of survival also will change based on whether they have any medical complications or past conditions. The purpose of this project is to determine which factors impact the outcome of a patient's health after they visit an Intensive Care Unit. 

### Methods Used
* Chi-square Test
* Multinomial Logistic Regression
* Inferential Statistics
* Data Visualization
* Hypothesis Testing

### Technologies
* R 

## Data Set Description
This data set includes different patient charactertistics 
when they are checked into the intensive care unit. The variables are listed below with a breif description.
* renal : binary variable where yes indicates that the patient had a history of chronic renal failure and no indicates otherwise 
* infect.prob : binary variable where yes indicates that an infection is possible and no otherwise
* PO2 : The measure of oxygen partial pressure measured in mm Hg and the healthy level is inbetween 75-100 and unhealthy levels are less than 60
* PCO2 : The measure of carbon dioxide partial pressure which is measured in mm Hg and the healthy range is inbetween 35-45 mm Hg and unhealthy is higher than 45 mm Hg
* PH : healthy values are inbetween 7.35 and 7.45. If the pH value is lower then the patient could have acidosis 
* bicarb : the bicarbonate level which is measured by mEq/L and low levels mean that the patient has metabolic acidosis 
## Project Description
* Preliminary visualizations were created in order to understand the distributions of each variable
* A chi-square test was conducted on each predictor variable in order to understand whether an association existed
* The associated variables were put into a multinomial logistic regression model and the odds of mortality were calculated 
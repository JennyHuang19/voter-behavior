# Data

**Dataset Dimensions**

The original dataset (called `data_full`) has 28 variables and 643,429 observations. We cleaned the data for our project purposes and created a new dataset (called `elections_clean`) that has 22 variables and 643,429 observations. To complete model selection and analysis, we used a random sample of 10,000 observations. The following codebook is for the variables in the cleaned dataset that we created. 

**Codebook**

Based on information found in the 2020 Fall Data Challenge codebook [1].

* `voted`: binary variable for whether or not the survey respondent voted in the previous November election
* `metro`: binary variable for whether or not the respondent lives in a metro area
* `sex`: respondent sex
* `marst`: marital status
* `veteran`: binary variable for respondent veteran status
* `citizen`: respondent citizenship status (Native Born or Naturalized)
  + the dataset does not include anyone who is not a citizen
* `hispanic_status`: binary variable for whether a respondent is Hispanic
* `employed`: binary variable for whether the respondent is employed 
* `highest_education`: respondent's highest level of formal education achieved 
* `current_student`: enrollment status (full- or part-time) of respondents age 16 to 24 during the previous week
* `race`: responent race
* `voting_method`: respondent's method of voting (in-person or mail-in)
* `voting_time`: whether a respondent voted early or on election day
* `YEAR`: survey/election year
* `STATEFIP`: state identification in FIP format
* `AGE`: respondent age at their last birthday
* `Election`: type of election 
  + Presidential Election or Midterm Election

[1] American Statistical Association. “ASA’s 2020 Fall Data Challenge: Get Out the Vote! Challenge Dataset FAQ,” n.d. https://thisisstatistics.org/wp-content/uploads/2020/09/2020-Fall-Data-Challenge-DatasetFAQ-PDF.pdf.
 
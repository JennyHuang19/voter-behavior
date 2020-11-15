# What makes someone more likely to vote? Using logistic regression to calculate predicted probabilities for whether someone will vote. 

[Project](https://sta210-fa20.netlify.app/project/) for STA 210, Fall 2020

**A project by team Approximately Normal**

In this project, we investigated voter turnout rates over a 14-year period. We 
used data from IPUMS and the American Statistical Association that that were 
originally collected from surveys conducted by the United States Census Bureau 
and the Bureau of Labor Statistics [1,2]. The surveys are part of a “Voting and 
Registration Supplement” of the Current Population Survey that occurs every two
years after the November elections [3]. We used logistic regression and model 
selection processes (backward selection using AIC and drop-in-deviance tests) to 
predict whether a person voted or not based on predictor variables including 
sex, age, marital status, veteran status, citizenship status (native born or 
naturalized citizen), whether or not someone is Hispanic or Latinx, employment 
status and more. We assumed a hypothetical role of an organization planning to 
distribute mailers to encourage people to vote, with the goal of minimizing 
wasted resources by only sending mailers to the people who are not likely to 
vote using a decision threshold based on our final model.

**Dataset Dimensions**
The original dataset (called data_full) has 28 variables and 643,429 observations. We cleaned the data for our project purposes and created a new dataset (called elections_clean) that has 22 variables and 643,429 observations. To complete model selection and analysis, we used a random sample of 10,000 observations. The following codebook is for the variables in the cleaned dataset that we created. 

**Codebook**
Based on information found in the 2020 Fall Data Challenge codebook [3].

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
* `Presidential_Election_Status`: type of election 
  + Presidential election, Midterm Following Incumbent President, or a Midterm Following New President
* `Is_Presidential_Election`: binary variable for whether the election was a presidential election

[1] https://ipums.org/what-is-ipums

[2] https://thisisstatistics.org/falldatachallenge/  

[3] https://thisisstatistics.org/wp-content/uploads/2020/09/2020-Fall-Data-Challenge-DatasetFAQ-PDF.pdf 

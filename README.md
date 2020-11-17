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

[1] https://ipums.org/what-is-ipums

[2] https://thisisstatistics.org/falldatachallenge/  

[3] https://thisisstatistics.org/wp-content/uploads/2020/09/2020-Fall-Data-Challenge-DatasetFAQ-PDF.pdf 

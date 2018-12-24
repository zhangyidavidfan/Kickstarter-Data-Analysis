# Kickstarter-Data-Analysis
CIS 105 Final Project

Our group’s data set was based on startup success rates on Kickstarter and factors that could have affected them. 
We started by cleaning the data – we removed data where the numbers did not add up, dropped rows with incomplete data, 
and renamed ambiguous values. We then proceeded to do some feature engineering and came up with three hypotheses 
based on the final data:

1.	Null Hypothesis: 2015’s lackluster success rate occurred by chance
Alternative Hypothesis: 2015’s lackluster success rate occurred because of a specific variable
2.	A regression model predicting how successful the campaign was with respect to the goal
3.	A test using bootstrapping to see if Italy and Japan’s success rates were low by pure chance

We found three possible explanations for the lackluster success rate in 2015 – Kickstarter reached saturation,
the greater quantity of campaigns brought about lower standards, and a greater number of projects were tech, 
which were hard for the primary audience to empathize with.

For the second hypothesis we found that a regression model predicting number of pledges was more 
accurate than one based on the goal. The model that gauged how successful the campaign is dynamically 
was weakened because of the lack of predictive power for the goal. 

The third hypothesis found that Italy’s success rate had a low probability of being due to chance 
because it was concentrated within a very narrow range. Japan’s success rate was probably due to chance 
because it had a very large variance in success rate after bootstrapping. We also found out that bootstrapping
with a smaller dataset leads to a result which is more open to being affected by chance.

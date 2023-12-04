# datasci_6_anova

## data preperation

The dataset which was used for this assignment was the one presented to use in class as examples number 2 in our lecture powerpoint presentation. The variables which were selected for this analysis are also from the example presented in class which we were asked to work on for this assignment: race and A1C result. A subset was created with these two independent variables along with the dependent variable of time in hospital. 

## assumption checks

During this portion I found it challenging to come up more accurate p-values while mainting the integrity of the dataset. Due to the subset being very large since the existing dataset it was derived from being large as well, the p-values were very small and all fell under 0.05 suggesting that the different groups were not normal distributions and not of equal variance. Due to the warning which appreared while running the Shapiro-Wilk test, I was unsure of the accuracy of the p-values however, while analyzing the values under the groups of the two independent variables and running the ANOVA, it is evident that there is a difference between the average time in hospital spent and the groups within the independant variables.  

## ANOVA outcomes
An insight for the future is to use a smaller dataset however a dataset which has at least more than 30 rows. In the future I would also continue to refer to an print the information regarding the variables used in the dataset I am analyzing so that I can make a educated decisions on which variables to use for analysis. Some of the information I would take into consideration if the variable is catergorical or numerical and check if it has any missing information within its column. 

A pattern I noticed within this ANOVA test is that low p-values < 0.05 which appeared in all the tests conducted. However, at the end of the ANOVA the p-value for both independant values suggested that there is a difference within the length of time a patient spent in the hospital between different races and patients with different A1C result interpretations. 


## Key Findings  ##

This is a short description of results which i found during the analysis of the two projects Doctor Complaints and Bumpus Analysis.

For detailed report and methodology please have a look at my reports.

Project 1 - Doctor Complaints Analysis 

Aim - To Determine the Effect of Variables on the Number of Complaints Received by the Doctors in an Emergency Department

Method used - 
Research of the dataset from different sources and using different models to find the relationship and picking out the best one. I found the best one is zero inflation poisson model. 

<img width="451" height="269" alt="image" src="https://github.com/user-attachments/assets/2afc6798-1b40-4061-a58c-174e95b909bb" />

Findings

<img width="807" height="614" alt="image" src="https://github.com/user-attachments/assets/823347dc-b04d-440d-9236-b0fd9abc3e02" />


1) If the doctor is male the expected count of complaints increases by a factor of exp(1.344) i.e 3.83 times , compared to being female.
2) For every one-unit increase in revenue, the expected count of complaints decreases by a factor of exp(-0.0007) i.e 0.999 times. This indicates a small negative effect of revenue on the count of complaints.
3) If the doctor is in residency training , the expected count of complaints increases by a factor of exp(3.921) compared to when the doctor is not in residency i.e it’s chances increases by 50.45 times.
4) For every one-unit increase in the number of visits, the expected count of complaints increases by a factor of exp(0.0014) i.e 1 times. This suggests a small positive effect of the number of visits on the count of complaints.



Project 2  - Bumpus Analysis

Aim - To determine the relationship between survival and the other variables of sparrows in the Bumpus data.

Method used - Research of the dataset from different sources and using different models to find the relationship and picking out the best one. The best one was logistic regression model and i used drop in deviance test method. 

<img width="584" height="569" alt="image" src="https://github.com/user-attachments/assets/3ae648e7-7e51-421d-aac2-79b3fdd8c2d5" />

Findings - 

1) males are 5.375 times likely to survive than females (Scatter Plot). Hence, males survival is more.
2) when the length of the bird increases chances of survival gets reduced by almost 58%.
3) one unit increase in weight chances of survival reduce by 65.2 %.
4) For one unit increase in humerus. This is an extremely small value, it means there is not much dependency of humerus on Survival of the birds.














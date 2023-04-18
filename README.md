# Lead-Scoring-Case-Study

1. Which are the top three variables in your model which contribute most towards the probability of a lead getting converted?
Ans :
Tags and Lead Source and What is your current occupation are the top 3 variables which contribute most towards the probability of a lead getting converted.
2. What are the top 3 categorical/dummy variables in the model which should be focused the most on in order to increase the probability of lead conversion?
Ans:
and What matters most to you in choosing a course and Last Notable
are the 3 variables which should be focused for the most in order to increase the
probability of lead conversion.
3. X Education has a period of 2 months every year during which they hire some interns. The sales team, in particular, has around 10 interns allotted to them. So, during this phase, they wish to make the lead conversion more aggressive. So, they want almost all of the potential leads (i.e., the customers who have been predicted as 1 by the model) to be converted and hence, want to make phone calls to as much of such people as possible. Suggest a good strategy they should employ at this stage.
Ans:
From the curve above, 0.4 is the optimum point to take it as a cutoff probability and at this point the accuracy is great, so it means that the probability of converting is high, and we should make calls or email based on the customers preference.
4. Similarly, at times, the company reaches its target for a quarter before the deadline. During this time, the company wants the sales team to focus on some new work as well. So, during this time, the company’s aim is to not make phone calls unless it’s extremely necessary, i.e., they want to minimize the rate of useless phone calls. Suggest a strategy they should employ at this stage.
Ans:
During this time, company can reach out to customer in bulk email strategy or company interns can reach out to leads in person.
     Country
  Activity
     
     
         Lead Scoring Case Study Summary
• Tags and Lead Source and What is your current occupation and Last Notable activity are the top 4 variables which contribute most towards the probability of a lead getting converted.
• Country and What matters most to you in choosing a course and Last Notable Activity are the 3 variables which should be focused for the most in order to increase the probability of lead
conversion.
•
• Accuracy at threshold 0.4 is highest.
• A common way to visualize the trade-offs of different thresholds is by using an ROC curve, a
plot of the true positive rate ( true positives/ total positives) versus the false positive rate ( false
positives /total negatives) for all possible choices of thresholds.
• A model with good classification accuracy should have significantly more true positives than
false positives at all thresholds.
• The optimum position for roc curve is towards the top left corner where the specificity and
sensitivity are at optimum levels
Area Under The Curve (AUC)
• The area under the ROC curve quantifies model classification accuracy ; the higher the area, the greater the disparity between true and false positives, and the stronger the model in classifying members of the training dataset.
• An area of 0.5 corresponds to a model that performs no better than random classification and a good classifier stays as far away from that as possible. An area of 1 is ideal.
• The closer the AUC to 1 the better.
        All variables have a good value of VIF. So we need not drop any more variables and we can
 proceed with making predictions using this model only
  

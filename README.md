# credit-risk-classification
 Module 20
When lending companies give out loans, they expect borrowers to either return the asset or pay back the money. However, there's always a risk that the borrower might not repay, which can cause the lender to lose money. This risk is known as "Credit Risk."

In this analysis, we're using Machine Learning to examine historical lending data from a peer-to-peer lending company. Our goal is to build a model that can help predict how likely a borrower is to repay their loan, which is called "creditworthiness."

To do this, we used a machine learning technique called Logistic Regression. This method is popular for predicting outcomes that fall into two categories, like whether a loan is "low-risk" (likely to be repaid) or "high-risk" (unlikely to be repaid).

Initially, we created a Logistic Regression model using the data provided by the lending company. This model was able to predict loan outcomes with 95% accuracy. However, it was better at predicting low-risk loans than high-risk ones. This happened because the data we used was unbalanced, meaning there were a lot more low-risk loans than high-risk ones.

To improve our model, we adjusted the data so that there were equal amounts of low-risk and high-risk loans. After this adjustment, the model's accuracy increased to 99%. It also became much better at identifying high-risk loans correctly, which is crucial for a lending company.

For a lender, correctly identifying both low-risk and high-risk loans is important. If a low-risk loan is mistakenly labeled as high-risk, the lender might lose customers. On the other hand, if a high-risk loan is mistakenly labeled as low-risk, the lender could lose money.

To illustrate how well the models performed, we looked at confusion matrices, which show the number of correct and incorrect predictions:

Imbalanced Data Model:

56 loans were incorrectly labeled as high-risk when they were actually low-risk.
102 loans were incorrectly labeled as low-risk when they were actually high-risk.
Balanced Data Model:

4 loans were incorrectly labeled as high-risk when they were actually low-risk.
116 loans were incorrectly labeled as low-risk when they were actually high-risk.
In conclusion, the adjusted model with balanced data does a much better job at accurately predicting both low-risk and high-risk loans, which is essential for minimizing financial losses and retaining customers.

# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * The first machiene model predicited the correct loan status with 95% accuracy.
  * Where this model struggled was with the assesment of high-risk loans (85% accuracy) due to the fact that the sample size of the high-rish loan applicants (2500) was very small when compared to the size of the entire dataset (77506).



* Machine Learning Model 2:
  * The second machiene model predicted the correct loan status with 99% accuracy.
  * This model performed better than the first to the RandomOverSampling function. It gave both sides of the data equal and ample size for the machiene to learn off of.
  
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

* The point of this machiene learning program was to train a model to asses whether or not applicants should/shount not be approved for loan based on a list of factors (interst rate, income, debt to income ratio, etc.) Both models used Logisitic Regression to train the models. The first model used strictly used the dataset given to use, and predicited the loan applicant risk rate with a 95% accuracy. This first model struggled with the fact that there was a low amount of high-risk applicants to learn from in the dataset. The second machiene model uses Random OverSampling to make the number of high-risk and low-risk loan data equal and ample enough to learn off of. The second model predicted the loan risk status with 99% accuracy, only miss labeling 4 high-risk loan applicants as low-risk. When recommending a model to use for a loan company, the second model would be a much better route. The part that would lose a loan company the most money, is giving loans to applicants that are high-risk, because of the mislabeling by a machiene, with the potential of these applicants never paying the loan back. Therefor, due to the accuracy of the second odel, I would reccomend the second machiene model. 

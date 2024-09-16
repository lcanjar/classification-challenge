# Module 13 Challenge, UNC AI Bootchamp
## classification-challenge
## Completed classification analysis of the Spam Detector data using both the Logistic Regression and Random Forest Models.
## Compared and assessed the results of both models using accuracy_score.

Dataset Source: [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase)

### 1. I read the data in to a DataFrame and analyzed the data (checked for null and non-scaler values).  I also created a custom function (test_model()) to streamline training, fitting, and scoring models.  I re-used this method from another assignment.
### 2. I split the data (training v. testing) and scaled the features as instructed.
### 3. Using the custom function, I fit and score the data.  And then made testing predictions.
- I did this first on the LogisticRegression() model.
- Then ran the same funcntion using the RandomForestClassifier() model.
## 4. My evaluation is as follows:
- **How does this compare to your prediction?**  The accuracy results for the Random Forrest Classifier is higher, at .97. This is consistent with my original hypothesis. The accuracy results for the Logistic Regression model is .93. 


- **Which model performed better?** 
-- The test and training scores for Random Forest Classifier are very high. And the test score is lower than the training score which could indicate overfitting.
-- By contrast, the test and training scores for Logistic Regression model are lower, but the training and test scores are much closer.
-- Based on this (and the limited data set in this exercise), I would need to do more feature analysis to improve the score and reduce overfitting.
-- But given the choice of both model outputs, I'd be more included to use the Logistic Regression model with 'new' data for prediction.
---
Assignment comleted by Louis Canjar

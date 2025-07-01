# Predicting Health Risks, Stay Healthy, Stay Ahead!

![img alt](https://github.com/Melina28072010/Predicting-Health-Risks-Stay-Healthy-Stay-Ahead/blob/8ec6a09b212ec41be9cc48bd719667346d04de25/Image%20of%20Health%20Risks.gif)
# Dataset:
• [Heart Attack Prediction Dataset](https://drive.google.com/file/d/1KVsmdFNsy8x3pqYsxlN1V-RJvV9aRgRI/view?usp=drivesdk)
# Problem Statement:
Health issues like heart disease, diabetes, and obesity are on the rise, and understanding how lifestyle choices impact these conditions is more important than ever. Early prediction of health risks can help people make better choices and lead healthier lives.



# Steps
• Data Cleaning: Handle missing values and standardize lifestyle-related variables.

• EDA: Explore correlations between lifestyle factors (e.g., smoking, exercise) and health outcomes (focus on heart disease).

• Feature Engineering: Create aggregated health indices, lifestyle scores, and demographic profiles.

• Modeling:
Implement logistic regression and kNN classification to predict health risks.
Use tree-based models to understand the impact of various lifestyle factors.

• Evaluation: Use metrics like precision, recall, and ROC-AUC for model evaluation.

• Insights: Identify key lifestyle factors associated with health risks and suggest preventive measures.

# Milestone 1
This was a document including our core problem and how we were initially going to solve it.
Basically, the document was 2 pages of methodology (the steps included above), our dataset and how we were planning to evaluate it
and the core problem statement "Health issues like heart disease, diabetes, and obesity are on a rise, 
and understanding how life choices impact these conditions are more important than ever."

# Milestone 2
In this milestone, we managed to bind a PowerPoint explaining each step above individually and how we are planning to use them to solve our problem.
In addition, our innovation was added and why we picked this problem statement initially as we were confident that tackling this problem was possible.
As we're both extremely interested in medicine we thought that this would be the ideal project to work on and that would stimulate our ability to work
more efficiently as a group.

# Milestone 3
Milestone 3.1: In this part of our project we managed to create a Google colab notebook including our dataset cleaned and we managed to visualize it in different forms
(bar charts, line graphs, pie charts, scatter plots). We basically encountered what we're dealing with and what we will take into account (e.g it's classification
or a regression problem).

Milestone 3.2: Here we presented an elongated Powerpoint explaining our problem once again. Also, our data analysis from milestone 3.1 and what we've learned from it with advantages added on every visualization. Last of all, our adjustments that we've made until this point.

# Milestone 4
Here we implemented baseline models into our code with their evaluations respectively. The models we presented were kNN (k-nearest neighbors), logistic regression and a decision tree (classification). To add to that, we provided loss functions for each such as binary cross entropy, Mean Squared Error (MSE) and Gini Index to evaluate how well our models are performing. Lastly, we further evaluated each model's accuracy using Accuracy, Precision, Recall, F1score and a Confusion Matrix.

# Milestone 5
In this miledtone we utilized a total of 8 models, these include: Logistic Regression, K-Nearest Neighbors, Decision Tree Classifier, Random Forest, Bagging, XGBoost and AdaBoost. We applied loss functions for each such as binary cross entropy, Mean Squared Error (MSE), Gini Index, Accuracy, Precision, Recall, F1score, a Confusion Matrix and a ROC AUC Curve to evaluate our models and to also compare them to reach the conclusion of which is the best model. Overall, we agreed that the best model was XGBoost with a relatively high accuracy of 0.59. However, there were other models with higher accuracy such as bagging (0.62) and the Decision Tree (0.62). The reason we viewed this as the best model was due to its completeness of having both a decent recall (0.23) and the highest precision (0.39) which lead it having a good F1 score of 0.3 in comparison to our other models. Lastly, it handled complex patters better than other models and had one of the lowest log loss. Unsurprisingly, the worst model was KNN with the lowest accuracy of 0.49. In addition to that, its performance was the lowest for precision (0.34) and somewhat good for recall (0.45) meaning a 0.39 for F1 score. Lastly, it had the most false alarms which isn’t ideal for predicting heart disease.

![image](https://github.com/user-attachments/assets/4c78e020-2e9f-4702-baa0-0f65960d3165)
![image](https://github.com/user-attachments/assets/e7fe26f5-7499-4a30-946b-4ddf79350751)
# ROC AUC Curve
![image](https://github.com/user-attachments/assets/4d96b5c7-e48b-4c3c-844a-7d66c930df40)



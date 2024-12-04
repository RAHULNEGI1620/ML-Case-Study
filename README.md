# ML-Case-Study
Cardiovascular_risk_prediction-
Aim:

Our aim was to use Machine Learning Algorithms to predict who might develop heart disease in the next 10 years using data from a large cardiovascular study in Framingham, Massachusetts.

Process:

Data preprocessing was crucial to ensure the accuracy and reliability of the predictive model. This involved meticulous cleaning, transformation, and management of missing values and outliers within the dataset. To address skewed variables that could potentially impact model performance, appropriate transformations were applied. Additionally, feature selection techniques were employed to mitigate multicollinearity and to create a new feature known as pulse pressure. This process facilitated the identification of the most influential features for predicting CHD risk.

Given the inherent imbalance within the dataset, a strategic approach was adopted to address this challenge.

The Synthetic Minority Over-sampling Technique (SMOTE) combined with Tomek Links Undersampling was implemented to effectively balance the distribution of CHD instances. Furthermore, standard scaling was applied to ensure uniformity across all features, thereby enhancing model performance and interpretability.

Several machine learning models were evaluated based on their recall performance, with emphasis placed on correctly identifying individuals at risk of CHD, even at the expense of some false positives. Following thorough evaluation, the Neural Network model, after appropriate tuning, emerged as the optimal choice due to its superior recall score.

Conclusion:

Our study highlights the potential of using machine learning to predict heart disease risk. By refining data and selecting the right model, we developed a tool that can help identify those at risk early on, enabling more proactive healthcare interventions.

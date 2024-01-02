### Findings

- Original Logistic Regression Model Accuracy (Using all features) = **96.49%**
- Sequential Forward Selection for Optimal 9 Best Features Accuracy = **97.35%**
- Sequential Backward Selection for Optimal 7 Best Features Accuracy = **97.49%**
- Recursive Feature Elimination for Optimal 8 Best Features Accuracy = **99.72%**


### Description and Visuals

In this project, I analyzed data from a survey conducted by Fabio Mendoza Palechor and Alexis de la Hoz Manotas that asked people about their eating habits and weight. The data was obtained from the UCI Machine Learning Repository. Categorical variables were changed to numerical ones to facilitate analysis.

First, I fitted a logistic regression model to try to predict whether survey respondents were obese based on their answers to questions in the survey. After that, I used three different wrapper methods to choose a smaller feature subset.

I used sequential forward selection, sequential backward floating selection, and recursive feature elimination. After implementing each wrapper method, I evaluated and visualized the model accuracy on the resulting smaller feature subsets and compared that with the model accuracy using all available features.


![image](https://github.com/ammaarmelethil/FeatureSelection_WrapperMethods_Project/assets/100314064/1cfde3e7-4c4d-472d-b293-9c88285790af)

![image](https://github.com/ammaarmelethil/FeatureSelection_WrapperMethods_Project/assets/100314064/1a77ebce-dc0c-4878-bebf-be9dc897d274)


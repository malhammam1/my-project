# my-project
**Project Overview:**
This project analyzes mental health conditions within the tech industry, focusing on the factors influencing whether individuals seek treatment for mental health issues. The aim is to provide insights that can assist tech companies in crafting more supportive environments for mental health.

**Hypothesis:**
The primary hypothesis is that individuals with a family history of mental health issues are more likely to seek treatment for their own mental health problems compared to those without a similar family background.

**Dataset Description:**
The dataset originates from a survey targeting individuals in the tech industry across various countries, encompassing variables like Age, Gender, Country, self-employed status, family history of mental health issues, treatment for mental health issues, work interference due to mental health. The data was meticulously cleaned to address missing values, normalize text entries, and eliminate duplicates.

**Methods:**
Two machine learning models were employed to predict the likelihood of individuals seeking mental health treatment:

Logistic Regression: This model was chosen for its simplicity and effectiveness in binary classification tasks, providing a solid baseline for performance comparison.

Random Forest Classifier: Known for handling complex patterns better than logistic regression, this model uses multiple decision trees to prevent overfitting and improve predictive accuracy.

**Model Evaluation:**
The models were assessed using accuracy, precision, recall, and F1-score on a test set. Confusion matrices provided detailed insights into each model's performance, highlighting true positives, false positives, true negatives, and false negatives. 

**Results and Key Takeaways:**

-Both models showed that family history is a significant predictor of seeking treatment. 

- Individuals with a family history of mental health issues are more likely to seek treatment.


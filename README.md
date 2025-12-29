# Random-Forest-Evaluation-of-Sailfort-Motors-Employee-Retention

This project's goal was to use employee data of Sailfort Motors to gain actionable insight on employees who leave, and improve retention. Project using "employee data" to gain actionable insight on employees who leave, and improve retention. Performed EDA and finally used XGBoost to review employee data for strong correlations with employees leaving the company.
The model performed with 97% accuracy and 93% precision determining the most important features.
Years at the company, Satisfaction Level, and Number of Projects were determined to be the most important.

**Data Understanding**
The data consisted of approximately 11,999 employees and 10 features.
Below bar chart shows comparison of employees who stay vs. leave over time.
<img width="562" height="432" alt="image" src="https://github.com/user-attachments/assets/a2d7ec47-090d-4bf2-82a5-900aec8f689a" />

**Modeling and Evaluation**
Random forest model with GridSearchCV using between 200 and 400 estimators was used to identify important features.
<img width="690" height="390" alt="image" src="https://github.com/user-attachments/assets/94cdcc9d-5197-4a3c-9149-9b135b85609d" />

**Conclusion**
This model can help Sailfort Motors HR identify key points to focus on which will improve employee retention.

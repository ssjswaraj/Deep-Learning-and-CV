## Graduate Admission Prediction Using ANN
**dataset** : https://www.kaggle.com/datasets/mohansacharya/graduate-admissions 

### Exploratory Data Analysis (EDA)
* Identified correlations between input and output variables through analysis
* Plotted histograms for 'GRE Score', 'TOEFL Score', 'University Rating', 'SOP', 'LOR', and 'CGPA' to understand their distributions
* Identified a clear positive relationship between GRE scores, TOEFL scores, CGPA, and Chance Of Admission.
* Applicants with research experience tend to have higher GRE scores, TOEFL scores, CGPA, and a greater chance of admission.
  
### Regression Analysis with Artificial Neural Networks (ANNs)
* Used ANN architecture with sigmoid activation function in the final layer
* Achieved an impressive R-squared score of 0.8, indicating the model's strong predictive power.
* Achieved a remarkable mean absolute error (MAE) of 0.04 and Root Mean Squared Error (RMSE) of 0.06 indicating high predictive accuracy

### Binary Classification for Admission Decisions
* Implemented a guideline: applicants with a chance of admission greater than 0.7 were considered accepted
* Attained an impressive 95% recall rate, ensuring effective identification of prospective students likely to be admitted.
  
By using EDA with deep learning, our project not only increases the predictive accuracy of graduate program admissions but also furnishes invaluable insights for person involved in the admissions process.






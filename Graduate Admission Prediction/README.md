## Graduate Admission Prediction Using ANN
**dataset** : https://www.kaggle.com/datasets/mohansacharya/graduate-admissions 

### Exploratory Data Analysis (EDA)
* Identified correlations between input and output variables through analysis
* Plotted detail histograms for 'GRE Score', 'TOEFL Score', 'University Rating', 'SOP', 'LOR', and 'CGPA' to understand their distributions
* Identified a clear positive relationship between GRE scores, TOEFL scores, CGPA, and Chance Of Admission.
* Applicants with research experience tend to have higher GRE scores, TOEFL scores, CGPA, and a greater chance of admission.
  
### Regression Analysis with Artificial Neural Networks (ANNs)
* Used ANN architecture with sigmoid activation function in the final layer
* Achieved an impressive R-squared score of 0.8, indicating the model's strong predictive power.
* Achieved a remarkable mean absolute error (MAE) of 0.04 and Root Mean Squared Error (RMSE) of 0.06 indicating high predictive accuracy

### Binary Classification for Admission Decisions

* Established a threshold of 0.7 for admission likelihood
Delineated applicants as selected or rejected based on this threshold
Attained an impressive 95% recall rate, ensuring effective identification of prospective students likely to be admitted
By seamlessly integrating EDA with advanced deep learning techniques, our project not only enhances the predictive accuracy of graduate program admissions but also furnishes invaluable insights for stakeholders involved in the admissions process.






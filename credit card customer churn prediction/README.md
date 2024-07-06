### Project Description: Credit Card Customer Churn Prediction
**Dataset** : https://www.kaggle.com/datasets/rjmanoj/credit-card-customer-churn-prediction

This project aims to predict customer churn for a bank's credit card services using machine learning techniques. Customer churn prediction is crucial for businesses to understand which customers are likely to leave (churn) so that proactive steps can be taken to retain them. The dataset used for this project contains various customer attributes such as credit score, geography, gender, age, tenure, balance, and more.

#### Data Preprocessing
1. **Data Cleaning**: Dropping unnecessary columns.
2. **Encoding**: Converting categorical variables into numerical using one-hot encoding.
3. **Feature Scaling**: Standardizing numerical features to have a mean of 0 and a standard deviation of 1.

#### Model Development
- **Neural Network Architecture**: Using a Sequential model with three layers:
  - **Input layer**: 8 neurons (equal to the number of features after preprocessing) with `relu` activation function.
  - **Hidden layer**: 3 neurons with `relu` activation function.
  - **Output layer**: 1 neuron with `sigmoid` activation function for binary classification.
- **Compilation**: Using Adam optimizer, binary cross-entropy loss function, and tracking `accuracy` metric.
- **Training**: Training the model on the preprocessed data with a batch size of 30, for 100 epochs, and validating on 20% of the training set.
- **Hyperparameter Tuning**: Further optimize the model's performance by tuning parameters like learning rate, batch size, and number of neurons in hidden layers.

#### Results
The model achieved an accuracy of approximately 86% on the validation set, indicating good performance in predicting customer churn based on the provided features.

This project demonstrates the application of machine learning in predicting customer behavior to support business objectives, specifically focusing on customer retention in the banking sector.

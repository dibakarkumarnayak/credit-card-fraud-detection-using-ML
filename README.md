# credit-card-fraud-detection-using-ML
Credit Card Fraud Detection Workflow
Data Loading and Exploration

Loaded the dataset and explored its structure, summary statistics, and class distribution.
Visualized key features using histograms, scatter plots, and heatmaps to detect patterns.
Preprocessing and Feature Engineering

Checked for missing values (none found).
Standardized features using StandardScaler to improve model performance.
Handled class imbalance with SMOTE to oversample minority (fraudulent) transactions.
Model Building

Split the balanced dataset into training and test sets.
Trained a Logistic Regression model to classify fraudulent and legitimate transactions.
Evaluation Metrics

Evaluated the model using accuracy, recall, precision, ROC-AUC score, and a confusion matrix.
Visualized Precision-Recall and ROC curves to assess model performance.
Feature Importance

Extracted and visualized the coefficients from the logistic regression model to interpret the influence of features.
Model Deployment

Saved the trained model and scaler using joblib for future use.
Next Steps/Improvements
Hyperparameter Tuning: Use GridSearchCV or RandomizedSearchCV to optimize model parameters.
Try Advanced Models: Experiment with ensemble methods like Random Forest or XGBoost for potentially better performance.
Deploy the Model: Build an API using Flask or FastAPI to deploy the fraud detection system.
Real-Time Streaming: Integrate a streaming framework (like Kafka) for real-time transaction monitoring.

![image](https://github.com/user-attachments/assets/7e30df2d-7ea3-4c16-b12a-0eb4fad485cc)


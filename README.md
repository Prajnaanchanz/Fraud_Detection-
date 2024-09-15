Fraud Detection Model
Objective:
This project aims to build a machine learning model to predict fraudulent financial transactions using a dataset containing 6,362,620 rows and 10 columns.

Dataset Overview:
The dataset includes features such as transaction details (oldbalanceDest, newbalanceDest, and nameDest) and fraud indicators (isFraud and isFlaggedFraud). These features were used to train the model and identify potential fraudulent activity.

Project Workflow:

Data Cleaning & Preprocessing:
The data was cleaned by handling missing values and irrelevant features. The balance data and destination names were processed to ensure consistency. Imbalanced classes in fraud detection were tackled using techniques like oversampling or undersampling.

Feature Selection:
We selected relevant features that directly impacted the likelihood of fraud, such as balance discrepancies and transaction destinations. This helped in building a more efficient model.

Model Development:
Various machine learning algorithms were explored, including Random Forest and XGBoost. These models were trained using cross-validation to ensure reliable performance on unseen data. After training, the model with the best performance was selected.

Model Evaluation:
The model was evaluated using metrics such as accuracy, precision, recall, and F1-score. We aimed to reduce both false positives (non-fraudulent transactions marked as fraud) and false negatives (fraudulent transactions missed).

Results:
The final model achieved high accuracy in detecting fraud with minimal false positives, making it a reliable tool for financial transaction monitoring.

Technologies Used:

Languages: Python
Libraries: pandas, scikit-learn, XGBoost
Platform: Google Colab
Future Work:
We plan to explore deep learning techniques and improve the model’s integration into real-time transaction systems. 

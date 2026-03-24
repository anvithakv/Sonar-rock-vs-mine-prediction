# Sonar-rock-vs-mine-prediction
ML model to classify sonar signals

📌##Project Overview
This project uses Machine Learning to classify sonar signals as either:
-Rock (R)
-Mine (M)
The model is trained on sonar signal data where each sample represents reflected sound waves from objects underwater.

📊 ##Dataset Information
-Total Samples: 208
-Features: 60 numerical attributes
-Target:
-R → Rock
-M → Mine
Each feature represents energy values at different frequencies of sonar signals.

⚙️ Workflow
1. Data Loading
  Dataset loaded using Pandas
  Checked for missing values
2. Data Preprocessing
Split into:
  Features (X)
  Labels (y)
Converted labels:
  Rock → 0
  Mine → 1
3. Train-Test Split
  80% training data
  20% testing data
4. Model Training
  Used Logistic Regression
  Model trained on training dataset
5. Evaluation
Accuracy calculated for:
  Training data
  Testing data
6. Prediction System
Custom input is given
Model predicts:
  Rock or Mine

🧠 Technologies Used
Python
NumPy
Pandas
Scikit-learn

📈 Results
Training Accuracy: ~85–90%
Testing Accuracy: ~75–85%





💳 Anomaly Detection in Credit Card Transactions
Project Overview
Financial fraud costs the global economy billions of dollars annually. This project focuses on building a robust Machine Learning pipeline to detect fraudulent credit card transactions in real-time.
The primary challenge addressed here is the extreme class imbalance inherent in financial data (where fraudulent transactions often represent less than 0.2% of the total dataset). This project implements anomaly detection algorithms to minimize false negatives and protect consumer assets.
🚀 Key Features
Advanced Feature Engineering: Scaled features using StandardScaler to handle outliers effectively.
Multiple Model Implementation:
Isolation Forest for unsupervised anomaly detection.
Autoencoders (Deep Learning) for reconstructing normal patterns and flagging deviations.
Performance Metrics: Focused on F1_Score, ROC_AUC Score and Confusion Matrix rather than simple accuracy to ensure fraud is actually caught.
🛠️ Tech Stack
Language: Python 3.x
Data Science: Pandas, NumPy, Scikit-learn.
Deep Learning: TensorFlow / Keras (for Autoencoders).
Visualization: Matplotlib, Seaborn, Plotly.
📊 Results Summary
Best Performing Model: [Isolation Forest]
Recall for Fraud Class: [90%]
ROC AUC Score: [92.6%]

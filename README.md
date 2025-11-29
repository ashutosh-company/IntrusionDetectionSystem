# Intrusion Detection System using Machine Learning

- Intrusion Detection System is a software application that detects network intrusion using various machine learning algorithms. IDS monitors a network or system for malicious activity and protects a computer network from unauthorized access by users, including perhaps insiders. The intrusion detector learning task is to build a predictive model (i.e., a classifier) capable of distinguishing between 'bad connections' (intrusion/attacks) and 'good (normal) connections'.

- Attacks are basically of four types :
  - #DOS: denial-of-service, e.g. syn flood.
  - #R2L: unauthorized access from a remote machine, e.g., guessing password.
  - #U2R: unauthorized access to local superuser (root) privileges, e.g., various ``buffer overflow'' attacks.
  - #probing: surveillance and other probing, e.g., port scanning.

- You can download the dataset used in this project from Kaggle : https://www.kaggle.com/datasets/subho117/intrusion-detection-system-using-machine-learning

- In this project I have used Naive Bayes, Decision Tree, Random Forest, Support Vector Machine, Logistic regression, Gradient Boosting.

- I have followed all the steps required for better results which includes
  - Data Exploration
  - Data Preprocessing
  - Splitting the Dataset
  - Feature Encoding
  - Correlation Analysis
  - Removal of Highly Correlated Features
  - Scaling the Data
  - Model Training and Test Accuracy

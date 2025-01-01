This project demonstrates the use of machine learning for predictive maintenance based on pump sensor data. The goal is to predict the machine status (normal, broken, or recovering) using sensor readings from various sensors attached to pumps. This is a multi-class classification problem where the model helps in predicting when a pump is likely to fail or recover, enabling proactive maintenance.

Key Features:
Data Preprocessing: The dataset includes sensor readings that are preprocessed (standard scaling and label encoding) to make them ready for model training.
Model: The project uses LightGBM (Light Gradient Boosting Machine) for training a model that can predict the status of the machine based on sensor data. The model is specifically trained for multi-class classification, as there are three possible states for the machine: NORMAL, BROKEN, and RECOVERING.
Evaluation: The model is evaluated using various metrics, including accuracy, ROC-AUC, and confusion matrix.  

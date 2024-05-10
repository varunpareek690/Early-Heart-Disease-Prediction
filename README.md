# Early Heart Disease Prediction

## Introduction
This project aims to predict the likelihood of early heart disease using machine learning techniques. The dataset used for this project is obtained from Kaggle and is locally named "dataset". It contains over 70,000 rows and 21 features. The target variable used for predicting is "HeartDiseaseorAttack".

Dataset URL: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

## Data Preprocessing
Before building the machine learning models, the dataset underwent preprocessing steps including:
- **Class Balancing**
- Handling missing values
- Feature scaling

## Machine Learning Models
Two machine learning algorithms were used for prediction:
1. Random Forest Classifier
2. Gradient Boosting Classifier

## Model Evaluation
The models were evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score


## Results
- Random Forest Model:
  - Accuracy: 91.67%
  - Precision: 0.92
  - Recall: 0.91
  - F1 Score: .915

- Gradient Boosting Model:
  - Accuracy: 90.52%
  - Precision: 0.91
  - Recall: 0.90
  - F1 Score: .905
  

## Conclusion
Both Random Forest and Gradient Boosting models showed promising results in predicting early heart disease. Further optimization and fine-tuning of hyperparameters could potentially improve the model performance.

## Future Work
Future work may include:
- Exploring additional machine learning algorithms
- Feature engineering to create new informative features
- Hyperparameter tuning for improved model performance

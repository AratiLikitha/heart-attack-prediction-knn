# Heart Attack Possibility Prediction

Predicts heart attack risk using KNN with hyperparameter tuning.

## Dataset
Kaggle - Health care: Heart attack possibility (303 patients, 14 features)
Link: https://www.kaggle.com/datasets/nareshbhat/health-care-data-set-on-heart-attack-possibility
Note: Dataset not included in repo, download heart.csv from Kaggle

## What I Did
- StandardScaler for scaling
- KNN Classifier (n_neighbors=5)
- GridSearchCV to find best K (tested 3,5,7,9)
- Pipeline for clean workflow
- Train-Test Split (random_state=42)

## Results
- Accuracy: ~86%
- Precision: ~93%
- Recall: ~79%

## Tech Stack
Python, Pandas, Scikit-Learn, GridSearchCV, Pipeline

## Files
- heart_attack_knn.ipynb

## How to Run
1. Download heart.csv from Kaggle link above
2. Place it in same folder as notebook
3. Run notebook

## Author
Pati Likitha

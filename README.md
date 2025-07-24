## 📊 Dataset
- **Features**: Includes fields like `network_packet_size`, `login_attempts`, `ip_reputation_score`, `browser_type`, etc.
- **Target**: Binary classification (`0 = Normal`, `1 = Attack`)

##  Models Used

- ✅ Random Forest
- ✅ XGBoost
- ✅ Logistic Regression

## Feature Selection

- Feature importance was used to select the **top 12 features** for each model.
- Each model's selection is **specific** based on internal scoring (e.g., `.feature_importances_` or `coef_`).

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Cross-Validation Score 

## Visualizations

- Confusion Matrices
- Feature Importance Barplots
- Model Comparison Bar Chart

## 🛠 Tools & Libraries

- Python 3.10+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost
- randomForest
- logistic regression

##  How to Run

1. Clone the repository
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

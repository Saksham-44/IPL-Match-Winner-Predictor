# IPL-Match-Winner-Predictor
IPL Match Winner Predictor using Machine Learning | EDA + RandomForest + XGBoost + Logistic Regression
A machine learning project that predicts the winner of an IPL match based on historical IPL data.
Given match details like teams, venue, toss winner and toss decision, the model predicts which team is likely to win.

## Dataset
IPL Dataset from Kaggle containing two files:
- `matches.csv` — match-level data
- `deliveries.csv` — ball-by-ball data

EDA was performed on both datasets to extract key insights like win rates, top scorers, top wicket takers and venue statistics.

## Models Trained
| Model | Accuracy |
|---|---|
| XGBoost | 53% |
| Random Forest | 49% |
| Logistic Regression | 21% |

XGBoost performed best and was used for the final prediction function.

## How to Run
1. Clone the repository
2. Install dependencies: `pip install pandas scikit-learn xgboost`
3. Open `ipl_predictor.ipynb` in Jupyter Notebook or Kaggle
4. Run all cells in order
5. Call the prediction function:

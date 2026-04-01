# Market Making Hackathon Project

This project explores predicting fair values for 9 stocks using machine learning models.

## Models tested
- Linear Regression
- Ridge
- Gradient Boosting
- XGBoost
- LightGBM

## Approach
- Cross-validation RMSE used as uncertainty
- Best model selected per stock
- Bid/ask quotes produced using fair value ± k * CV RMSE

## Files
- `start_your_submission_here.ipynb`
- `hackathon_data/`

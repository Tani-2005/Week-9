# 🏡 House Price Prediction - Machine Learning Model

## 🎯 Project Overview
This project builds a simple machine learning architecture to forecast house prices based on features including Property Area, Number of Bedrooms, Location, and Property Type using Regression Techniques. 

## 🛠️ Setup Instructions
1. Install Python 3.8 or above.
2. Ensure you have the datasets.
3. Install dependencies: `pip install -r requirements.txt`.
4. Run `house_price_prediction.ipynb` in your Jupyter Environment.

## 📊 Technical Detail & Model Architecture
We explored standard methodologies starting from building basic metrics sequentially to using standard libraries:
* **Train-Test Split**: Implemented using an 80/20 data breakdown strategy.
* **Basic Linear Regression**: Built single-feature mathematical gradient extraction to evaluate data trajectory.
* **Scikit-Learn Modeling**: Evaluated continuous values mapping predictions across multi-variant arrays (`Area`, `Location`, `Property Type`).
* **Random Forest Regressor**: Upgraded logic tracking complex tree dependencies mapping out specific regional variants.

## 📈 Evaluation Matrix
Our testing configurations yield the following data on model prediction behaviors:
### Baseline Linear Regression Model
* **Mean Absolute Error (MAE)**: $2,188,736
* **MSE Metric**: 8,454,330,868,276
* **R² Score**: 0.940

### Optimized Tree Estimator
* **MAE**: $1,493,949
* **R² Score**: 0.971

## 💡 Summary Feature Output
When assessing continuous values, the highest priority elements impacting output valuations are **Property Area (69% Impact)** and regional metrics tied to whether the space is positioned in **Rural Locations (20% Impact)**.

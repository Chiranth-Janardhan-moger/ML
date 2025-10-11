# Product Price Prediction Model

This project predicts product prices using machine learning models. Below is a summary of the training results and feature importance.

---

## 🏋️‍♂️ Model Training

Three different models were trained and evaluated on the dataset:

| Model        | Training MAE | Validation MAE | Validation RMSE | Validation R² |
|-------------|-------------|----------------|----------------|----------------|
| Random Forest | $10.61      | $14.47         | $34.33         | 0.2192         |
| XGBoost      | $12.66      | $14.63         | $34.52         | 0.2103         |
| LightGBM     | $13.70      | $14.84         | $34.49         | 0.2117         |

### 🏆 Best Model
**Random Forest**  
- Validation MAE: $14.47  

---

## 📊 Feature Importance

The top 3 features influencing price prediction:

1. **Brand (12.8%)** – Brand heavily influences the price.  
2. **Total Text Length (11.5%)** – More detailed product descriptions generally result in higher prices.  
3. **Value/Quantity (11.3%)** – Package size significantly affects the price.  

---

## 🔧 Usage

1. Load the trained Random Forest model.  
2. Preprocess the input data (brand, description, value/quantity).  
3. Predict the product price using the model.  

---

## ⚡ Insights

- Brand recognition is a major factor in product pricing.  
- Detailed descriptions contribute positively to the predicted price.  
- Larger packages or higher quantities lead to higher predicted prices.  
# ML

# Car Price Prediction 🚗💰

This project predicts the selling price of used cars using **machine learning regression models** such as Linear Regression, Lasso.  
It helps car dealers, customers, and businesses estimate the fair market price of a car based on key features like year, present price, fuel type, etc.

---

## 🔧 Technologies Used
- **Python 3.x**
- **Pandas, NumPy** → data analysis & preprocessing  
- **Scikit-learn** → ML models & evaluation  
- **Matplotlib, Seaborn** → data visualization  
- **Google Colab** → experimentation & analysis
  
---

## 📊 Dataset
The dataset contains information about used cars with the following features:

- `Year` → Manufacturing year  
- `Present_Price` → Current ex-showroom price (in Lakhs)  
- `Kms_Driven` → Distance driven (in km)  
- `Fuel_Type` → Petrol / Diesel / CNG  
- `Seller_Type` → Dealer / Individual  
- `Transmission` → Manual / Automatic  
- `Owner` → Number of previous owners  

🔹 **Target Variable:** `Selling_Price`

---

## 📈 Results & Evaluation
Example Prediction:
Actual Price: 5.9 Lakhs (when buying the new car)
Predicted Price: 5.53 Lakhs (price after using nad resaling it).

📌 This shows the model is predicting very close to the true value.

---

### Model Performance (on test data)

| Model              | R² Score | MAE   | RMSE  |
|--------------------|----------|-------|-------|
| Linear Regression  | 0.91     | 0.32  | 0.45  |
| Lasso Regression   | 0.89     | 0.36  | 0.49  |

✅ **Linear Regression performed slightly better** on this dataset.

---

## 🔮 Future Work
- Adding more advanced models like (Ridge, Random Forest, XGBoost).  
- Performing hyperparameter tuning for better accuracy.  

  ---

## 🙌 Acknowledgements
Dataset source: [Kaggle / Official Source / Provided Dataset]
Libraries: Scikit-learn, Pandas, Matplotlib
Inspiration: ML regression 

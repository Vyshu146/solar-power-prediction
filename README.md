# ☀️ Solar Power Generation Prediction

## 📌 Overview
This project predicts solar power generation using machine learning models based on weather and environmental parameters. Multiple regression models were implemented and compared to identify the best performing algorithm.

---

## 🚀 Models Implemented
- Random Forest Regressor
- XGBoost Regressor
- Stochastic Gradient Descent (SGD)
- Adam Optimizer based model

---

## 📊 Model Performance

| Model           | RMSE   | R² Score | MSE      |
|----------------|--------|----------|----------|
| Random Forest | 159.06 | 0.75     | 25300.65 |
| XGBoost       | 164.81 | 0.73     | 27161.60 |
| SGD           | 209.38 | 0.56     | 43841.87 |
| Adam          | 169.33 | 0.71     | 28673.17 |

### 🏆 Best Model
Random Forest achieved the highest R² score (0.75) and lowest RMSE among all models.

---

## 📈 Visual Results

### Actual vs Predicted
<img src="screenshots/actual-vs-predicted.png" width="700"/>

---

### Feature Importance
<img src="screenshots/feature-importance.png" width="700"/>

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn

---

## 📂 Dataset Features
- Radiation
- Temperature
- Pressure
- Humidity
- Wind Direction
- Wind Speed
- Sunrise & Sunset Time
- Hour

---

## 💡 Key Concepts Implemented
- Data Preprocessing
- Feature Engineering
- Model Training & Evaluation
- Performance Comparison
- Regression Metrics (RMSE, MSE, R²)

---

## 👩‍💻 Author
Lepakshi Vyshnavi  
Integrated M.Tech CSE | VIT-AP University

# 🏠 House Price Prediction Using Linear Regression

This project demonstrates a basic machine learning workflow using **Linear Regression** to predict house prices based on square footage. Built using Python and Scikit-learn in a Jupyter Notebook environment.

---

## 📁 Dataset

- **File**: `house_price_data.csv`
- **Features**:
  - `SqFt Area`: Total area of the house in square feet (independent variable)
  - `Price (INR in Lakhs)`: Selling price of the house (target variable)

---

## 🔧 Features Implemented

1. **Data Loading**
2. **Data Cleaning**
   - Checked for missing values
   - Removed outliers using IQR method
3. **Data Preparation**
   - Feature-label separation
   - Train/test split (80/20)
4. **Model Building**
   - Trained Linear Regression model using `scikit-learn`
5. **Evaluation Metrics**
   - MSE, RMSE, R² Score
6. **Visualization**
   - Actual vs Predicted house price plot

---

## 📊 Evaluation Results

| Metric | Value |
|--------|-------|
| MSE    | ~45.67 |
| RMSE   | ~6.76  |
| R²     | ~0.89  |

---

## 📈 Visualization

![Actual vs Predicted Plot](preview.png)

> 📌 *Make sure to replace this with an actual image or notebook screenshot if needed.*

---

## 📚 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

---

## 💡 Future Improvements

- Add more features: Location, age, number of rooms, etc.
- Use polynomial regression or decision trees for complex patterns
- Apply K-Fold Cross Validation
- Build a frontend for user input and price prediction

---

## 🧠 Author

Developed as part of a learning project to understand **regression-based prediction** in machine learning using Python and Jupyter.


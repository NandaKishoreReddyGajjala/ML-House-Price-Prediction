# House Price Prediction using Linear Regression and Random Forest Regressor

## 📌 Project Overview
This project aims to predict **house prices in California** using **Linear Regression** and **Random Forest Regressor**. The dataset used is the **California Housing Dataset (housing.csv)**. The goal is to build a machine learning model that accurately predicts the **median house value** based on various housing features like population, median income, and proximity to the ocean.

---

## 🛠️ Tech Stack
- Python
- Pandas
- Numpy
- Scikit-Learn
- Seaborn
- Matplotlib

---

## 📂 Dataset Description
The **housing.csv** dataset contains 10 columns:
- **longitude**: Geographical coordinate
- **latitude**: Geographical coordinate
- **housing_median_age**: Median age of houses
- **total_rooms**: Total number of rooms
- **total_bedrooms**: Total number of bedrooms
- **population**: Population in the area
- **households**: Number of households
- **median_income**: Median income of residents
- **median_house_value**: Target variable (House price)
- **ocean_proximity**: Proximity to the ocean

---

## 🏁 Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Converting categorical data to numerical using one-hot encoding
- Applying **log transformation** to handle skewed data
- Feature engineering to create new features:
  - **bedroom_ratio**: total_bedrooms / total_rooms
  - **household_rooms**: total_rooms / households

### 2. Exploratory Data Analysis (EDA)
- Heatmap to check feature correlations
- Visualizing the distribution of features

### 3. Model Building
- **Linear Regression**
- **Random Forest Regressor**

### 4. Model Evaluation
- **Mean Squared Error (MSE)**
- **R-squared Score (R²)**

---

## 🔥 Results
| Model                 | R-Squared Score |
|----------------|------------------|
| Linear Regression | 64%          |
| Random Forest Regressor | 80%          |

---

## 📖 How to Run the Project
1. Clone the repository:
```bash
https://github.com/your-repo/house-price-prediction.git
```
2. Install the required libraries:
```bash
pip install pandas numpy seaborn scikit-learn matplotlib
```
3. Run the script:
```bash
python house_price_prediction.py
```

---

## 📈 Visualizations
- Correlation Heatmap
- Histogram Distribution

---

## 🧐 Future Improvements
- Hyperparameter tuning
- Feature scaling
- Deploying the model using Flask/FastAPI

---

## 🎯 Conclusion
The **Random Forest Regressor** performed better with an **80% R-squared score**, capturing more complex relationships between features compared to **Linear Regression (64%)**.

---

## 👨‍💻 Author
**Nanda Kishore Reddy Gajjala Venkata**

GitHub: [nandakishorereddygv](https://github.com/nandakishorereddygv)

LinkedIn: [Nanda14](https://linkedin.com/in/Nanda14)

---


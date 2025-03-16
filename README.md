
---

# 💎 Diamonds Price Prediction

## 📊 Overview

This project is a **machine learning model** designed to predict diamond prices based on their characteristics. It utilizes data analysis, feature engineering, and regression models to create an effective price predictor for diamonds using the **Diamonds dataset** (commonly available via Kaggle, HuggingFace and Seaborn).

The notebook contains a complete pipeline: from data loading and preprocessing to training, evaluation, and visualization of the model's performance.

---

## 🚀 Project Structure

- **Data Analysis**: Exploration of the Diamonds dataset to understand the distribution and correlation of features like carat, cut, color, clarity, depth, table, x, y, z, and price.
- **Data Cleaning & Preprocessing**: Handling outliers, missing values, and encoding categorical variables.
- **Feature Engineering**: Creation of new features and selection of relevant attributes to improve model performance.
- **Model Training**: Training of various regression models (e.g., Linear Regression, Random Forest, Gradient Boosting).
- **Evaluation**: Model performance evaluation using metrics like RMSE, MAE, and R².
- **Visualization**: Graphical analysis of predictions vs. real prices and feature importance.

---

## 🛠 Technologies Used

- **Python** (Jupyter Notebook)
- **Pandas & NumPy** – Data manipulation and analysis
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning algorithms and model evaluation

---

## 📂 Dataset

The dataset includes the following features:

| Feature | Description                |
|--------|---------------------------|
| carat  | Weight of the diamond (carat) |
| cut    | Quality of the cut (Fair, Good, Very Good, Premium, Ideal) |
| color  | Diamond color (from J (worst) to D (best)) |
| clarity| Diamond clarity (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)) |
| depth  | Total depth percentage (z / mean(x, y)) |
| table  | Width of top of diamond relative to widest point |
| price  | Price in US dollars ($326–$18,823) |
| x      | Length in mm |
| y      | Width in mm |
| z      | Depth in mm |

---

## 🔑 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/milosz-amg/Diamonds_Price_Prediction.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd diamonds-price-prediction
   ```
3. **Open Jupyter Notebook**:
   ```bash
   jupyter notebook Diamonds_price_prediction.ipynb
   ```
4. **Run all cells** to see the analysis and model output.

---

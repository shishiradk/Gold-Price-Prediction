# 🟡 Gold Price Prediction

This project predicts gold prices using historical financial data with a **Random Forest Regressor**. The workflow includes data preprocessing, exploratory data analysis, model training, and evaluation—all implemented in a Jupyter Notebook using Python.

---

## 📁 Project Structure

The notebook follows a structured approach:

1. **Import Libraries**  
   Importing required libraries like `pandas`, `numpy`, `matplotlib`, etc.

2. **Data Collection & Processing**  
   - Load dataset  
   - Handle missing values  
   - Prepare features and target variable

3. **Exploratory Data Analysis (EDA)**  
   - Analyze correlations (positive/negative)  
   - Visualize key insights

4. **Data Splitting**  
   - Split into features (`X`) and target (`y`)  
   - Perform train-test split

5. **Model Training**  
   - Train a `RandomForestRegressor` on the training data

6. **Model Evaluation**  
   - Calculate R² score  
   - Visual comparison of actual vs. predicted prices

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 📈 Results

The trained model is evaluated using R² score and prediction plots to visualize how well the model performs on test data.

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

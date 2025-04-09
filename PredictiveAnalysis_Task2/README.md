# Big Data Analysis - Task 1
# 📊 Predictive Analysis – Task 2

This task focuses on building predictive models using machine learning techniques to analyze NYC taxi data. The objective is to predict **fare amount** and **tip amount** using features like distance, passenger count, and trip time.

---

## ✅ Task Objectives

- Load and preprocess the NYC Taxi dataset
- Perform exploratory data analysis (EDA)
- Train machine learning models to predict:
  - 🚕 **Fare Amount**
  - 💰 **Tip Amount**
- Evaluate model performance using:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - R² Score
- Save and export trained models (`.pkl` files)

---

## 📁 Dataset

- Dataset used: processed_nyc_taxi_data.parquet(which is come from task1 implementation)
- Format: `.csv`
- Size: 1 Crore records 

---

## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib & Seaborn (for visualization)

---

## 📌 Key Files

| File Name                   | Description                                     |
|----------------------------|-------------------------------------------------|
| `predictive_analysis.ipynb`| Jupyter Notebook with model training code       |
| `fare_prediction_model.pkl`| Saved model for predicting fare amount          |
| `tip_prediction_model.pkl` | Saved model for predicting tip amount           |
| `sample_nyc_taxi_data.csv` | Sample dataset used for quick testing           |

---

## 📈 Model Performance (Sample)

| Metric        | Fare Prediction | Tip Prediction |
|---------------|------------------|----------------|
| MAE           | ~2.10            | ~0.95          |
| RMSE          | ~4.90            | ~1.35          |
| R² Score      | 0.86             | 0.91           |

---

## 📥 Future Improvements

- Deploy models using Flask/FastAPI
- Create a Streamlit UI for predictions
- Improve feature engineering with datetime parsing
- Experiment with advanced models (e.g., XGBoost, LSTM)

---

## 🙋 Author

**Vyshnavi Gopireddy**  
[GitHub Repository](https://github.com/vyshnavigopireddy/big-data-taxi-analysis)

---

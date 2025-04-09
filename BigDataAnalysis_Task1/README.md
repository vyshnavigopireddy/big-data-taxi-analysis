# Big Data Analysis - Task 1
# 📊 Big Data Analysis - Task 1

This task focuses on analyzing large-scale NYC Taxi data using **Dask**, a powerful parallel computing library in Python. The dataset is over 7.5 GB in size, making it ideal for big data processing techniques.

---

## ✅ Objective

- Efficiently load and process a large CSV file using Dask
- Extract and transform relevant features
- Generate a sample dataset for further analysis

---

## 🗃️ Dataset Details

- **Dataset Name:** NYC Taxi Trip Records (Processed)
- **Size:** ~7.5 GB (full), 1 crore rows (~1.8 GB) sample
- **Source:** (https://www.kaggle.com/datasets/vyshnavisrinivas/proccessed-nyc-taxi-datacsv)
- https://www.kaggle.com/datasets/vyshnavisrinivas/nyc-taxi-processed-dataset
https://www.kaggle.com/datasets/praveenaparimi/nyc-taxi

---

## 📌 Key Steps Performed

1. Loaded the 7.5 GB CSV file using Dask
2. Converted pickup and dropoff timestamps to datetime format
3. Extracted hour and weekday from pickup time
4. Calculated trip duration in minutes
5. Created a 1 crore row sample using Pandas for further usage
6. Exported cleaned sample for Task 2 and visualization tools

---

## 🧰 Technologies Used

- Python
- Dask
- Pandas
- Jupyter Notebook

---

## 📁 Files Included

- `big_data_analysis.ipynb` - Main notebook with Dask implementation
- `sample_nyc_taxi_data.csv` - 1 crore row sample extracted for further tasks
- `README.md` - Task summary and documentation

---

## 📍 Next Steps

Proceed to:
- [Task 2 - Predictive Analysis](../PredictiveAnalysis_Task2)
- [Task 3 - Dashboard in Tableau](../dashboard_task3)

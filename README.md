# Customer Segmentation Using K-Means Clustering

This project uses the **K-Means Clustering algorithm** to segment retail customers based on their purchase behavior. It helps identify different types of customers using **Annual Income** and **Spending Score**, which can assist businesses in targeted marketing and customer retention strategies.

## 📁 Dataset

- **Source**: [Kaggle - Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **File Used**: `Mall_Customers.csv`

## 📊 Features Used for Clustering

- `Annual Income (k$)`
- `Spending Score (1-100)`

> Optionally, more features like `Age` and `Gender` can be included for advanced clustering.

## 🔍 Project Workflow

1. Load and explore the dataset
2. Select relevant features
3. Scale the data
4. Use the **Elbow Method** to determine the optimal number of clusters
5. Apply the K-Means algorithm
6. Visualize the resulting customer segments

## 📌 Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
# PRODIGY_ML_02

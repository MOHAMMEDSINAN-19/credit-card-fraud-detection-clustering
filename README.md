# credit-card-fraud-detection-clustering
Credit Card Fraud Detection using K-Means Clustering with data preprocessing, exploratory data analysis (EDA), feature scaling, PCA visualization, and performance evaluation.

# 💳 Credit Card Fraud Detection using K-Means Clustering

## 📌 Project Overview
This project demonstrates how **K-Means Clustering**, an unsupervised machine learning algorithm, can be used to identify potentially fraudulent credit card transactions. The project includes data preprocessing, exploratory data analysis (EDA), feature scaling, dimensionality reduction using PCA, clustering, and performance evaluation.

---

## 🎯 Objectives
- Load and explore the credit card transaction dataset.
- Perform data preprocessing and cleaning.
- Analyze transaction patterns using Exploratory Data Analysis (EDA).
- Scale numerical features for better clustering performance.
- Apply K-Means Clustering to group similar transactions.
- Visualize clusters using Principal Component Analysis (PCA).
- Evaluate clustering performance and interpret results.

---

## 📂 Dataset
The dataset contains anonymized credit card transaction records, including legitimate and fraudulent transactions.

**Features include:**
- Time
- Amount
- Principal Components (V1–V28)
- Class (0 = Legitimate, 1 = Fraud)

> **Note:** The dataset is highly imbalanced, making fraud detection a challenging task.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. K-Means Clustering
6. Elbow Method for Optimal Clusters
7. PCA Visualization
8. Cluster Analysis
9. Model Evaluation

---

## 📈 Results

- Successfully grouped similar credit card transactions using K-Means Clustering.
- Visualized transaction clusters using PCA.
- Compared clusters with actual fraud labels for analysis.
- Demonstrated the application of unsupervised learning for anomaly detection.

---

## 📁 Repository Structure

```
Credit-Card-Fraud-Detection-Clustering/
│
├── credit card.ipynb
├── README.md
└── dataset.csv
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/credit-card-fraud-detection-clustering.git
```

2. Navigate to the project folder

```bash
cd credit-card-fraud-detection-clustering
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all cells.

---

## 📸 Sample Output

- Data Distribution
- Correlation Heatmap
- Elbow Curve
- PCA Cluster Visualization
- Cluster Analysis

---

## 🚀 Future Improvements

- Implement DBSCAN for anomaly detection.
- Compare multiple clustering algorithms.
- Use Autoencoders for advanced fraud detection.
- Deploy the model as a web application using Streamlit.

---

## 👨‍💻 Author

**Mohammed Sinan**

Machine Learning & Data Science Enthusiast

---

## ⭐ If you found this project useful, please consider giving it a Star!

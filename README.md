# mall-customer-segmentation
Customer segmentation using KMeans clustering and visualization techniques.
# 🛍️ Mall Customer Segmentation with KMeans

Unsupervised learning project to group mall customers based on spending behavior and demographics using KMeans clustering.

## 📊 Dataset
- **Source**: Kaggle - Mall Customer Segmentation Dataset
- **Columns**:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

## 🔍 Exploratory Data Analysis (EDA)
- Distribution plots of Age, Income, and Spending Score
- Countplot of Gender distribution
- Scatterplots of customer clusters
- Elbow method to determine optimal `k`

## 🧠 Unsupervised Learning
- Used **KMeans clustering**
- Applied the **Elbow method** and **Silhouette score** for cluster selection
- Final visualization shows clear customer groups based on income vs. spending

## 📈 Results
- Best `k`: 5 clusters
- Segmentation based on:
  - Low spenders with low income
  - High spenders with high income
  - Middle-tier customers
  - Targetable high-spending groups

## 🧠 Skills Used
- EDA with Seaborn/Matplotlib
- Clustering with Scikit-learn
- Unsupervised learning concepts
- Cluster visualization and interpretation

---

🔗 **Kaggle Notebook**:  
[Mall Customer Segmentation with KMeans](https://www.kaggle.com/code/mahmoudehab6677/mall-customer-segmentation-kmeans)

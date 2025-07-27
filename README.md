# Mall Customer Segmentation

This project clusters mall shoppers into 4 segments using PCA + K-Means, then profiles them for marketing use.

## Dataset

- Source: [Kaggle](https://www.kaggle.com/datasets/shwetabh123/mall-customers)
- 200 customers with: Gender, Age, Income (k$), Spending Score (1–100)

## Techniques Used

- StandardScaler
- PCA (2 components)
- KMeans clustering (K=4)
- Elbow & Silhouette score selection

## Folder Structure

mall-customer-segmentation/
├── data/raw/Mall_Customers.csv
├── notebooks/01-eda.ipynb
├── marketing_playbook.md
├── requirements.txt
├── README.md


## Segment Examples

- **Cluster 0:** High-income young men (Premium targeting)
- **Cluster 3:** Young low-income women who spend big (Deal hunters)
- **Cluster 2 & 1:** Older, low-spending groups (Frugal or unengaged)

## Run
pip install -r requirements.txt

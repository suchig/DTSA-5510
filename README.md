# Customer Segmentation using Unsupervised Learning
The objective of this work is to cluster customers into segments using Unsupervised Learning. The data will be analyzed through Exploratory Data Analysis (EDA), cleaned and various types of unsupervised algorithms will be applied to cluster the segments.

## Data
The data used is from https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python. It can also be found under data folder

Data Fields:
1. Customer ID - Unique Identification of Customers
2. age - Age of customer
3. gender - Gender of Customer (Male or Female)
4. Annual Income - Income in K$
5. Spending score - Score depicting how much Customer spends - Between 1 to 100. 

## Models
- KMeans 
- Agglomerative
- DBScan

## Metrics
| Model  | Silhouette Score |
| ------ | ------ |
| KMeans with 5 clusters | 0.44 |
| Agglomerative with 5 clusters | 0.44 |
| DBScan with 5 clusters | 0.18 |

# Project 8: Customer Segmentation

## Objective

The objective of this project is to segment customers into meaningful groups using K-Means Clustering. Customer segmentation helps businesses understand customer behavior, identify similar customer groups, and develop targeted marketing strategies.

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

**Number of Records:** 7,043

The dataset contains customer demographic information, account details, subscribed services, and billing information.

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Data Preprocessing
5. Feature Scaling
6. Determine Optimal Number of Clusters using the Elbow Method
7. Apply K-Means Clustering
8. Analyze Customer Segments
9. Generate Business Insights

---

## Machine Learning Technique

* Unsupervised Learning
* K-Means Clustering

---

## Data Preprocessing

The following preprocessing steps were performed:

* Replaced blank values with missing values
* Converted `TotalCharges` to numeric format
* Filled missing values using the median
* Removed `customerID`
* Encoded categorical variables
* Standardized features using `StandardScaler`

---

## Results

* Applied the Elbow Method to determine the optimal number of clusters.
* Selected **4 clusters** for customer segmentation.
* Successfully grouped customers based on similar characteristics.

---

## Business Insights

The customer segmentation process identified four different customer groups.

These segments can help businesses:

* Design targeted marketing campaigns
* Improve customer engagement
* Personalize promotional offers
* Increase customer retention
* Support business decision making

---

## Skills Learned

* Unsupervised Learning
* Customer Segmentation
* K-Means Clustering
* Elbow Method
* Feature Scaling
* Data Preprocessing
* Business Interpretation

---

## Project Structure

```
08-Customer-Segmentation/
│
├── data/
├── images/
├── notebooks/
├── outputs/
├── reports/
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Future Improvements

* Experiment with DBSCAN clustering
* Experiment with Hierarchical Clustering
* Visualize customer clusters using PCA
* Compare different clustering algorithms
* Build customer personas for each segment

---

## Author

**Manan Paliwal**

AI & Machine Learning Student

Birla Institute of Technology, Mesra

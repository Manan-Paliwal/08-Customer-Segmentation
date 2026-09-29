# Customer Segmentation — Telco Data

An unsupervised-learning project that applies **K-Means clustering** to customer attributes from the IBM Telco Customer Churn dataset.

## Objective

Group customers with similar characteristics into segments that can be explored for differences in service usage, billing, and customer behavior.

## Dataset

| Attribute | Value |
|---|---:|
| Dataset | IBM Telco Customer Churn |
| Records | 7,043 |
| Learning Type | Unsupervised |
| Selected Clusters | 4 |

## Data Preparation

The workflow includes:

- Converting `TotalCharges` to numeric
- Handling missing values
- Removing `customerID`
- Encoding categorical variables
- Standardizing features

## Method

1. Prepare customer features
2. Scale the data
3. Apply the Elbow Method
4. Train K-Means
5. Assign customers to clusters
6. Analyze the resulting segments

## Result

The project selected **4 clusters** and grouped customers based on similarities across the prepared feature space.

## Skills Demonstrated

- Unsupervised learning
- K-Means
- Feature preprocessing
- Feature scaling
- Elbow Method
- Customer segmentation
- Business interpretation

## Limitations

Cluster assignments are exploratory rather than ground-truth labels. Their value depends on whether the groups are stable, interpretable, and actionable in a real business setting.

## Future Improvements

- Evaluate silhouette score and cluster stability
- Compare DBSCAN and hierarchical clustering
- Use PCA / UMAP for visualization
- Profile each cluster in more detail
- Develop clearer customer personas

---

**Author:** Manan Paliwal  
B.Tech Computer Science Engineering — Artificial Intelligence & Machine Learning
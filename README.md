# Customer-Segementation-Mall-Customers
This project is a part of Mall Customer Segmentation Data competition held on Kaggle.  The goal of K means is to group data points into distinct non-overlapping subgroups. One of the major application of K means clustering is segmentation of customers to get a better understanding of them which in turn could be used to increase the revenue of the company.

## References-

1. https://en.wikipedia.org/wiki/K-means_clustering

2. https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html


## 🎯 Project Objectives

- Identify customer groups with similar characteristics
- Explore customer income and spending patterns
- Support data-driven customer segmentation
- Demonstrate unsupervised machine learning using K-Means clustering

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Methodology

1. Load and inspect the mall customer dataset.
2. Clean the data and explore relevant features.
3. Perform exploratory data analysis (EDA) using visualizations.
4. Apply K-Means clustering to group similar customers.
5. Visualize the resulting customer segments and interpret their characteristics.

## 📊 Evaluation

The number of clusters can be explored using the Elbow Method. The Silhouette Score can also help assess how well-separated the clusters are. Actual results depend on the dataset and selected features.

## 💼 Business Applications

- Understand customer spending behaviour
- Identify customer groups for targeted marketing
- Support customer engagement and loyalty strategies
- Help businesses explore potential customer segments

## 🚀 Future Improvements

- Compare different clustering algorithms
- Add interactive visualizations and a dashboard
- Experiment with additional customer features
- Provide clearer descriptions of each customer segment
- Evaluate clustering quality using appropriate metrics

## ⚠️ Limitations

Customer segments depend on the selected features, preprocessing steps, and number of clusters. Clustering results indicate patterns in data and should not be treated as definitive customer labels.

## Experimentation Checklist

- Inspect feature distributions and standardize features when appropriate before distance-based clustering.
- Use the Elbow Method as one exploratory aid and compare candidate cluster counts with the Silhouette Score.
- Profile each cluster using the original feature units so that segment descriptions remain interpretable.
- Check whether the segment patterns remain reasonably stable when the random seed or sample changes.

## Interpretation

K-Means assigns groups based on the selected features and distance measure. Segment labels are descriptive and should not be treated as fixed customer identities or as proof of purchasing intent.

## Project Development Notes

Standardize numeric features before distance-based clustering, compare candidate cluster counts, and profile segments in original units. Treat clusters as exploratory patterns.

For reproducible updates, record the dataset or upstream version, environment and dependency versions, configuration, and actual outputs from each run. Keep illustrative examples clearly labelled and never commit credentials or private data.

### Technical Deep Dive

K-Means minimizes within-cluster squared distances, so numeric features with larger scales can dominate the result. Standardize selected features, compare several values of `k` using inertia and silhouette score, and inspect cluster profiles using the original feature units. Cluster identifiers are arbitrary labels; interpret the segment characteristics rather than treating a numeric cluster ID as a customer category.

Suggested engineering checks: test stability across random seeds, document the exact features used, and avoid claims about customer intent that are not supported by the data.

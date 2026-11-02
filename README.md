# Mall Customer Segmentation

An unsupervised-learning project that uses customer attributes and K-Means clustering to explore groups with similar spending behaviour.

## Objectives
- Explore customer income and spending patterns.
- Identify groups with similar characteristics.
- Visualize clusters and interpret their profiles.
- Demonstrate a practical use of unsupervised learning.

## Workflow
1. Load and inspect the customer dataset.
2. Explore feature distributions and relationships.
3. Select and prepare clustering features.
4. Use the Elbow Method to investigate cluster count.
5. Fit K-Means and visualize the segments.
6. Review cluster profiles and limitations.

## Technology
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook

## Getting started
```bash
git clone https://github.com/Ravi506051/Mall-Customer-Segementation-master.git
cd Mall-Customer-Segementation-master
python -m venv .venv
# Windows: .venv\\Scripts\\activate
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

## Evaluation
Use the Elbow Method as an exploratory aid and consider the Silhouette Score. Cluster quality also requires interpretation in the context of the selected features and business question.

## Future work
Compare clustering settings, standardization strategies and alternative algorithms. Add a concise segment profile with sample counts and average feature values.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

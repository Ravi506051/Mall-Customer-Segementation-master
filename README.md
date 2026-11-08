# Mall Customer Segmentation

An unsupervised machine-learning project that applies K-Means clustering to explore customer groups with similar income and spending behaviour.

## Objectives
- Explore customer income and spending patterns.
- Identify groups with similar feature profiles.
- Visualize clusters and interpret segment characteristics.
- Demonstrate an unsupervised-learning workflow for customer analytics.

## Workflow
1. Load and inspect the customer dataset.
2. Explore feature distributions and relationships.
3. Select and prepare clustering features.
4. Use the Elbow Method to explore candidate cluster counts.
5. Fit K-Means and visualize the resulting segments.
6. Profile clusters and discuss their limitations.

## Technology
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook

## Setup
```bash
git clone https://github.com/Ravi506051/Mall-Customer-Segementation-master.git
cd Mall-Customer-Segementation-master
python -m venv .venv
# Windows: .venv\Scripts\activate
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

## Evaluation
Use the Elbow Method as an exploratory aid and consider the Silhouette Score. Cluster quality should also be assessed by examining cluster sizes, feature profiles, and whether the segments are meaningful for the intended business question.

## Future Improvements
Compare scaling strategies and alternative clustering algorithms. Add a segment summary with sample counts, feature averages, and actionable interpretations.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

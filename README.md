# Mall Customer Segmentation

A notebook-based K-Means project exploring customer groups using annual income and spending behavior.

## Project workflow

The notebook explores the customer dataset, examines candidate cluster counts with the Elbow Method, fits K-Means, and visualizes groups for interpretation.

## Data and files

- Mall_Customers.csv — customer records used by the notebook.
- Jupyter notebook — exploration and clustering workflow.
- Image assets — visual materials included with the project.

Open the notebook and confirm its CSV path before running. Cluster IDs are arbitrary labels, not rankings. Compare cluster sizes and feature profiles; treat groups as exploratory patterns.

## Run locally

~~~bash
git clone https://github.com/Ravi506051/Mall-Customer-Segementation-master.git
cd Mall-Customer-Segementation-master
python -m venv .venv
# Windows: .venv\Scripts\activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
~~~

## Maintainer

Ravi Kumar Rao · [GitHub](https://github.com/Ravi506051)

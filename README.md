# WEEK-4-TASK
Unsupervised Learning & Customer Segmentation

## Project Overview

This project applies **unsupervised machine learning** techniques to segment credit card customers based on their financial behavior. Using clustering algorithms, customers are grouped into meaningful segments that can support targeted marketing, customer relationship management, and business decision-making.

---

## Dataset

* **Dataset:** Credit Card Dataset for Clustering
* **Source:** Kaggle
* **Records:** ~9,000 credit card customers
* **Features:** Balance, purchases, credit limit, cash advance, payment behavior, purchase frequency, tenure, and more.

---

## Project Workflow

* Loaded and explored the dataset
* Removed the `CUST_ID` column
* Handled missing values using median imputation
* Standardized features with `StandardScaler`
* Applied **K-Means Clustering**
* Used the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters
* Profiled and interpreted customer segments
* Applied **Hierarchical Clustering** and generated a dendrogram
* Compared Hierarchical Clustering with K-Means using cross-tabulation

---

## Results

The analysis identified **three customer segments**:

* **High Spenders** – Frequent purchases, high credit limits, and regular payments.
* **Low Activity Customers** – Lower balances, fewer transactions, and lower spending.
* **Cash Advance Users** – High cash advance usage with fewer purchase transactions.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Jupyter Notebook

---

## Repository Structure

```text
WEEK-4-TASK/
│
├── data/
├── notebooks/
│   └── week4_clustering.ipynb
├── requirements.txt
└── README.md
```

---

## How to Run

```bash
git clone https://github.com/hania-sajjad/WEEK-4-TASK
cd WEEK-4-TASK
pip install -r requirements.txt
jupyter notebook
```

Open **`notebooks/week4_clustering.ipynb`** and run all cells.

---

## Author

**Hania Sajjad**
Intern at ITSimplera Solutions

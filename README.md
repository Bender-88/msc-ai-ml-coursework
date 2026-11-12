# MSc AI & ML Coursework (University of Hull)

Notebooks from my MSc in Artificial Intelligence and Machine Learning. Outputs are saved in the notebooks, so they can be read without re-running.

The coursework data is provided by the university and is **not included** in this repo. To re-run a notebook, place the dataset files named below next to it.

## Module 1: Data cleaning and EDA (Global Superstore)
`module-1-superstore/Superstore_Data_Cleaning_EDA.ipynb`

Cleaning, missing-value handling, outlier treatment and exploratory analysis of retail sales data with pandas, matplotlib and SciPy.
Example finding: Discount and Profit are negatively correlated overall (r = -0.495) and within every Category (Furniture -0.639, Technology -0.501, Office Supplies -0.483).

## Module 2: Machine learning
`module-2-ml/Task1_RandomForest_and_Task2_CNN.ipynb` (needs `dataset1.xlsx` and `dataset2.zip`)

| Task | Problem | Model | Result (from the saved notebook output) |
|---|---|---|---|
| 1 | Tabular binary classification, mixed numeric, categorical and datetime features | Random Forest (scikit-learn) | accuracy 0.962, ROC-AUC 0.982, precision 1.000, recall 0.924 |
| 2 | Multi-label classification of images containing three handwritten digits | CNN (PyTorch) | 0.9815 exact match, about 99.4% per digit |

## Stack
Python, pandas, NumPy, SciPy, matplotlib, scikit-learn, PyTorch.

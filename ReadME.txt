# Pandas DataFrame Learning and Practice

This repository documents my hands-on learning of pandas while studying the RealPython tutorial on DataFrames.

Source Article:
https://realpython.com/pandas-dataframe/

The goal of this project is to understand how pandas DataFrames work and practice common data manipulation operations using Jupyter Notebook.

---


pandas-learning/
│
├── notebooks/
│   └── pandas_practice.ipynb
│
├── datasets/
│
└── README.md

- notebooks/ contains my Jupyter notebook where I practiced the concepts.
- datasets/ will contain sample datasets used for experimentation.

---

# Topics Covered

## 1. Introducing the pandas DataFrame
Understanding what a DataFrame is and how it represents tabular data with rows, columns, and labeled indexes.

## 2. Creating a pandas DataFrame
Creating DataFrames from different data sources such as:
- dictionaries
- lists
- NumPy arrays
- CSV files

## 3. Retrieving Labels and Data
Understanding how to access:
- column labels
- row indexes
- underlying data values

## 4. Accessing and Modifying Data
Working with:
- column selection
- row selection
- modifying existing values

## 5. Inserting and Deleting Data
Adding and removing:
- columns
- rows
- data entries

## 6. Applying Arithmetic Operations
Performing arithmetic operations directly on DataFrame columns.

## 7. Applying NumPy and SciPy Functions
Using NumPy and SciPy functions on pandas data structures for numerical computation.

## 8. Sorting a pandas DataFrame
Sorting data using column values or index labels.

## 9. Filtering Data
Selecting subsets of data using logical conditions.

## 10. Determining Data Statistics
Using built-in methods to summarize data such as:
- mean
- median
- count
- summary statistics

## 11. Handling Missing Data
Detecting and managing missing values in datasets.

## 12. Iterating Over a pandas DataFrame
Understanding different methods to iterate through rows and columns.

## 13. Working With Time Series
Using pandas for working with time-based data.

## 14. Plotting With pandas DataFrames
Visualizing data directly from pandas using built-in plotting capabilities.

---

# Notebook

All learning examples and experiments are documented in the Jupyter notebook:

notebooks/pandas_practice.ipynb

---

# Goal of This Repository

This repository serves as a learning record while building foundational skills in:

- Python data analysis
- pandas DataFrames
- data manipulation
- exploratory data analysis

---


# Example

```python
import pandas as pd

data = [
    {'Student': 'Ada', 'rank': 1, 'Mark': 100},
    {'Student': 'Chima', 'rank': 2, 'Mark': 95}
]

df = pd.DataFrame(data)


---


# Key Takeaways

- A pandas DataFrame is a two-dimensional labeled data structure.
- Each column in a DataFrame is a pandas Series.
- DataFrames can be created from multiple data sources such as lists, dictionaries, NumPy arrays, and files.

# Environment

Python Version: Python 3.x

Libraries used:

- pandas
- numpy
- scipy
- matplotlib

To install dependencies:

pip install pandas numpy scipy matplotlib



print(df)
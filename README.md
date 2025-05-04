# Dataset Analysis and Visualization using Iris

## Overview

This project demonstrates data analysis and visualization using Python libraries **Pandas**, **Matplotlib**, and **Seaborn**. The well-known **Iris dataset** is used to explore, analyze, and visualize relationships between flower features and species.

## Objectives

- Load and explore a dataset using **pandas**
- Clean and prepare the data
- Perform basic statistical analysis
- Visualize the data using **matplotlib** and **seaborn**
- Derive meaningful insights from the data

## Dataset

- **Name**: Iris Dataset
- **Source**: Built-in dataset from `sklearn.datasets`
- **Description**: The dataset consists of 150 samples from three species of Iris flowers (*Iris-setosa*, *Iris-versicolor*, *Iris-virginica*), with four features: sepal length, sepal width, petal length, and petal width.

## Files

- `iris_data_analysis.ipynb`: Jupyter notebook containing code, visualizations, and observations.
- `README.md`: Project overview and usage instructions.

## Key Tasks Performed

### 1. Data Loading and Exploration
- Loaded the Iris dataset using `sklearn.datasets`.
- Converted it into a pandas DataFrame.
- Inspected the first few rows and checked data types and missing values.

### 2. Data Cleaning
- Verified that no missing values existed.
- Data was clean and ready for analysis.

### 3. Basic Data Analysis
- Used `.describe()` to compute basic statistics.
- Grouped data by species to compare average values of flower features.

### 4. Data Visualization
- **Bar Chart**: Compared average petal length across species.
- **Histogram**: Showed the distribution of petal lengths.
- **Scatter Plot**: Visualized correlation between sepal length and petal length.
- (Optional) **Line Chart**: Not included due to absence of time-series data.

### 5. Error Handling
- Demonstrated how to handle errors during file loading using `try-except`.

## Tools Used

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run

1. Open the `dataAnalysis.ipynb` notebook in Jupyter Lab or Jupyter Notebook.
2. Run all cells to see the analysis and plots.
3. Make sure required libraries are installed using pip:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn

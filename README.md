# Dataset Exploration Using Pandas

A beginner-level Python project that explores the Iris dataset using Pandas.

## Objective

To understand a dataset's structure, dimensions, column types, and statistical characteristics before modeling.

## Technologies Used

- Python 3
- Pandas
- Scikit-learn
- Jupyter Notebook

## Functions Used

- `head()` – displays the first five rows
- `tail()` – displays the last five rows
- `shape` – provides the number of rows and columns
- `columns` – displays column names
- `info()` – shows data types and non-null counts
- `describe()` – generates summary statistics
- `value_counts()` – counts observations in each species category
- `isnull().sum()` – checks for missing values

## Dataset Overview

The Iris dataset contains 150 observations and five columns:

- Sepal length
- Sepal width
- Petal length
- Petal width
- Species

The first four columns are numerical, while species is categorical.

## Observations

1. The dataset contains 150 rows and 5 columns.
2. It has four numerical features and one categorical column.
3. The species column contains setosa, versicolor, and virginica.
4. Each species has 50 observations.
5. The dataset contains no missing values.
6. The `describe()` function provides summary statistics for numerical columns.

## How to Run

1. Open `Dataset_Exploration.ipynb` in VS Code or Jupyter Notebook.
2. Install the required packages if needed using `pip install pandas scikit-learn`.
3. Select the Python kernel.
4. Run all cells from top to bottom.
5. Review the dataset information and observations.

## Learning Outcome

- Learned how to inspect a dataset using Pandas.
- Practiced identifying numerical and categorical columns.
- Learned to calculate basic descriptive statistics.
- Practiced checking dataset dimensions and missing values.
- Understood why dataset exploration is important before modeling.

## Project Structure

```text
Dataset-Exploration/
│
├── Dataset_Exploration.ipynb
└── README.md
```
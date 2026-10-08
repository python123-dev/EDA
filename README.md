# Exploratory Data Analysis with Python

A hands-on, four-hour course on EDA using pandas, SciPy, scikit-learn, Matplotlib and Seaborn. Each notebook is self-contained and ends with "Try it yourself" exercises.

## Setup (Windows)

    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt
    python -m ipykernel install --user --name eda-venv --display-name "Python (eda-venv)"
    jupyter lab

Open the notebooks and pick the kernel **Python (eda-venv)**.

## Agenda

### Hour 1 - pandas fundamentals (60 min)
| # | Notebook | Topics | Time |
|---|----------|--------|------|
| 1 | 01_series.ipynb | Series | 6 min |
| 2 | 02_dataframes.ipynb | DataFrames, read_csv, info/describe | 8 min |
| 3 | 03_indexing.ipynb | [], loc, iloc, filtering | 10 min |
| 4 | 04_row_column_operations.ipynb | add/drop/rename/sort/concat | 8 min |
| 5 | 05_apply_function.ipynb | apply, lambda, map | 8 min |
| 6 | 06_grouping.ipynb | groupby, agg, pivot_table | 8 min |
| 7 | 07_wrangling_cleaning.ipynb | missing, duplicates, text, dtypes, merge | 12 min |

### Hour 2 - Statistics
| # | Notebook | Topics |
|---|----------|--------|
| 8 | 08_statistics_hour2.ipynb | Descriptive statistics (centre, spread, quartiles/IQR), bivariate analysis (scatter, Pearson correlation, best-fit line), hypothesis testing (t-test, one-way ANOVA) |

### Hour 3 - Feature engineering
| # | Notebook | Topics |
|---|----------|--------|
| 9 | 09_feature_engineering_hour3.ipynb | Univariate analysis, label encoding, one-hot encoding, standard scaling (z-score), min-max normalization |

### Hour 4 - Data visualization
| # | Notebook | Topics |
|---|----------|--------|
| 10 | 10_data_visualization_hour4.ipynb | Matplotlib (line, bar, scatter, histogram, pie, subplots), Seaborn (countplot, barplot, histplot, boxplot, scatterplot, heatmap, pairplot), chart best practices, storytelling with data |

## Data

| File | Used for |
|------|----------|
| `data/students.csv` | Clean student dataset used across the notebooks |
| `data/messy_data.csv` | Deliberately messy data for the cleaning notebook |
| `data/clean_data.csv` | Cleaned version of the messy data |

## Slides

`EDA_Course_Slides.pptx` accompanies the notebooks.

## Requirements

Python 3.10+ and the packages in `requirements.txt`: pandas, numpy, scipy, scikit-learn, matplotlib, seaborn, jupyterlab, ipykernel.

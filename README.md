# NBA Stats and Salaries Analysis

## Notebooks

HTML versions of the notebooks can be found in the `notebooks/html` folder.

The code in the notebooks should work when executed in the following order:

`notebooks/1-data-cleaning.ipynb`: Holds code for all data cleaning and merging operations.

`notebooks/2-0-eda.ipynb ~ notebooks/2-3-eda.ipynb`: Holds code for all exploratory data analysis.

`notebooks/3-feature-engineering.ipynb`: Holds code for the entire feature engineering process.

`notebooks/4-model-training-final.ipynb`: Holds code for all data modeling and hyperparameter tuning.

`notebooks/model-results-comparison.ipynb`: Notebook for generating a plot comparing performance of old model to performance of new model.

## Data Sources

`data/raw/basketball.sqlite`: https://www.kaggle.com/datasets/wyattowalsh/basketball

`data/raw/csv/salaries.csv`: https://www.kaggle.com/datasets/patrickhallila1994/nba-data-from-basketball-reference?select=salaries.csv

`data/raw/csv/payroll.csv`: https://hoopshype.com/salaries/

`data/raw/csv` (excluding payroll, salary data): https://www.kaggle.com/datasets/nathanlauga/nba-games
# Mass-Mobilization-Project
This project analyzes a global dataset on protest events, exploring the dynamics between protester demands, state responses, and the occurrence of violence.

## Motivation

The motivation behind this project is to understand patterns in mass mobilizations across the globe. By analyzing data on protests, demands, and state responses, we aim to uncover insights into the factors that lead to successful protests and the circumstances under which states resort to deadly force.


## Tech/framework used

- Python
- Jupyter Notebook
- Pandas, Numpy, Seaborn, Matplotlib
- Scipy for statistical analysis
- Tableau

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) of global protest data
- Hypothesis testing to explore the correlation between protest count and state violence
- Visualizations to represent findings and patterns

## Code Example


```python
# Example of hypothesis testing code
from scipy.stats import spearmanr

# Calculate Spearman's correlation
correlation, p_value = spearmanr(df['protest_count'], df['deadly_force'])
print(f"Spearman correlation coefficient: {correlation}")
print(f"P-value: {p_value}")


## Tableau public link


https://public.tableau.com/views/MassMobilizationProjectAbelIronHack_Complete/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

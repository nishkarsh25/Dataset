# Exploratory Data Analysis using Python

The following Python code performs an exploratory data analysis on a CSV file named "dataset.csv". The code uses various Python libraries such as:

- NumPy
- Matplotlib
- Seaborn
- Pandas
- Scipy.stats

## Data Analysis Steps

The code performs the following steps:

1. Reads the CSV file and creates a list of column names.
2. Plots kernel density estimation (KDE) plots for each column in the dataset using Seaborn's kdeplot function.
3. Creates a heatmap to show the correlation matrix between all pairs of columns in the dataset using Seaborn's heatmap function.
4. For each pair of columns, creates a 3D wireframe plot and a scatter plot to show the joint probability distribution and the correlation between the two columns, respectively.
5. Calculates the proportion of data points that are more than 2.6 standard deviations away from the mean for each column in the dataset. This calculation is often used to identify outliers in the dataset. The result is printed for each column in the dataset.

This exploratory data analysis can help identify patterns and trends in the dataset, as well as potential outliers that may need to be further investigated.

# Difficulty viewing large code files?

If you're having trouble viewing large code files on GitHub, you may find it helpful to download a ZIP file containing the entire repository. To do so, follow these steps:

1. Click on the green "Code" button on the repository page.
2. Select "Download ZIP" from the dropdown menu.
3. Save the ZIP file to your computer.

This can be particularly useful if you're experiencing issues with GitHub's web interface or if you need to access the repository without an internet connection. If you have any questions or concerns, please don't hesitate to contact us. 
<img width="624" alt="image" src="https://user-images.githubusercontent.com/117291117/231703905-7469ae09-6d82-4f77-ad05-fa29142ac9a8.png">

 


# Introduction
In this code, we analyze a dataset using pandas, numpy, seaborn, and matplotlib libraries in Python. The dataset is loaded from a CSV file named "dataset.csv". The data is first analyzed in its original form and then normalized to analyze the normalized data.

# Data Analysis
The code first loads the dataset into a pandas dataframe and drops the index column. The summary statistics of the original data are then printed using the `describe()` function. Next, a correlation heatmap and a distribution plot are created using seaborn and matplotlib libraries.
<img width="638" alt="image" src="https://user-images.githubusercontent.com/117291117/231911986-c44b3cab-71b0-4e7b-8aa2-a86035fad150.png">
<img width="638" alt="image" src="https://user-images.githubusercontent.com/117291117/231912181-e6a07373-ea0f-4de4-8d72-2e241fb580a5.png">
<img width="638" alt="image" src="https://user-images.githubusercontent.com/117291117/231912225-e8adbb45-9716-4223-b85c-abc31ccc4e4f.png">


# Data Normalization
The data is then normalized using the min-max normalization technique. The normalized data is obtained by subtracting the minimum value of each column from each value of that column and then dividing the result by the difference between the maximum and minimum values of that column. The summary statistics of the normalized data are then printed using the `describe()` function. Next, a correlation heatmap and a distribution plot are created for the normalized data.
<img width="638" alt="image" src="https://user-images.githubusercontent.com/117291117/231912291-88999664-34dc-4a01-96e3-fa3030e19e7e.png">
<img width="638" alt="image" src="https://user-images.githubusercontent.com/117291117/231912362-084000e7-9649-4437-aa09-4703fe60e985.png">
<img width="638" alt="image" src="https://user-images.githubusercontent.com/117291117/231912424-0ecf24c2-9abb-4014-a78a-97912eeac1d8.png">



# Comparison
The code then compares the correlation heatmaps of the original and normalized data using a subplot. The subplot shows two heatmaps side by side, one for the original data and the other for the normalized data. The title of the subplot is "Comparison of Correlation Heatmaps".
<img width="626" alt="image" src="https://user-images.githubusercontent.com/117291117/231912527-b7ef7e92-9f9c-4a6c-b574-aee7115bf5cf.png">

# Box Plots
Finally, the code creates box plots of the original and normalized data using seaborn library, and removes the outliers from the plots using the "showfliers=False" parameter.


<img width="644" alt="image" src="https://user-images.githubusercontent.com/117291117/231912636-e9b44bb1-1829-4286-82b6-c34c7e861fa7.png">
<img width="648" alt="image" src="https://user-images.githubusercontent.com/117291117/231912749-86529fab-5f08-46ef-b16a-52c53490044a.png">


# Conclusion
In this code, we have analyzed a dataset using various statistical techniques and visualizations. We have also normalized the data to improve the correlation analysis. The box plots have provided an insight into the distribution of the data, and the removal of outliers has made the plots more readable. The code provides a good example of how to analyze and visualize a dataset using Python libraries.


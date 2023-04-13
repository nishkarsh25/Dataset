# Difficulty viewing large code files?

If you're having trouble viewing large code files on GitHub, you may find it helpful to download a ZIP file containing the entire repository. To do so, follow these steps:

1. Click on the green "Code" button on the repository page.
2. Select "Download ZIP" from the dropdown menu.
3. Save the ZIP file to your computer.

This can be particularly useful if you're experiencing issues with GitHub's web interface or if you need to access the repository without an internet connection. If you have any questions or concerns, please don't hesitate to contact us. 
 


# Exploratory Data Analysis using Python

The following Python code performs an exploratory data analysis on a CSV file named "dataset.csv". The code uses various Python libraries such as:

- NumPy
- Matplotlib
- Seaborn
- Pandas
- Scipy.stats

<img width="266" alt="image" src="https://user-images.githubusercontent.com/117291117/228689669-237c3783-c16a-4617-9782-b35ad19653db.png">

## Data Analysis Steps

The code performs the following steps:

1. Reads the CSV file and creates a list of column names.
<img width="532" alt="image" src="https://user-images.githubusercontent.com/117291117/228689948-bb4078bd-9ed2-49bd-be11-40b7284fbfed.png">

2. Plots kernel density estimation (KDE) plots for each column in the dataset using Seaborn's kdeplot function.
<img width="318" alt="image" src="https://user-images.githubusercontent.com/117291117/228689770-b3211e99-7a45-42fc-900f-af3e31188c3d.png">
<img width="318" alt="image" src="https://user-images.githubusercontent.com/117291117/228689813-df5c0e69-c875-4eab-9156-647c5fc66477.png">
<img width="318" alt="image" src="https://user-images.githubusercontent.com/117291117/228689852-4e51656c-0299-418e-977b-72d3c55599a0.png">

3. Creates a heatmap to show the correlation matrix between all pairs of columns in the dataset using Seaborn's heatmap function.
<img width="423" alt="image" src="https://user-images.githubusercontent.com/117291117/228690048-61bc1682-cb27-45f5-a668-f2a3c31ed206.png">

4. For each pair of columns, creates a 3D wireframe plot and a scatter plot to show the joint probability distribution and the correlation between the two columns, respectively.

<img width="409" alt="image" src="https://user-images.githubusercontent.com/117291117/228690129-c104f074-e12f-4695-85d1-634be39fbaf4.png">
<img width="409" alt="image" src="https://user-images.githubusercontent.com/117291117/228690157-d79755cf-f61d-4183-a7f0-e7ef75907d3c.png">
<img width="409" alt="image" src="https://user-images.githubusercontent.com/117291117/228690196-ca460ec8-518b-4b40-82a8-4bc1d1157ee9.png">
<img width="409" alt="image" src="https://user-images.githubusercontent.com/117291117/228690219-cbd52999-712f-4c95-951f-1b64eeaeefa6.png">

5. Calculates the proportion of data points that are more than 2.6 standard deviations away from the mean for each column in the dataset. This calculation is often used to identify outliers in the dataset. The result is printed for each column in the dataset.
<img width="427" alt="image" src="https://user-images.githubusercontent.com/117291117/228690356-c8dbe93c-db0f-48b5-98e7-1caf89a08ac4.png">


This exploratory data analysis can help identify patterns and trends in the dataset, as well as potential outliers that may need to be further investigated.

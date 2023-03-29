<h2>Dataset</h2>

<p>The code imports necessary libraries such as <code>NumPy</code>, <code>Matplotlib</code>, <code>Seaborn</code>, <code>Pandas</code>, and <code>Scipy.stats</code> for data manipulation, visualization, and statistical analysis. It then reads a CSV file named "dataset.csv" and creates a list of column names. The code then plots kernel density estimation (KDE) plots for each column in the dataset using Seaborn's <code>kdeplot</code> function.</p>

<div>
  <h3>KDE Plots</h3>
  <p>The following plots show the kernel density estimation (KDE) for each column in the dataset:</p>
  <div style="display: flex; flex-wrap: wrap;">
    <figure style="margin: 10px;">
      <img src="kde1.png" alt="KDE Plot 1">
      <figcaption>KDE Plot 1</figcaption>
    </figure>
    <figure style="margin: 10px;">
      <img src="kde2.png" alt=" KDE Plot 2">
      <figcaption>KDE Plot 2</figcaption>
    </figure>
    <figure style="margin: 10px;">
      <img src="kde3.png" alt="KDE Plot 3">
      <figcaption>KDE Plot 3</figcaption>
    </figure>
  </div>
</div>

<div>
  <h3>Correlation Heatmap</h3>
  <p>The following heatmap shows the correlation matrix between all pairs of columns in the dataset:</p>
  <figure>
    <img src="heatmap.png" alt="Correlation Heatmap">
    <figcaption>Correlation Heatmap</figcaption>
  </figure>
</div>

<div>
  <h3>Joint Probability Distributions</h3>
  <p>The following plots show the joint probability distribution and correlation between each pair of columns in the dataset:</p>
  <div style="display: flex; flex-wrap: wrap;">
    <figure style="margin: 10px;">
      <img src="wireframe1.png" alt="Wireframe Plot 1">
      <figcaption>Wireframe Plot 1</figcaption>
    </figure>
    <figure style="margin: 10px;">
      <img src="scatter1.png" alt="Scatter Plot 1">
      <figcaption>Scatter Plot 1</figcaption>
    </figure>
    <figure style="margin: 10px;">
      <img src="wireframe2.png" alt="Wireframe Plot 2">
      <figcaption>Wireframe Plot 2</figcaption>
    </figure>
    <figure style="margin: 10px;">
      <img src="scatter2.png" alt="Scatter Plot 2">
      <figcaption>Scatter Plot 2</figcaption>
    </figure>
    <figure style="margin: 10px;">
      <img src="wireframe3.png" alt="Wireframe Plot 3">
      <figcaption>Wireframe Plot 3</figcaption>
    </figure>
    <figure style="margin: 10px;">
      <img src="scatter3.png" alt="Scatter Plot 3">
      <figcaption>Scatter Plot 3</figcaption>
    </figure>
  </div>
</div>

<div>
  <h3>Outliers</h3>
  <p>The following proportions represent the number of data points that are more than 2.6 standard deviations away from the mean for

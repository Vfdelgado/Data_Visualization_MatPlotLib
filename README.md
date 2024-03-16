# MatPlotLib Data Visualization

### Objective:

This project involves analyzing cancer treatment data to evaluate the effectiveness of various drug regimens. The analysis includes generating summary statistics, creating visualizations such as bar charts and pie charts, identifying outliers, and performing correlation and regression analysis.

### Prepare the Data:

The provided dataset includes two separate DataFrames: mouse_metadata and study_results. These DataFrames are merged into a single DataFrame based on the common key "Mouse ID."
The number of unique mice IDs is displayed, and any duplicate mouse IDs with duplicate time points are identified and removed from the dataset. The cleaned DataFrame is used for subsequent analysis.

### Generate Summary Statistics:

Summary statistics are calculated for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume. Groupby operations are used to calculate these statistics, and a new DataFrame is created to store the results.

### Create Bar Charts and Pie Charts:

Bar charts are generated to visualize the total number of timepoints for all mice tested for each drug regimen. Both Pandas DataFrame.plot() method and Matplotlib's pyplot methods are used to create identical bar charts.
Pie charts are generated to display the distribution of female versus male mice in the study, using both Pandas DataFrame.plot() method and Matplotlib's pyplot methods.

### Calculate Quartiles, Find Outliers, and Create a Box Plot:

Final tumor volumes for mice treated with the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) are calculated. Quartiles and potential outliers are identified for each treatment regimen.
A box plot is generated to visualize the distribution of final tumor volume for all mice in each treatment group. Outliers are highlighted in the plot.

### Create a Line Plot and a Scatter Plot:

A line plot is generated to display tumor volume versus time point for a single mouse treated with Capomulin.
A scatter plot is generated to show the relationship between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.

### Calculate Correlation and Regression:

The correlation coefficient and linear regression model are calculated to assess the relationship between mouse weight and average observed tumor volume for the Capomulin treatment regimen. The regression model is plotted on top of the scatter plot for visualization.

### Conclusion:

Through comprehensive analysis of the cancer treatment data, valuable insights into the effectiveness of different drug regimens are obtained. 

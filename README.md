# data_Visualization_challenge

This is the Data Visualization Challenge that uses Pandas, Matplotlib and Statistics.

This assignment is broken down into the following tasks:
    a. Prepare the data.
        1.Run the provided package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame. Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.
    b. Generate summary statistics.
        Your summary statistics should include: A row for each drug regimen. These regimen names should be contained in the index column. A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.
    c. Create bar charts and pie charts.
        Generate two bar charts. Both charts should be identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study. Create the first bar chart with the Pandas DataFrame.plot() method. Create the second bar chart with Matplotlib's pyplot methods.Generate two pie charts. Both charts should be identical and show the distribution of unique female versus male mice in the study.Create the first pie chart with the Pandas DataFrame.plot() method. Create the second pie chart with Matplotlib's pyplot methods.
    d. Calculate quartiles, find outliers, and create a box plot.
        Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens
    e. Create a line plot and a scatter plot.
        Select a single mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse. Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.
    f. Calculate correlation and regression.
        Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen. Plot the linear regression model on top of the previous scatter plot.

   References
   1.Class Recordings: Zoom Cloud Recordings.

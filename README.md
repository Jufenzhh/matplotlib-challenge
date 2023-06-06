# matplotlib-challenge
pymaceuticals_starter script reads the csv files of mouse_metadata and study_results and stores then merges and cleans the data for analysis. 
Using the clean and merged data the script generates a summary statistic of the data including the values of mean, median, variance, standard deviation, and standard error. 
The script then generates bar and pie charts utilizing pandas, and pyplot to graph, the total number of rows (Mouse ID/Timepoints) and the gender distribution of mouses. 
Furthermore, the script loops through the data through quartiles to look for outliers within the data. 
Then the script creates more charts and plots starting with a box plot to visualize the tumor volume for each treatment group. 
Focusing on an individual mouse id a line and scatter plot is created. 
The line plot illustrates the "individual mouse's tumor volume vs. time point of Capomulin treatment"
The scatter plot illustrates the "individual mouse's weight vs.the average observed tumor volume for the entire Capomulin regimen"
Final line plot illustrates the correlation "individual mouse's weight vs.the average observed tumor volume for the entire Capomulin regimen"
The script provides visualization to the mouse and study data.  

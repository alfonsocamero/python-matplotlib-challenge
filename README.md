# python-matplotlib-challenge
This script analyzes a study on the effect that certain drugs had on tumor volume in mice. 
The first section of code focuses on the following:
  1. Merges both given data sets to yield a complete a dataset from which all information will be calculated. 
  2. Calculates the number of mice in the study
  3. Removes a duplicate mouse
  4. Updates the count of total mice in the study
  5. Provide a statistics summary table for tumor volumen across all drug regimens that includes calculations for mean, median, variance, standard variation and standard error in mean. 

The second section of the script focuses on the following:
  1. Divide the final tumor volume data into quartiles to determine the lower and upper bounds for the tumor volume data across 4 drug regimens of interest. 
  2. Find any outliers contained within any of these 4 regimens.
  3. Create a box plot graph to visualize the range in tumor volumen for all mice across these for drug treatments.
  4. Generate a line plot of tumor volume vs. time point for a mouse treated with Capomulin.
  5. Generate a scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen.
  6. And finally, calculate the correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin regimen.

<H1>Code Book</H1>

<H3>This file describes the script run_analysis.R from the perspective of the variables used during processing of the script.</H3>

1) The script first assigns values to new variables for the file and url. <br>
2) Then we create the files, directories and download the file. <br>
3) Use the f and data variables for loading the data and formatting initially. <br>
4) Create the data set with the x_data and y_data variables. <br>
5) SaveResult variable will get the final table as part of a function during processing of the data. <br>
6) features variable holds column name values from the features.txt file as part of the original data set. <br>
7) train and test variables hold the requisite data for processing. <br>
8) data variable is again manipulated to clean the data set. <br>
9) activity_lables variable is used to store values of the descriptive names for activity from the activity.txt file in the original data set. <br>
10) kdata variable is used to hold the means and std deviations for the data set. <br>
11) tidyData variable holds the merged and cleaned data set with descriptive identification labels added. <br>

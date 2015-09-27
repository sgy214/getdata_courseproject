Getting and Cleaning Data Course Project CodeBook
=================================================
* The site where the data was obtained:  
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones      
The data for the project:  
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  


1. Merges the test dataset and train dataset into one dataset labeled "merge_data".
2. Subsets this dataset into a new dataset called "extract_data" containing only mean and std values.
3. Replaces numeric labels of activity with actual descriptions.
4. Adds descriptive variable names to columns.
5. Forces R to recognize "_" as a valid variable name.
6. Finds the average of all columns sorted by subject and activity.
7. Writes this final table to new text file called "step5.txt"

Getting-and-Cleaning-Data
=========================

### Project Summary
The R script run_analysis.R:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

### Running
To run the script:
1. Download dataset form [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
2. Extract in your project directory
3. Start R
4. Set your project directory `setwd('PATH_OF_YOUR_PROJECT_DIRECTORY')`
5. Run script `source('run_analysis.R')`

### Resulting dataset
You can find the resulting dataset in your project directory named: tidy_dataset.txt
Getting-and-Cleaning-Data
=========================

### Project Summary
The R script run_analysis.R:
* Merges the training and the test sets to create one data set
* Extracts only the measurements on the mean and standard deviation for each measurement
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject

### Running
To run the script:
* Download dataset form [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
* Extract in your project directory
* Start R
* Set your project directory `setwd('PATH_OF_YOUR_PROJECT_DIRECTORY')`
* Run script `source('run_analysis.R')`

### Resulting dataset
You can find the resulting dataset in your project directory named: tidy_dataset.txt
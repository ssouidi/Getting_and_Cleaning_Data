# Getting_and_Cleaning_Data

Source of the original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The attached R script (run_analysis.R) performs the following to clean up the data:

Merges the training and test sets to create one data set, namely train/X_train.txt with test/X_test.txt, train/subject_train.txt with test/subject_test.txt, and train/y_train.txt with test/y_test.txt.

Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement.


Creates independent tidy data set (DataSet_Step5.txt) with the average of each variable for each activity and each subject.



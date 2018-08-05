# gettingAndCleaningData_run_analysis
Data for the project
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Need to create one R script called run_analysis.R that does the following:

1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement.
3.	Uses descriptive activity names to name the activities in the data set
4.	Appropriately labels the data set with descriptive variable names.
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

activityLabels = 6 diff activities extracted from UCI HAR Dataset/activity_labels.txt
features = all the features extracted from UCI HAR Dataset/features_info.txt
f = extracts of only the mean and standard deviation from features
measurements = name of features from f (cleaned up, with no paranthesis)
XTrain/XTest- training/test data
YTrain/YTest - training/test data labels
trainSubjects/testSubjects - subjects for training or test set
Test/Train  - final (combined) test/training set
combined - final combined by subject, activity, label data  set



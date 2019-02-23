# Code Book for gettingAndCleaningData_run_analysis
This code book describes STidyData.txt file located in this repository.

See the README.md file of this repository for background information on this data set.

Data
The STidyData.txt data file is a text file, with space as delimiter.

The first row contains the variable names (isted and described in the Variables section), and the following rows contain the values for these variables.

Variables
Each row contains, for a given subject and activity, 79 averaged signal measurements.

Subject identifier 1-30.

6 different activity types:

(1) WALKING
(2) WALKING_UPSTAIRS 
(3) WALKING_DOWNSTAIRS
(4) SITTING
(5) STANDING
(6) LAYING

Tranformations

The training and test sets were merged to create one data set.
The measurements on the mean and standard deviation (i.e. signals containing the strings mean and std) were extracted for each measurement, the rest were discarded.
The activity identifiers were replaced with descriptive activity names.
The variable names were replaced with descriptive variable names.


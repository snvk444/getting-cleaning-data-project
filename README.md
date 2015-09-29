Getting-and-Cleaning-Data-Coursera
Objective:- Getting and Cleaning data by following all the principles of tidy data set

* create one R script called run_analysis.R that does the following.

- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement.
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names.
- From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

Approach:
Read the data and store it in given tables
Create new tables by merging them
Extract columns names with mean() or std()
Subset columns
Update the values with correct activity names
Correct the Column names
Bind the data elements again
List of variables used


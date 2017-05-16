Introduction
The script run_analysis.R does the following tasks, as described for the project's scope:
- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement.
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names.
- From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Variables
dataActivityTest, dataActicivityTrain, dataSubjectTrain, dataSubjectTest, dataFeaturesTrain, and dataFeaturesTest contain the downloaded files. 
dataSubject, dataActivity, and dataFeatures contain the merged data tables. 
dataCombine and Data are the merged tables using the cbind command. 
activityLabels describe the activity labes in the activity_labes.txt table. 
Descriptive vaiables names are assigned using rh gsub command. THe following vaiables were assigned: 
  t - time
  f - frequency
  Acc - Accelerometer
  Gyro - Gyroscope
  Mag - Magnitude
Data2 contains the second, independent tidy data set.

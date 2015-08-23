
# **Getting and Cleaning Data**
# **Course Project Code Book**

#### *Author: Margherita Grossi*

## **Data set**

Original data: [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) 

Description of the data set: [http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

The data set includes the following files (loaded by *run_analysis.txt*):
* *UCI HAR Dataset/README.txt*
* *UCI HAR Dataset/activity_labels.txt*: labels for each of the 6 activities
* *UCI HAR Dataset/features.txt*: list of all features.
* *UCI HAR Dataset/features_info.txt*: information about the variables contained in *feature.txt*
* *UCI HAR Dataset/train/X_train.txt*: Training set 
* *UCI HAR Dataset/train/y_train.txt*: Training labels
* *UCI HAR Dataset/train/subject_train.txt*: subject who performed the activity
* *UCI HAR Dataset/test/X_test.txt*: Test set
* *UCI HAR Dataset/test/y_test.txt*: Test labels
* *UCI HAR Dataset/test/subject_test.txt*: subject who performed the activity

## **Variable list and description**

The output data set tidy.txt contains the following variables:

* **Subject** : ID of the subject who performed the activity. The experiment was
|carried out on a group of 30 volonteers (range 1-30). 
* **Activity**: Activity name. Possible activities include:  WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING and LAYING
* All mean measurements from the files *X_train.txt* and *X_test.txt* in the
form **Feature_name-(mean/std)-(X/Y/Z)** (3-axial linear accelleration and
3-axial angular velocity). More in details it contains:
 "tBodyAcc-mean()-X"      "tBodyAcc-mean()-Y"      "tBodyAcc-mean()-Z"
 "tBodyAcc-std()-X"       "tBodyAcc-std()-Y"       "tBodyAcc-std()-Z"
 "tGravityAcc-mean()-X"   "tGravityAcc-mean()-Y"   "tGravityAcc-mean()-Z"
 "tGravityAcc-std()-X"    "tGravityAcc-std()-Y"    "tGravityAcc-std()-Z"
 "tBodyAccJerk-mean()-X"  "tBodyAccJerk-mean()-Y"  "tBodyAccJerk-mean()-Z"
 "tBodyAccJerk-std()-X"   "tBodyAccJerk-std()-Y"   "tBodyAccJerk-std()-Z"
 "tBodyGyro-mean()-X"     "tBodyGyro-mean() -Y"    "tBodyGyro-mean()-Z"
 "tBodyGyro-std()-X"      "tBodyGyro-std()-Y"      "tBodyGyro-std()-Z"
 "tBodyGyroJerk-mean()-X" "tBodyGyroJerk-mean()-Y" "tBodyGyroJerk-mean()-Z"
 "tBodyGyroJerk-std()-X"  "tBodyGyroJerk-std()-Y"  "tBodyGyroJerk-std()-Z"
 "tBodyAccMag-mean()"     "tBodyAccMag-std()"      "tGravityAccMag-mean()"
 "tGravityAccMag-std()"   "tBodyAccJerkMag-mean()" "tBodyAccJerkMag-std()"
 "tBodyGyroMag-mean()"    "tBodyGyroMag-std()"     "tBodyGyroJerkMag-mean()"
 "tBodyGyroJerkMag-std()" "fBodyAcc-mean()-X"      "fBodyAcc-mean()-Y"
 "fBodyAcc-mean()-Z"      "fBodyAcc-std()-X"       "fBodyAcc-std()-Y"
 "fBodyAcc-std()-Z"       "fBodyAccJerk-mean()-X"  "fBodyAccJerk-mean()-Y"
 "fBodyAccJerk-mean()-Z"  "fBodyAccJerk-std()-X"   "fBodyAccJerk-std()-Y"
 "fBodyAccJerk-std()-Z"   "fBodyGyro-mean()-X"     "fBodyGyro-mean()-Y"
 "fBodyGyro-mean()-Z"     "fBodyGyro-std()-X"      "fBodyGyro-std()-Y"
 "fBodyGyro-std()-Z"      "fBodyAccMag-mean()"     "fBodyAccMag-std()"
 "fBodyBodyAccJerkMag-mean()"    "fBodyBodyAccJerkMag-std()"
 "fBodyBodyGyroMag-mean()"       "fBodyBodyGyroMag-std()"
 "fBodyBodyGyroJerkMag-mean()"   "fBodyBodyGyroJerkMag-std()"
 






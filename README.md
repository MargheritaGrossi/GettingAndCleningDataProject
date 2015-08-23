

# **Getting and Cleaning Data Course Project** 

#### *Author: Margherita Grossi*

##**Description**

The purpose of this project is to collect, work with, and clean a data set.
The goal is to prepare tidy data that can be used for later analysis.

One of the most exciting areas in all of data science right now is wearable
computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop
the most advanced algorithms to attract new users. The data linked to from the
course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full
description is available at the site where the data was obtained:

[http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

Here are the data for the project:

[https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) 

##**Course Project**

The R script called *run_analysis.R* does the following:

- Step 1. Download original data from the internet and unzip the data set if
necessary. Read the training and the test set and merge them to create one data set.
- Step 2. Read the activity labels and features and extracts only the measurements on the mean and standard deviation for each measurement.
- Step 3. Use descriptive activity names to name the activities in the data
set. Add subject and Activity columns in the merged data set.
- Step 4. Appropriately labels the data set with descriptive variable
names. Add activity labels to the merged data set
- Step 5. Creates a second, independent tidy data set named "./data/tidy.txt"
containing the average of each variable for each activity and each subject (60
activities in total, 30 subjects in total, and 66 features).

##**Contents**

- *run_analysis.R* : R-code run on data set

- *tidy.txt* : clean data extracted from the original data using *run_analysis.R* 

- *CodeBook.md* : CodeBook reference to the variables in *tidy.txt*

- *README.md* : readme file




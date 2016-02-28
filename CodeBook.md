=============================================================

###This Code Book describes all variables in the clean_data.txt

=============================================================

This file gives a description of all variables contained in the 

Signals from Samsung smart phones worn by subjects performing different activities were used to 
estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions. Only the means and standard
deviations are extracted in clean_data.txt/.csv while the average of each variable for each activity
per subject is contained in clean_data2.txt/.csv. To obtain the full data set pls visit 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

====================================================================================================

###clean_data.txt/csv contains 69 variables and 10299 observation

###The variables contained in clean_data.txt/csv are: 

====================================================================================================

* Subject: An id for the subject performing the activity.

* Activity: A factor variables with 6 levels for the activities performed
	* 1 - 'WALKING'
	* 2 - 'WALKING_UPSTAIRS
'
	* 3 - 'WALKING_DOWNSTAIRS'
	* 4 - 'SITTING
'
	* 5 - 'STANDING'
	* 6 - 'LAYING'

* Class: A factor variable with two levels indicating the group each measurement came from
	* 1 - 'test'
	* 2 - 'train'

---------------------------------------------------------------------------

All variables below are quantitative variables

---------------------------------------------------------------------------

* tBodyAcc_mean_X: Mean of total body acceleration measured in direction x

* tBodyAcc_mean_Y: Mean of total body acceleration measured in direction Y

* tBodyAcc_mean_Z: Mean of total body acceleration measured in direction Z

* tBodyAcc_std_X: Standard deviation of total body acceleration measured in direction x

* tBodyAcc_std_Y: Standard deviation of total body acceleration measured in direction Y

* tBodyAcc_std_Z: Standard deviation of total body acceleration measured in direction Z

* tGravityAcc_mean_X: Mean gravity acceleration measured in direction x

* tGravityAcc_mean_Y: Mean gravity acceleration measured in direction Y

* tGravityAcc_mean_Z: Mean gravity acceleration measured in direction Z

* tGravityAcc_std_X: Standard deviation acceleration gravity measured in direction x

* tGravityAcc_std_Y: Standard deviation acceleration gravity measured in direction Y

* tGravityAcc_std_Z: Standard deviation acceleration gravity measured in direction Z

* tBodyAccJerk_mean_X: Mean total body acceleration jerk signals measured in direction x

* tBodyAccJerk_mean_Y: Mean total body acceleration jerk signals measured in direction Y

* tBodyAccJerk_mean_Z: Mean total body acceleration jerk signals measured in direction Z

* tBodyAccJerk_std_X: Standard deviation of total body acceleration jerk signals measured from direction x

* tBodyAccJerk_std_Y: Standard deviation of total body acceleration jerk signals measured in direction Y

* tBodyAccJerk_std_Z: Standard deviation of total body acceleration jerk signals measured in direction Z

* tBodyGyro_mean_X: Mean of Total Angular velocity measured in direction x

* tBodyGyro_mean_Y: Mean of Total Angular velocity measured in direction Y

* tBodyGyro_mean_Z: Mean of Total Angular velocity measured in direction Z

* tBodyGyro_std_X: Standard deviation of total Angular velocity measured in direction x

* tBodyGyro_std_Y: Standard deviation of total Angular velocity measured in direction Y

* tBodyGyro_std_Z: Standard deviation of total Angular velocity measured in direction Z

* tBodyGyroJerk_mean_X: Mean of Total Angular velocity jerk signals measured in direction x

* tBodyGyroJerk_mean_Y: Mean of Total Angular velocity jerk signals measured in direction Y

* tBodyGyroJerk_mean_Z: Mean of Total Angular velocity jerk signals measured in direction Z

* tBodyGyroJerk_std_X: Standard deviation of total Angular velocity jerk signals measured in direction x

* tBodyGyroJerk_std_Y: Standard deviation of total Angular velocity jerk signals measured in direction Y

* tBodyGyroJerk_std_Z: Standard deviation of total Angular velocity jerk signals measured in direction Z

* tBodyAccMag_mean: Mean of Total Acceleration Magnitude 

* tBodyAccMag_std: Standard deviation of Total Acceleration Magnitude

* tGravityAccMag_mean: Mean of Total Gravity Acceleration Magnitude

* tGravityAccMag_std: Standard deviation of Total Gravity Acceleration Magnitude

* tBodyAccJerkMag_mean: Mean of total body acceleration jerk magnitude

* tBodyAccJerkMag_std: Mean of total body acceleration jerk magnitude

* tBodyGyroMag_mean: Mean of total body angular velocity magnitude

* tBodyGyroMag_std: Standard deviation of body angular velocity magnitude

* tBodyGyroJerkMag_mean: Mean of total body angular velocity jerk signals magnitude

* tBodyGyroJerkMag_std: Standard deviation of total body angular velocity jerk signals magnitude

* fBodyAcc_mean_X: Mean of Acceleration frequency domain signals measured in direction X

* fBodyAcc_mean_Y: Mean of Acceleration frequency domain signals measured in direction Y

* fBodyAcc_mean_Z: Mean of Acceleration frequency domain signals measured in direction Z

* fBodyAcc_std_X: Standard Deviation of Acceleration frequency domain signals measured in direction X

* fBodyAcc_std_Y: Standard Deviation of Acceleration frequency domain signals measured in direction Y

* fBodyAcc_std_Z: Standard Deviation of Acceleration frequency domain signals measured in direction Z

* fBodyAccJerk_mean_X: Mean of Acceleration Jerk frequency domain signals measured in direction X

* fBodyAccJerk_mean_Y: Mean of Acceleration Jerk frequency domain signals measured in direction Y

* fBodyAccJerk_mean_Z: Mean of Acceleration Jerk frequency domain signals measured in direction Z

* fBodyAccJerk_std_X: Standard Deviation of Acceleration Jerk frequency domain signals measured in direction X

* fBodyAccJerk_std_Y: Standard Deviation of Acceleration Jerk frequency domain signals measured in direction Y

* fBodyAccJerk_std_Z: Standard Deviation of Acceleration Jerk frequency domain signals measured in direction Z

* fBodyGyro_mean_X: Mean of Angular velocity frequency domain signals measured in direction x

* fBodyGyro_mean_Y: Mean of Angular velocity frequency domain signals measured in direction Y

* fBodyGyro_mean_Z: Mean of Angular velocity frequency domain signals measured in direction Z

* fBodyGyro_std_X: Standard Deviation of Angular velocity frequency domain signals measured in direction x

* fBodyGyro_std_Y: Standard Deviation of Angular velocity frequency domain signals measured in direction Y

* fBodyGyro_std_Z: Standard Deviation of Angular velocity frequency domain signals measured in direction Z

* fBodyAccMag_mean: Mean of Acceleration Magnitude frequency domain signals

* fBodyAccMag_std: Standard Deviation of Acceleration Magnitude frequency domain signals

* fBodyAccJerkMag_mean: Mean of body acceleration jerk magnitude frequency domain signals

* fBodyAccJerkMag_std: Standard Deviation of body acceleration jerk magnitude frequency domain signals

* fBodyGyroMag_mean: Mean of body angular velocity magnitude frequency domain signals

* fBodyGyroMag_std: Standard Deviation of body angular velocity magnitude frequency domain signals

* fBodyGyroJerkMag_mean: Mean of body angular velocity jerk magnitude frequency domain signals

* fBodyGyroJerkMag_std: Standard Deviation of body angular velocity jerk magnitude frequency domain signals

===================================================================================================================================













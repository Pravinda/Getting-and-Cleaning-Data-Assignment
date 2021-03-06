# CODE BOOK

---------------------------------------------------------------------------------

## Variables
The following are the variables of the variables that can be found in tidy_data.txt file

1. subject: Performers who performed the activity for each window sample. It is the ranges from 1 to 30.
2. Activity_Label: Label of activities performed by subject
3. mean() - Mean, std() - Standard Deviation, meanFreq() - Weighted average of the frequency components to obtain a mean frequency; Total _ Acc- The acceleration signal from the smartphone accelerometer X axis, Y axis and Z axis in standard gravity units 'g'; Acc- The body acceleration signal obtained by subtracting the gravity from the total acceleration; Gyro- The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second
      * tBodyAcc-mean()-X
      * tBodyAcc-mean()-Y
      * tBodyAcc-mean()-Z
      * tBodyAcc-std()-X
      * tBodyAcc-std()-Y
      * tBodyAcc-std()-Z
      * tGravityAcc-mean()-X
      * tGravityAcc-mean()-Y
      * tGravityAcc-mean()-Z
      * tGravityAcc-std()-X
      * tGravityAcc-std()-Y
      * tGravityAcc-std()-Z
      * tBodyAccJerk-mean()-X
      * tBodyAccJerk-mean()-Y
      * tBodyAccJerk-mean()-Z
      * tBodyAccJerk-std()-X
      * tBodyAccJerk-std()-Y
      * tBodyAccJerk-std()-Z
      * tBodyGyro-mean()-X
      * tBodyGyro-mean()-Y
      * tBodyGyro-mean()-Z
      * tBodyGyro-std()-X
      * tBodyGyro-std()-Y
      * tBodyGyro-std()-Z
      * tBodyGyroJerk-mean()-X
      * tBodyGyroJerk-mean()-Y
      * tBodyGyroJerk-mean()-Z
      * tBodyGyroJerk-std()-X
      * tBodyGyroJerk-std()-Y
      * tBodyGyroJerk-std()-Z
      * tBodyAccMag-mean()
      * tBodyAccMag-std()
      * tGravityAccMag-mean()
      * tGravityAccMag-std()
      * tBodyAccJerkMag-mean()
      * tBodyAccJerkMag-std()
      * tBodyGyroMag-mean()
      * tBodyGyroMag-std()
      * tBodyGyroJerkMag-mean()
      * tBodyGyroJerkMag-std()
      * fBodyAcc-mean()-X
      * fBodyAcc-mean()-Y
      * fBodyAcc-mean()-Z
      * fBodyAcc-std()-X
      * fBodyAcc-std()-Y
      * fBodyAcc-std()-Z
      * fBodyAcc-meanFreq()-X
      * fBodyAcc-meanFreq()-Y
      * fBodyAcc-meanFreq()-Z
      * fBodyAccJerk-mean()-X
      * fBodyAccJerk-mean()-Y
      * fBodyAccJerk-mean()-Z
      * fBodyAccJerk-std()-X
      * fBodyAccJerk-std()-Y
      * fBodyAccJerk-std()-Z
      * fBodyAccJerk-meanFreq()-X
      * fBodyAccJerk-meanFreq()-Y
      * fBodyAccJerk-meanFreq()-Z
      * fBodyGyro-mean()-X
      * fBodyGyro-mean()-Y
      * fBodyGyro-mean()-Z
      * fBodyGyro-std()-X
      * fBodyGyro-std()-Y
      * fBodyGyro-std()-Z
      * fBodyGyro-meanFreq()-X
      * fBodyGyro-meanFreq()-Y
      * fBodyGyro-meanFreq()-Z
      * fBodyAccMag-mean()
      * fBodyAccMag-std()
      * fBodyAccMag-meanFreq()
      * fBodyBodyAccJerkMag-mean()
      * fBodyBodyAccJerkMag-std()
      * fBodyBodyAccJerkMag-meanFreq()
      * fBodyBodyGyroMag-mean()
      * fBodyBodyGyroMag-std()
      * fBodyBodyGyroMag-meanFreq()
      * fBodyBodyGyroJerkMag-mean()
      * fBodyBodyGyroJerkMag-std()
      * fBodyBodyGyroJerkMag-meanFreq()
      
---------------------------------------------------------------------------------

## Provided Information

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

Additional vectors obtained by averaging the signals in a signal window sample. These are used on the angle() variable:

* gravityMean
* tBodyAccMean
* tBodyAccJerkMean
* tBodyGyroMean
* tBodyGyroJerkMean

---------------------------------------------------------------------------------

## Activity Labels
* WALKING (value 1): subject was walking during the test
* WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
* WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
* SITTING (value 4): subject was sitting during the test
* STANDING (value 5): subject was standing during the test
* LAYING (value 6): subject was laying down during the test

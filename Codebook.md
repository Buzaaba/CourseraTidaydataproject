
The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ).Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals  producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 


My is variable

```
[1] "Activity Id"  "Subject Id"

"tBodyAcc-mean()-X"  "tBodyAcc-mean()-Y" 

[65] "fBodyBodyGyroMag-mean()" "fBodyBodyGyroMag-std()"
"fBodyBodyGyroJerkMag-mean()" "fBodyBodyGyroJerkMag-std()" 

+We have 68 variables. In the table bellow we have described the variable.

+We are using:
+- `u` (unit): frecuency or time (**f** or **t**)
+- `measure`: **mean()** or **std()**
+- `direction`: **X**, **Y** or **Z**
For example u-BodyAcc-measure-direction are 6 variable

For example u-BodyAccMag-measure  are 4 variable (2 for unit and 2 for measure 2*2=4)

This is the table with the description

ariable name                    |  Description
-------------------------------- | -----------------------------
u-BodyGyroMag-measure            |  Ecludien norm for the Body Gyroscope
u-BodyGyroJerkMag-measure        |  Ecludien norm of the Jerk signal for
the Gyroscpe

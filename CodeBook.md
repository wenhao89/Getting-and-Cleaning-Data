# Code Book - Tidy Data
Wen Hao Wong

**Note: Format is as follows:**

1. **Variable no. 1**
	* **Description of Variable no. 1**
2. **Variable no. 2**
	* **Description of Variable no. 2**

**etc.**

1.	"tBodyAcc.mean...X"
	* Time-domain (units: seconds); Mean; X-axis; Acceleration of subject;2.	"tBodyAcc.mean...Y"	* Time-domain (units: seconds); Mean; Y-axis; Acceleration of subject;3.	"tBodyAcc.mean...Z"
	* Time-domain (units: seconds); Mean; Z-axis; Acceleration of subject;4.	"tBodyAcc.std...X"
	* Time-domain (units: seconds); Std dev; X-axis; Acceleration of subject;5.	"tBodyAcc.std...Y"
	* Time-domain (units: seconds); Std dev; Y-axis; Acceleration of subject;6.	"tBodyAcc.std...Z"
	* Time-domain (units: seconds); Std dev; Z-axis; Acceleration of subject;7.	"tGravityAcc.mean...X"
	* Time-domain (units: seconds); Mean; X-axis; Acceleration due to gravity;8.	"tGravityAcc.mean...Y"
	* Time-domain (units: seconds); Mean; Y-axis; Acceleration due to gravity;9.	"tGravityAcc.mean...Z"
	* Time-domain (units: seconds); Mean; Z-axis; Acceleration due to gravity;10.	"tGravityAcc.std...X"	
	* Time-domain (units: seconds); Std dev; X-axis; Acceleration due to gravity;	11.	"tGravityAcc.std...Y"	
	* Time-domain (units: seconds); Std dev; Y-axis; Acceleration due to gravity;12.	"tGravityAcc.std...Z"	
	* Time-domain (units: seconds); Std dev; Z-axis; Acceleration due to gravity;13.	"tBodyAccJerk.mean...X"	
	* Time-domain (units: seconds); Mean; X-axis; Jerk of acceleration of subject;14.	"tBodyAccJerk.mean...Y"	
	* Time-domain (units: seconds); Mean; Y-axis; Jerk of acceleration of subject;15.	"tBodyAccJerk.mean...Z"	
	* Time-domain (units: seconds); Mean; Z-axis; Jerk of acceleration of subject;16.	"tBodyAccJerk.std...X"	
	* Time-domain (units: seconds); Std dev; X-axis; Jerk of acceleration of subject;17.	"tBodyAccJerk.std...Y"	
	* Time-domain (units: seconds); Std dev; Y-axis; Jerk of acceleration of subject;18.	"tBodyAccJerk.std...Z"	
	* Time-domain (units: seconds); Std dev; Z-axis; Jerk of acceleration of subject;19.	"tBodyGyro.mean...X"	
	* Time-domain (units: seconds); Mean; X-axis; Gyroscope measurement of subject;20.	"tBodyGyro.mean...Y"	
	* Time-domain (units: seconds); Mean; Y-axis; Gyroscope measurement of subject;21.	"tBodyGyro.mean...Z"	
	* Time-domain (units: seconds); Mean; Z-axis; Gyroscope measurement of subject;22.	"tBodyGyro.std...X"	
	* Time-domain (units: seconds); Std dev; X-axis; Gyroscope measurement of subject;23.	"tBodyGyro.std...Y"	
	* Time-domain (units: seconds); Std dev; Y-axis; Gyroscope measurement of subject;24.	"tBodyGyro.std...Z"	
	* Time-domain (units: seconds); Std dev; Z-axis; Gyroscope measurement of subject;25.	"tBodyGyroJerk.mean...X"	
	* Time-domain (units: seconds); Mean; X-axis; Jerk of gyroscope of subject;26.	"tBodyGyroJerk.mean...Y"	
	* Time-domain (units: seconds); Mean; Y-axis; Jerk of gyroscope of subject;27.	"tBodyGyroJerk.mean...Z"	
	* Time-domain (units: seconds); Mean; Z-axis; Jerk of gyroscope of subject;28.	"tBodyGyroJerk.std...X"	
	* Time-domain (units: seconds); Std dev; Jerk of gyroscope of subject;29.	"tBodyGyroJerk.std...Y"	
	* Time-domain (units: seconds); Std dev; Jerk of gyroscope of subject;30.	"tBodyGyroJerk.std...Z"	
	* Time-domain (units: seconds); Std dev; Jerk of gyroscope of subject;31.	"tBodyAccMag.mean.."	
	* Time-domain (units: seconds); Mean; Magnitude of acceleration of subject;32.	"tBodyAccMag.std.."	
	* Time-domain (units: seconds); Std dev; Magnitude of acceleration of subject;33.	"tGravityAccMag.mean.."	
	* Time-domain (units: seconds); Mean; Magnitude of acceleration due to gravity;34.	"tGravityAccMag.std.."	
	* Time-domain (units: seconds); Std dev; Magnitude of acceleration due to gravity;35.	"tBodyAccJerkMag.mean.."	
	* Time-domain (units: seconds); Mean; Magnitude of jerk of acceleration of subject;36.	"tBodyAccJerkMag.std.."	
	* Time-domain (units: seconds); Std dev; Magnitude of jerk of acceleration of subject;37.	"tBodyGyroMag.mean.."	
	* Time-domain (units: seconds); Mean; Magnitude of gyroscope measurement of subject;38.	"tBodyGyroMag.std.."	
	* Time-domain (units: seconds); Std dev; Magnitude of gyroscope measurement of subject;39.	"tBodyGyroJerkMag.mean.."	
	* Time-domain (units: seconds); Mean; Magnitude of jerk of gyroscope measurement of subject;40.	"tBodyGyroJerkMag.std.."	
	* Time-domain (units: seconds); Std dev; Magnitude of jerk of gyroscope measurement of subject;41.	"fBodyAcc.mean...X"	
	* Frequency-domain (units: hertz); Mean; X-axis; Acceleration of subject;42.	"fBodyAcc.mean...Y"	
	* Frequency-domain (units: hertz); Mean; Y-axis; Acceleration of subject;43.	"fBodyAcc.mean...Z"	
	* Frequency-domain (units: hertz); Mean; Z-axis; Acceleration of subject;44.	"fBodyAcc.std...X"	
	* Frequency-domain (units: hertz); Std dev; X-axis; Acceleration of subject;45.	"fBodyAcc.std...Y"	
	* Frequency-domain (units: hertz); Std dev; Y-axis; Acceleration of subject;46.	"fBodyAcc.std...Z"	
	* Frequency-domain (units: hertz); Std dev; Z-axis; Acceleration of subject;47.	"fBodyAcc.meanFreq...X"
	* Frequency-domain (units: hertz); Mean frequency; X-axis; Acceleration of subject;48.	"fBodyAcc.meanFreq...Y"	
	* Frequency-domain (units: hertz); Mean frequency; Y-axis; Acceleration of subject;49.	"fBodyAcc.meanFreq...Z"	
	* Frequency-domain (units: hertz); Mean frequency; Z-axis; Acceleration of subject;50.	"fBodyAccJerk.mean...X"	
	* Frequency-domain (units: hertz); Mean; X-axis; Jerk of acceleration of subject;51.	"fBodyAccJerk.mean...Y"	
	* Frequency-domain (units: hertz); Mean; Y-axis; Jerk of acceleration of subject;52.	"fBodyAccJerk.mean...Z"
	* Frequency-domain (units: hertz); Mean; Z-axis; Jerk of acceleration of subject;53.	"fBodyAccJerk.std...X"	
	* Frequency-domain (units: hertz); Std dev; X-axis; Jerk of acceleration of subject;54.	"fBodyAccJerk.std...Y"	
	* Frequency-domain (units: hertz); Std dev; Y-axis; Jerk of acceleration of subject;55.	"fBodyAccJerk.std...Z"	
	* Frequency-domain (units: hertz); Std dev; Z-axis; Jerk of acceleration of subject;56.	"fBodyAccJerk.meanFreq...X"
	* Frequency-domain (units: hertz); Mean frequency; X-axis; Jerk of acceleration of subject;57.	"fBodyAccJerk.meanFreq...Y"	
	* Frequency-domain (units: hertz); Mean frequency; Y-axis; Jerk of acceleration of subject;58.	"fBodyAccJerk.meanFreq...Z"	
	* Frequency-domain (units: hertz); Mean frequency; Z-axis; Jerk of acceleration of subject;59.	"fBodyGyro.mean...X"	
	* Frequency-domain (units: hertz); Mean; X-axis; Gyroscope measurement of subject;60.	"fBodyGyro.mean...Y"	
	* Frequency-domain (units: hertz); Mean; Y-axis; Gyroscope measurement of subject;61.	"fBodyGyro.mean...Z"	
	* Frequency-domain (units: hertz); Mean; Z-axis; Gyroscope measurement of subject;62.	"fBodyGyro.std...X"	
	* Frequency-domain (units: hertz); Std dev; X-axis; Gyroscope measurement of subject;63.	"fBodyGyro.std...Y"
	* Frequency-domain (units: hertz); Std dev; Y-axis; Gyroscope measurement of subject;64.	"fBodyGyro.std...Z"	
	* Frequency-domain (units: hertz); Std dev; Z-axis; Gyroscope measurement of subject;65.	"fBodyGyro.meanFreq...X"	
	* Frequency-domain (units: hertz); Mean frequency; X-axis; Gyroscope measurement of subject;66.	"fBodyGyro.meanFreq...Y"	
	* Frequency-domain (units: hertz); Mean frequency; Y-axis; Gyroscope measurement of subject;67.	"fBodyGyro.meanFreq...Z"	
	* Frequency-domain (units: hertz); Mean frequency; Z-axis; Gyroscope measurement of subject;68.	"fBodyAccMag.mean.."	
	* Frequency-domain (units: hertz); Mean; Magnitude of acceleration of subject;69.	"fBodyAccMag.std.."	
	* Frequency-domain (units: hertz); Std dev; Magnitude of acceleration of subject;70.	"fBodyAccMag.meanFreq.."	
	* Frequency-domain (units: hertz); Mean frequency; Magnitude of acceleration of subject;71.	"fBodyBodyAccJerkMag.mean.."	
	* Frequency-domain (units: hertz); Mean; Magnitude of jerk of acceleration of subject;72.	"fBodyBodyAccJerkMag.std.."	
	* Frequency-domain (units: hertz); Std dev; Magnitude of jerk of acceleration of subject;73.	"fBodyBodyAccJerkMag.meanFreq.."	
	* Frequency-domain (units: hertz); Mean frequency; Magnitude of jerk of acceleration of subject;74.	"fBodyBodyGyroMag.mean.."	
	* Frequency-domain (units: hertz); Mean; Magnitude of gyroscope measurement of subject;75.	"fBodyBodyGyroMag.std.."	
	* Frequency-domain (units: hertz); Std dev; Magnitude of gyroscope measurement of subject;76.	"fBodyBodyGyroMag.meanFreq.."	
	* Frequency-domain (units: hertz); Mean frequency; Magnitude of gyroscope measurement of subject;77.	"fBodyBodyGyroJerkMag.mean.."	
	* Frequency-domain (units: hertz); Mean; Magnitude of jerk of gyroscope measurement of subject;78.	"fBodyBodyGyroJerkMag.std.."	
	* Frequency-domain (units: hertz); Std dev; Magnitude of jerk of gyroscope measurement of subject;79.	"fBodyBodyGyroJerkMag.meanFreq.."	
	* Frequency-domain (units: hertz); Mean frequency; Magnitude of jerk of gyroscope measurement of subject;80.	"subject"	
	* Subject of the observation;81.	"activity"	
	* Activity performed by subject during observation window;
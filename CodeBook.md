###Code Boo
This code book includes information about the source data, the transformations performed on the data and the variables of the final data sets.

####Study Design

The source data is collected from the UCI Machine Learning Repository. The assignment includes working with the source data and producing tidy data.

####Steps Performed

<ul>
<li>Downloaded the data set</li>
<li>Unzipped the data set into the working directory</li>
<li>Loaded test and training data sets into tables</li>
<li>Loaded the variable names</li>
<li>Loaded the activity labels</li>
<li>Combined test and training data using rbind</li>
<li>Extracted the the mean and standard deviation variables</li>
<li>Added the activity labels for readability</li>
<li>Merged the data to produce one data set containing the subjects, measurements and activities</li>
<li>created a second, independent tidy data set with the average of each variable for each activity and each subject.</li>
</ul>

####Variables


<ul>
<li>subjectId: 1 to 30 each representing a participant in the study</li>
<li>activity: the activity done at the time of the measurement</li>
<li>tBodyAcc-mean-X</li>
<li>tBodyAcc-mean-Y</li>
<li>tBodyAcc-mean-Z</li>
<li>tBodyAcc-std-X</li>
<li>tBodyAcc-std-Y</li>
<li>tBodyAcc-std-Z</li>
<li>tGravityAcc-mean-X</li>
<li>tGravityAcc-mean-Y</li>
<li>tGravityAcc-mean-Z</li>
<li>tGravityAcc-std-X</li>
<li>tGravityAcc-std-Y</li>
<li>tGravityAcc-std-Z</li>
<li>tBodyAccJerk-mean-X</li>
<li>tBodyAccJerk-mean-Y</li>
<li>tBodyAccJerk-mean-Z</li>
<li>tBodyAccJerk-std-X</li>
<li>tBodyAccJerk-std-Y</li>
<li>tBodyAccJerk-std-Z</li>
<li>tBodyGyro-mean-X</li>
<li>tBodyGyro-mean-Y</li>
<li>tBodyGyro-mean-Z</li>
<li>tBodyGyro-std-X</li>
<li>tBodyGyro-std-Y</li>
<li>tBodyGyro-std-Z</li>
<li>tBodyGyroJerk-mean-X</li>
<li>tBodyGyroJerk-mean-Y</li>
<li>tBodyGyroJerk-mean-Z</li>
<li>tBodyGyroJerk-std-X</li>
<li>tBodyGyroJerk-std-Y</li>
<li>tBodyGyroJerk-std-Z</li>
<li>tBodyAccMag-mean</li>
<li>tBodyAccMag-std</li>
<li>tGravityAccMag-mean</li>
<li>tGravityAccMag-std</li>
<li>tBodyAccJerkMag-mean</li>
<li>tBodyAccJerkMag-std</li>
<li>tBodyGyroMag-mean</li>
<li>tBodyGyroMag-std</li>
<li>tBodyGyroJerkMag-mean</li>
<li>tBodyGyroJerkMag-std</li>
<li>fBodyAcc-mean-X</li>
<li>fBodyAcc-mean-Y</li>
<li>fBodyAcc-mean-Z</li>
<li>fBodyAcc-std-X</li>
<li>fBodyAcc-std-Y</li>
<li>fBodyAcc-std-Z</li>
<li>fBodyAccJerk-mean-X</li>
<li>fBodyAccJerk-mean-Y</li>
<li>fBodyAccJerk-mean-Z</li>
<li>fBodyAccJerk-std-X</li>
<li>fBodyAccJerk-std-Y</li>
<li>fBodyAccJerk-std-Z</li>
<li>fBodyGyro-mean-X</li>
<li>fBodyGyro-mean-Y</li>
<li>fBodyGyro-mean-Z</li>
<li>fBodyGyro-std-X</li>
<li>fBodyGyro-std-Y</li>
<li>fBodyGyro-std-Z</li>
<li>fBodyAccMag-mean</li>
<li>fBodyAccMag-std</li>
<li>fBodyBodyAccJerkMag-mean</li>
<li>fBodyBodyAccJerkMag-std</li>
<li>fBodyBodyGyroMag-mean</li>
<li>fBodyBodyGyroMag-std</li>
<li>fBodyBodyGyroJerkMag-mean</li>
<li>fBodyBodyGyroJerkMag-std</li>
</ul>
(I)Activity

============

1 WALKING

2 WALKING_UPSTAIRS

3 WALKING_DOWNSTAIRS

4 SITTING

5 STANDING

6 LAYING



(II) Subject

======================
30 subjects 


(III) Measurement


The measurements are extracted from the following:

i) According to the file data/UCI HAR Dataset/feature_info, 
time domain signals is denoted as 't' and frequency domain signals is denoted as 'f'
So t is replaced with TimeSignal and f is replaced with FrequencySignal

ii)Other shorthand notations are substituted according as follows

mean = Mean

std = StandardDeviation

Acc = Acceleration

Gyro = AngularVelocity as mentioned in feature_info txt

X = Xaxis

Y = Yaxis

Z = Zaxis

BodyBody = to Body (redundency)

(), - = blank



Measurement Variables is as followed (Old vs New)



Old 			                          New 

==========			                    ========

tBodyAcc-mean()-X			            TimeSignalBodyAccelerationMeanXaxis

tBodyAcc-mean()-Y			            TimeSignalBodyAccelerationMeanYaxis

tBodyAcc-mean()-Z			            TimeSignalBodyAccelerationMeanZaxis

tBodyAcc-std()-X			            TimeSignalBodyAccelerationStandardDeviationXaxis

tBodyAcc-std()-Y			            TimeSignalBodyAccelerationStandardDeviationYaxis

tBodyAcc-std()-Z		  	          TimeSignalBodyAccelerationStandardDeviationZaxis

tGravityAcc-mean()-X		          TimeSignalGravityAccelerationMeanXaxis

tGravityAcc-mean()-Y		          TimeSignalGravityAccelerationMeanYaxis

tGravityAcc-mean()-Z		          TimeSignalGravityAccelerationMeanZaxis

tGravityAcc-std()-X			          TimeSignalGravityAccelerationStandardDeviationXaxis

tGravityAcc-std()-Y			          TimeSignalGravityAccelerationStandardDeviationYaxis

tGravityAcc-std()-Z			          TimeSignalGravityAccelerationStandardDeviationZaxis

tBodyAccJerk-mean()-X		          TimeSignalBodyAccelerationJerkMeanXaxis

tBodyAccJerk-mean()-Y		          TimeSignalBodyAccelerationJerkMeanYaxis

tBodyAccJerk-mean()-Z		          TimeSignalBodyAccelerationJerkMeanZaxis

tBodyAccJerk-std()-X		          TimeSignalBodyAccelerationJerkStandardDeviationXaxis

tBodyAccJerk-std()-Y		          TimeSignalBodyAccelerationJerkStandardDeviationYaxis

tBodyAccJerk-std()-Z		          TimeSignalBodyAccelerationJerkStandardDeviationZaxis

tBodyGyro-mean()-X		            TimeSignalBodyAngularVelocityMeanXaxis

tBodyGyro-mean()-Y		            TimeSignalBodyAngularVelocityMeanYaxis

tBodyGyro-mean()-Z	  	          TimeSignalBodyAngularVelocityMeanZaxis

tBodyGyro-std()-X			            TimeSignalBodyAngularVelocityStandardDeviationXaxis

tBodyGyro-std()-Y			            TimeSignalBodyAngularVelocityStandardDeviationYaxis

tBodyGyro-std()-Z		  	          TimeSignalBodyAngularVelocityStandardDeviationZaxis

tBodyGyroJerk-mean()-X	          TimeSignalBodyAngularVelocityJerkMeanXaxis

tBodyGyroJerk-mean()-Y	          TimeSignalBodyAngularVelocityJerkMeanYaxis

tBodyGyroJerk-mean()-Z	          TimeSignalBodyAngularVelocityJerkMeanZaxis

tBodyGyroJerk-std()-X		          TimeSignalBodyAngularVelocityJerkStandardDeviationXaxis

tBodyGyroJerk-std()-Y		          TimeSignalBodyAngularVelocityJerkStandardDeviationYaxis

tBodyGyroJerk-std()-Z		          TimeSignalBodyAngularVelocityJerkStandardDeviationZaxis

tBodyAccMag-mean()		            TimeSignalBodyAccelerationMagMean

tBodyAccMag-std()			            TimeSignalBodyAccelerationMagStandardDeviation

tGravityAccMag-mean()		          TimeSignalGravityAccelerationMagMean

tGravityAccMag-std()		          TimeSignalGravityAccelerationMagStandardDeviation

tBodyAccJerkMag-mean()	          TimeSignalBodyAccelerationJerkMagnitudeMean

tBodyAccJerkMag-std()		          TimeSignalBodyAccelerationJerkMagStandardDeviation

tBodyGyroMag-mean()		            TimeSignalBodyAngularVelocityMagMean

tBodyGyroMag-std()		            TimeSignalBodyAngularVelocityMagStandardDeviation

tBodyGyroJerkMag-mean()	          TimeSignalBodyAngularVelocityJerkMagMean

tBodyGyroJerkMag-std()	          TimeSignalBodyAngularVelocityJerkMagStandardDeviation

fBodyAcc-mean()-X			            FrequencySignalBodyAccelerationMeanXaxis

fBodyAcc-mean()-Y			            FrequencySignalBodyAccelerationMeanYaxis

fBodyAcc-mean()-Z			            FrequencySignalBodyAccelerationMeanZaxis

fBodyAcc-std()-X			            FrequencySignalBodyAccelerationStandardDeviationXaxis

fBodyAcc-std()-Y			            FrequencySignalBodyAccelerationStandardDeviationYaxis

fBodyAcc-std()-Z			            FrequencySignalBodyAccelerationStandardDeviationZaxis

fBodyAcc-meanFreq()-X		          FrequencySignalBodyAccelerationMeanFrequencyXaxis

fBodyAcc-meanFreq()-Y		          FrequencySignalBodyAccelerationMeanFrequencyYaxis

fBodyAcc-meanFreq()-Z		          FrequencySignalBodyAccelerationMeanFrequencyZaxis

fBodyAccJerk-mean()-X		          FrequencySignalBodyAccelerationJerkMeanXaxis

fBodyAccJerk-mean()-Y		          FrequencySignalBodyAccelerationJerkMeanYaxis

fBodyAccJerk-mean()-Z		          FrequencySignalBodyAccelerationJerkMeanZaxis

fBodyAccJerk-std()-X		          FrequencySignalBodyAccelerationJerkStandardDeviationXaxis

fBodyAccJerk-std()-Y	          	FrequencySignalBodyAccelerationJerkStandardDeviationYaxis

fBodyAccJerk-std()-Z		          FrequencySignalBodyAccelerationJerkStandardDeviationZaxis

fBodyAccJerk-meanFreq()-X		      FrequencySignalBodyAccelerationJerkMeanFrequencyXaxis

fBodyAccJerk-meanFreq()-Y		      FrequencySignalBodyAccelerationJerkMeanFrequencyYaxis

fBodyAccJerk-meanFreq()-Z		      FrequencySignalBodyAccelerationJerkMeanFrequencyZaxis

fBodyGyro-mean()-X		            FrequencySignalBodyAngularVelocityMeanXaxis

fBodyGyro-mean()-Y		            FrequencySignalBodyAngularVelocityMeanYaxis

fBodyGyro-mean()-Z		            FrequencySignalBodyAngularVelocityMeanZaxis

fBodyGyro-std()-X			            FrequencySignalBodyAngularVelocityStandardDeviationXaxis

fBodyGyro-std()-Y			            FrequencySignalBodyAngularVelocityStandardDeviationYaxis

fBodyGyro-std()-Z		      	      FrequencySignalBodyAngularVelocityStandardDeviationZaxis

fBodyGyro-meanFreq()-X	  	      FrequencySignalBodyAngularVelocityMeanFreqXaxis

fBodyGyro-meanFreq()-Y	  	      FrequencySignalBodyAngularVelocityMeanFreqYaxis

fBodyGyro-meanFreq()-Z		        FrequencySignalBodyAngularVelocityMeanFreqZaxis

fBodyAccMag-mean()	      	      FrequencySignalBodyAccelerationMagMean

fBodyAccMag-std()		      	      FrequencySignalBodyAccelerationMagStandardDeviation

fBodyAccMag-meanFreq()	          FrequencySignalBodyAccelerationMagMeanFrequency

fBodyBodyAccJerkMag-mean()	      FrequencySignalBodyAccelerationJerkMagMean

fBodyBodyAccJerkMag-std()		      FrequencySignalBodyAccelerationJerkMagStandardDeviation

fBodyBodyAccJerkMag-meanFreq()	  FrequencySignalBodyAccelerationJerkMagMeanFrequency

fBodyBodyGyroMag-mean()	  	      FrequencySignalBodyAngularVelocityMagMean

fBodyBodyGyroMag-std()	  	      FrequencySignalBodyAngularVelocityMagStandardDeviation

fBodyBodyGyroMag-meanFreq()	      FrequencySignalBodyAngularVelocityMagMeanFrequency

fBodyBodyGyroJerkMag-mean()     	FrequencySignalBodyAngularVelocityJerkMagMean

fBodyBodyGyroJerkMag-std()	      FrequencySignalBodyAngularVelocityJerkMagStandardDeviation

fBodyBodyGyroJerkMag-meanFreq()	  FrequencySignalBodyAngularVelocityJerkMagMeanFrequency


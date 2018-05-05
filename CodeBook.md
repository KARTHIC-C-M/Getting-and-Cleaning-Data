## Getting and Cleaning Data Project Coursera

### Description
Additional information about the variables, data and transformations used in the course project for the Johns Hopkins University Getting and Cleaning Data course of Data Science Specialisation.

### Source Data
Data + Description can be found here [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

### Data Set Information
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

## Identifiers
    subject : corresponding ID for the test subject. The ID ranges from 1 to 30
    activity: type of activity for a particular/corresponding measurement
    SITING if the subject was sitting
    LAYING if the subject was laying
    STANDING if the subject was standing
    WALKING if the subject was walking
    WALKING_UPSTARS if the subject was ascending up the stairs
    WALKING_DOWNSTAIRS if the subject was descending down the stairs

## Frequency domain (prefixed by frequencyDomain)
    frequencyDomainBodyAccelerometerMeanX
    frequencyDomainBodyAccelerometerMeanY
    frequencyDomainBodyAccelerometerMeanZ
    frequencyDomainBodyAccelerometerJerkMeanX
    frequencyDomainBodyAccelerometerJerkMeanY
    frequencyDomainBodyAccelerometerJerkMeanZ
    frequencyDomainBodyAccelerometerMeanFrequencyX
    frequencyDomainBodyAccelerometerMeanFrequencyY
    frequencyDomainBodyAccelerometerMeanFrequencyZ
    frequencyDomainBodyAccelerometerStandardDeviationX
    frequencyDomainBodyAccelerometerStandardDeviationY
    frequencyDomainBodyAccelerometerStandardDeviationZ
    frequencyDomainBodyAccelerometerJerkStandardDeviationX
    frequencyDomainBodyAccelerometerJerkStandardDeviationY
    frequencyDomainBodyAccelerometerJerkStandardDeviationZ
    frequencyDomainBodyAccelerometerJerkMeanFrequencyX
    frequencyDomainBodyAccelerometerJerkMeanFrequencyY
    frequencyDomainBodyAccelerometerJerkMeanFrequencyZ
    frequencyDomainBodyGyroscopeMeanX
    frequencyDomainBodyGyroscopeMeanY
    frequencyDomainBodyGyroscopeMeanZ
    frequencyDomainBodyGyroscopeStandardDeviationX
    frequencyDomainBodyGyroscopeStandardDeviationY
    frequencyDomainBodyGyroscopeStandardDeviationZ
    frequencyDomainBodyGyroscopeJerkMagnitudeMean
    frequencyDomainBodyGyroscopeJerkMagnitudeStandardDeviation
    frequencyDomainBodyGyroscopeJerkMagnitudeMeanFrequency
    frequencyDomainBodyGyroscopeMagnitudeMean
    frequencyDomainBodyGyroscopeMagnitudeStandardDeviation
    frequencyDomainBodyGyroscopeMagnitudeMeanFrequency
    frequencyDomainBodyAccelerometerJerkMagnitudeMean
    frequencyDomainBodyAccelerometerJerkMagnitudeStandardDeviation
    frequencyDomainBodyAccelerometerJerkMagnitudeMeanFrequency
    frequencyDomainBodyAccelerometerMagnitudeMean
    frequencyDomainBodyAccelerometerMagnitudeStandardDeviation
    frequencyDomainBodyAccelerometerMagnitudeMeanFrequency
    
## Time domain (prefixed by timeDomain)
    timeDomainBodyAccelerometerMeanX
    timeDomainBodyAccelerometerMeanY
    timeDomainBodyAccelerometerMeanZ
    timeDomainGravityAccelerometerMeanX
    timeDomainGravityAccelerometerMeanY
    timeDomainGravityAccelerometerMeanZ
    timeDomainBodyAccelerometerJerkMeanX
    timeDomainBodyAccelerometerJerkMeanY
    timeDomainBodyAccelerometerJerkMeanZ
    timeDomainBodyAccelerometerStandardDeviationX
    timeDomainBodyAccelerometerStandardDeviationY
    timeDomainBodyAccelerometerStandardDeviationZ
    timeDomainGravityAccelerometerStandardDeviationX
    timeDomainGravityAccelerometerStandardDeviationY
    timeDomainGravityAccelerometerStandardDeviationZ
    timeDomainBodyAccelerometerJerkStandardDeviationX
    timeDomainBodyAccelerometerJerkStandardDeviationY
    timeDomainBodyAccelerometerJerkStandardDeviationZ
    timeDomainBodyGyroscopeMeanX
    timeDomainBodyGyroscopeMeanY
    timeDomainBodyGyroscopeMeanZ
    timeDomainBodyGyroscopeStandardDeviationX
    timeDomainBodyGyroscopeStandardDeviationY
    timeDomainBodyGyroscopeStandardDeviationZ
    timeDomainBodyGyroscopeJerkMeanX
    timeDomainBodyGyroscopeJerkMeanY
    timeDomainBodyGyroscopeJerkMeanZ
    timeDomainBodyGyroscopeJerkStandardDeviationX
    timeDomainBodyGyroscopeJerkStandardDeviationY
    timeDomainBodyGyroscopeJerkStandardDeviationZ
    timeDomainBodyGyroscopeMagnitudeMean
    timeDomainBodyGyroscopeMagnitudeStandardDeviation
    timeDomainBodyGyroscopeJerkMagnitudeMean
    timeDomainBodyGyroscopeJerkMagnitudeStandardDeviation
    timeDomainBodyAccelerometerMagnitudeMean
    timeDomainBodyAccelerometerMagnitudeStandardDeviation
    timeDomainGravityAccelerometerMagnitudeMean
    timeDomainGravityAccelerometerMagnitudeStandardDeviation
    timeDomainBodyAccelerometerJerkMagnitudeMean
    timeDomainBodyAccelerometerJerkMagnitudeStandardDeviation

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

### Attribute Information
For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

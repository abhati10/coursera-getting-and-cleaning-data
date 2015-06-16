
Codebook for wearable computing dataset
Variables

subject                    1..2
    Subject number
                           1..30 .Unique identifier assigned to each subject

label                      6..18
    Acitivity label
                           "WALKING"
                           "WALKING_UPSTAIRS"
                           "WALKING_DOWNSTAIRS"
                           "SITTING"
                           "STANDING"
                           "LAYING"

tbodyaccmeanx              12
    Described below

tbodyaccmeany              12
    Described below

tbodyaccmeanz              12
    Described below

tbodyaccstdx               12
    Described below

tbodyaccstdy               12
    Described below

tbodyaccstdz               12
    Described below

tgravityaccmeanx           12
    Described below

tgravityaccmeany           12
    Described below

tgravityaccmeanz           12
    Described below

tgravityaccstdx            12
    Described below

tgravityaccstdy            12
    Described below

tgravityaccstdz            12
    Described below

tbodyaccjerkmeanx          12
    Described below

tbodyaccjerkmeany          12
    Described below

tbodyaccjerkmeanz          12
    Described below

tbodyaccjerkstdx           12
    Described below

tbodyaccjerkstdy           12
    Described below

tbodyaccjerkstdz           12
    Described below

tbodygyromeanx             12
    Described below

tbodygyromeany             12
    Described below

tbodygyromeanz             12
    Described below

tbodygyrostdx              12
    Described below

tbodygyrostdy              12
    Described below

tbodygyrostdz              12
    Described below

tbodygyrojerkmeanx         12
    Described below

tbodygyrojerkmeany         12
    Described below

tbodygyrojerkmeanz         12
    Described below

tbodygyrojerkstdx          12
    Described below

tbodygyrojerkstdy          12
    Described below

tbodygyrojerkstdz          12
    Described below

tbodyaccmagmean            12
    Described below

tbodyaccmagstd             12
    Described below

tgravityaccmagmean         12
    Described below

tgravityaccmagstd          12
    Described below

tbodyaccjerkmagmean        12
    Described below

tbodyaccjerkmagstd         12
    Described below

tbodygyromagmean           12
    Described below

tbodygyromagstd            12
    Described below

tbodygyrojerkmagmean       12
    Described below

tbodygyrojerkmagstd        12
    Described below

fbodyaccmeanx              12
    Described below

fbodyaccmeany              12
    Described below

fbodyaccmeanz              12
    Described below

fbodyaccstdx               12
    Described below

fbodyaccstdy               12
    Described below

fbodyaccstdz               12
    Described below

fbodyaccjerkmeanx          12
    Described below

fbodyaccjerkmeany          12
    Described below

fbodyaccjerkmeanz          12
    Described below

fbodyaccjerkstdx           12
    Described below

fbodyaccjerkstdy           12
    Described below

fbodyaccjerkstdz           12
    Described below

fbodygyromeanx             12
    Described below

fbodygyromeany             12
    Described below

fbodygyromeanz             12
    Described below

fbodygyrostdx              12
    Described below

fbodygyrostdy              12
    Described below

fbodygyrostdz              12
    Described below

fbodyaccmagmean            12
    Described below

fbodyaccmagstd             12
    Described below

fbodybodyaccjerkmagmean    12
    Described below

fbodybodyaccjerkmagstd     12
    Described below

fbodybodygyromagmean       12
    Described below

fbodybodygyromagstd        12
    Described below

fbodybodygyrojerkmagmean   12
    Described below

fbodybodygyrojerkmagstd    12
    Described below

Data

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).

These signals were used to estimate variables of the feature vector for each pattern:
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

tbodyacc-xyz

tgravityacc-xyz

tbodyaccjerk-xyz

tbodygyro-xyz

tbodygyrojerk-xyz

tbodyaccmag

tgravityaccmag

tbodyaccjerkmag

tbodygyromag

tbodygyrojerkmag

fbodyacc-xyz

fbodyaccjerk-xyz

fbodygyro-xyz

fbodyaccmag

fbodyaccjerkmag

fbodygyromag

fbodygyrojerkmag

The set of variables that were estimated from these signals are:

mean: Mean value

std: Standard deviation
Transformation

All the values are means, aggregated over 30 subjects and 6 activities, hence the resulting dataset is 180 rows by 68 columns.

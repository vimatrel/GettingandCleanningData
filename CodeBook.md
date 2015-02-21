# **Code Book**    
#  
#  
#  
##subject 1  
   Subject Identifier  

    1..30 Unique volunteer identifier from group within an age bracket of 19-48 years  
		1 3 5 6 7 8 11 14 15 16 17 19 21 22 23 25 26 27 28 29 30  .Training Subjects    
		2 4 9 10 12 13 18 20 24  .Test Subjects
 


##activity 7..18
Activity Identifier  
 
	Activity performed during meassurements  
		WALKING  
		WALKING_UPSTAIRS  
		WALKING_DOWNSTAIRS  
		SITTING  
		STANDING  
		LAYING 


##feature  12..24
Feature Identifier  

	Vector of mean and std calculated from features obtained from the sensor of a 
	smartphone (Samsung Galaxy S II) on the subject waist. 
	
	Prefix 't' denotes time domain signals.
	Captured at a constant rate of 50 Hz. Then filtered using a median filter and 
	a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise.

	Prefix 'f' indicates frequency domain signals.
	A Fast Fourier Transform (FFT) was applied to some of these signals.  

	The acceleration signal was separated into body and gravity acceleration signals 
	using another low pass Butterworth filter with a corner frequency of 0.3 Hz.
	Subsequently, the body linear acceleration and angular velocity were derived 
	in time to obtain Jerk signals.  
	Also the magnitude of these three-dimensional signals were calculated using 
	the Euclidean norm.
	
	'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.
	"mean" and "std" indicate the calculation applied to the feature  
	 
		tbodyaccmeanx      		 .Mean of time frequency from body acceleration in axis x 
		tbodyaccmeany     		 .Mean of time frequency from body acceleration in axis y
		tbodyaccmeanz      		 .Mean of time frequency from body acceleration in axis z
		tbodyaccstdx       		 .Standard diviation of time frequency from body acceleration in axis x 
		tbodyaccstdy       		 .Standard diviation of time frequency from body acceleration in axis y
		tbodyaccstdz       		 .Standard diviation of time frequency from body acceleration in axis z
		tgravityaccmeanx   		 .Mean of time frequency from gravity acceleration in axis x
		tgravityaccmeany   		 .Mean of time frequency from gravity acceleration in axis y
		tgravityaccmeanz   		 .Mean of time frequency from gravity acceleration in axis z
		tgravityaccstdx    		 .Standard diviation of time frequency from gravity acceleration in axis x
		tgravityaccstdy    		 .Standard diviation of time frequency from gravity acceleration in axis y
		tgravityaccstdz    		 .Standard diviation of time frequency from gravity acceleration in axis z
		tbodyaccjerkmeanx  		 .Mean of time frequency from jerk acceleration in axis x
		tbodyaccjerkmeany  		 .Mean of time frequency from jerk acceleration in axis y
		tbodyaccjerkmeanz  		 .Mean of time frequency from jerk acceleration in axis z
		tbodyaccjerkstdx   		 .Standard diviation of time frequency from jerk acceleration in axis x
		tbodyaccjerkstdy 	     .Standard diviation of time frequency from jerk acceleration in axis y
		tbodyaccjerkstdz 	     .Standard diviation of time frequency from jerk acceleration in axis z
		tbodygyromeanx   	     .Mean of time frequency from body movement of gyroscope in axis x
		tbodygyromeany    		 .Mean of time frequency from body movement of gyroscope in axis y
		tbodygyromeanz     		 .Mean of time frequency from body movement of gyroscope in axis z
		tbodygyrostdx      		 .Standard diviation of time frequency from body movement of gyroscope in axis x
		tbodygyrostdy      		 .Standard diviation of time frequency from body movement of gyroscope in axis y
		tbodygyrostdz      		 .Standard diviation of time frequency from body movement of gyroscope in axis z
		tbodygyrojerkmeanx 		 .Mean of time frequency from jerk movement of gyroscope in axis x
		tbodygyrojerkmeany 		 .Mean of time frequency from jerk movement of gyroscope in axis y
		tbodygyrojerkmeanz 		 .Mean of time frequency from jerk movement of gyroscope in axis z
		tbodygyrojerkstdx  		 .Standard diviation of time frequency from jerk movement of gyroscope in axis x
		tbodygyrojerkstdy  		 .Standard diviation of time frequency from jerk movement of gyroscope in axis y
		tbodygyrojerkstdz	     .Standard diviation of time frequency from jerk movement of gyroscope in axis z
		tbodyaccmagmean   		 .Mean of time frequency from body acceleration magnitud
		tbodyaccmagstd   	     .Standard diviation of time frequency from body acceleration magnitud
		tgravityaccmagmean 		 .Mean of time frequency from gravity acceleration magnitud
		tgravityaccmagstd  		 .Standard diviation of time frequency from gravity acceleration magnitud
		tbodyaccjerkmagmean		 .Mean of time frequency from jerk acceleration magnitud
		tbodyaccjerkmagstd 		 .Standard diviation of time frequency from jerk acceleration magnitud
		tbodygyromagmean   	     .Mean of time frequency from body movement of gyroscope magnitud
		tbodygyromagstd    	   	 .Standard diviation of time frequency from body movement of gyroscope magnitud
		tbodygyrojerkmagmean 	 .Mean of time frequency from jerk movement of gyroscope magnitud
		tbodygyrojerkmagstd 	 .Standard diviation of time frequency from jerk movement of gyroscope in axis y
		fbodyaccmeanx  		     .Mean of time frequency from body acceleration in axis x 
		fbodyaccmeany  		     .Mean of time frequency from body acceleration in axis y
		fbodyaccmeanz  		     .Mean of time frequency from body acceleration in axis z
		fbodyaccstdx  		     .Standard diviation of time frequency from body acceleration in axis x 
		fbodyaccstdy    	     .Standard diviation of time frequency from body acceleration in axis y 
		fbodyaccstdz     	     .Standard diviation of time frequency from body acceleration in axis z
		fbodyaccjerkmeanx 		 .Mean of time frequency from jerk acceleration in axis x
		fbodyaccjerkmeany        .Mean of time frequency from jerk acceleration in axis y
		fbodyaccjerkmeanz        .Mean of time frequency from jerk acceleration in axis z
		fbodyaccjerkstdx         .Standard diviation of time frequency from gravity acceleration in axis x
		fbodyaccjerkstdy         .Standard diviation of time frequency from gravity acceleration in axis y
		fbodyaccjerkstdz         .Standard diviation of time frequency from gravity acceleration in axis z
		fbodygyromeanx           .Mean of time frequency from body movement of gyroscope in axis x
		fbodygyromeany           .Mean of time frequency from body movement of gyroscope in axis y
		fbodygyromeanz           .Mean of time frequency from body movement of gyroscope in axis z
		fbodygyrostdx            .Standard diviation of time frequency from body movement of gyroscope in axis x
		fbodygyrostdy            .Standard diviation of time frequency from body movement of gyroscope in axis y
		fbodygyrostdz            .Standard diviation of time frequency from body movement of gyroscope in axis z
		fbodyaccmagmean          .Mean of time frequency from body acceleration magnitud
		fbodyaccmagstd           .Standard diviation of time frequency from body movement of gyroscope magnitud
		fbodybodyaccjerkmagmean  .Mean of time frequency from jerk acceleration magnitud
		fbodybodyaccjerkmagstd   .Standard diviation of time frequency from jerk acceleration magnitud
		fbodybodygyromagmean     .Mean of time frequency from body movement of gyroscope magnitud
		fbodybodygyromagstd      .Standard diviation of time frequency from body movement of gyroscope magnitud
		fbodybodygyrojerkmagmean .Mean of time frequency from jerk movement of gyroscope magnitud
		fbodybodygyrojerkmagstd  .Standard diviation of time frequency from jerk movement of gyroscope in axis y


##meanvalue 9..10  
Mean calculated value of feature  

		-0.9976661..0.9745087  Mean calculated value of feature  

##Note:  
	-Data users should be aware that this file only contains the standard deviation 
	 and the mean as a subset of all the available features from the original file.
	-Feature names differ from original source as "()" and some "-" were removes.
	-Source features are normalized and bounded within [-1,1]   

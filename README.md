# data-mining
A computing system that can understand human gestures (American Sign Language)

Initially the data was collected from students (in different groups) for the accelerometer, gyroscope, orientation and EMG sensors. 

Phase 1 – The collected 18 data streams (34 sensor data including the left-hand and right-hand data), are annotated into 10 different files based on the gestures.

Phase 2 – We have performed the feature extraction and the feature selection tasks forming the annotated data from Phase 1 as the input and from different intuitions (using the plotted data of different groups).

Phase 3 - We analyze the feature extraction methods picked in Phase 2 and identify the features that are responsible for the highest variance in the data set, according to the Principal Component Analysis (PCA).

After all the above described phases, we found that the PCA results were very helpful in drilling down the list of candidate sensors for specific gestures based on the principal component MATLAB results. Also, PCA geared us in the right direction with respect to certain wrong intuitions of Phase 2. 

Then the user independent and user dependent analysis were carried out using the raw data collected initially and some of the Machine Learning algorithms like Decision Tree, Support Vector Machine and Artificial Neural Network were implemented. Here, Artificial Neural Network gave us the best possible results in terms of Precision, Recall, F1 score and Accuracy values (calculated from the confusion matrices) in the process of segmenting the sequence of gestures.

# ECG-heart-rate-variability-
This code analysis heart rate variability before and after phsysical activity. The heart rate variability was registered at 250 Hz and recorded in 1 minute. To use this code you need to upload DIANABEFORE.mat and DIANAAFTER.mat, you can record your own Heart rate variability and use it with this program, you just will need to have them in format ".mat"

# 1st part before physical activity
This code open a 2 x 1 figure, graphs 10 seconds of the ECG before physical exertion. At the bottom graph there is the spectrum of the COMPLETE RECORD of the ECG signal. In the graph above, mark the frequency to which the heart rate corresponds in beats per minute.
# 2nd part after physical activty 
This code open a 2 x 1 figure, graphs 10 seconds of the ECG before physical exertion. At the bottom graph there is the spectrum of the COMPLETE RECORD of the ECG signal. In the graph above, mark the frequency to which the heart rate corresponds in beats per minute.
# 3rd part Heart Rate Analysis: BEFORE vs AFTER:
1. Calculate the HR_after / HR_before ratio. And calculates the HR_Frequency_after/ HR_Frequency_before ratio. The code opens a bar figure where you compare the two previous factors. It Can be seen that the ratios between the factors are equal because the relationship they just were simply changed from the time domain to the frequency domain and by the conservation law, the amount of energy remains the same regardless if it is transformed into another type of energy.

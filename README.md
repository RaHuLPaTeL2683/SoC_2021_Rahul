# SoC_2021_Rahul

Task Completed : Task 4(B3), Task 5(B4), Task 6(C1), Task (A12), Task (D5), Task (D6) : Total Credits = 100

### Task 4(B3) : Live Age & Gender Detection : 20 Credit
For this task a tutorial from youtube is referred. Pre-trained caffe model is used as a project module to get the age & gender prediction. In the main code pre-trained models are loaded and used directly as a variable. Live webcam feed is passes through those models and predicted results are put as a text along with square box around dectected face in the resulting cam feed. 

Youtube Tutorial Link - https://www.youtube.com/watch?v=rZTHD-kewt8

### Task 5(B4) : Age & Gender Prediction from Youtube Videos : 20 Credit
Same pre-trained models as used in Task 4(B3) are used here also. In the main code google drive is mounted and set the location for input and output video. Some libraries are installed first and then same as previous code, they are processed and an output file is sent to the drive.

### Task 6(C1) : Age & Gender Detection App : 40 Credit 
With the help of TenserFlow Lite and Android Studio an app is made to predict age and gender through live camera. Basic Youtube tutorial explaining basic things about this android project is reffered for this task. A zip file containing whole android studio project is attached here. 

## Projects Other Than Age & Gender Predictions using Computer Vision

### Task (A12) : Real Time Face Emotion Detection : 10 Credit
From Youtube tutorial a jupyter notbook code is made to dectect real time emotion. The DeepFace is library is used as a main source for this Task.

### Task (D5) : Volume Control using Gestures : 5 Credit 
This project controls volume of computer using hand gestures. A distance between tip of index finger and tip of thumb is referred as a measure for volume. Pre-build HandTracking Module is used to dectect a one hand at a time and it also determine joints of fingers as point. It helps to determine tip of fingers which is main part of project. MediaPipe library is used for making project.

### Task (D6) : Making a Virtual Mouse with CV : 5 Credit
Same hand tracking module is used for this project and it dectects when the index finger or middle finger or both are up, And according to the code written it moving mode is activated when only index finger is up and clicking mode is activated when both fingers are up and distence between them is close.

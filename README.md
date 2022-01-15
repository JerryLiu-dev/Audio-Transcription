# Audio-Transcription

In attempt at speech recognition via 2D convolution, I tried 2 different methods for hyperparameter tuning to optimize the model. The for loops were too intensive for my computer so I opted for the Kerastuner package. 

![alt text](https://github.com/JerryLiu-dev/Audio-Transcription/blob/main/hyperparameter_tuning.PNG)
Near its best:
![alt text](https://github.com/JerryLiu-dev/Audio-Transcription/blob/main/topoart.PNG)

The reason why it could perform even better is that I did not extend the range of the possible amount of filters to be higher.

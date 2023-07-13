# ANVI_HACK
Predict the movement of fingers from muscle activity.
## About us
ALVI labs develop versatile motor interfaces that can restore original fingers movement for people with hand amputee. Our breakthrough technology uses progress of virtual reality and machine learning and provide the best movements experience for people.
This hackathon is good opportunity to push progress in prosthesis development.

## Goal of the Competition
Predict the movement of fingers from muscle activity.

## Data:

* input: 8 channel EMG signal
* output: 3D Hand position (Hand Tracking Oculus Quest 2)
* size of the dataset: 50 minutes
## Metrics:
The average deviation between the prediction and the real position. MAE metric will be used for this.
You need to create a solution that predict hand's fingers positions (described as quaterions) based on data taken from electrodes on myo armband.

To understand which quaternions you need to predict and what is data check Data section.
To understand what is our metric and how to prepare solution check Evaluation section.

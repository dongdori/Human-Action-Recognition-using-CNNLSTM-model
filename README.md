# Human-Action-Recognition-using-CNNLSTM-model
## 1. Problem statement
Task is to classify human action given sensor data of 600 timestep. sensor data is composed of 6 features(accelometer sensor x,y,z / gyroscope sensor x,y,z).
Easily, model have to predict whether it is benchpress or squat or jumpsquat etc.., given sensor data.

## 2. Approach
I augmented data by random rolling(np.roll()) and used CNNLSTM model.
My model achieved top 10% on Dacon Fitness Action Classification competition. 

You can check my notebook to check detailed implementation!

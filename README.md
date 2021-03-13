# Power Quality Classification


## Multi Layer Perceptron
### Dataset 1:
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/MLP/MLP_Model_1.png?raw=true)
### STM32CUBEMX Results 
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/MLP/MLP_STM_Data1.png?raw=true)
### Dataset 2:
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/MLP/MLP_Model_2.png?raw=true)
### STM32CUBEMX Results 
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/MLP/MLP_STM_Data2.png?raw=true)

### Test Results
#### Dataset 1: Test accuracy - 98.79% (using accuracy as a loss function)
#### Dataset 2: Test accuracy - 95.74% (using accuracy as a loss function)

## CNN
### Dataset 1:
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/CNN/CNN_Model_1.png?raw=true)
### STM32CUBEMX Results 
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/CNN/CNN_STM_Data1.png?raw=true)
### Dataset 2:
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/CNN/CNN_Model_2.png?raw=true)
### STM32CUBEMX Results 
![alt text](https://github.com/aswarth123/Amrita_Honeywell_Hackathon/blob/main/images/CNN/CNN_STM_Data2.png?raw=true)

### Test Results
#### Dataset 1: Test accuracy - 100% (using accuracy as a loss function)
#### Dataset 2: Test accuracy - 96.74% (using accuracy as a loss function)



### Progress
- [x] Python Keras model as output.
- [x] The module developed shall read through and parse the csv input files.
- [x] Model should be built and evaluated within your python code.
- [x] STM32MX project to be created to evaluate the memory size of the model
- [ ] Ability to detect a combination of conditions - Higher scores
- [x] Model should be adjustable dynamically to changed sampling rate or number of samples

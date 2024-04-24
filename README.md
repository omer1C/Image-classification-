In this project I build a convolutional neural network that can predict whether two shoes are from the same pair or from two different pairs.
I will be using two different approaches, the first will be CNN - every entery in the data will be to picture of the same shoe one on each other,
left and right.
The second one will be CNN channel - every entery of the data will include 2 diffrente images.
![image](https://github.com/omer1C/Image-classification-/assets/135855862/700126e9-4a56-4ab3-8527-4ed4cc3dc46a)

Generate the same pair: 
![image](https://github.com/omer1C/Image-classification-/assets/135855862/2af1de2a-2194-4105-82f0-1c3de3985b87)

Generate different pair:
![image](https://github.com/omer1C/Image-classification-/assets/135855862/304c944f-9e67-4480-b395-12ae00c27590)

Sanity check will determine if learning has occured, by using the same data as training and validation : 
![image](https://github.com/omer1C/Image-classification-/assets/135855862/d6746509-5da6-4bc6-8dbd-d1e991ded64c)
We can see here that the loss and the accuracy of the train aand validation are more or less the same.


After the sanity check we will train are modle to get the maximum accuracy,
By changing the parameters like learning rate, kernel size, bach size, number of epochs etc.

We can see here that we have overffiting in some points but that's fine, in every epoch we save the best model.

![image](https://github.com/omer1C/Image-classification-/assets/135855862/96e3e3f1-79b1-4422-8cef-2a62492c1a4a)

The best model and parameters achieved here:
![image](https://github.com/omer1C/Image-classification-/assets/135855862/6cee346e-08e9-43cc-bdc5-0dca24a4e98e)


The purpose of this project is to use a convolutional neural network (CNN) to predict dog breeds. 
The pipeline is the evaluation of an image as a dog or a human, then a prediction of which dog breed the dog is, 
or which dog breed the human most resembles. If the image is detected as neither a dog nor a human, the classifier will not run.

In summary, the performance of the pre-trained model I built far exceeded the hand made CNN model. 
The accuracy of the Xception model (pre-trained on ImageNet) reached nearly85% while my CNN was about 11%. 
This improved performance can be attributed to the vast dataset on which the pre-trained model was built. 

# traffic-sign-recognition
<h3> Traffic Sign Recognition </h3>
</br>
<h5> Description </h5>
Traffic sign recongnition is a system used in self driving cars and driving assistance systems for automatic detection of various traffic signs and act or guide according to the sign.</br>
This system will assistant humans when then exceed any traffic limit in driving assistance systems. </br>
This system directs the car according to the traffic sign in the self driving cars. </br>
In this project, we used deep neural networks - convolutional neural network and VGG16 for developing traffic sign recognition system. </br>
We used German dataset which consists around 50,000 images and 43 classes for developing this model. </br>
</br>
<h5> Objectives </h5>
In this project, we are building a neural network model for the German Dataset which detects the particular image type and gives the description of the image i.e, about anyone of the traffic sign. </br>
In the real-time implementation of this model, it predicts the traffic sign with high accuracy. </br>
we are developing a web interface for the model. </br>
</br>
<h5> Scope </h5>
This model can help self-driving cars to recognize traffic signs. </br>
The model will assist the drivers by recognizing the traffic sign. </br>
Traffic sign recognition has become an important research topic in the area of convolution neural network. </br>
In the future, we will implement the traffic sign capture and  recognition over video datasets. </br>
</br> 
<h5> Technologies and libraries used </h5>
Python </br>
Flask </br>
TensorFlow</br>
Numpy </br>
Pandas </br>
OpenCv </br>
Keras </br>
gTTS </br>
Translate </br>
PIL </br>
mathplot </br>
</br>

<h5> CNN Model </h5>
import required libraries. </br>
convert the input images into numpy array. </br>
read the training data using loop and add try exception for any errors. </br>
split the data into training and validation sets. </br>
convert the labelled data to numerical data using onehot encoding. </br>
create a sequential method and add convolving layers and Maxpooling layers. </br>
create the learning phase of the model using compile method. </br>
train and fit the method, add earlystopping as callback method here. </br>
plot the graph for training and validation accuracy. </br>
plot another graph for training loss and validation loss. </br>
get the test data prediction. </br>
save the model in .h5 format. </br>


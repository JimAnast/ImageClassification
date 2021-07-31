# ImageClassification

This is a Python application where TensorFlow is being used for image classification. 

Some important details about the implementation of my application:

First of all, in this application we train a neural network, so that it can classify images of dolphins and sharks with high accuracy. I have collected all of the images from the internet and therefore, I made my own dataset of images of dolphins and sharks. I have split the data manually in training and validation data. Also, I collected a few images for the testing part that I am doing after I have already trained the network. You can find all those data in the attached zip file named "data".

As it is also mentioned with #comment inside the code, before importing, one should make sure that the needed packages that will be imported are all installed in their machine. If not, then install them with "pip install" and then proceed and run the program.

When you want to load the dataset, make sure that you will give the correct path, where you have locally stored the data that you have extracted from the zip file.

Apart from TensorFlow, which is the protagonist library in the application, we are also using other Python libraries, such as NumPy, matplotlib, cv2 and Keras, which acts as an interface for the TensorFlow library.

It can happen that the classification will not work with properly with a low number of epochs/steps per epoch. In case of that happening, you can try to increase the number of epochs and steps per epoch and run the program again. It can reach 100% accuracy, which means that it classifies correctly every image from the testing dataset. When you put the model to train, make sure that you do not put a high number of epochs/steps per epoch, as the model will run out of training data.
The two species can have many images in which they look similar, so the model can have an increased classification difficulty level. That is also one of the reasons that I chose to implement this application, as it is challenging to reach 100% accuracy.

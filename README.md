# Classifier-with-camera
An Object classifier using our webcam.

In this project, We utilize our device camera to classify the object present in front of it.

We use openCV to use the device's camera to get the object images and save them to use as input to our classifier model.

Tkinter library is used to create a GUI for our camera app.

And finally we use Support Vector Machine(SVM) as a classifier to classify the images taken.

We can use DNN to improve the accuracy of the model and we can also implement the model for more than 2 objects.

Working:
1. User Enters the names of the two classes for classification
2. User clicks images of the respective objects of the two classes using the camera
3. User trains the model
4. Use predict to classify the item in front of the camera

Required Libraries:
1. Tkinter
2. openCV
3. Pillow(PIL)
4. Scikit-learn
5. Numpy

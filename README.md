# Image Classifier using TensorflowJS

This is a image classifier where we use the webcam to train the model with predefined images as A, B, C or D. Once trained when any of these objects appear in front of the webcam, we get the image classified as A, B, C or D. We also get the probability of the prediction. 

It is based on the MobileNet model which is trained on the ImageNet dataset. With the K-nearest neighbor approach we do transfer learning, to train the model on four different images.

Since the image classifier is built on TensorflowJS, you done need to install/compile anything. You can just execute the
index.html, enable the webcam, train and test. 

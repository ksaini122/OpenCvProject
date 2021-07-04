# Face Attendence Project

## Packages involved
opencv-python, numpy, face_recognition, dlib, cmake

## Contributed By
Kunal Saini, Kushal Maheshwari, Tanay Bavchikar

## Summary
### Understanding the project
**1)First, look at a picture and find all the faces. **:\
**2)Second, focus on each face and be able to understand that even if a face is turned in a random direction or in bad lighting, it is still the same person.**:\
**3)Third, be able to pick out unique features of the face.**:\
**4)Finally, compare the unique features of that face to all the people you already know to determine the person’s name.**:\

### What's next?
Face Recognition:It involved three steps:
**a) Loading Images and Converting to RGB : The Face Recognition package consists of a load image function that loads the image,then the image has to be converted to RGB.**:\
**b) Find Faces Locations and Encodings:  First we will find the faces in our images.This is done using HOG (Histogram of Oriented Gradients) . Once we have the face they are warped to remove unwanted rotations. Then the image is feed to a pretrained neural network that outputs 128 measurements that are unique to that particular face.**:\
**c) Compare Faces and Find Distance: Once we have done with  encodings for both faces, then we can compare these 128 measurements of these two faces to find similar features. For comparison, use one of the most common Machine Learning methods linear SVM classifier.**:\

### Results
A random image was selected from the dataset and observed the similarities of that image from the image which we have provide in the code.\
**Input Image**:\
![Input](assets/Elon-Musk.jpg)\




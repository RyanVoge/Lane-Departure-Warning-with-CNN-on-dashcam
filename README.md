# **Lane-Departure-Warning-with-CNN-on-dashcam**
The project uses images from the point of view of a vehicle dashcam to predict whether a vehicle is traveling within the lane of a highway or departing from the lane.  Images were collected from a phone mounted to a windshield for three scenarios (1) traveling within the lane, (2) departing lane to right, and (3) departing lane to left.  A convolutional neural network was trained on the three classes of images and evaluated on a holdout sample for high accuracy.  The resulting model prediction was used to score a new video with a message label for the frames where the lane departure was predicted.  

### Built With
Language(s): Python
Libraries: cv2, Keras, matplotlib, numpy

### Authors
Ryan Voge: https://github.com/RyanVoge

### License
This project is licensed under the MIT License - see the LICENSE.md file for details

### Acknowledgements
https://github.com/jorditorresBCN and his article at https://towardsdatascience.com/convolutional-neural-networks-for-beginners-using-keras-and-tensorflow-2-c578f7b3bf25

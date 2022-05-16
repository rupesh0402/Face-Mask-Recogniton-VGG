
# Facemask Recognition using VGG model

Facemask Recognition on via webcam with above 95% accuracy using VGG and another one using Keras and tensorflow while using SDD to train the Model.
As a side project the dataCollector File can be called as Face Recognition project.

For now the second model is inaccurate and buggy. will soon fix it.


## Requirements
#### main:
Keras  
tensorFlow     
VGG  
CV2  
Sklearn  

#### Sub:
 Can also use Matplotlib to Plot the Accuracy and Loss Curve.

 
 
## Features

- Good Accuracy Webcam Face Recogniton.
- easy Model to train.



## Data Set For training:
The dataset for training is Downloaded from Kaggle.
some Basic Images are also kept along the side in the files.

- The downloaded Dataset should be named 'train' and the inner folders should be named 'with_mask', 'without_mask' for smooth functioning of project. 

- no need to seperate data for Training and testing Purpose.
- VGG model doesn't take that much of memory to train.


## Additional:

As a part of increasing accuracy you can also pass cropped Face images from the camera using Cv2.

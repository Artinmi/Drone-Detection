# Drone Detection using convolutional neural network
this application, receives images and predict the Drones and UAV in that image. you can input image to the program and receive the predicted classes with bounding boxes.

<p align="center">
  <img src="https://github.com/Artinmi/Drone-Detection/blob/master/drone.jpg" width="50%" alt="Leg"/>
</p>




<p align="center">
  <img src="https://github.com/Artinmi/Drone-Detection/blob/master/drone%20(1).jpg" width="50%" alt="Leg"/>
</p>

<p align="center">
  <img src="https://github.com/Artinmi/Drone-Detection/blob/master/drone%20(2).jpg" width="50%" alt="Leg"/>
</p>

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Credits](#credits)

## Introduction
We have used YOLO.v8 and ultralytics to train a custom model to detect Drones and UAVs. This Custom Training is based on convolutional neural network (CNN)


The program includes two files ```model_train.ipynb``` and ```model_test.ipynb``` the training file takes about 7 hours to train the model and in the end it gives you best.pt file which includes the weights.
> [!TIP]
> As a user you just have to open ```model_test.ipynb``` file to predict your images



## Dataset
the Data set includes 20 thousand labled pictures of Drones. ( 16 thousand train data , 2 thousand validation data , 2 thousand test data)
you can find the data set [here](https://https://universe.roboflow.com/get/uav-detect-pfiqs/dataset/1/).
   



## Installation
 Clone this repository:

        git clone https://github.com/Artinmi/Drone_Detection.git

## Usage
 Open the ```model_test.ipynb``` in google colab and upload your image you want to predict the UAV in it. run the cells respectively and run the last cell to predict your image. lastly your predicted image will be placed in ```runs/detect/predict``` folder.

<p align="center">
  <img src="https://github.com/Artinmi/Drone-Detection/blob/master/drones.jpg" width="95%" alt="Leg"/>
</p>
        
## Credits

### Contributions
Contributions are always welcome! If you'd like to improve the project or add new features:
1. Fork this repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request for review.

### Contact
If you have any questions or suggestions, feel free to reach out:

- Artin Mokhtariha - [artin1382mokhtariha@gmail.com](mailto:artin1382mokhtariha@gmail.com)
- GitHub: [Artinmi](https://github.com/Artinmi)
- Linkedin Post: [Click here](https://www.linkedin.com/posts/artin-mokhtariha-759a3b330_dronedetection-deeplearning-yolov8-activity-7293599568674349057-x8xW?utm_source=share&utm_medium=member_desktop)


![image](https://github.com/user-attachments/assets/56449746-ee22-4f13-ba6f-78352d836c04)# Drone Detection using convolutional neural network

this application, receives images and predict the Drones and UAV in that image. you can input image to the program and receive the predicted classes with bounding boxes.

<p align="center">
  <img src="https://github.com/Artinmi/Drone-Detection/blob/master/drone.jpg" width="45%" alt="Leg"/>
</p>


<p align="center">
  <img src="https://github.com/Artinmi/Drone-Detection/blob/master/drone%20(1).jpg" width="45%" alt="Leg"/>
</p>

<p align="center">
  <img src="https://github.com/Artinmi/Drone-Detection/blob/master/drone%20(2).jpg" width="45%" alt="Leg"/>
</p>

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)


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
        


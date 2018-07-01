# faceRecognition

This repository contains code for facial recognition using openCV and python with a tkinter gui interface. It takes 50 images for an individual during the training phase. After that it uses openCV to create a label and features for the training images and saves it as a yml file.<br /><br />
During the tracking phase, it opens a csv file containing the id and name and matches the predicted id with it. If it matches them id and name of the indiviuals are displayed else it displays unknown. It also captures the timestamp of the tracked person and saves it as a csv file.<br /><br />
If you want to use this code then download the project and change the path values in train.py and run it. If you want to convert the python code into executable format run the setup.py

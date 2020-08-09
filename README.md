#  Facial recognition based Attendance Management System

![title](facial_2.png)


This repository contains code for facial recognition using OpenCV and python with a Tkinter GUI interface. If you want to test the code, then run the train.py file.

The technology used: OpenCV (Opensource Computer Vision) -Python -Tkinter  GUI interface


Here I am working on a Face recognition based Attendance Management System by using OpenCV(Python). One can mark their attendance by merely facing the camera.
How it works :

When we run, train.py, a window is opened and asks for entering Id and Enter Name. 

After entering the name and id, then we have to click the Take Images button. By clicking Take Images camera of running, the computer is opened, and it starts taking an image sample of the person. This Id and Name is stored in folder StudentDetails, and the file name is StudentDetails.csv. It takes 60 images as a sample and stores them in folder TrainingImage.After completion, it notifies that pictures saved.

After taking the image sample, we have to click the Train Image button. It takes a few seconds to train the machine for the images taken by clicking the Take Image button and creating a Trainner.yml file and store in the TrainingImageLabel folder. 

Now all initial setups are done. By clicking the Track Image button camera of the running machine is opened again. If the system recognizes the face, then Id and Name of person are shown on Image.

Press Q(or q) for quit this window. After quitting it, attendance of person will be stored in the Attendance folder as CSV file with name, id, date, and time and it is also available in the window.


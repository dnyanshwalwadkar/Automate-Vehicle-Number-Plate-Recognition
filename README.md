# Automate-Vehicle-Number-Plate-Recognition

Automatic number plate recognition (ANPR) is quickly becoming an increasingly popular solution offering organisations effective visitor and car park access management.

Several trends and challenges are driving the popularity of this solution, such as increasing vehicle thefts, security concerns as well as the growing interest in smart parking solutions and automated vehicle identificatio.

We are using Faster RCNN Inception V2 COCO Model for Deep Learning Algorithm.
## What Exactly Is ANPR?

  
![alt text](https://github.com/dnyanshwalwadkar/Automate-Vehicle-Number-Plate-Recognition/blob/main/ANPR-DEMO.png)



Automatic Number Plate Recognition is a technology that uses optical character recognition to read vehicle registration plates. Initially, ANPR was used by police forces around the world for law enforcement purposes.

However, it soon entered the security market as more and more providers saw the benefits of utilising this solution for applications such as electronic toll collection, parking management and smart parking

## ANPR Technology: How Does It Work?
ANPR is a type of camera that automatically reads vehicle number plates as they approach, allowing these details to be compared against database records.

This camera takes an image of a vehicle number plate, which then is passed on to a reader that locates a vehicle's number and converts valid number plates into standard Wiegand format ID numbers.

This data is then analysed by the access control system which decides whether to allow or deny access to this vehicle. If the access is verified, then the controller sends a signal to the barrier/gate to open.

An ANPR system consists of the following elements:

A high-definition infrared digital camera that illuminates and captures an image of the vehicle’s number plate. Some ANPR cameras can even take images at the speed of up to 240km/h.
Computer server with software to process the information.
Wi-Fi, Ethernet or any other forms of the high-speed data network to transmit the vehicle’s number to computer software for identifying and verifying an approaching vehicle.
A database of employee’s and authorised individuals’ number plates.
Barriers, gates etc. as a physical barrier for entering the premises.
Access controller connected to all of the above.
# Project Architecture & Flow

![alt text](https://github.com/dnyanshwalwadkar/Automate-Vehicle-Number-Plate-Recognition/blob/main/Project-Architecture.jpg)

### We have focused on following stages manily.
1. Data Collection & Augmentations
2. Data Prerapration 
3. Data Annotation
4. Model Traning for higher accuracy

![alt text](https://github.com/dnyanshwalwadkar/Automate-Vehicle-Number-Plate-Recognition/blob/main/Car-Detected.jpg)

## Important Requirements as per our current development 

![alt text](

Flask==1.1.1

Keras-Applications==1.0.8
Keras-Preprocessing==1.1.0

matplotlib==3.1.1

numpy==1.17.3
object_detection-0.0.3.tar
opencv-contrib-python==4.1.1.26
Pillow==6.2.0

tensorboard==1.14.0
tensorflow==1.14.0
tensorflow-estimator==1.14.0


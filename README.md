
# Vehicle Detection system
## Yolov8+Sort(For Tracking) 

This project detect the Vehicle and count them. Yolov8 is used to detect the Vehicles and sort model is used to track the vehicles.  
To build this project I use pretrained model which is trained on COCO data set and my all classes whic i need present in COCO dataset. So i do not train it on my customized data.  
But issue is that, I am not able to detect Auto. And this model consider Auto as a truck wihich is not correct.



## Demo
![Image](https://github.com/Asad-Mhmood/VehicleDetectionSystem/blob/master/data/1.PNG)
## Video
[Watch this video](https://youtu.be/1z4_jPtqKFc?si=VLkZ5aO4Gc4sqL5-)




## Installation



```bash
  pip install -r requirements.txt
```
if Libraries/Dependencies are not install using this command than you have to download these libraries manualy using pip.
You have to go terminal and install each library using following command:
```bash
  pip install library-name
```

## How to use the Project
1: You have to download all dependencies which mention in requirements file. You can install these dependencies by the methods which mention in Installation section.  

2: After installation you have to add video in the project. You hav to give the path of the video in run.py where i mention. 

3: After this how have to change the limits of your line accordingly 

4: Chage the logic of detection according to your requirements. I mentionin the code where you have to make changes.

## Limitations

This project have some limitations like it is not able to use the id which is given by tracker properly. This issue occur because detection and tracking models working sperately.

## Solution
To solve this issue i use Bytetrack tracking model instead of sort. Using ByteTrack we can perform detections and tracking at the same time. And can get ids of object during detection.


# Vehicle Detection system

This project detect the Vehicle and count them. Yolov8 is used to detect the Vehicles and sort model is used to track the vehicles.  
To build this project I use pretrained model which is trained on COCO data set and my all classes whic i need present in COCO dataset. So i do not train it on my customized data.  
But issue is that, I am not able to detect Auto. And this model consider Auto as a truck wihich is not correct.



## Demo
![Image](https://github.com/Asad-Mhmood/VehicleDetectionSystem/blob/master/data/1.PNG)

[Watch this video](https://youtu.be/1z4_jPtqKFc?si=VLkZ5aO4Gc4sqL5-)




## Installation



```bash
  pip install -r requirements.txt
```
if Libraries/Dependencies are not install using this command than you have to download these libraries manualy using pip.
You have to go terminal and install each library using following command:
```bash
  pip install libraries-name
```
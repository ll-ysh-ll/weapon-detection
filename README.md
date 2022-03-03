# Weapon Detection

Weapon detection only using visiual inspection

#### YOLO v4 :
YOLO is a state-of-the-art, real-time object detection algorithm. In this notebook, we will apply the YOLO algorithm to detect objects in images. darknet prints out the objects it detected, its confidence, and how long it took to find them. We didn't compile Darknet with OpenCV so it can't display the detections directly. Instead, it saves them in predictions.png. You can open it to see the detected objects. Since we are using Darknet on the CPU it takes around 6-12 seconds per image. If we use the GPU version it would be much faster.
checkout [![@AlexeyAB](https://img.shields.io/badge/AlexeyAB-%20-black)](https://github.com/AlexeyAB/darknet) for more information on YOLO

#### Classes used for training :
- Handgun
- Knife

#### Dataset gathering and image annotation:

labeling tool: [![@labelImg](https://img.shields.io/badge/LabelImg-%20-blue)](https://github.com/tzutalin/labelImg)
#### Loss and mAP chart 
![App Screenshot](https://github.com/ll-ysh-ll/weapon-detection/blob/master/Screenshots/chart_yolov4-custom%20(4).png?raw=true)



## Screenshots

#### Weapon Detection on Images
![App Screenshot](https://github.com/ll-ysh-ll/weapon-detection/blob/master/Screenshots/(1).jpeg?raw=true)
![App Screenshot](https://github.com/ll-ysh-ll/weapon-detection/blob/master/Screenshots/(2).jpeg?raw=true)
![App Screenshot](https://github.com/ll-ysh-ll/weapon-detection/blob/master/Screenshots/(3).jpeg?raw=true)
![App Screenshot](https://github.com/ll-ysh-ll/weapon-detection/blob/master/Screenshots/(4).jpeg?raw=true)


# CV-Based-Waste-Management-System
This is a computer vision based automatic waste management system built as a demonstration for real world project. In this work real data is used to facilitate the system; Basler industrial video camera is used to collect dataset, you can refer the official python support for this system in their github https://github.com/basler/pypylon. For the computer vision task the latest yolo model is used yolov8 https://github.com/ultralytics/ultralytics, so this model is trained on custom collected dataset, and for showcase it was trained only on two classes paper and plastic and the model is good it was able to generalize well with small dataset.
## 1. Collect dataset
![image](https://user-images.githubusercontent.com/96078343/229242536-ac0e0d65-1939-4398-ade2-a0f51ff461cc.png)
## 2 Annotatioin for object detection using computer vision annotation tool https://www.cvat.ai/
![image](https://user-images.githubusercontent.com/96078343/229242924-0587d45d-d179-420e-a717-954aedb5e0a5.png)
## 3 Train YOLO v8 model
## 4 Deploy the trained model with real time input from idustrial video camera

https://user-images.githubusercontent.com/96078343/229243202-fb0c706e-1d6f-4539-9ee1-02596fde80d2.mp4


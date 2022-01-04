# Real Time Object Detection using YOLO (You Only Look Once)

## How To Use 

### Files needed in Directory :
- yolov3.weights* 
- yolov3.cfg* 
- coco.names* 

weights and cfg files downloaded from https://pjreddie.com/darknet/yolo/

coco.names file downloaded from https://github.com/pjreddie/darknet/blob/master/data/coco.names, 
inside this file contains the classes available in the yolo packages so that the detected object is a class from the coco.names file.

### Preparation
- Open Text Editor like Visual Studio Code, or PyCharm which is specific to python programming.
- In Pycharm, create Virtual Environtment (venv) using python3.8, etc.
- Install Packages like cv2 and numpy
- Insert 3 files that needed above to main program file

### Use this python code to run a program. Program will automatically open web cam to start detection an Objects. Make sure that your memory RAM is 4 GB because RAM usage caused by running this program is so large that it can cause laptop performance to slow down.




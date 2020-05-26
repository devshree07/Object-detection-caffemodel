# Real time object detection using pretrained mobile net SSD model in caffe 

Install dependencies like imutils, opencv in python using following commands:
1. pip install imutils
2. pip install opencv-python==4.1.0.25 (Later versions through an error while using webcam)

To run the main file use the below given command:<br>
python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --confidence 0.2

<b> Note: You can tweak the level of confidence as any value between 0 to 1 but 0.2 is a preferable choice.<b/>

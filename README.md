# Object Detection using YOLOv3

### Project Description
The project utilizes OpenCV library to apply YOLO algorithm for object detection in images, videos and real time. The code is compatible to run on a CPU. I used the pre-trained weights of COCO dataset which is capable of recognizing 80 objects. A Tkinter window popup allows you to load video and images from local disk and display results. For real time detection, a pop up window on the running file would display results given that one has web cam access.

### Link to download pre-trained weights of COCO dataset
Create a folder using titled "weights" and add these files. For better speed in videos and real time, one can use the tiny weights file instead of the original one. However, the detection becomes a little less efficient in this case. So, try using the original weights file for more accuracy.
1. https://pjreddie.com/media/files/yolov3.weights
2. https://pjreddie.com/media/files/yolov3-tiny.weights

### Libraries Used in Project
1. OpenCV 3.4.2 (Try using this version or its later developments)
2. Numpy 1.19.1
3. Tkinter 8.6

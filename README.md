# Yolov3-Object-Detection

This project implements an image and video object detection classifier using pretrained yolov3 models. The yolov3 models are taken from the official yolov3 paper which was released in 2018. The yolov3 implementation is from darknet. Also, this project implements an option to perform classification real-time using the webcam.

## How to use?
1. Clone the repository

  ` git clone https://github.com/qusaionali/Yolov3-Object-Detection.git`
  
2. Move to the directory

  ` cd YOLOv3-Object-Detection`
  
3. To infer on an image that is stored on your local machine

  ` python yolo.py --image-path='/path/to/image/'`
  
4. To infer on a video that is stored on your local machine

  ` python yolo.py --video-path='/path/to/video/'`
  
5. To infer real-time on webcam

  `python yolo.py`

Note: You will need to download the Yolo pretrained weights. This works considering you have the weights and config files at the yolov3-coco directory.
If the files are located somewhere else then mention the path while calling the yolov3.py. 
For more details:

` yolo.py --help`

## Inference on images

![](YOLOv3-Object-Detection-with-OpenCV-master/images/4.png)
![](YOLOv3-Object-Detection-with-OpenCV-master/images/2.png)
![](YOLOv3-Object-Detection-with-OpenCV-master/images/1.png)
![](YOLOv3-Object-Detection-with-OpenCV-master/images/5.png)


## Inference on Video

![](YOLOv3-Object-Detection-with-OpenCV-master/images/demo.gif)

## Inference in Real-time

![](YOLOv3-Object-Detection-with-OpenCV-master/images/3.jpg)


References:

[PyImageSearch YOLOv3 Object Detection with OpenCV Blog](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/)

License:
> The code in this project is distributed under the MIT License.

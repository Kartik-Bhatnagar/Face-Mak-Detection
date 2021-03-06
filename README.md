# Face-Mak-Detection
Object Detection

Object detection is a computer vision technique that allows us to identify and locate objects in an image or video. With this kind of identification and localization, object detection can be used to count objects in a scene and determine and track their precise locations, all while accurately labeling them.

Object detection is commonly confused with image recognition. -> Image recognition assigns a label to an image.
A picture of a mask receives the label “mask”. A picture of two masks, still receives the label “mask”. -> 
Object detection, on the other hand, draws a box around each mask and labels the box “mask”. The model predicts where each object is and what label should be applied. In that way, object detection provides more information about an image than recognition.

![th-4027857752](https://user-images.githubusercontent.com/80669502/175999066-e5e05859-cba8-4558-a446-1872ea8dfbac.jpg)

![th-3179749370](https://user-images.githubusercontent.com/80669502/175999622-c7541473-4fa6-4af8-a155-0ed3eb41c9a5.jpg)

Object detection can be broken down into machine learning-based approaches and deep learning-based approaches.
In more traditional ML-based approaches, computer vision techniques are used to look at various features of an image, such as the color histogram or edges, to identify groups of pixels that may belong to an object. These features are then fed into a regression model that predicts the location of the object along with its label.

On the other hand, deep learning-based approaches employ convolutional neural networks (CNNs) to perform end-to-end, unsupervised object detection, in which features don’t need to be defined and extracted separately.

**How does object detection work?**

Deep learning-based object detection models typically have two parts. An encoder takes an image as input and runs it through a series of blocks and layers that learn to extract statistical features used to locate and label objects. Outputs from the encoder are then passed to a decoder, which predicts bounding boxes and labels for each object.

A number of popular object detection models belong to the R-CNN family. Over the years, they’ve become both more accurate and more computationally efficient. There are also a number of models that belong to the single shot detector family. MobileNet + SSD models feature a MobileNet-based encoder and the YOLO model features its own convolutional architecture.

**Purpose**

The main purpose of object detection is to identify and locate one or more effective targets from still image or video data. It comprehensively includes a variety of important techniques, such as image processing, pattern recognition, artificial intelligence and machine learning.
It has broad application prospects in such areas such as road traffic accident prevention [1], warnings of dangerous goods in factories, military restricted area monitoring and advanced human–computer interaction.
Since the application scenarios of multi-target detection in the real world are usually complex and variable, balancing the relationship between accuracy and computing costs is a difficult task.

**Outline**

In this project, we will detect the objects from a still image with the help of OpenCV library in Python. OpenCV library is widely known for image processing, object detection and has many real world applications.
After importing the necessary libraries, we would read the sample image, train the model, use the coco dataset for the pre-defined classes (objects) and as an outcome we would detect the object, it's location, accuracy and index of the class (which helps us to identify the object).
Successfully in this project objects such as person, car, truck and traffic light are detected accurately from the image. Also the average accuracy of the model is greater than 60% which is fair enough.
Object detection using deep learning with OpenCV and Python
When it comes to object detection, popular detection frameworks are

YOLO
SSD
Faster R-CNN
Dependencies
opencv
numpy
matplotlib
![th-3179749350](https://github.com/Kartik-Bhatnagar/Face-Mak-Detection/blob/main/results/Face-mask-web-cam.gif))

# MiniProject2

# Introduction 
YOLO is a new approach to detect objects. It performs an fast and accurate real-time objects detection. Moreover, you can easily tradeoff between speed and accuracy simply by changing the size of the model, no retraining required!
# Summary of Reference
YOLO is based on a regression problem to spatially separated bounding boxes and associated class probabilities. It could accomplish a full image detection in one evaluation with a single network. The networks divide images into several regions and predict bounding boxes and probabilities for each region.It is much faster and easier to optimize than other detectors.
# Result 
First, I run detector with one image, and the result is shown below.  
![resource](https://github.com/qinghan531/MiniProject2/blob/master/predictions.jpg)  
![resource](https://github.com/qinghan531/MiniProject2/blob/master/Output_dog.png)  
It takes around 18 seconds to run detection, and the confidence for each objects are displayed. As the data shown above, the detetction progress is really fast and the result is accurate.
# Pros & Cons
Pros: The  object detection is fast and accurate.It can simply detect multiple images in a row. 
Cons: low accuracy, small objects in group such as flocks of birds, new or unusual objects, incorrect localization
#Reccomendations
Autodriver, delivery robots

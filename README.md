## This is a license plate recognition project. The system can recognize the license plate in the images and videos, and calculate how long the license plate is visible in the video.
## This folder contains all Zhe Cui's work, which is completed by Zhe Cui independently.
License plate recognition system is divided into two parts, license plate location and character recognition.

<br>(1) The **Character Recognition folder** contains *Hog_SVM.ipynb* and the *CNN character dataset*. 
<br>(2) **License Plate Recognition folder** contains *LPR_1.ipynb* and *License plate dataset*, and *a demo of identifying the license plate that appears in the video* (output.avi). 

<br> I use **Unet** to locate the license plate. And I use the Scrapy framework of Python language to code the web crawler, 500 images are crawled according to the keywords, then label them manually. **License Plate Recognition folder**, this folder contains the implementation of the license plate location and 500 images of the car license plates that have been labeled.

<br>I use HOG+SVM to implement character recognition. **License Plate Recognition folder**, this folder contains the implementation of the single character recognition, the **CNN letter Dataset**, this folder contains the images of 0-9 and A-Z, which are cut from the license plate, and I have labeled them as well.

<br>The system can recognize the license plate in the picture and video. 
<br>Please click here to see the demo of identifying the license plate that appears in the video:https://www.youtube.com/watch?v=TcZ0gQQxhY0

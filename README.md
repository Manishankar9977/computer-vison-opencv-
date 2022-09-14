# computer-vison-opencv

Computer vision is the field of computer science that focuses on creating digital systems that can process, analyze, and make sense of visual data (images or videos) in the same way that humans do. The concept of computer vision is based on teaching computers to process an image at a pixel level and understand it.

Face Detection:

Face Detection From an Image in Python using OpenCV https://github.com/opencv/opencv/tree/master/data/haarcascades You need to download the trained classifier XML file (haarcascade_frontalface_default.xml), which is available in OpenCv’s GitHub repository. Save it to your working location.
The detection works only on grayscale images. So it is important to convert the color image to grayscale
Detect faces in the image The detectMultiScale function is a general function that detects objects. Since we are calling it on the face cascade, that’s what it detects.
The first option is the grayscale image.
The second is the scaleFactor. Since some faces may be closer to the camera, they would appear bigger than the faces in the back. The scale factor compensates for this.
The detection algorithm uses a moving window to detect objects. minNeighbors defines how many objects are detected near the current one before it declares the face found.

Output for face detection in images:

![Screenshot (170)](https://user-images.githubusercontent.com/91583687/190114875-a233db5c-464b-462e-ac75-16f851af7011.png)

output for live detection:

![Screenshot (173)](https://user-images.githubusercontent.com/91583687/190121762-32ae0cbb-bda3-461e-a392-11744854fb0d.png)


![Screenshot (172)](https://user-images.githubusercontent.com/91583687/190115236-16e020d6-e646-4e74-8ab6-61c7b980d252.png)


## Setup
### Install opencv
https://docs.opencv.org/3.4/d1/d0a/tutorial_java_eclipse.html


## Next steps
- [ ] allow use of test images in addition to feed from camera
- [ ] add tests
- [ ] separate image detection logic to be used independently on the robot
- [ ] find a way to detect lines
- [ ] give answer as x,y relative to camera



## Object Recognition with OpenCV and JavaFX

*Computer Vision course - [Politecnico di Torino](http://www.polito.it)*

A project, made in Eclipse (Neon), for identify and track one or more tennis balls. It performs the detection of the tennis balls upon a webcam video stream by using the color range of the balls, erosion and dilation, and the `findContours` method. Some screenshots of the running project are available in the `screenshots` folder.

Please, note that the project is an Eclipse project, made for teaching purposes. Before using it, you need to install the OpenCV library (version 3.x) and JavaFX 8 and create a `User Library` named `opencv` that links to the OpenCV jar and native libraries.

A guide for getting started with OpenCV and Java is available at [http://opencv-java-tutorials.readthedocs.org/en/latest/index.html](http://opencv-java-tutorials.readthedocs.org/en/latest/index.html).

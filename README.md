# Vehicle-Speed-Estimation-using-Open-CV-Python
Introduction :
This project uses the optical flow algorithm, specifically the Lucas-Kanade tracker, to estimate vehicle speeds from mono camera (CCTV) footage. Speed of a vehicle is an important parameter in many application areas such as traffic management, law enforcement and autonomous vehicles. It is being used for road safety monitor, speed control enforcement actions and increased efficiency of transportation systems due to accurate estimation. Now we can calculate the speed of a vehicle by using computer vision and machine learning. Here we are going to learn how to estimate the speed of a car and for that, I will be using Computer Vision powerful library OpenCV in Python. OpenCV is a complete open- source platform that has useful tools related to processing video and image, which makes it an excellent choice for implementing speed estimation systems.

Language And Interface :-
Vehicle Speed Estimation Using Python , A Versatile Programming Language With Source Code

Required Modules Or Packages:-
You Need The Packages List Given Below :-

sys :- System-specific parameters and functions sys This module provides access to some variables used or maintained by the interpreter .
_future_ :- gives access to features from future python versions in the current interpreter, permitting forward compatibility.
Functools :- Implements higher-order functions for working with functions, such as decorators and other tools to build fault-tolerant APIs.
Numpy :- It is a core library for numerical computation in python and it can handle large arrays of numbers.
cv2 :- It is a library to use in Computer Vision You will get basic image processing tools while using cv2 for example, Image Reading and Writing .
Os :- It offers facilities for working with OS, such as handling files and
Itertools :-This module implements a number of iterator building blocks inspired by constructs from APL, Haskell.
Contextlib :- some of the utilities I have found useful when working with context managers and code that need to close up resources, used in combining multiple operations together which requires being executed in one section killed.
Common :- Often just a shared module or package, but not including
Video :- Likely a custom or implementation specific video processing module in your project and not one from the standard libraries.
tst_scene_render :- Most likely a package or custom module for scene rendering in some form of test environment, not part of the standard library.
How to Run the Code :
Step 1 . First , You Download and Install Visual Studio Code or VS Code In your PC or Laptop by VS Code Official Website .
Step 2 . Now Open CMD As Administrator and install the above packages using pip .
Step 3 . Now Open Visual Studio Code .
Step 4. Now Make The files named as main.py , common.py , tst_scene_render.py , video.py .
Step 5 . Now Copy And Paste The Code Given Below 𝗍
Step 7 . After pasting The code , Save This & Click On Run Button . Step 8 . Now You will See The Output ..

Code Explanation :-
This is a Python Script to estimate vehicle speed in videos . It is a computer vision and numerical computation code, based on OpenCV and NumPy.

Overview:
The script first needs to import some essential libraries such as: sys for system operation; numpy is a numerical processing library; cv2 is the helper of all openCV

operations. And it imports a custom module video for the tools at use with capture, and common utilities as well. Print functions derived from future that guarantees compatibility with Python 2/3.

Main Components:

App Class, it is at the core of this script and will include video processing functions as well as vehicle tracking logic.

Initialization: It performs video capture, sets parameters for tracking and initializes to track variables. Video is used to open the video source. create_capture.

Main Loop:

Parameter Setup: parameters setting for Lucas-Kanade tracking and feature detection

Implementation: It carries out optical flow tracking and for each valid frame, it uses the above speeds in different lanes to track feature points that off-passes are counted every 5 seconds.

Speed Calculation — Analyzes the distance that tracked points have traveled to determine vehicle speed within set lanes and convert pixel measurements into KomotorHeures.

Visualisation — Draws tracked points and lane boundaries on video frames, as well as the speeds that have been calculated. It saves the video that is annotated after

processing :

Main Function (main): This is the entry point of any script. It consumes the video source(bpu on voxl and a file) from command-line arguments or it defaults to webcam. It causes a creating new App object and the trackin starting.

Execution:

The script can be run, and it will go through video frames for vehicle tracking with the Lucas-Kanade method diffusion (for moving objects), speeds calculation from point to other in one frame process using required computer vision techniques; such as optical flow ) alongwith saving this data into a Video file. It gives a live view of the speeds and

lane tracking for vehicles so can be used as a traffic analysis and monitoring tool.

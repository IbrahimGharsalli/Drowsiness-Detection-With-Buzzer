# Drowsiness and Yawn detection with buzzer using Dlib

Simple code in python to detect Drowsiness and Yawn and alert the user using Dlib.

## Dependencies

1. Python 3
2. opencv
3. dlib
4. imutils
5. scipy
6. numpy
7. argparse

## How to Install OpenCV

** Access the terminal of your Pi
1. Update and upgrade : sudo apt-get update && sudo apt-get upgrade
2. Check your python version : python3 -V
3. sudo apt-get install python3-pip python3-virtualenv
4. mkdir project
5. cd project
6. python3 -m pip install virtualenv
7. python3 -m virtualenv env
8. source env/bin/activate
9. sudo apt install -y build-essential cmake pkg-config libjpeg-dev libtiff5-dev libpng-dev libavcodec-dev libavformat-dev libswscale-dev libv4l-dev libxvidcore-dev libx264-dev libfontconfig1-dev libcairo2-dev libgdk-pixbuf2.0-dev libpango1.0-dev libgtk2.0-dev libgtk-3-dev libatlas-base-dev gfortran libhdf5-dev libhdf5-serial-dev libhdf5-103 libqt5gui5 libqt5webkit5 libqt5test5 python3-pyqt5 python3-dev
10. Install OpenCV : pip install opencv-contrib-python --Takes a long time

## Run 

```
Python3 drowsiness_yawn.py -- webcam 0		//For external webcam, use the webcam number accordingly
```

## Setups

Change the threshold values according to your need
```
EYE_AR_THRESH = 0.3
EYE_AR_CONSEC_FRAMES = 30
YAWN_THRESH = 10`	//change this according to the distance from the camera
```

## Authors

** IBRAHIM GHARSALLI 


## Acknowledgments

* https://www.pyimagesearch.com/
* Arijit1080
* Sam Westby Tech



# Face-Tracking-With-Camera
opencv, serial converter, arduino, servo motor and webcam

-----Adding a python library-----

//Serial

After running cmd as administrator on the computer, we write the following code:

pip install serial

//OpenCV

After running cmd as administrator on the computer, we write the following code:

pip install opencv-python

-----Adding an Arduino library-----

//Servo.h

After writing servo in the library adding section in Arduino, we install the necessary plugins.

-----Places to change in python code------

vid=cv2.VideoCapture(0)                                                    #   <---- Select your camera as 0 or 1. On laptops, disable the computer's own camera.

ArduinoSerial=serial.Serial('com5',9600,timeout=0.1)                       #   <---- ENTER YOUR PORT NUMBER



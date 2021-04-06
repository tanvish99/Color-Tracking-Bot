# Color-Tracking-Bot

A mobile robot built using Raspberry Pi which detects initialized colored objects and follows it using the Pi camera module. 

Here, the initial case was a Red-colored ball and the features such as color and shape of the ball are used.The robot tries to find a color which is hard coded, if it finds a ball of that color it follows it.Raspberry pi 3 is used as a micro-controller as it gives great flexibility to use Raspberry Pi camera module and allows to code in Python which is very user friendly and OpenCV library, for image analysis. H-Bridge is used to switch from clockwise to counter-clockwise or to stop the motors. If there are frame drops or the ball goes out of the scope then the bot takes a 360 degree view of it's environment till the ball comes back in the scope of the camera and then start moving in it's direction.

### Prerequisites

#### Hardware Components
1. Raspberry Pi 3 Model B
2. Raspberry Pi Camera Module
3. Arduino Ultrasonic Sensor (3 Nos)
4. H-Bridge Motor Driver 
5. DC Motor (2 Nos)

#### Software
[OpenCV](https://opencv.org/releases/)

## Video
[Color Tracking Bot](https://youtu.be/JMg0vKWw1IY)


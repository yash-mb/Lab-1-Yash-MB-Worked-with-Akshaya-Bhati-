### Lab 1: Yash Budhe | Worked-with: Akshaya Bhati

# 3.2 - Firefly

<img src = "Videos/Firefly.gif" width="400" height="600"/>

# 4.4 - Custom Visualizer Overview: 

This is a motion detector which permits the side (left and right) motion (hand gestures) by signaling a green light and blinks red whenever a perpendicular (up and down) motion is detected. For this purpose a RP2040 microcontroller connected APDS9960 sensor through a Stemma QT cable is used. 

Instructions:

1. Hold the sensor in this position. 

2. Move your hand on the sensor. Check the notepad. The microcontroller will blink red or green depending upon the direction of hand motion and HID keyboard types the corresponding text on the notepad ("Moving up"/"Moving left").

<img src = "Videos/Motion detector.gif" width="600" height="600"/>

3. To stop the algorithm from running, use a mobile flaslight on the sensor. Microcontroller will blink blue and the code will stop.




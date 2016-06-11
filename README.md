# Info 

Controls the flaps on the IM suit. When activated, the servos move to a few positions, then return to rest.


Make sure to install the [Arduino Servo Library](https://www.arduino.cc/en/Reference/Servo). 
Unzip the servo library and place the files into the same folder that you have Arduino installed on your pc.

The servos should be wired with Red cable to +5V,  Black cable to GND, and Yellow/Orange cable to any of the numbered Arduino ports.
The servos move to particular positions when prompted by the Hall Effect switch. The numbers that are in the code are based on the particular servos I'm using, the [HS-311](https://www.amazon.com/Hitec-31311S-HS-311-Standard-Universal/dp/B0006O3WVE/ref=sr_1_6?s=toys-and-games&ie=UTF8&qid=1465665745&sr=1-6&keywords=servo). Change the values as needed.

Hall effect tutorial can be found [in this tutorial by Hobbytronics](http://www.hobbytronics.co.uk/arduino-tutorial11-hall-effect).

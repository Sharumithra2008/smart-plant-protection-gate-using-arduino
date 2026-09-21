#  Smart Plant Protection Gate

# 1\. Description

A smart plant protection system using an Arduino, ultrasonic sensor and servo motor. It detects nearby objects or animals and automatically controls a protective gate around the plant.

# 2\. Product Use

* Protects plants from unwanted animals and objects.  
*  Useful for home gardens and small farms.  
*  Demonstrates smart farming and automation.  
*  Provides automatic gate control without manual operation.

# 3\. Components Used

* Arduino Uno  
*  HC-SR04 Ultrasonic Sensor  
* SG90 Servo Motor  
*  Breadboard  
*  Jumper Wires  
*  Plant / Mini Garden Model  
*  Small Gate

# 4\. How We Made It

We created a small plant protection model with a gate. The ultrasonic sensor was connected to the Arduino to detect nearby objects. The servo motor was attached to the gate and controlled by the Arduino. When an object comes within the set distance, the servo moves the gate to protect the plant.

# 5\. Working

*  Object detected → Arduino processes the signal →  Servo moves →  Gate closes  
*  Object moves away →  Servo returns → Gate opens

# 6\. Arduino Code

The Arduino program reads the distance from the ultrasonic sensor and controls the servo motor according to the detected distance.

# 7.Conclusion

This project helped us understand ultrasonic distance sensing, Arduino programming, servo motor control and automation. It demonstrates a simple application of technology in smart gardening and plant protection.  

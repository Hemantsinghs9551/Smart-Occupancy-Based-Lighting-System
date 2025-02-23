Smart-Occupancy-Based-Lighting-System

Introduction

Imagine a scenario where you are at a party house enjoying your evening. The place has an automatic light system that works on motion detection, which is a common technology nowadays. However, when everything calms down and you move to a corner of the room, the motion sensors may not detect any activity and turn off the lights automatically, assuming no one is present.

This project aims to solve this problem by implementing a system that counts the total number of people entering and exiting the premises. The lights will only turn off when everyone who entered has exited, ensuring that no one is left in the dark.

"Where there is darkness, let there be light."— Francis of Assisi

Components and Basic Working

Components Required:

Solderless Breadboard

Arduino UNO

Ultrasonic Sensor (HC-SR04) ×2

16×2 LCD Display

100Ω Resistor

4.7KΩ Resistor

1KΩ Resistor

1-Channel 5V Relay Module

Male to Male Jumper Wires

Male to Female Jumper Wires

Bulb Holder

LED Bulb

Estimated Cost: ₹1,300 (Approximately)

Working Principle:

The system initializes with a “Welcome” message displayed on the LCD screen.

When a person enters the premises, the entry sensor detects them and turns ON the light while incrementing the count of people inside.

When a person exits, the exit sensor detects them and decrements the count of people inside.

The number of people currently inside is displayed on the LCD screen.

The light remains ON until the count of people inside reaches zero, ensuring that the premises are not left in darkness while people are present.

Circuit Diagram

(Add the circuit diagram image here)

How to Use

Assemble the components as per the circuit diagram.

Upload the Arduino code to the Arduino UNO.

Power up the system.

The system will automatically turn ON the lights when someone enters and keep track of the count.

The lights will turn OFF only when all entered persons have exited.

Future Improvements

Implementing an infrared camera for better accuracy in low-light conditions.

Integrating IoT to monitor the system remotely.

Adding a manual override switch for emergency situations.

Conclusion

This Smart Light Control System ensures efficient energy usage and enhances user convenience by keeping track of people present in the premises. It is an innovative solution to overcome the limitations of traditional motion sensor-based lighting systems.


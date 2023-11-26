# Door Lock based IoT Model🔒🔑

## 1. Introduction
The IoT based project involves creating a secure and automated RFID door lock system using an Arduino Uno board, RFID reader, and servo motor. By reading unique identification numbers from RFID tags, the system grants access by sending a signal to the servo motor to unlock the door, providing key-less entry for homes, businesses, offices, and vehicles.
## 2. Methodology 
● The RFID tag is attached to a key chain or another device that the user carries.
● The RFID reader is placed near the door and is connected to the Arduino board.
● The servo motor is attached to the door lock mechanism.
● When the user brings the RFID tag close to the reader, the reader sends the tag's unique identification number to the Arduino.
● The Arduino then checks if the received number matches any of the predefined authorized numbers stored in its memory.
● If the received number matches an authorized number, the Arduino sends a signal to the servo motor to rotate and unlock the door.
● If the received number does not match any of the authorized numbers, the door lock remains locked.
## 3. Modules Used 
● Arduino Uno Board
● RFID Module - RC522 RF IC Card Reader
● Jumper Wires
● Foam Board
● Servo motor -SG90
● Bread Board
## 4. Prototype
1. Authentication Model
<p align="center">
  <img src="Model Pictures/Authentication Model.jpeg"/>

</p>
2. Front View (Keypad & Fingerprint Sensor)
<p align="center">
  <img src="Model Pictures/Front View.jpeg"/>

</p>
3. Top View (LCD)
<p align="center">
  <img src="Model Pictures/Top View.jpeg"/>

</p>

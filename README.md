RFID-Based-Vehicle-Access-Control-Sytem
The RFID Based Vehicle Access Control System uses RFID cards to allow or deny entry to vehicles. When a card is scanned, the system reads its unique ID and checks if it matches an authorized user. If valid, access is granted and shown on the LCD; if not, access is denied. This provides a quick, secure, and contactless method.

-  Overview

This project implements an RFID-based entry system where only authorized RFID cards/tags can grant vehicle access.
The RC522 module reads the card UID, Arduino checks it, and the 16×2 LCD displays “Access Granted/Denied”.  

1) Full Project Report
Detailed documentation including introduction, methodology, circuit explanation, flowchart, conclusion, and references.

2) Code (PDF)

RFID tag reading
LCD display interface
Authorized UID verification
Output control logic

3) Results & Photos
Includes testing screenshots, LCD output photos, RFID scanning images, and setup pictures.

4) Components, Circuit Diagram & Working

Contains:
It has list of components with the wiring diagram(Arduino, LCD, RC522,), the role of the components are also given in brief with the working principle of the project

-  Features
*  Fast RFID card detection
*  Contactless & secure vehicle authentication
*  LCD shows live access status
*  Supports multiple RFID UIDs
*  Simple wiring, easy to modify
*  Cost-effective design

-  Applications
THe RFID Vehicle Access Control Systemcan be used in Parking gate vehicle authentication, Office/Apartment access control,
Transportation verification, Smart campus or industry gates and Restricted area access

-  Advantages

Hygienic contactless operation
Reliable and fast detection
Low maintenance cost
Highly customizable
Can be automated with motors/relays
Suitable for real-world use

-  Hardware Used

*  Arduino UNO
*  RC522 RFID Reader
*  RFID Card + Tag
*  16×2 LCD (with LiquidCrystal library)
*  Jumper wires
*  Power source (5V adapter/battery)

- How the System Works

The system works by using an RFID card and an RFID reader. When a vehicle comes near the entry gate, the driver places the RFID card near the reader. The reader scans the card and sends the card’s unique ID to the Arduino. The Arduino then checks whether the scanned ID matches with the stored authorized IDs. If the ID is valid, the system allows access by activating a signal such as displaying a message on the LCD and allowing the gate to open. If the ID is not valid, access is denied and a message like “Access Denied” is shown on the display. This process happens within a few seconds, making vehicle entry fast, secure, and automatic without any manual checking.

▶️ How to Use

To use the RFID Based Vehicle Access Control System, first ensure that the system is properly powered and connected. The RFID reader, Arduino, LCD display, and other components should be working correctly. When a vehicle arrives at the entry point, the driver needs to bring the RFID card close to the RFID reader. The system will automatically scan the card. If the card is registered and authorized, the LCD will display a message like “Access Granted” and the gate will open. If the card is not registered, the system will display “Access Denied” and the gate will remain closed.
This process makes vehicle entry simple, fast, and secure without the need for manual checking.

![AD Card](https://github.com/user-attachments/assets/397db518-00f8-4972-8d9b-e52b223b1280)
![IS Tag](https://github.com/user-attachments/assets/1cd5ffe7-3cb2-4866-81bd-bd5bcc9bcf34)
![AG tag](https://github.com/user-attachments/assets/b28d17b1-dbd7-4666-825d-0b0f9c0d19a9)

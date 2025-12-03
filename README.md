# RFID-Based-Vehicle-Access-Control-Sytem
The RFID Based Vehicle Access Control System uses RFID cards to allow or deny entry to vehicles. When a card is scanned, the system reads its unique ID and checks if it matches an authorized user. If valid, access is granted and shown on the LCD; if not, access is denied. This provides a quick, secure, and contactless method.


🚀 Overview

This project implements an RFID-based entry system where only authorized RFID cards/tags can grant vehicle access.
The RC522 module reads the card UID, Arduino checks it, and the 16×2 LCD displays “Access Granted/Denied”.

📁 Project Files
📦 RFID-Based-Vehicle-Access-Control  
 ├── 📄 Full_Project_Report.pdf  
 ├── 📄 Code.pdf (Arduino Program)  
 ├── 📸 Results_and_Photos/  
 ├── 🔧 Components_Circuit_Working.pdf  
 ├── 📘 README.md  

1) Full Project Report

Detailed documentation including introduction, methodology, circuit explanation, flowchart, conclusion, and references.

2) Code (PDF)

Contains the complete Arduino source code, including:

RFID tag reading

LCD display interface

Authorized UID verification

Output control logic

3) Results & Photos

Includes testing screenshots, LCD output photos, RFID scanning images, and setup pictures.

4) Components, Circuit Diagram & Working

Contains:

List of all components

Wiring diagram (Arduino + LCD + RC522 + Relay if used)

Explanation of each component’s role

Working principle

✨ Features

✔️ Fast RFID card detection

✔️ Contactless & secure vehicle authentication

✔️ LCD shows live access status

✔️ Supports multiple RFID UIDs

✔️ Simple wiring, easy to modify

✔️ Cost-effective design

📌 Applications

Parking gate vehicle authentication

Office/Apartment access control

Transport/logistics entry verification

Smart campus or industry gates

Restricted area access

⭐ Advantages

Hygienic contactless operation

Reliable and fast detection

Low maintenance cost

Highly customizable

Can be automated with motors/relays

Suitable for real-world use

🛠️ Hardware Used

Arduino UNO

RC522 RFID Reader

RFID Card + Tag

16×2 LCD (with LiquidCrystal library)

Jumper wires

Power source (5V adapter/battery)

Optional: Relay + Motor/Gate

📡 How the System Works

When powered ON, the LCD asks the user to Scan Card.

RC522 reads the card UID and sends it to Arduino via SPI.

Arduino compares the UID with the authorized list:

Match → Access Granted (LED/Relay ON)

Mismatch → Access Denied

LCD displays the result and system resets for next scan.

▶️ How to Use

Upload the provided Code.pdf program into Arduino UNO.

Make the connections exactly as given in “Components, Circuit & Working” PDF.

Power the system.

Scan any RFID card or tag.

View the result on LCD → Granted/Denied.

![AD Card](https://github.com/user-attachments/assets/397db518-00f8-4972-8d9b-e52b223b1280)
![IS Tag](https://github.com/user-attachments/assets/1cd5ffe7-3cb2-4866-81bd-bd5bcc9bcf34)
![AG tag](https://github.com/user-attachments/assets/b28d17b1-dbd7-4666-825d-0b0f9c0d19a9)

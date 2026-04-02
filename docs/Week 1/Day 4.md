# Day 4: RFID-Based Server Room Access Control System with Role Identification

## 📝 Description
On Day 4 of the internship, we designed and implemented a complete RFID-based access control system for a server room. The system uses the RFID RC522 module to scan access cards assigned to different roles, including Manager, Technical Manager, and Assistant.

Each card is uniquely identified using its UID, and when scanned, the system verifies whether the card is authorized. If access is granted, the LCD displays the name of the user, the servo motor unlocks the door, and the buzzer produces a single beep as confirmation. If the card is not recognized, access is denied, and the buzzer sounds three times to indicate rejection.

This project helped us understand real-world security systems, role-based authentication, and the integration of multiple components such as RFID, LCD, servo motors, and buzzers in embedded systems.

---

## 🛠️ Components Used
- Arduino Uno  
- RFID RC522 Module  
- RFID Cards (3)  
- LCD 16x2 (I2C)  
- Servo Motor  
- Buzzer  
- Jumper Wires  

---

## ⚙️ System Functionality
- Displays user identity on LCD  
- Grants access to authorized users  
- Denies access to unknown users  
- Uses servo motor as door lock  
- Provides buzzer feedback for actions  

---

## 📸 Project Image
![RFID System](../images/WhatsApp%20Image%202026-04-02%20at%209.27.20%20PM.jpeg)



---

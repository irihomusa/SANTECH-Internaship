# 📅 Day 4: RFID-Based Smart Room Access Dashboard

## 📝 Overview
On Day 4 of the internship, we focused on building a complete **RFID-based web dashboard system**.  
The goal was to allow users to scan RFID cards and have their access data displayed in real-time on a web interface.

This system integrates **hardware (RFID scanner)** with a **web-based dashboard**, enabling monitoring and logging of access activities.

---

## 🎯 Objectives
- Develop a web-based dashboard using PHP and MySQL  
- Store RFID scan data in a database  
- Display real-time logs of users accessing the system  
- Implement user registration for RFID cards  

---

## 🛠️ Technologies Used
- **PHP** – Backend logic  
- **MySQL** – Database management  
- **HTML/CSS (Bootstrap)** – User Interface  
- **XAMPP** – Local server environment  
- **RFID RC522 Module** – Card scanning  

---

## ⚙️ System Workflow

1. User taps RFID card  
2. UID is sent to the server (`scan.php`)  
3. Server stores UID in database  
4. Dashboard retrieves and displays logs  
5. Admin monitors access in real-time  

---

## 💻 Key Features
- 🔐 RFID-based authentication  
- 📊 Live dashboard display  
- 🧾 Access logs with timestamps  
- 👤 User registration system  
- 🔄 Auto-refresh for real-time updates  

---

## 🧩 Code Highlights

### 📌 Database Connection (`db.php`)
```php
$conn = new mysqli("localhost", "root", "", "smart_room");

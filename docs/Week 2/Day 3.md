# Day 3: IoT Data Communication and PHP Dashboard Integration

## 📝 Description
On Day 3, we moved from simulation to real-world system integration by connecting our IoT project to a web-based dashboard. We learned how sensor data (temperature and humidity) can be transmitted from a microcontroller (such as ESP8266) to a web server using HTTP requests.

We created a MySQL database to store incoming sensor data and developed a PHP script to receive and insert this data into the database. This allowed us to build the foundation of a real-time monitoring system.

Additionally, we implemented a web dashboard using PHP that retrieves and displays the stored data, including temperature, humidity, and system status (ONLINE/OFFLINE).

---

## 🧪 What We Learned

- Sending data from IoT devices to a server
- Basics of PHP backend development
- Using MySQL databases
- Real-time data storage and retrieval
- Building a dynamic web dashboard

---

## 🧰 Technologies Used

- Arduino / ESP8266
- PHP
- MySQL
- HTML & CSS
- XAMPP

---

## 📡 Sample Code (Data Receiver)

```php
<?php
include "db_connect.php";

$temp = $_GET['temperature'];
$hum = $_GET['humidity'];

$sql = "INSERT INTO sensor_data (temperature, humidity)
        VALUES ('$temp', '$hum')";

$conn->query($sql);
?>

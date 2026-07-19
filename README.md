# Smart_Device_Management_System

## Project Description

The Smart Device Management System is a Python Object-Oriented Programming (OOP) mini project that simulates the management of smart home devices. The program demonstrates the use of classes, inheritance, encapsulation, polymorphism, and method overriding through a menu-driven application.

The system allows users to manage different smart devices such as lights, security cameras, and temperature sensors.

---

## Features

- Display information about all devices
- Turn devices ON and OFF
- Increase or decrease light brightness
- Start and stop camera recording
- Read temperature from the sensor
- Menu-driven interface for easy interaction

---

## OOP Concepts Used

- Classes and Objects
- Constructors (`__init__`)
- Encapsulation (private attributes)
- Getters and Setters
- Inheritance
- Method Overriding
- Polymorphism

---

## Classes

### SmartDevice
The base class that represents a generic smart device.

**Attributes**
- Device Name
- Device ID
- Power Status

**Methods**
- Turn device ON
- Turn device OFF
- Display device information

---

### SmartLight
Inherits from `SmartDevice`.

**Additional Features**
- Brightness control
- Increase brightness
- Decrease brightness

---

### SecurityCamera
Inherits from `SmartLight`.

**Additional Features**
- Start recording
- Stop recording
- Display recording status

---

### TemperatureSensor
Inherits from `SecurityCamera`.

**Additional Features**
- Read temperature
- Display temperature information

---

## Program Menu

The application provides the following menu options:

1. Display Information
2. Turn Devices ON
3. Turn Devices OFF
4. Read Temperature
5. Adjust Brightness
6. Recording
7. Exit

---

## Requirements

- Python 3.x

No external libraries are required.

---

## How to Run

1. Download or clone the project.
2. Open the project folder.
3. Run the Python file.

Example:

```bash
python smart_device.py
```

or

```bash
python main.py
```

(depending on your filename)

---

## Sample Output

```
=== Smart Device Menu ===
1. Display Information
2. Turn Devices ON
3. Turn Devices OFF
4. Read Temperature
5. Adjust Brightness
6. Recording
7. Exit

Choose an option:
```

---

## Author

**Name:** Bravestone

Course: EL 162 / 234 – Object Oriented Programming

Mini Project: Smart Device Management System

---

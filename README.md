# Smart-Device-Management-system
Boateng Bruhaan
FOE.21.006.018.24
 Smart-Device-Management-system
Bossman Emmanuel
FOE.21.006.019.24
EL2 DIP
 Smart Device Management System

Project Introduction
This project is a Mini Project for EL 162 / 234 Object Oriented Programming at UMaT, taught by Dr. Matthew Cobbinah. The goal is to demonstrate core Object Oriented Programming concepts using Python.

The system simulates a simple smart home setup where different devices can be managed through a menu-driven interface.

Task Summary
The program implements:

1. Parent Class SmartDevice
   - Private attributes: __device_id, __power_status
   - Public attribute: name
   - Methods: turn_on(), turn_off(), display_info()
   - Encapsulation using @property and getters/setters

2. Child Classes with Inheritance
   - SmartThermostat: Reads temperature
   - SmartLight: Adjusts brightness (0-100 validation)
   - SmartCamera: Starts/stops recording
   - All use super() to initialize inherited attributes

3. Encapsulation & Validation
   - Device ID cannot be empty
   - Power status cannot be modified directly
   - Brightness must be between 0 and 100

4. Menu-Driven Interface
   Users can:
   1. Display Device Information
   2. Turn Device On
   3. Turn Device Off
   4. Read Temperature
   5. Adjust Brightness
   6. Start Recording
   7. Exit

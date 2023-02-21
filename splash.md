# Infrared Camera-Based Toaster
## Cameron Barrett & Torin Schlunk
## February 2023

## 1. Overview
The proposed project is an infrared camera-based toaster that can monitor the temperature of food during toasting. The toaster will use an infrared sensor to determine the temperature and use an algorithm to reach the desired toast amount. The algorithm will adjust the toasting time and temperature based on the food’s temperature, ensuring that the food is prepared to the user’s preference every time.
## 2. Peripherals
Microcontroller: A microcontroller will be used to control the system and process data from the infrared camera.
Infrared camera: An infrared camera will be used to track the temperature of the bread.
Toaster: A toaster will be modified to integrate with the infrared camera and microcontroller.
Bluetooth Module: An attached module will allow wireless communication to control the toast level and provide status updates.
## 3. Serial Interface Protocols
The microcontroller will communicate with the infrared sensor using the I2C protocol. The Bluetooth module will communicate via UART.

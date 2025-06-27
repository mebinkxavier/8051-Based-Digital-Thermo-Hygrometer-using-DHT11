# 8051-Based-Digital-Thermo-Hygrometer-using-DHT11

Project Description:

This project demonstrates the interfacing of the DHT11 temperature and humidity sensor with the 8051 microcontroller to monitor environmental conditions. The DHT11 sensor transmits digital data consisting of the integral and decimal parts of humidity and temperature, along with a checksum for data validation. The 8051 microcontroller processes this data and displays the values in real-time on a 16x2 LCD using a 4-bit interface.

Timing-critical operations such as sensor pulse-width reading are handled using Timer0-based delays. Error checking is implemented by validating the checksum received from the sensor. The system operates continuously in a loop, updating the LCD display with current temperature (in °C) and humidity (%RH), making it a simple yet effective embedded system application for environmental monitoring.


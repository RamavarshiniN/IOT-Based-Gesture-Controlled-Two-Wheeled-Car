# IOT-Based-Gesture-Controlled-Two-Wheeled-Car
The project is an IOT Based Gesture Controlled Two-Wheeled Car designed as a low-cost, smart mobility solution for disabled wheelchair users. It utilizes the MPU6050 sensor for gesture recognition and the HC-05 Bluetooth module for voice commands, providing a hands-free alternative to enhance independence in navigation

Key Technology and Implementation:
1. Gesture Recognition: We used the MPU6050 accelerometer/gyroscope sensor to detect real-time hand or head movements. These gestures are processed to generate commands for movement (forward, backward, left, right, and stop).
2. Voice Control Feature: Improved accessibility was achieved by integrating the HC-05 Bluetooth module. This allows a smartphone app to send voice commands wirelessly to the system.
3. Core Architecture: The system employs an Arduino Nano as the transmitter controller and an Arduino UNO as the receiver controller.
4. Wireless Communication: The NRF24L01 transceiver module was crucial for establishing wireless data communication between the gesture/voice input module and the receiver module.
5. Motor Control: The commands were translated into physical movement using the L298N Motor Driver to control the DC motors of the vehicle.
   
Impact and Results: The prototype was successfully developed and tested, demonstrating high accuracy in responding to both gestures and voice commands. This gesture-controlled system offers a real solution for traditional wheelchair users by improving accessibility and significantly reducing dependency on caregivers. We proved that this design can be constructed from low-cost, open-source components, making it simple and reproducible for real-world application.

Challenges Met: During demonstration, we resolved specific challenges, including initial communication errors with the NRF24L01 and ensuring the correct baud rate for serial communication. We also managed issues concerning the overheating of the L298N motor driver

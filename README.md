# Smart_Home_Automation_Using_Arduino
This project aims to create a home automation system using an Arduino board with Bluetooth capabilities, remotely controlled by an Android smartphone. As technology advances, homes are becoming smarter. Modern households are moving away from traditional switches toward centralized control systems that include remote-controlled switches. Conventional wall switches, located in various parts of the house, can be inconvenient for users to operate, especially for the elderly or physically disabled individuals. A remote-controlled home automation system offers a contemporary solution using smartphones.

To achieve this, a Bluetooth module is interfaced with the Arduino board on the receiver end. On the transmitter end, a GUI application on the smartphone sends ON/OFF commands to the receiver, where loads are connected. By touching specific locations on the GUI, users can remotely turn loads ON/OFF using this technology.
# Content
This Readme is divided into several parts

1. Description
2. Components
3. Implementation
# Description
This project is a significant Arduino endeavor, focusing on home automation using Bluetooth technology. It lets users control electronic devices through the Device Control app on their Android smartphones. The Android app sends commands to the Arduino controller via Bluetooth. The Arduino is connected to a main PCB that houses five relays, as the block diagram depicts. These relays can be linked to various electronic devices such as lights, a television, a fan, and more.

When the user presses the 'On' button for device 1 on the app, the buzzer is activated. Pressing the same button again will switch off the buzzer. Similarly, pressing the 'On' button for device 2 on the app will turn on the fan, which can be switched off by pressing the same button again.

This home automation project using Bluetooth and Arduino can control any AC or DC device. The flow diagram below illustrates the project workflow.

![diagram](https://github.com/RohitAvhad-2628/Smart_Home_Automation_Using_Arduino/assets/174472645/946806b2-569e-4974-90e2-0dc57d5f70e5)
# Components
Here is the section with the hardware and software components used in the project:

### Hardware

The list of components mentioned here are specifically for controlling 4 different loads:

- Arduino UNO
- HC-05 Bluetooth Module
- 5V Relay (x4)
- Prototyping board (Breadboard)
- Connecting wires
- Smartphone or tablet (Bluetooth enabled)
- 5V Power Source

### Software

- Arduino 1.8.5 compiler
- Android application
# Implementation
## Circuit Diagram
![ciruit_diagram](https://github.com/RohitAvhad-2628/Smart_Home_Automation_Using_Arduino/assets/174472645/505c1208-b0b5-4548-8ba1-c333bb8d8c26)
## Android App
![app_screenshot](https://github.com/RohitAvhad-2628/Smart_Home_Automation_Using_Arduino/assets/174472645/0414ab5f-2dd6-45ed-bbde-783d27cb82aa)

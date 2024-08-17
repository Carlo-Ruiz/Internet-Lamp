# Iot Neopixel Lamp - Documentation

By Carlo Ruiz

![Main_Idea](https://github.com/user-attachments/assets/ae5ed548-c570-44dc-81c0-f7bc4f9ad649)


# **Project Overview**

**Description**:
Our goal is to create a simple lamp connected to the internet where you
can toggle the lamp on and off using your phone or laptop. We will use an
ESP32 inside of the lamp which will connect it to the Arduino cloud
where we will have our “thing” setup and can toggle it on or off from there.

# **Hardware Setup Documentation**

**Bill of Materials:**

- Wroom ESP32 (Usb type C)
- 120V AC power supply
- Light Bulb Socket with a 9W light bulb
- Breadboard
- Relay Module

ESP32 Pinout Diagram  
![NodeMCU-ESP8266-Pinout](https://github.com/user-attachments/assets/5707f88a-84c6-4d64-aae4-c949f21ea34b)




Note: Built in LED is pin 2 in Arduino IDE (connects to pin D2 on the board)

Arduino IDE Pins Index

![Arduino_IDE_Pins_Index](https://github.com/user-attachments/assets/83b4f056-7ef2-4035-80f3-8b09c135ef4f)

# **ESP32 Arduino IDE usage**

- **ESP-WROOM-32**
    
    To upload to ESP32 by Wroom (the one with the USB type C), select ESP-32-Wroom-DA Module
    

# **Software Development Documentation**

**Description**:
We are using Arduino Cloud IDE to host our “thing” for the lamp and our
cloud variables for the lamp. 

# Lamp Design idea
![DESIGN_1](https://github.com/user-attachments/assets/43bbd469-0dbc-46c8-9a3b-0e764489929b)


|Design 2|Design 2 exploded view|
|--|--|
|![Design 2](https://github.com/user-attachments/assets/b6b06c07-729f-4e8a-befd-56477e6e6964) |![Design 2 exploded view](https://github.com/user-attachments/assets/d7a11f8e-6f7f-43e3-a24a-703f67ffd983)|



# **Appendix**

**Links**

ESP32 Smart Home YT Tutorial

[https://www.youtube.com/watch?v=ZjVWXPnAgoE](https://www.youtube.com/watch?v=ZjVWXPnAgoE)

Arduino Relay Shield Basics

[https://docs.arduino.cc/tutorials/4-relays-shield/4-relay-shield-basics/](https://docs.arduino.cc/tutorials/4-relays-shield/4-relay-shield-basics/) 

Connecting a relay module to a microcontroller

 **[https://www.youtube.com/watch?v=FWvEEtrTGRQ](https://www.youtube.com/watch?v=FWvEEtrTGRQ)** 

How to use a relay module with ESP32

[**https://www.youtube.com/watch?v=5v3hguC41Kk**](https://www.youtube.com/watch?v=5v3hguC41Kk)

How to use a relay with Arduino

[https://www.youtube.com/watch?v=BSGwvAHy4As](https://www.youtube.com/watch?v=BSGwvAHy4As)

Software for making our own diagrams (Draw.io)

[https://draw.io](https://draw.io)

Arduino Cloud Home

[https://app.arduino.cc](https://app.arduino.cc) 

How to create a thread in On Shape

[https://www.youtube.com/watch?v=Y_KmMHZxtpU&pp=ygUgaG93IHRvIGNyZWF0ZSB0aHJlYWRzIGluIG9uc2hhcGU%3D](https://www.youtube.com/watch?v=Y_KmMHZxtpU&pp=ygUgaG93IHRvIGNyZWF0ZSB0aHJlYWRzIGluIG9uc2hhcGU%3D)

## Credits (In order of appearance)

Carlo Ruiz!

Ahsen Baig! (Advice, moral support)

Dr. O! (Circuit diagrams)

Professor Dillon! (Circuits, ideas)

Joshua Valadez! (3d printing)

Frank Holguin! (Screw inserts)

Lovleen! (Coloring)

Nikki! (Ideas)

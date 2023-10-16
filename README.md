# Problem
Smart Home Automation

Imagine you're building a smart home automation system where various devices (lights, thermostat, music player, etc.) can be controlled remotely using a central hub or app. Each device has different functionalities, but you want to create a unified and flexible control mechanism.

Design a system that allows you to control multiple smart home devices with ease. Your goal is to create a solution where:

1. You can control a variety of devices from a central hub or app, sending commands like "Turn On," "Turn Off," "Increase Temperature," "Decrease Volume," etc.
 
2. Each device has unique actions associated with these commands. For example, turning on the lights might involve changing their brightness level, while turning on the music player may involve playing a specific playlist.
   
3. New devices can be seamlessly integrated into the system without modifying existing code. You want to ensure that adding a new device doesn't require changes to the central control logic.
   
4. Devices can be controlled without the central hub or app needing to understand the internal workings of each device. It should send high-level commands without needing low-level details.
   
Your challenge is to apply a design pattern that provides a flexible and scalable way to control a variety of smart home devices, ensuring that new devices can be added without disrupting the existing system's functionality.

# Class Diagram

![image](https://github.com/Reirinn/commandPattern/assets/142465054/90ca0e23-6f0f-440d-9c44-d546e4362247)

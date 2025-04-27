# ParaEase: Smart IoT Solution for Differently Abled Individuals

## Overview

We live in an era of rapid technological advancements, especially in the realm of the **Internet of Things (IoT)** and smart devices. These advancements have brought significant changes to various fields, improving convenience and making life easier. For example, motion-sensing smart LEDs that activate when someone enters a room, or the ability to turn on lights with voice commands. As the world moves towards smarter solutions, it is essential to ensure that differently-abled individuals are not left behind. 

ParaEase is our solution to bridge the accessibility gap, helping specially-abled individuals live a more **comfortable, independent, and dignified life** using smart IoT applications. The system is designed to assist people with physical limitations due to various reasons such as accidents, birth defects, or nerve-related problems, making their daily lives easier and more manageable.

## Problem Statement

Many differently-abled individuals face challenges such as limited mobility, communication difficulties, and the inability to respond quickly during emergencies (e.g., gas leaks or intrusions). Traditional home automation systems often fail to meet the needs of these individuals due to lack of adaptability or inclusivity. 

Thus, ParaEase was developed with the aim to provide an affordable and simple prototype that helps these individuals live a normal life with minimal cost. 

## Key Features

1. **Multi-Sensor IoT-Based System**:
   ParaEase utilizes an IoT-based system using **ESP32**, along with sensors such as:
   - **MQ2 Gas Sensor**: Monitors gas leaks in the environment.
   - **DHT11 Temperature & Humidity Sensor**: Monitors room temperature and humidity.
   - **IR Sensor**: Detects motion to trigger alerts.
   - **LDR Sensor**: Measures light intensity to automatically control LED lights.
   - **Touch Sensor**: Allows the user to send alerts with a simple tap.

2. **Dual Alert Mechanism**:
   ParaEase incorporates a **dual alert mechanism** using:
   - **Telegram notifications**: Sends urgent notifications to the patient’s relatives or caretakers.
   - **Buzzer alert**: Activates to alert the caretaker if immediate attention is required.
   
   The user can either tap the **Touch Sensor** or use any part of their body to trigger the **IR Sensor**, which sends alerts to caretakers or relatives, ensuring they are notified even if they aren't physically present.

3. **Cloud Interface (Blynk)**:
   The system integrates with **Blynk**, a cloud-based interface that allows caretakers or relatives to remotely control LED lights in the patient's room. The **Blynk app** or **web version** can be used to turn the lights on or off from a distant location.

4. **Environmental Monitoring**:
   - The **MQ2 Sensor** and **DHT11 Sensor** allow monitoring of the room’s temperature, humidity, and any gas leakage. If the environmental conditions reach unsafe levels, the system can trigger appropriate actions.
   - The **LDR Sensor** turns on the LED light automatically when the room gets dark, making it easier for the patient to navigate their surroundings.

5. **Cost-Effective Solution**:
   ParaEase is designed to be **affordable**. With all the components required for the system, the total cost to set up the entire system is estimated to be **under ₹1000**. This ensures that the system is accessible to individuals who may not have a large budget for advanced technologies.

## How It Works

- **ESP32** serves as both the processor and communication module, integrated with **Wi-Fi** for cloud connectivity.
- The **sensors** continuously monitor the environment and detect any emergencies.
- If an emergency is detected, the system sends alerts through both **Telegram notifications** and a **buzzer**.
- The **Blynk cloud platform** allows caretakers to control the patient's room's lighting remotely.
- **LDR** sensors ensure that the LED lights turn on automatically when it gets dark in the patient's room.

## Components Used

- **ESP32** (Processor + Communication Module)
- **MQ2 Gas Sensor** (Gas Leak Detection)
- **DHT11 Temperature & Humidity Sensor**
- **IR Sensor** (Motion Detection)
- **LDR Sensor** (Light Intensity Detection)
- **Touch Sensor** (User Input for Alerts)
- **Buzzer** (Audio Alert)
- **Blynk Cloud Interface** (For remote control of devices)

## Project Cost

The total cost for setting up this system is **approximately under ₹1000**, making it an affordable solution for individuals in need of smart home automation and monitoring.

## Conclusion

ParaEase is a smart, affordable, and multi-functional system aimed at improving the lives of differently-abled individuals. With features such as environmental monitoring, motion detection, remote control, and emergency alerting, ParaEase ensures that users can live independently while being safe and connected to their caretakers or relatives. We believe that this solution has the potential to make a significant difference in the lives of people who are often overlooked by traditional technology.

## Installation

1. Connect the components as per the wiring diagram.
2. Program the **ESP32** using the Arduino IDE with the appropriate libraries for the sensors and Blynk.
3. Set up the **Blynk app** and connect it to the ESP32 via Wi-Fi.
4. Power up the system and test the sensors and alert mechanisms.

## Future Work

- **Voice Assistant Integration**: Add voice commands for controlling various features of the system.
- **More Sensor Integration**: Add more sensors for additional functionalities such as fall detection or heart rate monitoring.

## Acknowledgments

- **ESP32** and **Blynk** for their excellent platforms that made this project possible.
- **Sensor manufacturers** for providing affordable and reliable sensors.
- **Open-source community** for their contributions to making smart home solutions more accessible.

---

Feel free to check out the project repository, fork it, or contribute to further improving the solution.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


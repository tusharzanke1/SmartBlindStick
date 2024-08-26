Smart Blind Stick: Enhancing Mobility for the Visually Impaired

Table of Contents
Introduction
Features
Components
Block Diagram
Methodology
How It Works
Results
Conclusion
Getting Started
Installation
Usage
Contributing
License

Introduction
Approximately 253 million people around the world live with visual impairments, making daily navigation a significant challenge. The Smart Blind Stick project aims to enhance the independence and safety of visually impaired individuals by providing a cost-effective, easy-to-use solution. This smart stick is equipped with advanced sensors and IoT technology to detect obstacles and send emergency notifications to caregivers.

Features
Obstacle Detection: Ultrasonic sensors detect obstacles within 100 cm, providing timely alerts through a buzzer and vibrator motor.
Emergency Assistance: GPS module and NodeMCU ESP8266 send the user's location to a designated contact when the emergency button is pressed.
User-Friendly Design: Lightweight, budget-friendly, and easy to assemble, making it accessible to a wide audience.
Components
NodeMCU ESP8266
GPS Module
Ultrasonic Sensors
Buzzer
Vibrator Motor
Emergency Button



How It Works
Obstacle Detection
Ultrasonic Sensors: Three sensors detect obstacles at different heights.
Alert Mechanism: When an obstacle is detected, the buzzer sounds and the vibrator motor vibrates, alerting the user.
Distance Calculation: The distance to the obstacle is calculated using the formula: Distance = (Time × Speed of Sound) / 2.
Emergency Assistance
GPS and Wi-Fi Connection: When the stick is powered on, the NodeMCU connects to Wi-Fi, and the GPS module begins receiving location data.
Emergency Button: Pressing the emergency button triggers a Webhook request to the IFTTT server, which sends an alert message with GPS coordinates to the designated contact.
Results
The Smart Blind Stick provides a practical solution to simplify the lives of visually impaired individuals. It combines essential features at a minimal cost, making it accessible to a broader audience. The obstacle detection system effectively alerts users to nearby hazards, while the emergency button ensures help is always just a press away.

Conclusion
The Smart Blind Stick is a transformative tool for visually impaired individuals, enhancing their independence and safety. By addressing common challenges faced in daily life, this project offers a meaningful impact on the quality of life for blind individuals.

Getting Started
To get started with the Smart Blind Stick project, follow the instructions below.

Prerequisites
Arduino IDE installed on your computer
ESP8266 library installed in Arduino IDE
Basic knowledge of Arduino and IoT concepts
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/smart-blind-stick.git
Open the project in Arduino IDE.

Install the necessary libraries:

TinyGPS
ESP8266WiFi
WiFiClientSecure
Connect the hardware components as per the block diagram.

Usage
Upload the code to NodeMCU.
Connect the stick to a power source.
Test the obstacle detection system.
Press the emergency button to test the GPS location sending feature.
Contributing
We welcome contributions to enhance the Smart Blind Stick project. Please feel free to submit pull requests or open issues for suggestions and improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

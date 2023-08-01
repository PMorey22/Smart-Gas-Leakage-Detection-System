# Smart-Gas-Leakage-Detection-System

Problem Statement:

The safety and security of residential properties are of utmost importance, and timely detection of potential hazards such as fire outbreaks or gas leaks is essential to prevent accidents and property damage. However, conventional alert systems may lack real-time monitoring capabilities and fail to notify homeowners immediately when critical situations arise. To address this problem, there is a need for an advanced alert system that can continuously monitor the house for fire outbreaks and LPG gas leaks while also tracking temperature and methane ppm concentration levels. The system should be able to send instant SMS alerts to the registered mobile number in case of any hazardous conditions.

Solution:

The proposed solution is an IoT-based alert system that combines Raspberry Pi with various sensors to achieve real-time monitoring and immediate notifications. The system will include the following components:

Raspberry Pi: The central processing unit that will control all the components and execute the monitoring logic.

ADC121C_MQ4 Sensor: This sensor will be used to measure the methane (LPG) concentration in parts per million (PPM) in the air.

DHT-11 Sensor: This sensor will measure the ambient temperature inside the house.

GSM Module: The GSM module will enable Raspberry Pi to send SMS alerts to the registered mobile number.

Functionality:

Continuous Monitoring: The Raspberry Pi will continuously collect data from the ADC121C_MQ4 sensor to monitor the methane concentration in the air and from the DHT-11 sensor to measure the temperature inside the house.

Threshold Check: The system will check the sensor data against predefined threshold values (e.g., 1000 ppm for methane concentration and 60 degrees Celsius for temperature). If the readings exceed these thresholds, it will trigger an alert.

Alert Generation: When hazardous conditions are detected (high methane concentration or elevated temperature), the Raspberry Pi will activate the GSM module to send an SMS alert to the registered mobile number. The SMS will include information about the detected hazard and the exact sensor readings.

Web Portal: The system will provide a web portal accessible through any internet-connected device, allowing homeowners to remotely monitor real-time data and receive alerts. The web portal will display the current temperature, methane concentration level, and status of the alert system.

Benefits:

Immediate Alerting: The real-time monitoring and instant SMS alerts ensure that homeowners are immediately informed of any hazardous conditions, allowing them to take prompt action to prevent accidents or damage.

Remote Monitoring: The web portal offers convenient remote monitoring, enabling homeowners to stay informed about the safety status of their property even when away from home.

Early Fire and Gas Leak Detection: By continuously monitoring methane levels and temperature, the system can detect potential fire outbreaks or gas leaks at an early stage, reducing the risk of severe incidents.

Cost-Effective Solution: The use of Raspberry Pi and affordable sensors makes this alert system a cost-effective solution for enhancing home safety.

The proposed IoT-based alert system provides an effective and reliable solution to protect homes from fire outbreaks, gas leaks, and high-temperature incidents. By enabling real-time monitoring and immediate notifications, the system empowers homeowners to respond promptly to potential hazards and ensure the safety of their properties and loved ones.

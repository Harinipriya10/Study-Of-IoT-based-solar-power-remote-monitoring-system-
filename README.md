
🌞 IoT-Based Real-Time Solar Power Remote Monitoring System

This project presents a low-cost, real-time monitoring system for solar photovoltaic (PV) panels using Internet of Things (IoT) technologies. It collects and transmits real-time data from solar panels to the cloud, enabling users to monitor solar system performance remotely and efficiently.



📌 Objective

To develop an IoT-based solar power monitoring system that:

Continuously tracks parameters like voltage, current, temperature, and light intensity

Detects faulty panels and unfavorable conditions

Stores and visualizes data on the ThingSpeak cloud platform

Enables remote monitoring and easy maintenance


🔧 System Components

NodeMCU ESP8266 – Main microcontroller with WiFi capability

PV Panel (5W, 12V)

Sensors:

INA219 – Current and voltage sensor

LDR – Light intensity sensor

DS18B20 – Digital temperature sensor


Battery & Charging Module

ThingSpeak – Cloud platform for data storage and visualization

🧠 Features

Real-time data acquisition and monitoring

Wireless communication using WiFi

Visualized sensor data through ThingSpeak dashboard

Fault detection and preventive maintenance support

Remote accessibility for rural/remote installations


🛠 Working Methodology

1. Sensors collect data on PV panel output and environmental conditions.


2. NodeMCU processes this data and sends it to ThingSpeak via WiFi.


3. ThingSpeak displays real-time and historical data through customizable graphs.


4. Stored data can be used for performance analysis, predictive maintenance, and energy forecasting.


📊 Observations

Data was collected in three time frames:

Morning: Lower light intensity and temperature, lower energy output

Afternoon: Peak performance and energy generation

Night: Minimal generation due to lack of sunlight


📈 Sample Parameters

Time of Day	Voltage (V)	Current (mA)	Power (mW)	Light Intensity (cd)	Temperature (°C)

Morning	7.0 – 7.7	0.12 – 1.0	13.2 – 18.0	0.27 – 0.3	68.6 – 70.5
Afternoon	19.8	0.01 – 3.3	29.4	3.3	85.0 – 89.2
Night	0.17 – 0.78	0.6 – 1.28	0.10 – 12.0	0.26 – 3.3	-27.0 – 20.0


✅ Conclusion

This IoT-based solution effectively:

Enables real-time and remote monitoring

Improves maintenance efficiency

Increases solar panel utilization

Facilitates better decision-making with historical data


👩‍💻 Developed By

V. Anusuya

S. Harinipriya

R. Nisha

V. Vithyashri

R. Vinothini


> 🏫 Department of Electrical Engineering, Annamalai University
📅 Academic Year: 2021-2022



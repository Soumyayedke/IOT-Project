Development of Bluetooth Jammer using ESP32 and NRF24L01

This project demonstrates the development of a Bluetooth jammer using an ESP32 microcontroller and an NRF24L01 RF module. The primary goal is to disrupt Bluetooth communication frequencies within a specific range—showcasing practical security concerns in wireless communication.

⚠️ Note: This project is for educational and research purposes only. Jamming communication signals may be illegal in some regions. Ensure you're aware of local laws and operate responsibly within controlled environments.

📡 Project Overview

Bluetooth communication, though widely used, can be susceptible to signal interference. In this project, we use the ESP32 and NRF24L01 to generate noise/interference signals within the 2.4 GHz band—causing disruption of nearby Bluetooth devices.

🛠️ Hardware Components
Component	Description
🔘 ESP32	Main microcontroller with Wi-Fi and BLE
📡 NRF24L01	RF transceiver module (2.4 GHz)
🔋 Power Supply	Battery/USB for powering the components
🧰 Jumper Wires	Connections between ESP32 and NRF24L01
💻 Optional	USB-to-Serial for programming
🔌 Wiring Diagram
ESP32 Pin	NRF24L01 Pin
3.3V	VCC
GND	GND
D18	SCK
D19	MISO
D23	MOSI
D5	CE
D17	CSN

⚠️ Make sure not to power NRF24L01 with 5V; it requires 3.3V.

🧠 Features

Transmits signal patterns within the 2.4 GHz band

Disrupts Bluetooth devices within range

Programmable through Arduino IDE / ESP-IDF

Compact and low-cost solution

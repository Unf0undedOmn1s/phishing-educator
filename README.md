# Phishing Educator

A Phishing Simulator designed to simulate phishing scenarios for educational and professional use. This tool helps understand phishing attacks and trains individuals on identifying and mitigating such threats. It’s an ideal project for aspiring cybersecurity analysts.


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Disclaimer](#disclaimer)
- [License](#license)

## Introduction

Phishing is one of the most prevalent and effective cyberattack methods, targeting individuals and organizations by tricking them into revealing sensitive information, such as login credentials or financial details.
## Features

1. **Web-Based Interface**: A user-friendly dashboard accessible via any web browser.
2. **Traffic Intensity Control**: Allows users to specify the intensity of the traffic (measured in microseconds between packets) to simulate different scales of DDoS attacks.
3. **Target IP Specification**: Users can input the target IP address (IPv4) to direct the attack traffic.
4. **Start and Stop Controls**: Simple buttons to start and stop the DDoS attack simulation.
5. **Logging**: Detailed logging of attack parameters and status updates, aiding in monitoring and analysis.
6. **Educational Insights**: Informational sections explaining the importance of understanding DDoS attacks and their impact on network infrastructure.

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS (embedded in HTML)
- **Traffic Generation**: hping3
- **Logging**: Python's built-in logging module with RotatingFileHandler

## Installation and Setup

---

## Usage
Run the application by navigating to its folder using the terminal: **python3 app.py**
    Open a web browser and navigate to http://127.0.0.1:5000.
    Use the dashboard to set the target IP address and control the traffic intensity.
    Start and stop the DDoS attack simulation using the provided buttons.
    Monitor the logs for detailed information on the attack parameters and status updates.

## Disclaimer

This tool is intended for educational purposes only. Use it responsibly and only in environments where you have explicit permission to conduct such simulations. Misuse of DDoS tools can lead to legal consequences.

## License
© 2024 Marios Grivas. All rights reserved.

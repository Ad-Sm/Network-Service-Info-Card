# Network Service Info Card
**Author:** Adithya S M

## Overview
This Python application allows you to check...


## Features
- Detects common network services (HTTP, FTP, SSH, SMTP)
- Retrieves and cleans service banners
- Measures response time in milliseconds
- Supports manual IP/hostname and port input
- Responsive GUI with Tkinter
- Allows multiple checks without restarting


## Requirements
- Python 3.x
- Standard libraries: socket, threading, time, tkinter, re


## How to Run
1. Clone or download this repository.
2. Open a terminal or command prompt in the project folder.
3. Run the program with: python Network_Service_card.py
4. In the GUI window:
- Enter the IP address or hostname in the IP Address / Hostname field.
- Enter the port number in the Port field.
- Click Check Service.
5. The detected service, banner information, and response time will be displayed below.


## Example Usage
Try testing public servers like:
- IP/Hostname: google.com  
Port: 80
- IP/Hostname: ftp.dlptest.com  
Port: 21
- IP/Hostname: ssh.github.com  
Port: 443


## Disclaimer
Use this tool responsibly. Only scan hosts and services you have permission to access. Unauthorized scanning or probing can be illegal and unethical.


## Author
Adithya S M

# Python Port Scanner

This project is a simple Python-based Port Scanner developed to demonstrate the fundamentals of network reconnaissance and socket programming. Port scanning is one of the most important techniques used in cybersecurity, particularly during vulnerability assessment and penetration testing, to identify open ports and running services on a target system.

The primary goal of this project is to understand how network connections work and how open ports can be discovered programmatically using Python. The scanner attempts to establish a TCP connection with a list of specified ports on a target host. If the connection is successful, the port is considered open; otherwise, it is marked as closed. This process helps identify potential services running on the target machine.

The tool supports both IP addresses and domain names as input. When a domain name is provided, it is automatically resolved into an IP address before scanning begins. The script also includes basic error handling to manage invalid inputs or unreachable hosts.

This project is built using Python’s built-in **socket** module for network communication and the **IPy** library for validating IP addresses. The implementation focuses on simplicity and clarity, making it ideal for beginners who want to learn about networking concepts and cybersecurity tools.

## Features

* Scan open TCP ports on a target system
* Accepts both IP addresses and domain names
* Basic validation for target hosts
* Simple and easy-to-understand Python code
* Demonstrates basic network reconnaissance techniques

## Technologies Used

* Python
* Socket Programming
* IPy Library

## Learning Objectives

This project helps in understanding:

* How TCP connections work
* Basics of port scanning
* Network reconnaissance concepts
* Python socket programming

## Disclaimer

This tool is developed strictly for educational and learning purposes. Port scanning should only be performed on systems where you have explicit permission to test. Unauthorized scanning of networks or systems may violate security policies and laws.

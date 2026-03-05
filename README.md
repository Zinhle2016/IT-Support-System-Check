# IT Support System Check and Troubleshooting Report

## Student Information
Name: Nosipho Zinhle Ndebele  
Course: Technical Support Fundamentals  
Platform: Coursera  
Assignment: System Check and Basic Troubleshooting  

---

## 1. System Information

To check the system specifications, the System Information tool was opened using the command **msinfo32**.

The following system details were identified:

- Operating System: Windows 10
- Processor: Intel Core i5
- Installed RAM: 8 GB
- System Type: 64-bit Operating System

Screenshot: System Information

---

## 2. Network Status Verification

The Command Prompt was used to check the network configuration using the following command:

ipconfig

This command displayed important network details including:
- IPv4 Address
- Subnet Mask
- Default Gateway

These details confirm that the computer is connected to a network.

Screenshot: ipconfig command result

---

## 3. Internet Connectivity Test

To verify internet connectivity, the following command was used:

ping google.com

The results showed replies from Google's server, confirming that the computer had an active internet connection.

Screenshot: Successful ping result

---

## 4. Simulated Network Issue

To simulate a network issue, the WiFi connection was turned off. When the internet test command was run again, the system returned the message **"Request timed out"**, indicating that the computer was not connected to the internet.

Command used:

ping google.com

Screenshot: Network disconnection error

---

## 5. Troubleshooting Steps

To resolve the issue, the following troubleshooting steps were performed:

1. The WiFi connection was turned back on.
2. The IP address was refreshed using the following commands:

ipconfig /release  
ipconfig /renew

3. The internet connection was tested again using:

ping google.com

The system successfully received replies from the server, confirming that the internet connection had been restored.

Screenshot: Successful connection after troubleshooting

---

## 6. Conclusion

The system check confirmed that the computer hardware and network configuration were functioning correctly. A simulated internet connectivity issue was successfully identified and resolved by reconnecting to the network and renewing the IP address. This exercise demonstrated basic troubleshooting techniques used in IT support.

---

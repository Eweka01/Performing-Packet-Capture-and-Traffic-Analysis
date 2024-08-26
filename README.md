# Performing Packet Capture and Traffic Analysis

**Author**: Osamudiamen Eweka  
**Course**: CYB-605-Z2 Principles of Cybersecurity  
**Institution**: Utica University

## Overview

This lab focuses on packet capture and traffic analysis using Wireshark, a widely recognized open-source network protocol analyzer. The exercises simulate real-world scenarios where participants capture and analyze network traffic at a granular level, using various tools and techniques to understand the intricacies of network communication. This lab emphasizes the significance of packet capture for network security and troubleshooting.

## Objectives

- Understand the purpose and functionality of packet capture and analysis.
- Gain hands-on experience using Wireshark to capture and analyze live network data.
- Explore various network protocols and identify key information within each layer of the TCP/IP stack.
- Differentiate between wired and wireless network traffic.
- Apply filters to isolate specific traffic types and analyze the captured packets.

## Lab Setup

### Lab Environment Details

The lab environment consists of the following hardware and software:

- **Hardware**:
  - Manufacturer: Jones & Bartlett Learning
  - Model: Remote
  - Operating System: Windows 10

- **Software Tools**:
  - **Wireshark**: Packet capture and analysis software.
  - **PuTTY**: Terminal emulator for secure remote communication.
  - **FileZilla**: FTP client for file transfer activities.
  - **Mininet-WiFi**: Network emulator for virtual wireless network creation.
  - **Airodump-ng & Aireplay-ng**: Tools for wireless network security assessments.

## Hands-On Demonstrations

### 1. Packet Capture and Traffic Generation
Participants configure Wireshark to capture live network traffic and generate different types of network activity for analysis. Tasks include:

- Configuring Wireshark to capture packets on the LAN.
- Performing ICMP ping requests to generate network traffic.
- Using PuTTY for Telnet and SSH connections.
- Transferring files using FTP and SFTP protocols with FileZilla.

### 2. Traffic Analysis Using Wireshark
After capturing network traffic, participants analyze the packets within Wireshark, focusing on key details from each protocol. The analysis involves:

- Applying display filters to isolate specific packet types (e.g., ICMP, Telnet, SSH).
- Inspecting packet details at various layers of the TCP/IP model.
- Examining payload data and security implications, such as encryption and plain-text vulnerabilities.

### 3. Analyzing Wireless Network Traffic
Participants capture and analyze wireless network traffic, identifying key elements of wireless communication, including:

- Beacon frames for wireless network identification.
- Control and data frames for medium access and information exchange.
- WPA2 encryption and the four-way handshake process.

## Applied Learning

### 1. Simulating Malicious Traffic
Participants use tools from the Aircrack-ng suite to simulate malicious network traffic, such as deauthentication attacks, and analyze the results in Wireshark. Key tasks include:

- Capturing and analyzing deauthentication packets.
- Isolating and inspecting the four-way handshake used in WPA2 encryption.

### 2. Advanced Traffic Analysis
Participants apply advanced filters in Wireshark to identify and analyze specific types of network traffic, such as HTTP, EAPOL, and FTP. This analysis helps deepen understanding of network security vulnerabilities and encryption methods.

## Conclusion

This lab provides an in-depth exploration of packet capture and traffic analysis, essential skills for network security professionals. Through hands-on experience with Wireshark, participants gain practical knowledge of how network communication works, how to identify vulnerabilities, and how to protect against potential threats.

## References

- Hofstede, R., Celeda, P., Trammell, B., Drago, I., Sadre, R., Sperotto, A., & Pras, A. (2014). Flow Monitoring Explained: From Packet Capture to Data Analysis With NetFlow and IPFIX. IEEE Communications Surveys & Tutorials, 16(4), 2037–2064. https://doi.org/10.1109/comst.2014.2321898
- Imperva. (2021). What Is OSI Model | 7 Layers Explained. Imperva. https://www.imperva.com/learn/application-security/osi-model/
- Lotfollahi, M., Jafari Siavoshani, M., Shirali Hossein Zade, R., & Saberian, M. (2019). Deep packet: A novel approach for encrypted traffic classification using deep learning. Soft Computing. https://doi.org/10.1007/s00500-019-04030-2
- Petters, J. (2019, August 29). How to Use Wireshark: Comprehensive Tutorial + Tips | Varonis. Inside out Security. https://www.varonis.com/blog/how-to-use-wireshark

For a complete list of references, please refer to the full lab report.


## Documentation

For more details, you can refer to the full lab report: 
[Packet Capture and Traffic Analysis](https://github.com/user-attachments/files/16739327/Lab.3-.Performing.Packet.Capture.and.Traffic.Analysis.docx)

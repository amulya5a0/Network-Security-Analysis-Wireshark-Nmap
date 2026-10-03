# Wireshark 
## WireShark Network Packet Analysis

Overview

This project demonstrates basic network traffic analysis using Wireshark, a network protocol analyzer used to capture and inspect network packets in real time.

The project covers:

* Starting Wireshark
* Capturing network packets
* Saving packet captures
* Inspecting individual packets
* Analyzing packet details and bytes
* Using Wireshark statistics
* Analyzing network conversations
* Applying display filters
* Filtering TCP traffic

## Tools Used

* Wireshark
* TCP/IP Networking
* Packet Capture
* Network Traffic Analysis
* PCAP / PCAPNG

### 1. Starting Wireshark

Wireshark can be launched through the Start Menu or by using the Windows Run command.

### Steps

1. Open the Start Menu or press `Windows + R`.
2. Type `Wireshark`.
3. Press Enter.
4. Select the required network interface.

### 2. Packet Capture

After opening Wireshark, a network interface can be selected to begin packet capture.

### Steps

1. Select a network interface from the Wireshark welcome screen.
2. Double-click the interface or select Capture → Start.
3. Allow Wireshark to capture network traffic.
4. Stop the capture after collecting sufficient packets.


The captured packets are displayed in the packet list, where information such as protocols and packet details can be inspected.

### 3. Saving Packet Captures

Captured traffic can be saved for later analysis.

### Steps

1. Select File → Save.
2. Enter a filename.
3. Save the capture.

Recommended capture formats:

* `.pcap`
* `.pcapng`


### 4. Packet Analysis

After capturing or opening a packet capture file, individual packets can be selected from the packet list.

Wireshark provides detailed information through:

* Packet List Pane
* Packet Details Pane
* Byte View Pane

Expanding protocol sections allows individual protocol fields to be inspected.


### 5. Packet Details and Byte View

Selecting a field in the packet details tree highlights the corresponding bytes in the byte view.

This helps understand how protocol information is represented within the captured packet.


### 6. Wireshark Statistics

Wireshark provides statistical tools for analyzing captured network traffic.

Open:

Statistics → Capture File Properties

Statistics can be used to understand properties of the captured file and analyze network activity.


### 7. Conversations Analysis

Wireshark can be used to analyze conversations between network endpoints.

Conversation statistics can help identify communication between hosts and understand network traffic patterns.


### 8. Network Traffic Analysis

Wireshark statistics can be useful for investigating different layers of network communication.

## Ethernet / Layer 2

Can help identify and isolate issues such as broadcast storms.

## TCP/IP / Layer 3 and Layer 4

Can help analyze traffic between systems and identify hosts generating network traffic.

### 9. Wireshark Filters

Wireshark provides two types of filters:

## Capture Filters

Capture filters are applied while packets are being captured and can be configured through the Capture Options dialog.

## Display Filters

Display filters are used after packets have been captured to display only packets matching specific conditions.

Display filters can filter packets based on:

* Protocol
* Field presence
* Field values
* Comparisons between fields

### 10. TCP Display Filter

The `tcp` display filter can be entered in the Wireshark filter toolbar to display TCP packets.

The filter hides unrelated packets and displays only packets associated with TCP traffic.

What I Learned

Through this exercise, I gained practical exposure to:

* Network packet capture
* TCP/IP traffic analysis
* Packet inspection
* Protocol-level troubleshooting
* Wireshark display filters
* Network statistics
* Conversations between network endpoints
* PCAP/PCAPNG capture files


### Skills Demonstrated

Networking: TCP/IP, OSI Model, Layer 2/3/4 concepts, network traffic analysis

Tools: Wireshark, packet capture, packet inspection

Analysis: Packet filtering, protocol analysis, network statistics, troubleshooting



## Nmap

## Introduction to Nmap

**Nmap (Network Mapper)** is an open-source tool used for **network discovery and security auditing**. It helps identify devices, network services, open ports, and system information during authorized security assessments.

## Network Discovery and Scanning

Nmap can identify active hosts and help map a network through network discovery techniques such as **ping sweeps**, which determine which devices are active on a network.

## Port Scanning

Nmap scans target systems to identify **open and closed ports**. Open ports can indicate services running on a system and help administrators understand the services exposed on a network.

## Service Version Detection

Nmap can identify the versions of services running on open ports. This information can assist in identifying outdated services and assessing potential security risks.

## OS Fingerprinting

Nmap supports **OS detection** by analyzing responses from target systems and using TCP/IP stack fingerprinting to determine the operating system.

## Scan Types and Techniques

Nmap supports different scanning techniques, including:

* **SYN Scan**
* **TCP Connect Scan**
* **UDP Scan**

These techniques provide different approaches to network scanning depending on the assessment requirements.

## Nmap Scripting Engine (NSE)

The **Nmap Scripting Engine (NSE)** extends Nmap's capabilities by allowing scripts to automate tasks such as service enumeration and security-related checks.

## Stealth Scanning

Techniques such as **SYN scanning** can reduce the amount of connection establishment performed during a scan. The effectiveness of detection avoidance depends on the network configuration and security controls in place.

## Integration with Other Tools

Nmap supports structured output formats such as **XML**, allowing scan results to be processed by other network management and security tools.

## Security Auditing and Penetration Testing

Nmap is commonly used by network administrators and security professionals for authorized security assessments, network discovery, service enumeration, and configuration verification.

## Legal and Ethical Use

Nmap should only be used on systems and networks where you have **explicit authorization** to perform scanning. Unauthorized scanning may violate organizational policies or applicable laws.

## Conclusion

Nmap is a useful network security tool for understanding network environments, discovering active hosts, identifying exposed ports and services, and performing basic security analysis.


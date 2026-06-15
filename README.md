# Understanding Network Security & Basic Traffic Monitoring

**Done By:** Subodh Kumar
**Domain:** Cyber Security

## Objective

To understand network security fundamentals, common network attacks, and perform basic network traffic analysis using Wireshark.

## Network Security Concepts

Network security protects devices, networks, and data from unauthorized access, attacks, and misuse.

### Basic Networking Concepts

* **IP Address:** Unique address assigned to a device on a network.
* **DNS:** Converts domain names into IP addresses.
* **HTTP:** Protocol used for web communication.
* **HTTPS:** Secure version of HTTP that uses encryption.

## Common Network Attacks (Theory Only)

### Man-in-the-Middle (MITM)

An attacker intercepts communication between two parties.

### Distributed Denial of Service (DDoS)

A server is overwhelmed with excessive traffic, making services unavailable.

### Packet Sniffing

Capturing network packets for analysis. It can be used for troubleshooting or malicious purposes.

## Traffic Monitoring Using Wireshark

### Activities Performed

* Started packet capture on the active network interface.
* Visited websites such as Google and Wikipedia.
* Performed DNS lookups.
* Executed `ping google.com`.
* Applied protocol filters (DNS, TLS, ICMP, TCP).
* Analyzed captured traffic.

## Screenshots

### Screenshot 1 – Wireshark Home Screen

![Wireshark Home](Screenshots/screenshot1_wireshark_home.png)

### Screenshot 2 – Live Packet Capture

![Live Capture](Screenshots/screenshot2_live_capture.png)

### Screenshot 3 – DNS Traffic Analysis

![DNS Analysis](Screenshots/screenshot3_dns_analysis.png)

### Screenshot 4 – HTTPS/TLS Traffic

![HTTPS Traffic](Screenshots/screenshot4_https_tls.png)

### Screenshot 5 – ICMP Traffic

![ICMP Traffic](Screenshots/screenshot5_icmp_ping.png)

### Screenshot 6 – Ping Test in Command Prompt

![Ping Test](Screenshots/screenshot6_ping_google_cmd.png)

### Screenshot 7 – TCP Communication

![TCP Traffic](Screenshots/screenshot7_tcp_handshake.png)

## Traffic Analysis Observations

* DNS packets were observed when websites were accessed.
* TLS packets were observed during HTTPS communication.
* ICMP packets were generated during ping testing.
* TCP packets were used to establish and maintain connections.
* The ping test successfully confirmed connectivity to Google's server.

## Conclusion

This task provided practical exposure to network security fundamentals and traffic monitoring using Wireshark. Through packet analysis, I observed DNS, HTTPS/TLS, ICMP, and TCP traffic while following ethical cybersecurity practices.

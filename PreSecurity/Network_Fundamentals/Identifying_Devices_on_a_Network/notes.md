# Lab Name: Identifying Devices on a Network
**Path:** PreSecurity > Network Fundamentals

## Objective
Learn how devices are identified on a network using IP and MAC addresses, and understand practical implications of network identification and security.

## Environment / Setup
- Platform: TryHackMe Interactive Lab  
- Tools: Built-in lab simulator (no external tools required)  

## Steps Taken
1. Explored device identification on the simulated hotel Wi-Fi network.
2. Observed the behavior of packets for two devices: Alice (paid for Wi-Fi) and Bob (did not pay).
3. Identified Alice’s packets going through normally and Bob’s packets being blocked by the router.
4. Experimented by changing Bob’s MAC address to match Alice’s.
5. Observed that Bob’s packets were now allowed, demonstrating **MAC address spoofing** and its effect on access control.

## Observations & Learnings
- Devices can be identified by two primary identifiers:
  - **IP Address** – temporary and can change depending on the network (public vs private IP).  
  - **MAC Address** – permanent hardware identifier; can be spoofed.  
- Changing a device’s MAC address can bypass access controls that rely solely on MAC-based filtering.  
- Public IP addresses identify devices on the Internet; private IP addresses identify devices within a local network.  
- IPv4 is limited in available addresses; IPv6 solves this by vastly increasing the number of available addresses.  
- Practical labs reinforce the importance of **trust but verify** in network security, as relying only on MAC addresses is insecure.  

## Conclusion
This lab demonstrated the principles of device identification on networks, the difference between IP and MAC addresses, and the security implications of MAC address spoofing. Understanding these fundamentals is crucial for both network management and cybersecurity defense.

## References
- TryHackMe Network Fundamentals Lab: Identifying Devices on a Network
- Cisco (2021). Internet of Things Statistics

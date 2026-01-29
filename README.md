TCP Port Scanner (Python)
-------------------------

This project is a simple TCP port scanner written in Python that demonstrates basic network reconnaissance and enumeration concepts. 
It accepts a single target or multiple targets (comma-separated), resolves domain names to IP addresses, and scans ports 1–99 using raw sockets and the IPy library. 
For each open port discovered, the script attempts to grab and display the service banner, providing additional context about the service running on that port.

**Key features:**
- Resolves hostnames to IP addresses
- Scans ports 1–99 for TCP connectivity
- Attempts to retrieve and display service banners
- Supports scanning multiple targets in one run
- Uses socket timeouts to balance speed and reliability

This project helped me practice Python networking (sockets), understand TCP/IP and basic scanning techniques, and see how port scanners are used during reconnaissance and security assessments.

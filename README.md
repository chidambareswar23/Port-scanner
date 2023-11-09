# Port-scanner
A port scanner is a software tool that is used to identify open ports on a networked system. Ports are communication endpoints that computers and services use to exchange data. An open port is one that is actively accepting connections, while a closed port is not. Port scanning is often used by network administrators and security professionals to assess the security of a network, identify potential vulnerabilities, and ensure that only necessary ports are open.

This script defines two functions:

scan_port(target, port): Attempts to establish a connection to the specified port on the target. If successful, it prints that the port is open; otherwise, it prints that the port is closed.

scan(target, ports): Iterates through a range of ports and calls scan_port for each port.

In the script, the user is prompted to enter the target IP address and a port range. The script then scans each port in the specified range on the target IP address.

Keep in mind that this is a basic example, and in real-world scenarios, more advanced port scanners may be used, often incorporating multithreading or asynchronous techniques for faster scanning. Additionally, always ensure that you have permission to scan the target system, as unauthorized scanning can be considered malicious behavior.







How It Works:
Port Scanning: The script uses Python’s socket library to scan a range of ports (1-1024) on a target system.
Service Detection: It uses Nmap (through python-nmap library) to detect the service running on each open port.
Vulnerability Checking: The script cross-references the service version with a basic database of known vulnerabilities.
Report: It provides a simple report of open ports, services running on them, and potential vulnerabilities.

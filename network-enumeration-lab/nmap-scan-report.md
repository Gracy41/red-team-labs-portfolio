![nmap-scan png](https://github.com/user-attachments/assets/e45f6bd8-34bc-4909-a685-9b79815ca5ec)
Network Enumeration Lab – Nmap
Objective

To identify open ports and running services on a vulnerable target machine within my VMware lab environment.

Tool Used

Nmap

Command Executed
nmap -sV -sC -A <target-IP>

Summary of Findings

Example Findings (Lab Simulation)

* Port 21 – FTP service detected

* Port 22 – SSH service detected

* Port 80 – HTTP web server detected

* Service version information gathered

Identified multiple open ports

Detected running services and versions

Observed potential attack surface

Security Risk

Exposed services increase the attack surface and may allow attackers to identify vulnerable software versions that can be exploited.
Mitigation Recommendations

Disable unnecessary services

Apply security patches

Restrict access using firewall rules

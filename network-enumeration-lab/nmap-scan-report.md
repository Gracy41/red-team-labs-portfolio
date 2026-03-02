Network Enumeration Lab – Nmap
Objective

To identify open ports and running services on a vulnerable target machine within my VMware lab environment.

Tool Used

Nmap

Command Executed
nmap -sV -sC -A <target-IP>
Summary of Findings

Identified multiple open ports

Detected running services and versions

Observed potential attack surface

Security Risk

Exposed services increase the attack surface and may allow unauthorized access if not properly secured.

Mitigation Recommendations

Disable unnecessary services

Apply security patches

Restrict access using firewall rules

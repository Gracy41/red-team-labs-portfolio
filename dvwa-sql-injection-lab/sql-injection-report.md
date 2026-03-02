SQL Injection Lab – DVWA
Objective

To test and exploit SQL injection vulnerability in DVWA (Damn Vulnerable Web Application) within a controlled VMware lab environment.

Environment

Attacker Machine: Kali Linux

Target Application: DVWA

Security Level: Low (for demonstration)

Vulnerability Identified

SQL Injection vulnerability in user input field.

Sample Payload Used
' OR 1=1 --
Result

Successfully bypassed authentication and retrieved database output in low security mode.

Security Risk

SQL injection can allow attackers to:

Bypass authentication

Extract sensitive database information

Modify or delete records

Gain administrative access

Mitigation Recommendations

Use prepared statements

Implement parameterized queries

Perform proper input validation

Deploy Web Application Firewall (WAF)

Password Hash Cracking Lab
Objective

To practice password hash cracking techniques within a controlled VMware lab environment.

Tools Used

John the Ripper / Hashcat

Kali Linux

Hash Type

Example: MD5 (Lab simulation)

Command Used
hashcat -m 0 hash.txt rockyou.txt
Result

Successfully cracked weak password hash using wordlist attack.

Security Risk

Weak password hashing allows attackers to:

Recover plaintext passwords

Gain unauthorized system access

Escalate privileges

Mitigation Recommendations

Use strong hashing algorithms (bcrypt, Argon2)

Apply salting

Enforce strong password policies

Enable multi-factor authentication (MFA)

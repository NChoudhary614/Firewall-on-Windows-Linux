🔒 Task 4 – Setup and Use a Firewall (Windows/Linux)

📌 Objective

The goal of this task is to configure and test basic firewall rules to allow or block traffic on both Windows and Linux systems. This demonstrates understanding of network traffic filtering, ports, and firewall management.


---

🛠 Tools Used

Windows Firewall (GUI / Command Line)

UFW (Uncomplicated Firewall) on Linux



---

📖 Steps Performed

1. Opened Firewall Configuration Tool

Windows → Windows Defender Firewall with Advanced Security

Linux → ufw via terminal



2. Listed Current Firewall Rules

Windows: checked inbound/outbound rules

Linux:

sudo ufw status verbose



3. Added a Rule to Block Port 23 (Telnet)

Windows: created inbound rule to block port 23

Linux:

sudo ufw deny 23



4. Tested the Rule

Tried connecting via Telnet → confirmed connection blocked



5. Allowed SSH (Port 22) (Linux only)

sudo ufw allow 22


6. Removed Test Rule

Restored firewall to original state after verification





---

📊 Outcome

Gained hands-on experience in firewall configuration

Understood how to filter traffic by ports

Learned difference between allow / deny rules

Verified changes by testing blocked and allowed connections







---

📷 Deliverables

Screenshots of firewall rules (Windows + Linux)

Configuration commands used



---

📌 Key Concepts

Firewall configuration

Network traffic filtering

Ports and services

UFW & Windows Firewall

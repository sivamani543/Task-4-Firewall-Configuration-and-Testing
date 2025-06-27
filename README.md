# Task-4-Firewall-Configuration-and-Testing

## Cybersecurity Internship Task

-this task focuses on configuration a firewalls using UFW (uncomplicated firewall). on Linux to practice basic traffic filtering and improve system security

## Objective 

-enable and manage UFW 
-Block inbound traffic on port 239 (telnet)
-Allow inbound traffic on ports 22 (SSH)
-Test the rules and restore the firewalls to its original state.

## Tools Used

-Kali linux / ubuntu
-Firewalls Tools :UFW
(UNCOMPLICATED FIREWALL)

## 🔧 Steps Performed

1. *Enable UFW*
   ```bash
   sudo ufw enable

2. List Current Rules

sudo ufw status numbered


3. Block Port 23 (Telnet)

sudo ufw deny 23


4. Allow Port 22 (SSH)

sudo ufw allow 22


5. Verify Rules

sudo ufw status verbose


6. Remove Telnet Block Rule

sudo ufw delete deny 23

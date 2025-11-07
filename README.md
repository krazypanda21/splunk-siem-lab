# Splunk SIEM Lab

A real-world Splunk SIEM project for detecting and analyzing simulated cyberattacks in a controlled environment.  
This lab demonstrates threat detection, alerting, and log correlation using realistic attack scenarios.

---

## Project Overview
This project replicates a blue-team workflow for detecting and analyzing:
- SSH Brute Force attempts  
- Password Spraying attacks  
- Reverse Shells (C2 connections)  
- Data Exfiltration / Large File Transfers  
- Port Scanning / Reconnaissance  

Each attack is simulated using Kali Linux and monitored through Ubuntu Server logs ingested into Splunk.

---

## Lab Setup
- **Manager (SIEM):** Splunk Enterprise  
- **Attacker:** Kali Linux  
- **Victim:** Ubuntu Server (forwarding logs via Universal Forwarder)  
- **Network:** Local UTM virtualized environment (macOS host)

---

## Key Features
- Custom SPL queries and scheduled alerts  
- Severity-based classifications (Low → Critical)  
- Correlation of UFW, syslog, and authentication events  
- Screenshots of detection dashboards and triggered alerts  
- Realistic attack reproduction with nmap, sshpass, scp, and netcat  

---

## Folder Structure

## Folder Structure

```text
docs/
 ├── attacks/
 │   ├── brute_force.md
 │   ├── password_spray.md
 │   ├── reverse_shell.md
 │   ├── file_transfer.md
 │   └── port_scanner.md
 ├── images/
 ├── dashboards.md
 └── alert_results.md
config/
setup/
```


---

## Author
**Elyjaiah Durden**  
B.S. Computer Science – University of Houston  
CompTIA Security+ Certified  
[GitHub](https://github.com/krazypanda21) | [LinkedIn](https://www.linkedin.com/in/elyjaiah-durden-22b182255/)

---

## License
This project is released for educational and portfolio purposes only.

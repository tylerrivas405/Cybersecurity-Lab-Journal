# Cybersecurity Lab Journal

A log of Information Technology & Cybersecurity labs completed by Tyler Rivas, demonstrating acquired skills and practical experience.

---

## Lab Entry Template

**Lab Title:**  
TryHackMe Blue Room
**Platform/Provider:**  
TryHackMe
**Date Completed:**  
6/11/26
**Objectives:**  
Deploy & hack into a Windows machine, leveraging common misconfigurations issues.
**Summary of Activities:**  
I performed initial reconnaissance on the target using Nmap and identified open Windows-related services on ports 135, 139, and 445. Based on those results, I determined the machine was likely vulnerable to MS17-010 / EternalBlue and noted the SMB-based attack path commonly associated with the Blue room.
I also reviewed the hash shown in the challenge output and recorded the extracted value for later reference. Overall, the lab focused on basic enumeration, vulnerability identification, and documenting the attack surface of a Windows SMB target.
**Skills/Tools Used:**   
Nmap, Metasploit, Meterpreter
**Reflection:**  
This lab helped me build confidence in reading Nmap results and identifying likely vulnerabilities from exposed services.
I am getting better at connecting the dots between port scans and real-world attack paths. I still want to improve my speed and consistency when moving from reconnaissance to exploitation planning.
---

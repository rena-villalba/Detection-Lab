# Detection Lab

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Advanced system monitoring tool (Sysmon) that logs detailed information.

## Steps

Pre-Conditions:
- On the Target Machine we have to enable Remote Desktop Procedure (RDP)
- Also disable Real-Time Protection on Windows Security

*Img 1: Network Diagram*<br>
<img width="383" alt="Screenshot 2025-02-15 210717" src="https://github.com/user-attachments/assets/e7244e32-bf92-4180-a6c6-36677545fd8b" />

*Img 2: Port Scanning from the attacker machine (Reconnaissance)*<br>
<img width="887" alt="2 port_scanning" src="https://github.com/user-attachments/assets/369c751b-02ed-4710-8c55-11fd5010b112" />

*Img 3: Making the payload with the gathered information*<br>
<img width="524" alt="3 payload" src="https://github.com/user-attachments/assets/353eef2d-543f-40b1-9718-ede6def18ea0" />

*Img 4: Starting the handler with Metasploit*<br>
<img width="396" alt="4 handler_msfconsole" src="https://github.com/user-attachments/assets/6da8bbfd-e4b4-49b0-a008-14e0b89de641" />

*Img 5: Configuring the correct shell and payload options*<br>
<img width="442" alt="5 meterpreter_shell" src="https://github.com/user-attachments/assets/8f4936e6-a74e-4837-88d2-ace82f976ad3" />

*Img 6: Making the temporary http web server*<br>
<img width="584" alt="6 temporary_http_server" src="https://github.com/user-attachments/assets/79e4b577-c0d1-4f4f-8f56-099a6189bf20" />

*Img 7: Verifying on the target machine that there is a connection between the two machines*<br>
<img width="491" alt="7 ping_attacker" src="https://github.com/user-attachments/assets/3a0ebc37-53e0-4d43-85b7-2cd2da5db582" />

*Img 8: Accessing the web server of the attcker machine*<br>
<img width="278" alt="fake_http_server" src="https://github.com/user-attachments/assets/00060910-4565-4c04-91b8-dfbf2f93e67a" />

*Img 9: Downloading and running the malware*<br>
<img width="604" alt="running_malware" src="https://github.com/user-attachments/assets/c6dcd28e-8944-4cb8-a1d0-9a2ec7f3a166" />

*Img 10: Checking the established connection to the attacker's station*<br>
<img width="311" alt="connection_established" src="https://github.com/user-attachments/assets/495752e0-fb7b-4c7b-9853-6651fa79e64d" />

*Img 11: Confirming the process "malware" by name and PID*<br>
<img width="842" alt="task_manager_processes" src="https://github.com/user-attachments/assets/6f8c162a-43f2-478b-9b7b-9049f139aed8" />

*Img 12: Checking the Meterpreter shell at the attacker's machine*<br>
<img width="878" alt="12 successful_attack" src="https://github.com/user-attachments/assets/9e2cb8b1-7990-4acd-836a-a49eee396673" />

*Img 13: Creating a shell and searching for the user information*<br>
<img width="368" alt="13 getting_user_info" src="https://github.com/user-attachments/assets/027d49ff-58fc-4ede-9b91-9eec5e634292" />

*Img 14: Searching for the group information*<br>
<img width="356" alt="14 looking_group_info" src="https://github.com/user-attachments/assets/1b8dd956-7433-4a6c-a3d1-75f96e6fa0f0" />

*Img 15: Searching for the group information*<br>
<img width="314" alt="15 looking_ip_info" src="https://github.com/user-attachments/assets/f708c70b-4ce0-459d-a123-ab0244104e78" />

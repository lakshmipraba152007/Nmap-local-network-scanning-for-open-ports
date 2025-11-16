Local Network Port Scanning Using Nmap

📘 Overview


The goal of this task is to perform a network reconnaissance scan on the local network to identify active devices, open ports, and potential security exposures.

This task introduced me to essential concepts in network security such as port scanning, TCP SYN scans, service enumeration, and risk analysis.

🎯 Objective

To scan the local network using Nmap, discover open ports/services, and understand the security implications of exposed network services.

🛠 Tools Used

Nmap → For scanning hosts & ports

Wireshark (optional) → For packet-level analysis

Operating System: Windows / Linux / macOS

📡 Steps Performed

Installed Nmap from the official website.

Identified local IP range, e.g., 192.168.1.0/24.

Ran the following command for a TCP SYN scan:

nmap -sS 192.168.1.0/24

📸 Screenshots

📡 IP of Host device

<img width="399" height="318" alt="image" src="https://github.com/user-attachments/assets/96e1dd59-aada-4813-8fcc-da1f77b9d660" />

🔍 Nmap Scan Output

<img width="403" height="324" alt="image" src="https://github.com/user-attachments/assets/241d2277-a349-4bc7-814c-d0df9e0ed50c" />

<img width="594" height="491" alt="image" src="https://github.com/user-attachments/assets/10325f22-15cd-4546-bb88-024a7ce64330" />

Collected:

Active hosts

Open ports

Detected services

Saved results in text/HTML format (included in this repository).

Analyzed open ports and researched associated security risks.

📁 Repository Contents

scan-results.txt → Raw Nmap scan output

screenshots/ → Screenshots of the scanning process

analysis.md → Explanation of findings & risks

README.md → This documentation

Key Concepts Learned

Port scanning & network reconnaissance

TCP SYN scan mechanism

Service fingerprinting

Open port security risks

Difference between TCP and UDP scanning

Basic use of Wireshark for network observation

✅ Conclusion

This task provided hands-on experience with one of the most fundamental skills in cyber security—network reconnaissance. By scanning the local network with Nmap, I learned how to identify active hosts, detect open ports, and analyze exposed services. This helped me understand how attackers gather information and why securing network services is essential.
Overall, the task strengthened my practical knowledge of port scanning, improved my familiarity with Nmap, and highlighted the importance of proactive network security practices.

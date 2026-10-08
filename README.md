# Network-Penetration-Testing-Lab-
Reconnaissance, credential testing, and traffic analysis in an isolated Kali Linux lab
# Network Penetration Testing Lab

A hands-on lab exercise simulating reconnaissance and exploitation against a target machine in an isolated virtual environment, to practice the core stages of a penetration test.

## Tools
Kali Linux (VirtualBox), Nmap, Hydra, Wireshark, PyPhisher

## How it works
1. Reconnaissance: Used Nmap to scan the target and identify open ports and running services
2. Credential attack: Used Hydra to brute-force FTP login credentials
3. Traffic analysis: Captured and reviewed the FTP session in Wireshark to see how the protocol transmits data
4. Social engineering simulation: Ran PyPhisher in the lab to demonstrate how phishing pages capture victim data (browser, IP, geolocation)

> All testing was performed against machines I own/control in an isolated lab network, for learning purposes only.

## What I learned
How reconnaissance, credential attacks, and traffic analysis fit together in a real engagement, why cleartext protocols like FTP expose credentials, and how convincing phishing pages can look from the attacker's side — which sharpened my sense of what to defend against.

## Possible improvements
Repeat the exercise with encrypted protocols (SFTP) to compare, document full command sequences.
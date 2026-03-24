# SIEM-Splunk-Lab
The task was to make use of Splunk as a SIEM and detecting SSH brute force login attempts. Made use of Ubuntu as the victim computer and then used Kali Linux to brute force attempts which are then logged into a log file and read and analyzed in Slunk Cloud.

Ubuntu (Log source)
Kali (The attacking host)
Splunk Cloud (The SIEM)


What I found:
- Detected several failed login attempts.
- Identified the source IP of the attacker, which was the Kali Linux machine.

Improvements that I can make:
- Real time alerts and automated log forwarding.

<img width="1435" height="621" alt="Screenshot 2026-03-23 at 8 55 04 PM" src="https://github.com/user-attachments/assets/ff7efe7e-34ab-4925-a294-ced539e25d13" />

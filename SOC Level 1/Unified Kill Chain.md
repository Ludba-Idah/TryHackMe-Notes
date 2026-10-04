# Room: SOC L1 Alert Triage
**Category:** Fundamentals

## Overview
This room tells us about the UKR (unified kill chain.

## Key Takeaways

There are 18 stages to the unified kill chain. These include:

# 1. IN (Initial Foothold)
* **Reconnaissance**: Reconnaissance is the research and planning phase of an attack against a system or victim.
* **Resource Development**: Most attackers usually use automated tools to generate the malware or refer to the DarkWeb to purchase the malware.
* **Delivery**: An attacker can use email-address harvesting for a phishing attack (a type of social-engineering attack used to steal sensitive data, including login credentials and credit card numbers).
* **Social Engineering**: Tailoring phishing templates or OAuth-consent apps to look legitimate and dupe the victim.
* **Exploitation**: Exploits are programs or code that take advantage of the vulnerability or flaw in the application or system.
* **Persistence**: Infect the victim's host with a backdoor, which would provide a way to access the computer system, and bypass the security mechanisms.
* **Defense Evasion**: More sophisticated actors or nation-sponsored APT (Advanced Persistent Threat Groups) would write their custom malware to make the malware sample unique and evade detection on the target.
* **Command & Control (C2)**: Set up Command and Control (C2) infrastructure for executing the commands on the victim's machine or deliver more payloads.

# 2. THROUGH (Network Propagation)
* **Pivoting**: use the first hacked computer as a middleman to reach deeper networks
* **Discovery**: look around the network to see what other cool servers they have running
* **Privilege Escalation**: hack your way up from a basic user to admin level
* **Execution**: run your malicious scripts and executables on the internal machines
* **Credential Access**: steal passwords and hashes using tools like mimikatz
* **Lateral Movement**: hop from one computer to the next one in the office network

# 3. OUT (Action on Objectives)
* **Collection**: gather all the juicy files, databases, and sensitive data you found
* **Exfiltration**: sneak all the stolen data out of the network without setting off alarms
* **Impact**: break stuff, mess up their systems, or drop ransomware to lock them out
* **Objectives**: the final goal like getting bragging rights or whatever the hacker wanted

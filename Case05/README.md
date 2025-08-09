🖥️ System Information / Machine State

What is the macOS version and system architecture (Intel/ARM)?

What is the hostname and hardware model?

🧠 General Analysis

What were the first signs of compromise?

Build a timeline of the incident with the main events.

⚙️ Execution and Processes

What is the name of the identified malware (if applicable)?

How was it introduced into the system (e-mail, download, removable media, etc.)?

Which user executed the malware?

Are there signs of file encryption or ransomware activity?

Which binary or script initiated this action?

🛠️ Autostart and Launch Agents (macOS)

Are there indications of persistence through autostart mechanisms?

Was any suspicious LaunchAgent or LaunchDaemon created?

Were .plist files added in locations like ~/Library/LaunchAgents or /Library/LaunchDaemons? and Why?

🗃️ Modified Files

Were critical system or user files modified?

Are there signs of data exfiltration or staging for a leak?

Which files were accessed or copied?

🌐 Network Activity / C2 Communication

Were any connections made to external domains or IP addresses?

Was any Command & Control (C2) IP address or domain identified?

Which protocols and ports were used?

🔍 EDR (Endpoint Detection and Response)

Is there an active EDR solution on the machine (e.g., Microsoft Defender for Endpoint, SentinelOne, etc.)?

Was there an attempt to bypass or disable the EDR?

Did the EDR block any malicious actions or not?

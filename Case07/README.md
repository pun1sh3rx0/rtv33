🖥️ System Info / Machine State

What is the operating system and architecture of the compromised machine?

🧠 General Analysis

What were the first signs of compromise?
Include the initial timestamp, relevant logs, and alerts.

⚙️ Execution and Processes

What is the name of the identified malware?

How was it introduced into the environment?

Which user executed it?

Are there indications of file encryption or ransom demands?

Which process or binary initiated the action?

🛠️ Autostart and Initialization Scripts (Linux)

Are there signs of persistence via initialization or startup scripts?

Which files were modified (e.g., .bashrc, /etc/rc.local, systemd units)?

At what level were they implemented (user or system)?

What commands or scripts are executed automatically?

📅 Scheduled Tasks / Persistence

Are there indications of persistence using cron jobs, systemd timers, or other scheduling mechanisms?

What techniques were used?

Where and how were they deployed?

🪪 Authentication and Logon (Audit / Auth Logs)

Which user executed the malware?

Are there suspicious login or privilege escalation events?
Review /var/log/auth.log, journalctl, or equivalent sources.

🗃️ Modified Files

Is there evidence of data exfiltration or leakage?

Which files were involved?

Were any files encrypted or tampered with by the malware?

🌐 Network Activity / C2 Communication

Were there connections made to external domains or IPs?

What Command & Control (C2) IP was used?

How did the malware communicate (protocol, port, method)?

🔍 EDR (Endpoint Detection and Response)

Is there an active EDR solution on the machine (e.g., Microsoft Defender for Endpoint, SentinelOne, etc.)?

Was there an attempt to bypass or disable the EDR?

Did the EDR block any malicious actions or not?

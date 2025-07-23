🧠 General Analysis

What were the first signs of compromise?
Build a timeline of the incident with the main observed events.

⚙️ Execution and Processes

What is the name of the identified malware (if applicable)?
How was it introduced into the system (e-mail, download, removable media, RDP, etc.)?
Which user executed the malicious binary or script?
Are there indications of file encryption or ransomware activity?
Which executable or script initiated this action (e.g., powershell.exe, cmd.exe, wscript.exe)?

🛠️ Persistence / Autostart (Windows)

Are there any persistence mechanisms configured?
Are there suspicious entries in the Registry keys?
Were any tasks created in the Task Scheduler?

🗃️ Modified Files

Were critical system or user files modified?
Are there signs of data exfiltration or staging for a leak?
Which files were accessed, modified, or copied?

🌐 Network Activity / C2 Communication

Were connections made to suspicious external domains or IP addresses?
Was any Command & Control (C2) domain or IP identified?
Which protocols and ports were used (HTTP, HTTPS, DNS, etc.)?
Are there signs of DNS tunneling, use of PowerShell Remoting, WinRM, etc.?

🔍 EDR (Endpoint Detection and Response)

Is there an active EDR solution on the machine (e.g., Microsoft Defender for Endpoint, SentinelOne, etc.)?
Was there an attempt to bypass or disable the EDR?
Did the EDR block any malicious actions or not?

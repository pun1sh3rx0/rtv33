🧠 General Analysis

What does the malware appear to have done? (exfiltration, persistence, ransomware, etc.) Are there indications that the malware was executed with elevated privileges? Was it possible to identify the name or family of the malware?

🪪 Authentication and Logon (Event Viewer - Security)

Are there any suspicious logon events? Was any user created, modified, or elevated privileges during the incident?

⚙️ Execution and Processes

Which process did the attacker use to execute the malware? Is there any security tool process running? \n

📝 Registry (Registry Autostart Entries)

Were any new persistence entries in the registry identified? Were any known autostart keys modified (e.g., Run, RunOnce, Services, etc.)?

🗃️ Modified Files

Which files were modified before and after the malware execution? Are there any files that appear to be additional payloads or scripts?

🖥️ System Info / Machine State

Were there any changes to the hostname, domain, security settings, or firewall? Any evidence of EDR deactivation or bypass attempt?

📅 Scheduled Tasks / Persistence

Was any scheduled task created to ensure persistence? Does the task point to a malicious binary or script?

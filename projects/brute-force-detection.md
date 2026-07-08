**Brute force attack detection - TryHackMe lab**

OBJECTIVE
To identify and analyse a brute force login attack using log data

TOOLS
TryHackMe
Simulated SIEM interface
Log files

PROCESS
Reviewed authentication logs for failed login attempts
Identified repeated login failures from a single IP address
Observed high-frequency login attempts over a short time period
Correlated timestamps and usernames to confirm attack pattern

FINDINGS
Multiple failed login attempts targeting a specific account
Activity consistent with brute force attack behaviour
Suspicious IP identified as the likely source

LEARNING
How brute force attacks appear in logs
Importance of identifying patterns in authentication data
Basic investigation workflow in a SOC environment

OUTCOME
Successfully detected and analysed a simulated brute force attack, demonstrating foundational threat detection and log analysis skills.

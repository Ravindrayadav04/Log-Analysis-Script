# Log-Analysis-Script
The purpose of this task is to develop and operate a Python script which will perform the automation of server log file analysis. The script would process log files to provide insight as well as potential theft detection and generates a structured output.


**Key Points ::**

**Track User Activity:**
Analyze the log file to keep a count of all requests from each IP address.
Identify usage patterns and any irregularities that indicate higher numbers of requests from one IP.

**Determine Most Popular Endpoints:**
Extract and analyze the highest accessed endpoints (URLs) to know which places get visited the most.
Use this knowledge to apply emphasis on system optimization and resources allocation.

**Detection of Any Suspicious Activities:**
Determine potential brute forces logins or unauthorized access attempts with the help of failed logins from logs.
Flagging those IP addresses, which have any suspicious behavior exceeding defined thresholds for failed login attempts.

**Generate Structured Output:**
Findings should be clear and organized for the user in a terminal.
Result storage in CSV format.

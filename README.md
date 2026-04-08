# Log Analysis Project

## Objective
Analyze log data to detect suspicious login activity.

## Tools Used
- Command Prompt (CMD)

## Commands Used
find "Failed login" logs.txt
find /c "Failed login" logs.txt
find "10.0.0.3" logs.txt

## Results
- Total failed logins: 7
- Suspicious IP: 10.0.0.3
- Failed attempts from this IP: 4

## Analysis
Multiple failed login attempts were detected from a single IP address, which may indicate a brute-force attack.

## Conclusion
Log analysis can help identify suspicious patterns and potential security threats.

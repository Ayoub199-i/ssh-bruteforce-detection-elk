# SSH Brute Force Detection – Technical Report

## Objective
Detect and visualize SSH brute force attacks using ELK.

## Log Source
- `/var/log/auth.log`
- `journalctl (sshd)`

## Parsing
Logstash grok filters extract:
- Timestamp
- Username
- Source IP
- Event type

## Results
- SSH brute force events correctly indexed
- Visible in Kibana with @timestamp
- Screenshots included

## Conclusion
The system successfully detects SSH brute force attempts and provides actionable visibility for security monitoring.

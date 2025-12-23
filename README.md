# SSH Brute Force Detection with ELK Stack

This project implements an SSH brute force detection pipeline using the ELK Stack (Elasticsearch, Logstash, Kibana).

## Architecture
- **Logstash** parses SSH authentication logs
- **Elasticsearch** indexes security events
- **Kibana** visualizes brute force attempts

## Detection Logic
- Failed SSH authentication attempts are parsed
- Events are tagged as `SSH_BRUTE_FORCE`
- Security events are indexed in `security_events-*`

## Technologies
- Kali Linux
- Logstash 8.x
- Elasticsearch 8.x
- Kibana 8.x

## Output
- Structured security events
- Time-based analysis in Kibana
- Ready for SOC use cases

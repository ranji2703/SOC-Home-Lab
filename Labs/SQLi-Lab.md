# SQL Injection Detection Lab

## Objective

Simulate and detect SQL Injection attacks.

## Environment

- Kali Linux
- DVWA
- Splunk Enterprise

## Attack Simulation

Executed SQL Injection payloads against a vulnerable application.

## Detection Query

```spl
index=* ("UNION SELECT" OR "' OR '1'='1")
```

## Findings

Successfully detected SQL Injection attempts through log analysis.

## Skills Demonstrated

- Web Security
- Threat Hunting
- Detection Engineering
- Log Analysis
```

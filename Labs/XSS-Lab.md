# XSS Detection Lab

## Objective

Simulate and detect Cross-Site Scripting attacks.

## Environment

- Kali Linux
- DVWA
- Splunk Enterprise

## Attack Simulation

Injected JavaScript payloads into vulnerable input fields.

## Detection Query

```spl
index=* "<script>"
```

## Findings

Successfully detected XSS payloads in application logs.

## Skills Demonstrated

- Web Application Security
- Threat Hunting
- Log Analysis
- Incident Investigation
```

# Threat Hunting Report

## Overview

This report documents threat hunting activities performed within the SOC Home Lab.

## Data Sources

- Sysmon
- PowerShell Logs
- Snort IDS
- Web Server Logs

## Hunting Activities

### PowerShell Activity

Reviewed Event ID 4104 logs for suspicious script execution.

### Endpoint Monitoring

Analyzed Sysmon Event IDs 1, 3, and 11.

### Web Application Attacks

Investigated XSS and SQL Injection attempts.

### Network Monitoring

Reviewed Snort IDS alerts.

## Outcome

Successfully detected and investigated multiple attack scenarios across host, network, and application layers.
```

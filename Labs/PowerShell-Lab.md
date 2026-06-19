# PowerShell Monitoring Lab

## Objective

Monitor PowerShell activity using Event ID 4104.

## Environment

- Windows Server
- Sysmon
- Splunk Enterprise

## Attack Simulation

Executed PowerShell commands on the monitored host.

## Detection Query

```spl
index=* EventCode=4104
```

## Findings

PowerShell script execution activity was successfully detected and logged in Splunk.

## Skills Demonstrated

- Log Analysis
- Threat Hunting
- PowerShell Monitoring
- Incident Investigation
```

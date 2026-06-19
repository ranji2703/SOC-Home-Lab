# Sysmon Monitoring Lab

## Objective

Monitor endpoint activity using Sysmon.

## Event IDs Monitored

- Event ID 1 - Process Creation
- Event ID 3 - Network Connection
- Event ID 11 - File Creation

## Detection Query

```spl
index=* EventCode=11
```

## Findings

Successfully detected file creation activity and validated Sysmon log collection.

## Skills Demonstrated

- Endpoint Monitoring
- Threat Hunting
- Detection Engineering
- Log Analysis
```

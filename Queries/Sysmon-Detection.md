# Sysmon Detection

## Objective

Monitor endpoint activity using Sysmon logs.

## Event IDs

### Event ID 1
Process Creation

### Event ID 3
Network Connection

### Event ID 11
File Creation

## Detection Queries

### Process Creation

```spl
index=* EventCode=1
```

### Network Connections

```spl
index=* EventCode=3
```

### File Creation

```spl
index=* EventCode=11
```

## Investigation Steps

1. Identify suspicious processes.
2. Review network connections.
3. Detect unauthorized file creation.
4. Correlate events with user activity.

## Result

Successfully monitored endpoint activity using Sysmon logs in Splunk.

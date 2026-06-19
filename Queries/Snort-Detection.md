# Snort IDS Detection

## Objective

Detect suspicious network activity using Snort IDS alerts.

## Data Source

Snort Alert Logs

## Detection Query

```spl
index=* snort
```

## Investigation Steps

1. Review alert signatures.
2. Identify source and destination IP addresses.
3. Determine attack type.
4. Correlate with endpoint activity.

## Result

Successfully detected network-based attacks using Snort IDS.
```

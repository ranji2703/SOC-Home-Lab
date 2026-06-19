# PowerShell Detection

## Objective

Detect PowerShell script execution activity using Event ID 4104.

## Data Source

PowerShell Operational Logs

## Detection Query

```spl
index=* EventCode=4104
```

## Investigation Steps

1. Search for Event ID 4104.
2. Review script block contents.
3. Identify suspicious commands.
4. Investigate source host and user.

## Result

Successfully detected PowerShell execution events within the SOC Home Lab.
```

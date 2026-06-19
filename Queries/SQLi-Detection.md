# SQL Injection Detection

## Objective

Detect SQL Injection attempts against vulnerable web applications.

## Attack Examples

```sql
' OR '1'='1
UNION SELECT
```

## SPL Query

```spl
index=* ("UNION SELECT" OR "' OR '1'='1")
```

## Investigation Steps

1. Review web requests.
2. Identify malicious parameters.
3. Validate affected application.
4. Correlate source IP activity.

## Result

Successfully detected SQL Injection attempts in web logs.
```

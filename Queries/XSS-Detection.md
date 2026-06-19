# Cross-Site Scripting (XSS) Detection

## Objective

Detect XSS attack attempts in web server logs.

## Attack Example

```html
<script>alert("you are hacked")</script>
```

## SPL Query

```spl
index=* "<script>"
```

## Investigation Steps

1. Identify malicious payloads.
2. Review source IP address.
3. Determine affected application.
4. Validate attack success or failure.

## Result

Successfully detected XSS attack attempts from web server logs.
```

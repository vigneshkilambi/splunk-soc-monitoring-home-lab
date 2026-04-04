# Failed Login Detection (Brute Force Indicator)

## Description
This detection monitors multiple failed login attempts on the system, which may indicate a brute-force attack.

## Log Source
- Windows Security Logs
- Event ID: 4625 (Failed Login)

## Detection Logic
If multiple failed login attempts are observed for a user account within a short time, it may indicate a brute-force attempt.

## Analysis
The logs showed repeated failed login attempts for specific user accounts. This pattern suggests unauthorized access attempts.

## Conclusion
Failed login monitoring helps detect brute-force attacks and potential account compromise attempts.

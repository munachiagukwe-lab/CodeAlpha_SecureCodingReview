# Secure Coding Review Report

## Programming Laanguage
Python

## Application Reviewed
Simple Login System

## Review method 
Manual Code Inspection

## Vulnerabilities Found

### 1. Hardcoded Credentials
Issue:
Username and password are directly written inside the code.
risk: Anyone who accesses the source code can see login details.
Reccomendation:
Store credentials securely instead of inside source code'

### 2. Weak Password
Issue: 
User input is accepted without checks.
risks:
may lead to unexpected behaviour.
Recommendation:
Validate and sanitize inputs.


## conclusion
The application contains security weakness.

## Security Improvements Suggested

- Avoid storing usernames and passwords directly in code.
- Use stronger password policies.
- Validate user input before processing
- Consider secure authentication mechanisms.

## Result

The code review identified multiple security concerns and recommendations were provided to improve application security.

## Findings Summary

    Total Vulnerabilities Identified: 3
    Review Status: Completed
    Inspection Method Used: Manual Inspection
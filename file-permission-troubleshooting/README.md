# File Permission Troubleshooting Lab

## Scenario
A user reported they could not access an important file needed for work.

## Problem
The file had incorrect permissions, preventing any user from reading or writing to it.

## Investigation Steps
- Checked file permissions using `ls -l`
- Verified current user with `whoami`
- Attempted to read file using `cat`

## Commands Used
- ls -l
- whoami
- chmod 600
- cat

## Solution
Restored proper owner read/write permissions using:

chmod 600 report.txt

## Security Considerations
Access was restricted to the file owner only to prevent unauthorized data exposure.

## Skills Demonstrated
- Linux file permissions
- Command-line troubleshooting
- Access control
- Security best practices
- Technical documentation

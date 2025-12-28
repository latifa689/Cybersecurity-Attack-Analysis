# Attack Techniques (Attack Chain)

## Reconnaissance
- Scanned for WebVPN, ASDM, HTTPS
- Identified vulnerable versions

## Initial Access
- Authentication bypass (CVE-20362)
- Stolen/phished VPN credentials
- Crafted HTTPS requests → RCE (CVE-20333)

## Exploitation
- Privilege escalation
- Modifications to AAA, ACL, WebVPN
- Creation of hidden admin accounts

## Persistence
- Startup-config manipulation
- Hidden VPN tunnels
- Unauthorized scripts for reboot persistence

## Lateral Movement
- Target internal servers, AD, admin systems
- Expand privileges across internal segments


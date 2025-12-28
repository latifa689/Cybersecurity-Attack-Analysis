# Mitigation and Hardening Recommendations

## ASA / FTD Devices
- Isolate management interfaces
- Disable unnecessary HTTP server services
- Restrict admin access to internal Jumpbox
- Monitor AAA, ACL, WebVPN with SIEM

## IOS / IOS XE Devices
- Enable CoPP
- Restrict SSH/HTTPS to trusted Ips
- Disable unused services (CDP/LLDP, Ipv6)
- Verify integrity (Secure Boot, image hash)

## Network-Wide Measures
- Separate VLANs for management/production
- Deploy IDS/IPS
- Centralize logging via SIEM
- Regular audits comparing running/startup-config
- Enforce strict ACLs and MFA for VPN accounts


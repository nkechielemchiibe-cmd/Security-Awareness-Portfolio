 Unauthorized Access Incident Response Playbook

This playbook outlines the steps for responding to unauthorized access attempts or confirmed access to systems, applications, or PHI in a healthcare environment.

 1. Detection
Unauthorized access may be detected by:
- SOC alerts
- EHR audit logs
- Unusual login patterns
- Failed login attempts
- Staff reports of suspicious activity

 2. Initial Assessment
- Identify the affected user account
- Determine whether access was internal or external
- Review timestamps and access logs
- Check whether PHI or critical systems were accessed
- Determine whether the account was compromised or misused

 3. Containment
- Immediately disable the affected account
- Revoke active sessions and tokens
- Block suspicious IP addresses or devices
- Reset passwords and enforce MFA re‑authentication

 4. Eradication
- Remove unauthorized changes or configurations
- Scan affected systems for malware
- Patch vulnerabilities exploited during the incident
- Review access permissions and remove unnecessary privileges

 5. Recovery
- Restore legitimate access for the user (if appropriate)
- Re-enable required applications and permissions
- Monitor the account and system for 48–72 hours

 6. User Education
If the incident involved a compromised account:
- Provide targeted training on password hygiene
- Reinforce MFA usage
- Review secure login practices

 7. Documentation & Reporting
- Document the incident in the security log
- Notify privacy/compliance if PHI was accessed
- Determine whether regulatory reporting is required
- Conduct a post‑incident review

 8. Prevention Improvements
- Strengthen access controls
- Improve log monitoring and alerting
- Enforce least‑privilege access
- Update staff training based on incident findings

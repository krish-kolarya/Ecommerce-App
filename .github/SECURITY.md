# Security Policy

_Last updated: May 16, 2025_

This document describes the security vulnerability disclosure process for the **MERN Stack Ecommerce** project. It covers supported versions, reporting guidelines, response commitments, and safe-harbor protections for security researchers.

---

## Supported Versions

| Version   | Supported |
| --------- | --------- |
| `1.1.x`   | YES       |
| `1.0.x`   | YES       |
| `< 1.0.0` | NO        |

We backport critical and high-severity security fixes to the latest two minor versions (`1.1.x` and `1.0.x`) for at least 90 days after release. Older versions are no longer supported—users should upgrade to a supported release as soon as possible.

## Response Timeline

| Phase                            | Commitment              |
| -------------------------------- | ----------------------- |
| Acknowledgement                  | Within 48 hours         |
| Preliminary triage & severity    | Within 5 business days  |
| Patch deployment (high/critical) | Within 30 days          |
| Patch deployment (medium/low)    | Within 90 days          |
| Public disclosure                | After patch is released |

We’ll keep you updated throughout the process. If you do not hear back within 48 hours, feel free to send a reminder.

---

## Safe Harbor

We welcome and appreciate good-faith security research. As long as you:

- Limit your testing to your own accounts or demo environments.
- Do not access, modify, or delete any data you do not own.
- Do not degrade the service for other users.
- Promptly report any issues you find to us.

—you will not face legal action from the MERN Stack Ecommerce team.

---

## Acknowledgments

Thank you to all security researchers and contributors who help us keep our project safe. If you would like to be acknowledged publicly for your responsibly disclosed finding, please let us know in your report.

---

## References

- [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Node.js Security Working Group](https://github.com/nodejs/security-wg)

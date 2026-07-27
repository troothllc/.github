# Security Policy

## Reporting a Vulnerability

Trooth, LLC welcomes responsible disclosure of security vulnerabilities. We treat all reports with the seriousness they deserve and we do not pursue legal action against good-faith security researchers who comply with this policy.

### How to Report

Send your report to **security@trooth.co**. Use PGP if your report contains sensitive proof-of-concept material; our PGP key is available on request.

Include the following information where available:

- A description of the vulnerability and its potential impact
- Step-by-step reproduction instructions
- The affected version of this repository
- Any proof-of-concept code or screenshots
- Your name or handle (if you wish to be credited)

### Our Commitments

- **Acknowledgment within three (3) business days.**
- **Substantive response within ten (10) business days.**
- **Coordinated disclosure.** Standard window is ninety (90) days from acknowledgment.
- **Credit.** We credit reporters who request acknowledgment in our security advisories.

### Scope

In scope:

- This repository and any code in it
- Documented behavior of this project against the Trooth public API

Out of scope:

- The Trooth backend at `api.trooth.co` and other Trooth proprietary services (report through the same channel; they have separate scope)
- Vendor-managed infrastructure (Cloudflare, GitHub, npm, PyPI). Report to those vendors directly.
- Vulnerabilities in upstream language runtimes or libraries (report to the upstream maintainers)
- Denial-of-service testing of any Trooth infrastructure without prior written authorization

### Safe Harbor

Trooth, LLC commits to the following safe harbor for security researchers acting in good faith and consistent with this policy:

- We will not initiate or support legal action against you for accessing or interacting with our systems for the limited purpose of identifying vulnerabilities.
- We will not initiate or support legal action against you for accessing data necessary to identify or reproduce a vulnerability, provided that you do not access, modify, exfiltrate, retain, or share more data than is necessary for that purpose.
- If a third party initiates legal action against you for research conducted under this policy, we will make it known that your activities were conducted in compliance with this policy.

You must comply with all applicable laws. You must not access, modify, exfiltrate, retain, or share customer data, and you must not disrupt the availability or integrity of services for customers.

### Full Disclosure Policy

See the Trooth Vulnerability Disclosure Policy at https://www.trooth.co/vdp for the full version of this policy as it applies across all Trooth assets.

_Last reviewed: June 8, 2026._

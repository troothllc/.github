# Security Policy

Trooth, LLC welcomes good-faith disclosure of security vulnerabilities and does not pursue legal action against researchers who follow this policy.

This file is the repository-level summary. The governing document is the [Vulnerability Disclosure Policy](https://trooth.co/security/vulnerability-disclosure-policy) at trooth.co, and the machine-readable record is [/.well-known/security.txt](https://trooth.co/.well-known/security.txt). Where this file and that policy differ, the policy on trooth.co applies.

## How to report

Send the report to **security@trooth.co**. That is the address in `security.txt`, and it is the only reporting channel.

Include, where you have it:

- A description of the vulnerability and what an attacker could do with it.
- Step-by-step reproduction instructions.
- The affected repository, endpoint or version.
- Any proof-of-concept material that helps validate the finding.
- Your name or handle, if you want to be credited.

Reports in English are processed fastest.

**On encryption:** Trooth publishes no PGP key. `security.txt` carries no `Encryption` field and there is no key at any URL. Earlier copies of this file said one was available on request, and another Trooth repository's security policy still sends researchers to a PGP-key page on trooth.co, and to a researcher credits page beside it, neither of which has ever existed. If your finding requires sending sensitive material, say so in a first plain email without the payload and a channel will be arranged before you send it.

## What you can expect

- **Acknowledgment within three (3) business days.**
- **A substantive response within ten (10) business days**, carrying an assessment and an expected remediation timeline.
- **Progress reports** as the fix is worked on.
- **Credit** in the advisory, if you want it. Trooth publishes no researcher hall of fame; the credit is in the advisory for the issue you reported.

## Coordinated disclosure

Give Trooth a reasonable opportunity to remediate before disclosing publicly.

Ninety (90) days from acknowledgment is the window Trooth proposes as a default. The Vulnerability Disclosure Policy asks instead that a timeline be agreed between us for the specific finding. The two are not the same commitment and the policy is the one that governs; the default is stated here so you know what is being proposed if nothing else is agreed.

## Scope

In scope for this repository:

- This repository and any code in it.
- The documented behaviour of this project against the public Trooth API.

Out of scope for this repository, but **in scope for the Vulnerability Disclosure Policy**, reported to the same address:

- `trooth.co` and the backend at `api.trooth.co`. They have their own scope under the policy; sending it here is correct.

Out of scope everywhere:

- Vendor-managed infrastructure — Cloudflare, GitHub, npm, PyPI. Report to the vendor under its own programme. Trooth will help coordinate where that makes sense.
- Vulnerabilities in upstream language runtimes or libraries. Report to the upstream maintainers.
- Volumetric denial-of-service testing against any Trooth infrastructure, without prior written authorisation.
- Social engineering of Trooth personnel or customers, and physical attacks.
- Automated scanner output with no demonstrated impact, and missing-header or best-practice findings with no concrete exploit.

## Safe harbour

For research conducted in good faith and consistent with this policy, Trooth, LLC commits that:

- It will not initiate or support legal action against you for accessing or interacting with its systems for the limited purpose of identifying a vulnerability.
- It will not initiate or support legal action against you for accessing the data necessary to identify or reproduce a vulnerability, provided you do not access, modify, exfiltrate, retain or share more than that.
- If a third party brings legal action against you for research conducted under this policy, Trooth will make it known that your activity complied with it.

You must comply with applicable law. You must not access, modify, exfiltrate, retain or share customer data, and you must not degrade the availability or integrity of the service for anyone else.

## What this policy is not

Trooth witnesses and dates facts; it does not score, rate, rank or certify anyone. Reporting a vulnerability here does not produce a rating of Trooth or of anybody else, and a fixed vulnerability does not become a mark on anyone's record.

---

Last reviewed 2026-09-19. The Vulnerability Disclosure Policy it defers to was last updated 2026-06-08.

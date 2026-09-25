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

**On encryption:** Trooth publishes no PGP key. `security.txt` carries no `Encryption` field and there is no key at any URL. Earlier copies of this file said one was available on request, and another Trooth repository's security policy has sent researchers to a PGP-key page on trooth.co, and to a researcher credits page beside it, neither of which has ever existed. If your finding requires sending sensitive material, say so in a first plain email without the payload, and wait for a reply before you send it.

## What you can expect

- **Acknowledgment within three (3) business days.**
- **A substantive response within ten (10) business days**, carrying an assessment and an expected remediation timeline.
- **Progress reports** as the fix is worked on.
- **Credit**, publicly and once the issue is resolved, if you want it. Trooth publishes no researcher hall of fame.

## Coordinated disclosure

Give Trooth a reasonable opportunity to remediate before disclosing publicly.

The Vulnerability Disclosure Policy sets no fixed number of days. It says Trooth will work with you in good faith to agree on a disclosure timeline for the specific finding. Earlier copies of this file proposed ninety (90) days from acknowledgment as a default. The policy does not contain that figure and the policy is the one that governs, so this file no longer proposes it.

## Scope

In scope for this repository:

- This repository and any code in it.
- The documented behavior of this project against the public Trooth API.

Out of scope for this repository, but **in scope for the Vulnerability Disclosure Policy**, reported to the same address:

- `trooth.co` and the backend at `api.trooth.co`. They have their own scope under the policy; reporting them to security@trooth.co is correct.

Out of scope everywhere:

- Vendor-managed infrastructure (Cloudflare, GitHub, npm). Report to the vendor under its own program. Trooth will help coordinate where that makes sense.
- Vulnerabilities in upstream language runtimes or libraries. Report to the upstream maintainers.
- Volumetric denial-of-service testing against any Trooth infrastructure.
- Social engineering of Trooth personnel or customers, and physical attacks.
- Automated scanner output with no demonstrated impact, and missing-header or best-practice findings with no concrete exploit.

## Safe harbor

The safe harbor is the one in the Vulnerability Disclosure Policy, and its words govern. It reads:

> Trooth, LLC will not pursue legal action against security researchers who act in good faith and comply with this policy. Good faith means you make a reasonable effort to avoid privacy violations, degradation of service, and destruction or exfiltration of data; you do not access, modify, or retain customer data beyond the minimum necessary to demonstrate a vulnerability; and you give us a reasonable opportunity to remediate before any public disclosure.

Earlier copies of this file listed further commitments here, including one about legal action brought by a third party. The policy does not contain them and the policy governs, so this file no longer lists them.

If you are unsure whether an action is covered, email security@trooth.co and ask before you take it.

## What this policy is not

Trooth witnesses and dates facts; it does not score, rate, rank or certify anyone. Reporting a vulnerability here does not produce a rating of Trooth or of anybody else, and a fixed vulnerability does not become a mark on anyone's record.

---

Last reviewed 2026-09-25. The Vulnerability Disclosure Policy it defers to was last updated 2026-06-08.

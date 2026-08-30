<div align="center">

<img src="https://raw.githubusercontent.com/troothllc/.github/main/profile/banner.png" alt="Trooth" width="820" />

### The witnessed trust network for software and AI companies

Every company on the Trooth Network gets a public trust profile built from **witnessed evidence**: real security, privacy, and AI-governance posture, observed from live systems, signed and timestamped, and kept current automatically. Buyers and their AI agents read and compare it with no login. No self-marked questionnaires. No pay-for-a-badge.

**[Join the Network](https://trooth.co/signup)** · **[Browse the Network](https://trooth.co/network)** · **[How witnessing works](https://trooth.co/methodology)** · **[Docs](https://trooth.co/docs)** · **[Pricing](https://trooth.co/pricing)**

[![Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-0B0B0B)](https://www.apache.org/licenses/LICENSE-2.0) [![npm trooth](https://img.shields.io/npm/v/trooth?label=npm%20trooth&color=D5C884)](https://www.npmjs.com/package/trooth) [![MCP registry](https://img.shields.io/badge/MCP%20registry-io.github.trooth--eng%2Ftrooth--network-1A73E8)](https://registry.modelcontextprotocol.io)

</div>

---

## For companies: prove it once, and stop repeating yourself

Trooth witnesses your public and system evidence and turns it into one link a buyer can trust. Send a profile, not a 300-row spreadsheet.

| You are | What the Network does for you |
| --- | --- |
| **An indie founder** | A public trust profile that answers "can we trust this vendor?" before you can afford a security team, and a listing in a directory buyers actually search. |
| **A startup** | Witnessed security posture that turns weeks of enterprise security review into a link. |
| **A mid-size company** | Posture mapped to SOC 2, ISO 27001, the EU AI Act, NIST AI RMF, GDPR, and HIPAA, with drift surfaced when it happens, not at audit time. |
| **An enterprise** | Every vendor evaluated on the same witnessed evidence, side by side. Require Trooth across your vendor list and stop chasing PDFs. |

Marketing, exposure, security posture, AI posture: one profile carries all of it, because it all comes from the same witnessed evidence.

**Get witnessed at [trooth.co/signup](https://trooth.co/signup).**

## For buyers and AI agents: check anyone, no login

The Network directory is public and free. Search it, open any profile, and compare vendors without creating an account, at [trooth.co/network](https://trooth.co/network).

Your AI can read it too. Add the read-only Trooth connector to Claude, ChatGPT, or Cursor and ask about any company in plain words, or check one from your terminal:

```bash
npx trooth check stripe.com
```

Endpoint (read-only, no key, no account): `https://api.trooth.co/public/mcp`

## What we open-source

The Trooth platform is proprietary. What we open-source is everything a third party needs to read a company's record, verify a Trooth-issued artifact, and wire Trooth into their own stack. All public repositories are Apache 2.0.

| Repo | What it is |
| --- | --- |
| [**trooth-mcp**](https://github.com/trooth-eng/trooth-mcp) | The public, read-only MCP connector. Point Claude, ChatGPT, or Cursor at `https://api.trooth.co/public/mcp` and check any company. |
| [**trust-verifier-sdk**](https://github.com/troothllc/trust-verifier-sdk) | Independently verify any Trooth Trust Receipt without trusting Trooth. Ed25519 and RFC 3161 against our published keys. |
| [**trooth-platform**](https://github.com/troothllc/trooth-platform) | The developer platform: canonical OpenAPI 3.1 spec, architecture, and copy-paste examples in cURL, Node, Python, and Go. |
| [**trooth-cli**](https://github.com/troothllc/trooth-cli) | Run Trooth from your terminal: scan your posture, verify Trust Receipts, and check any company's standing. |
| [**trooth-action**](https://github.com/troothllc/trooth-action) | GitHub Action that witnesses your repo's posture on every push. Free for public repos. |
| [**trooth-vscode**](https://github.com/troothllc/trooth-vscode) | VS Code and Cursor extension: witness posture, check drift, and verify receipts without leaving your editor. |
| [**trooth-templates**](https://github.com/troothllc/trooth-templates) | Open-source policy and disclosure templates the Network witnesses: Privacy Policy, ToS, AUP, AI Use Policy, Model Card, security.txt, SBOM, and AI-code disclosure. |
| [**trooth-eval-harnesses**](https://github.com/troothllc/trooth-eval-harnesses) | Open evaluation harnesses for NIST CSF 2.0, NIST AI RMF 1.0, the EU AI Act, GDPR, and CCPA. |

## For security researchers

See our [Vulnerability Disclosure Policy](https://trooth.co/security) and [/.well-known/security.txt](https://trooth.co/.well-known/security.txt). Our own posture is witnessed the same way every other company on the Network is, at [trooth.co/security](https://trooth.co/security).

## Contact

General: hello@trooth.co · Security: security@trooth.co · Legal: legal@trooth.co · Privacy: privacy@trooth.co

<div align="center">

**Trooth automates. Trooth never signs.** Your systems produce the evidence; Trooth witnesses it and shows the source and timestamp of every claim. Nothing on the Network is certified, guaranteed, or taken on anyone's word, including ours.

// BUILT FOR YOU, NOT OFF YOU //

© 2026 Trooth, LLC · Miami, Florida

</div>

<div align="center">

<img src="https://raw.githubusercontent.com/troothllc/.github/main/profile/banner.png" alt="Trooth" width="820" />

### The trust profile every software and AI company needs

Your company has a LinkedIn. It probably has a Crunchbase, maybe a G2. The Trooth Network is where its **security, privacy, and AI trust** lives: the record a buyer, or a buyer's AI assistant, reads before deciding whether to trust you. Witnessed from your live systems, signed, dated, and kept current on its own.

**[Claim your free profile](https://trooth.co/signup)** · **[How witnessing works](https://trooth.co/methodology)** · **[Docs](https://trooth.co/docs)** · **[Pricing](https://trooth.co/pricing)**

[![Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-0B0B0B)](https://www.apache.org/licenses/LICENSE-2.0) [![npm trooth](https://img.shields.io/npm/v/trooth?label=npm%20trooth&color=D5C884)](https://www.npmjs.com/package/trooth) [![MCP registry](https://img.shields.io/badge/MCP%20registry-io.github.trooth--eng%2Ftrooth--network-1A73E8)](https://registry.modelcontextprotocol.io)

</div>

---

## When a buyer checks you, what do they find?

Before anyone buys software, someone on their side asks the same question: can we trust this vendor? Today that means a slow questionnaire, a stale PDF, or a self-marked badge no one witnessed. More and more, an AI assistant answers it first, from whatever it can find.

Give it something real to find. A witnessed Trooth profile shows your security, privacy, and AI posture with a source and a date on every claim. The vendor with a current, witnessed profile is the one that clears review and wins the deal. The vendor with nothing looks like a risk.

**[Claim your free profile at trooth.co/signup](https://trooth.co/signup)**

## What a profile gives you

**Witnessed, not self-reported.** Trooth reads your public and system evidence directly, signs it, and dates it. Buyers trust it precisely because you did not write it.

**One link instead of a questionnaire.** Send a profile, not a 300-row spreadsheet, every time a buyer asks.

**Always current.** Your profile is re-witnessed on its own, so it never goes stale, and drift shows up when it happens instead of at audit time.

**Read by buyers and their AI agents.** Your profile is public and readable with no login, so a buyer or their AI assistant can check you in seconds.

**Mapped to the frameworks buyers ask about.** SOC 2, ISO 27001, the EU AI Act, NIST AI RMF, GDPR, and HIPAA. One profile carries all of it.

From a solo founder without a security team yet to an enterprise managing a hundred vendors of its own, it is the same witnessed evidence, read the same way.

**[Claim your company's page, free](https://trooth.co/signup)**

## For buyers and AI agents: check any company, no login

Anyone can check a company's witnessed record with no account. From an AI assistant, add the read-only Trooth connector to Claude, ChatGPT, or Cursor and ask in plain words. From your terminal:

```bash
npx trooth check trooth.co
```

Endpoint (read-only, no key, no account): `https://api.trooth.co/public/mcp`

This is exactly why a profile matters: when a buyer or their AI checks you, a witnessed profile is what they find.

## What we open-source

The Trooth platform is proprietary. What we open-source is everything a third party needs to read a company's record, verify a Trooth-issued artifact, and wire Trooth into their own stack. All public repositories are Apache 2.0.

| Repo | What it is |
| --- | --- |
| [**trooth-mcp**](https://github.com/troothllc/trooth-mcp) | The public, read-only MCP connector. Point Claude, ChatGPT, or Cursor at `https://api.trooth.co/public/mcp` and check any company. |
| [**trust-verifier-sdk**](https://github.com/troothllc/trust-verifier-sdk) | Independently verify any Trooth Trust Receipt without trusting Trooth. Ed25519 and RFC 3161 against our published keys. |
| [**trooth-platform**](https://github.com/troothllc/trooth-platform) | The developer platform: canonical OpenAPI 3.1 spec, architecture, and copy-paste examples in cURL, Node, Python, and Go. |
| [**trooth-cli**](https://github.com/troothllc/trooth-cli) | Run Trooth from your terminal: scan your posture, verify Trust Receipts, and check any company's standing. |
| [**trooth-action**](https://github.com/troothllc/trooth-action) | GitHub Action that witnesses your repo's posture on every push. Free for public repos. |
| [**trooth-vscode**](https://github.com/troothllc/trooth-vscode) | VS Code and Cursor extension: witness posture, check drift, and verify receipts without leaving your editor. |
| [**trooth-templates**](https://github.com/troothllc/trooth-templates) | Open-source policy and disclosure templates the Network witnesses: Privacy Policy, ToS, AUP, AI Use Policy, Model Card, security.txt, SBOM, and AI-code disclosure. |
| [**trooth-eval-harnesses**](https://github.com/troothllc/trooth-eval-harnesses) | Open evaluation harnesses for NIST CSF 2.0, NIST AI RMF 1.0, the EU AI Act, GDPR, and CCPA. |

## Security and contact

Our own posture is witnessed the same way every company on the Network is, at [trooth.co/security](https://trooth.co/security). See our [Vulnerability Disclosure Policy](https://trooth.co/security) and [/.well-known/security.txt](https://trooth.co/.well-known/security.txt).

General: hello@trooth.co · Security: security@trooth.co · Legal: legal@trooth.co · Privacy: privacy@trooth.co

<div align="center">

**Trooth automates. Trooth never signs.** Your systems produce the evidence; Trooth witnesses it and shows the source and timestamp of every claim. Nothing on the Network is certified, guaranteed, or taken on anyone's word, including ours.

// BUILT FOR YOU, NOT OFF YOU //

© 2026 Trooth, LLC · Miami, Florida

</div>

<div align="center">

<img src="https://trooth.co/brand/trooth-banner-1500x500.png" alt="Trooth: Machine-Readable Trust infrastructure for people and AI agents" width="820" />

### Machine-Readable Trust infrastructure for people and AI agents

Trooth is an infrastructure and cybersecurity company providing Machine-Readable Trust. Its one product is the Trooth Network: a public, signed, machine-readable record for each company. Find company disclosures and dated observations in one record. See what the company says, what Trooth observed, and where each item came from.

**[Claim your company's record](https://trooth.co/signup)** · **[How Trooth witnesses](https://trooth.co/methodology)** · **[Docs](https://trooth.co/docs)**

[![Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-0B0B0B)](https://www.apache.org/licenses/LICENSE-2.0) [![npm trooth](https://img.shields.io/npm/v/trooth?label=npm%20trooth&color=D5C884)](https://www.npmjs.com/package/trooth) [![MCP registry](https://img.shields.io/badge/MCP%20registry-io.github.trooth--eng%2Ftrooth--network-1A73E8)](https://registry.modelcontextprotocol.io)

</div>

---

## What a record is

A company's record carries its identity, products, commercial terms, people, documents, security and privacy posture, AI practices, procurement terms and relationships. Every item says where it came from: witnessed by Trooth, taken from a public record, attested by a named counterparty, or declared by the company. Every witnessed item carries the date Trooth last read it.

Trooth witnesses and dates facts. It does not grade, rate or rank anyone, and it never adds what it read into one number.

## Why a company keeps one

**One link instead of a questionnaire.** A buyer reads the record instead of sending the same security questionnaire on every deal.

**Readable by people and by their AI assistants.** The record is public and needs no login, so a buyer, or the assistant a buyer asks, can read it directly.

**Declared and witnessed are kept apart.** What a company states is labeled declared. What Trooth observed is labeled witnessed. A buyer can see which is which.

**Read again on a schedule.** Live probes are re-read hourly, and each category of fact has a published freshness window. Every witnessed item shows the date it was last read, and one past its window is labeled stale, so a reader can see how old each fact is.

The record is free.

## Read any company's record, no login

From an AI assistant, add the read-only Trooth connector to Claude, ChatGPT or Cursor and ask in plain words. The endpoint needs no key and no account: `https://api.trooth.co/public/mcp`

From your terminal:

```bash
npx trooth check trooth.co
```

## What we publish in the open

The Trooth platform is proprietary. What we publish in the open is what a third party needs to read a company's record and connect Trooth to their own tools, and the steps for checking a Trooth signature. Every repository in the table below is Apache 2.0 except `trooth-mcp`, which is MIT.

| Repo | What it is |
| --- | --- |
| [**trooth-mcp**](https://github.com/troothllc/trooth-mcp) | The public, read-only MCP connector. Point Claude, ChatGPT or Cursor at `https://api.trooth.co/public/mcp` and read any company's record. |
| [**trooth-signatures**](https://github.com/troothllc/trooth-signatures) | Meant for a tool that checks a Trooth signature with a public key and nothing else from Trooth. It holds no code yet. The Ed25519 keys Trooth signs with are published at [/verify/keys](https://trooth.co/verify/keys) today. |
| [**trooth-openapi**](https://github.com/troothllc/trooth-openapi) | The OpenAPI 3.1 contracts for the public API, one for each of Trooth's two public hosts. |
| [**trooth-cli**](https://github.com/troothllc/trooth-cli) | `npx trooth check <domain>` reads any company's public record from your terminal; `trooth lint` reads what your own repository declares, locally. Two commands, no account, no key. Published on npm as `trooth`. |
| [**trooth-action**](https://github.com/troothllc/trooth-action) | GitHub Action wrapping the CLI. Advisory by default: it reports what your repository declares and does not fail your build unless you ask it to. |
| [**trooth-vscode**](https://github.com/troothllc/trooth-vscode) | VS Code and Cursor extension. Version 0.1.0 is a scaffold: its commands open trooth.co pages, including the Trust Center, in your browser. It reads no company record, checks no signature and makes no network request of its own. |
| [**trooth-checklists**](https://github.com/troothllc/trooth-checklists) | Checklists a company can work through against its own systems and publish the results of. Trooth does not run them for you and does not grade the output. |

## Security and contact

Trooth's own Trust Center is at [trooth.co/security](https://trooth.co/security): its security, privacy and AI governance, with the evidence for each control and the gaps named. See our [Vulnerability Disclosure Policy](https://trooth.co/security/vulnerability-disclosure-policy) and [/.well-known/security.txt](https://trooth.co/.well-known/security.txt).

General: hello@trooth.co · Security: security@trooth.co · Legal: legal@trooth.co · Privacy: privacy@trooth.co

<div align="center">

**Trooth signs what it witnessed. It never signs on a company's behalf.** Every item on the Network shows its source, and every witnessed item shows the date it was read. Nothing on the Network is an endorsement or a guarantee, including what Trooth says about itself.

// BUILT FOR YOU, NOT OFF YOU //

© 2026 Trooth, LLC · Miami, Florida

</div>

<div align="center">

<img src="https://trooth.co/brand/trooth-banner-1500x500.png" alt="Trooth: Machine-Readable Trust infrastructure for people and AI agents" width="820" />

### Machine-Readable Trust infrastructure for people and AI agents

Trooth is an infrastructure and cybersecurity company providing Machine-Readable Trust. Its one product is the Trooth Network: a public, signed, machine-readable record for each company. Find company disclosures and dated observations in one record. See what the company says, what Trooth observed, and where each item came from.

**[Claim your company's record](https://trooth.co/signup)** · **[How Trooth witnesses](https://trooth.co/methodology)** · **[Docs](https://trooth.co/docs)**

[![Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-0B0B0B)](https://www.apache.org/licenses/LICENSE-2.0) [![npm trooth](https://img.shields.io/npm/v/trooth?label=npm%20trooth&color=D5C884)](https://www.npmjs.com/package/trooth) [![MCP registry](https://img.shields.io/badge/MCP%20registry-io.github.trooth--eng%2Ftrooth--network-1A73E8)](https://registry.modelcontextprotocol.io)

</div>

---

## What a record is

A company's record carries its identity, products, commercial terms, people, documents, security and privacy posture, AI practices, procurement terms and relationships. Every item says where it came from: witnessed by Trooth, taken from a public record, attested by a named counterparty, or declared by the company. Every item carries the date it was last read.

Trooth witnesses and dates facts. It does not score, rate, rank or certify anyone, and it never adds what it read into one number.

## Why a company keeps one

**One link instead of a questionnaire.** A buyer reads the record instead of sending a 300-row spreadsheet every time.

**Readable by people and by their AI assistants.** The record is public and needs no login, so a buyer, or the assistant a buyer asks, can read it directly.

**Declared and witnessed are kept apart.** What a company states is labeled declared. What Trooth observed is labeled witnessed. A buyer can see which is which.

**Read again on a schedule.** Trooth re-reads what it witnessed on a fixed schedule, and every item shows the date it was last read, so a reader can see how old each fact is.

The record is free.

## Read any company's record, no login

From an AI assistant, add the read-only Trooth connector to Claude, ChatGPT or Cursor and ask in plain words. The endpoint needs no key and no account: `https://api.trooth.co/public/mcp`

From your terminal:

```bash
npx trooth check trooth.co
```

## What we publish in the open

The Trooth platform is proprietary. What we publish in the open is what a third party needs to read a company's record, check a Trooth signature, and connect Trooth to their own tools. Every public repository is Apache 2.0 except `trooth-mcp`, which is MIT.

| Repo | What it is |
| --- | --- |
| [**trooth-mcp**](https://github.com/troothllc/trooth-mcp) | The public, read-only MCP connector. Point Claude, ChatGPT or Cursor at `https://api.trooth.co/public/mcp` and read any company's record. |
| [**trust-verifier-sdk**](https://github.com/troothllc/trust-verifier-sdk) | Where an independent verifier will live. It holds no code yet. The Ed25519 keys Trooth signs with are published at [/verify/keys](https://trooth.co/verify/keys) today. |
| [**trooth-platform**](https://github.com/troothllc/trooth-platform) | The OpenAPI 3.1 description of the public API. |
| [**trooth-cli**](https://github.com/troothllc/trooth-cli) | `npx trooth check <domain>` reads any company's public record from your terminal; `trooth lint` reads what your own repository declares, locally. Two commands, no account, no key. Published on npm as `trooth`. |
| [**trooth-action**](https://github.com/troothllc/trooth-action) | GitHub Action wrapping the CLI. Advisory by default: it reports what your repository declares and does not fail your build unless you ask it to. |
| [**trooth-vscode**](https://github.com/troothllc/trooth-vscode) | VS Code and Cursor extension. Early: it opens the Trust Center and a record from the editor. It does not yet verify anything locally. |
| [**trooth-eval-harnesses**](https://github.com/troothllc/trooth-eval-harnesses) | Checklists a company can work through against its own systems and publish the results of. Trooth does not run them for you and does not grade the output. |

## Security and contact

Trooth's own record is witnessed the same way as every other company's on the Network, at [trooth.co/security](https://trooth.co/security). See our [Vulnerability Disclosure Policy](https://trooth.co/security/vulnerability-disclosure-policy) and [/.well-known/security.txt](https://trooth.co/.well-known/security.txt).

General: hello@trooth.co · Security: security@trooth.co · Legal: legal@trooth.co · Privacy: privacy@trooth.co

<div align="center">

**Trooth signs what it witnessed. It never signs on a company's behalf.** Every item on the Network shows its source and the date it was read. Nothing on the Network is certified or guaranteed, including what Trooth says about itself.

// BUILT FOR YOU, NOT OFF YOU //

© 2026 Trooth, LLC · Miami, Florida

</div>

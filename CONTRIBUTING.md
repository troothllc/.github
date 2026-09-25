# Contributing to Trooth

Thanks for helping. These rules are the same in every public Trooth repository, so that what happens to your pull request does not depend on which one you opened it in.

## What Trooth is, before you propose anything

Trooth operates the Trooth Network: one public, signed, machine-readable record per company, carrying its identity, products and demos, commercial terms, domain and marketing links, people, documents, security and privacy posture, AI practices, procurement terms and relationships. It is Trooth's only product and it is free.

DNS says where a company is. A TLS certificate says the connection is authentic. The Trooth Network says who the company is and what it does with your data.

**Trooth witnesses and dates facts. It does not grade, rate or rank anyone.** That is a product boundary, not a missing feature, and it decides the fate of a whole class of contribution before it is written. A change that adds a number summarizing a company, a grade, a ranking, a pass mark, a badge that means "approved", or a check of a company against a named standard or certification, will be declined however good the code is. Where two sources disagree, both are published and neither wins. Where a fact is unknown, it is reported unknown rather than filled in.

If you are unsure whether an idea sits inside that boundary, open an issue and ask first. It is a cheaper conversation before the code than after it.

## Before you open a pull request

Open an issue first for anything beyond a typo or a one-line fix. Substantial changes, and anything touching a public interface, need a short discussion before code, so that review does not come as a surprise. Typos, broken links and obvious documentation fixes: open the pull request directly.

## Commits

Sign your commits, with GPG, SSH or S/MIME, so GitHub shows the Verified badge. An unsigned commit will be sent back to be re-signed before it is merged.

Clear, imperative commit messages. One concern per pull request; small diffs are quicker to review.

## Running things locally

Each repository documents its own setup in its README, and the setup is not the same in all of them, because they are not all the same kind of thing.

- Some carry code and a test suite with CI on it. Clone, install, run the tests, and fix any failure before you push.
- Some carry no code at all. `trooth-mcp` is a license, a README and the manifest published to the MCP Registry; the server it describes runs elsewhere. `trooth-signatures` is a license, a README, a contributing guide and a security policy today. There is nothing to run in either, and a pull request against one of them is a documentation change.

Where a repository has a linter or a type checker, run both and leave them clean. The linter is the authority on formatting; we do not argue about it in review.

## What review looks for

- Tests for a behavior change, where there are tests to add to.
- No new dependency without a reason in the pull request description.
- Documentation updated where the public interface or the behavior changed.
- No secrets committed, ever.
- The surrounding style, matched.

## Public text is held to the same rules as code

Several of these repositories are mostly prose, and their prose is a published surface. A statement about what Trooth does should name where it came from and when it was read. Do not add an absolute (a percentage claim of perfect security, a promise of total accuracy), a certification presented as something Trooth performs, or a future-tense promise with a date in it. A sentence like that does not change when the calendar does, so it becomes false without anyone editing it.

## Security

Do not open a public issue for a vulnerability. Follow `SECURITY.md` and report privately to **security@trooth.co**, under the [Vulnerability Disclosure Policy](https://trooth.co/security/vulnerability-disclosure-policy).

## Code of Conduct

By participating you agree to `CODE_OF_CONDUCT.md`. Conduct reports go to **hello@trooth.co**.

## License

By contributing, you agree your contribution is licensed under the repository's own license. That is Apache License 2.0 in `trooth-action`, `trooth-checklists`, `trooth-cli`, `trooth-openapi`, `trooth-signatures` and `trooth-vscode`, and MIT in `trooth-mcp`. The `.github` repository, which holds these organization-wide files, carries no `LICENSE` file. Check the `LICENSE` in the repository you are opening the pull request against; it governs, and this sentence does not.

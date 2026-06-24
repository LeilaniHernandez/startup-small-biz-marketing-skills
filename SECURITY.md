# Security Policy

## Scope

This repository contains **standalone Markdown skill files** — structured instructions meant to be copied into an AI tool. There is no executable code, no dependencies, and no build pipeline, so the usual software risks (remote code execution, vulnerable packages, leaked runtime secrets) do not apply.

The relevant risk for this project is **content integrity**: the skills are designed to be copied and pasted into AI systems, so a maliciously modified file could embed instructions that cause an AI tool to behave unexpectedly. We treat the following as security issues:

- **Injected or hidden instructions** in a skill file intended to manipulate an AI tool's behavior (e.g., prompt injection, data-exfiltration prompts, hidden text).
- **Secrets or personal data** accidentally committed (API keys, credentials, private contact information).
- **Misleading guidance** that could plausibly cause real harm if followed (e.g., a skill that instructs users to disable safety controls or mishandle customer data).

Reports of typos, broken links, or general quality issues are welcome — but please open a normal [issue](../../issues) for those rather than using the security process below.

## Reporting a Vulnerability

**Please do not open a public issue for security concerns.** Public disclosure before a fix gives others a window to misuse it.

Instead, report privately using GitHub's built-in private vulnerability reporting:

1. Go to the **Security** tab of this repository.
2. Click **Report a vulnerability**.
3. Describe the issue, the affected file(s), and steps to reproduce.



## What to Expect

This is a small, individually maintained project, so timelines are best-effort:

- **Acknowledgment** of your report within **5 business days**.
- An assessment of whether it's in scope and, if so, a planned fix.
- Credit for the report if you'd like it (optional).

Because all content is plain Markdown, remediation is usually a single commit removing or correcting the affected file.

## Supported Versions

Only the latest commit on the `main` branch is maintained. Forks and older copies are the responsibility of whoever holds them.

# Security Policy

## Supported version

Security fixes are applied to the latest version on the default branch.

## Reporting a vulnerability

Please do not publish exploitable details in a public issue. Contact the maintainer through the private security-reporting option on GitHub when available. Include:

- Affected feature and browser
- Reproduction steps
- Potential impact
- Suggested mitigation, if known

Never include real API keys, access tokens, private song files, or personal data in a report.

## Current security model

The core application is a static local-first HTML file. It does not send network requests, execute uploaded code, or require credentials. Imported JSON is treated as untrusted data and rendered as text.

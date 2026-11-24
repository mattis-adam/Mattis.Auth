# Security Policy

## Supported versions

Mattis.Auth is in early development. Only the latest commit on `main` receives security fixes. No release is supported for production use yet.

| Version | Supported |
|---|---|
| `main` | ✅ |
| Any other branch or tag | ❌ |

## Reporting a vulnerability

**Do not open a public issue, discussion or pull request for a security problem.**

Report it privately through GitHub:
**Security** tab → **Report a vulnerability** ([GitHub Private Vulnerability Reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)).

Please include:

- A description of the issue and its impact
- Steps to reproduce, or a proof of concept
- Affected commit or version
- Any suggested fix (optional)

## What to expect

This is a personal project maintained on a best-effort basis.

- **Acknowledgement**: within 7 days
- **Initial assessment**: within 14 days
- **Fix**: as soon as reasonably possible, depending on severity

You will be kept informed of progress. With your permission, you will be credited in the advisory once the issue is fixed.

## Scope

In scope:

- The `Mattis.Auth` package (authentication, tokens, password handling, configuration validation)
- The CI/CD workflows in this repository

Out of scope:

- The sample API when deployed with non-default or insecure configuration
- Vulnerabilities in third-party dependencies (please report them upstream; you may notify us as well)
- Denial of service through targeted account lockout (known and accepted in v1, mitigated by per-IP rate limiting)
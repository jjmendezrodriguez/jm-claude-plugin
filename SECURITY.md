# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.x     | ✅        |

## Reporting a Vulnerability

If you find a security issue, **do not open a public issue**.

Email: josejmendezrodriguez@gmail.com

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact

Expected response time: 48 hours.

## Scope

This plugin contains Claude Code skill definitions (Markdown files). It does not execute code directly. However, skills can influence Claude Code behavior, so prompt injection or unsafe instructions in skill files are considered security issues.

## Dependencies

- `ecc-agentshield` (optional, for security-scan skill) — maintained by [affaan-m](https://github.com/affaan-m/agentshield)

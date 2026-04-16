# jm-claude-plugin

Custom Claude Code plugin with cherry-picked skills and agents.

## Contents

### Skills
- **security-scan** — Scan `.claude/` config for vulnerabilities using AgentShield
- **e2e-testing** — Playwright E2E testing patterns, POM, CI/CD integration

### Agents
- **python-reviewer** — Python code reviewer (PEP 8, type hints, security, performance)

## Install

```bash
# Add marketplace
/plugin marketplace add https://github.com/jjmendezrodriguez/jm-claude-plugin

# Install
/install-plugin jm-claude-plugin@jm-claude-plugin
```

## Dependencies

- `ecc-agentshield` (for security-scan): `npm install -g ecc-agentshield`

## Credits

Skills sourced from [Everything Claude Code](https://github.com/affaan-m/everything-claude-code) (MIT license).

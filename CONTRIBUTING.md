# Contributing

## Adding a New Skill

1. Create `skills/<skill-name>/SKILL.md`
2. Use YAML frontmatter:
   ```yaml
   ---
   name: skill-name
   description: What it does
   origin: source (ECC, custom, etc.)
   ---
   ```
3. Test locally before submitting PR

## Pull Requests

- One skill per PR
- Include source attribution if cherry-picked from another project
- All files in English
- Test that the plugin installs cleanly: `claude plugins install jm-claude-plugin@jm-claude-plugin`

## Code of Conduct

Be respectful. Focus on technical merit.

## License

By contributing, you agree your contributions are licensed under MIT.

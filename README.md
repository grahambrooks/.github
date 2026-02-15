# .github

Organization-wide shared repository for GitHub configurations and Copilot Agent Skills.

## Overview

This is a special `.github` repository that provides shared resources across all repositories in the `grahambrooks` organization. It includes:

- **Shared Skills**: Reusable GitHub Copilot Agent Skills available to all repositories
- **Community Health Files**: Organization-wide templates and guidelines (future)
- **Workflow Templates**: Reusable GitHub Actions workflows (future)

## Shared Skills

The `skills/` directory contains Agent Skills that are automatically available to GitHub Copilot agents when working in any repository within this organization.

### Available Skills

1. **code-review** - Comprehensive code review guidelines focusing on quality, security, and best practices
2. **testing-best-practices** - Standards for writing effective tests with proper coverage
3. **documentation-standards** - Guidelines for creating clear, comprehensive technical documentation

### Using Skills

Skills in this repository are automatically loaded by GitHub Copilot agents when relevant to the current task. No additional configuration is needed in individual repositories.

### Adding New Skills

To add a new skill:

1. Create a new directory under `skills/` with a descriptive name (use lowercase and hyphens)
2. Add a `SKILL.md` file in that directory with:
   - YAML frontmatter containing `name`, `description`, and `license`
   - Instructions and guidelines for the skill
3. Optionally include supporting files (scripts, examples, etc.)

Example structure:
```
skills/
  my-new-skill/
    SKILL.md
    (optional supporting files)
```

## Resources

- [GitHub Docs: About Agent Skills](https://docs.github.com/en/copilot/concepts/agents/about-agent-skills)
- [VS Code: Use Agent Skills](https://code.visualstudio.com/docs/copilot/customization/agent-skills)
- [GitHub Skills Community](https://github.com/github/awesome-copilot)

## License

MIT License - See individual skill files for specific licensing information.
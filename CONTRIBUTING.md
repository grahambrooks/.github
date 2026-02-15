# Contributing to Shared Skills

Thank you for your interest in contributing to our shared skills repository! This guide will help you add new skills or improve existing ones.

## How to Contribute

### Adding a New Skill

1. **Create a skill directory**
   - Navigate to the `skills/` directory
   - Create a new folder with a descriptive name (use lowercase and hyphens)
   - Example: `skills/security-review`

2. **Create the SKILL.md file**
   - Every skill must have a `SKILL.md` file in its directory
   - Include YAML frontmatter with required fields:
     ```yaml
     ---
     name: your-skill-name
     description: A brief description of what this skill does
     license: MIT
     ---
     ```
   - Follow with markdown content containing instructions and guidelines

3. **Write clear instructions**
   - Be specific and actionable
   - Include examples where helpful
   - Organize with clear headings and lists
   - Consider the skill's audience

4. **Test your skill**
   - Verify the YAML frontmatter is valid
   - Check that instructions are clear and complete
   - Test with GitHub Copilot if possible

### Improving Existing Skills

- Submit issues for suggestions or improvements
- Open pull requests with clear descriptions of changes
- Ensure changes maintain backward compatibility
- Update documentation to reflect changes

## Skill Best Practices

- **Focus**: Each skill should have a single, clear purpose
- **Clarity**: Instructions should be unambiguous and easy to follow
- **Completeness**: Include all necessary information
- **Maintainability**: Keep skills up-to-date with current practices
- **Licensing**: Ensure all content is appropriately licensed

## Review Process

1. Submit a pull request with your changes
2. Provide a clear description of the skill or changes
3. Address any feedback from reviewers
4. Once approved, changes will be merged

## Questions?

If you have questions or need help, please:
- Open an issue for discussion
- Reach out to repository maintainers

Thank you for helping improve our shared skills!

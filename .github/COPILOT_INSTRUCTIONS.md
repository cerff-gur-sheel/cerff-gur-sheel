# Copilot Instructions

This file provides custom instructions to GitHub Copilot for working with repositories owned by @cerff-gur-sheel.

## General Guidelines

### Code Style & Standards
- Write clean, readable, and maintainable code
- Follow language-specific best practices and conventions
- Include meaningful comments for complex logic
- Use descriptive variable and function names
- Prefer composition over inheritance where appropriate

### Documentation
- Provide clear and concise documentation for all public APIs
- Include usage examples in README files
- Document complex algorithms and business logic
- Keep documentation up-to-date with code changes

### Testing
- Write unit tests for new features and bug fixes
- Aim for good test coverage of critical paths
- Include both positive and negative test cases
- Use descriptive test names that explain what is being tested

### Security & Best Practices
- Never commit sensitive information (API keys, passwords, tokens)
- Use environment variables for configuration
- Validate and sanitize all user inputs
- Follow the principle of least privilege
- Keep dependencies up-to-date

### Git Workflow
- Write clear, descriptive commit messages
- Use conventional commit format when possible (feat:, fix:, docs:, etc.)
- Keep commits atomic and focused
- Create feature branches for new work

## Language-Specific Preferences

### JavaScript/TypeScript
- Use modern ES6+ syntax
- Prefer `const` and `let` over `var`
- Use async/await over raw promises when possible
- Use TypeScript for type safety in larger projects

### Python
- Follow PEP 8 style guide
- Use type hints for function signatures
- Prefer list comprehensions for simple iterations
- Use virtual environments for dependency management

### General Purpose
- Optimize for readability first, performance second
- Avoid premature optimization
- Refactor code that becomes complex or hard to understand

## Project Structure
- Keep related files organized in appropriate directories
- Use meaningful directory names
- Include a comprehensive README.md in each project
- Maintain a CHANGELOG.md for tracking changes

## When Helping
- Explain your reasoning when suggesting changes
- Provide multiple options when there are different approaches
- Point out potential issues or edge cases
- Suggest improvements to existing code when relevant

---

**Note:** These instructions can be customized per repository by creating a `COPILOT_INSTRUCTIONS.md` file in the `.github` directory of any specific repository.
# Contributing to Swuabs Organization

Thank you for contributing to our projects! This guide will help you get started.

## Getting Started

1. **Accept your team invitation** and join the organization
2. **Set up 2FA** on your GitHub account (recommended)
3. **Clone the repository** you'll be working on
4. **Read the project README** to understand setup requirements

## Team Structure

| Role | Permissions | Responsibilities |
|------|-------------|------------------|
| **Founder** | Admin | Organization oversight, final decisions |
| **CHRO** | Admin | HR management, team coordination |
| **CLO** | Admin | Logistics, project management |
| **Developer** | Admin | Code development, technical decisions |
| **Admin** | Admin | General administration |
| **Manager** | Maintain | Repository management, PR reviews |
| **Moderator** | Write | Issue management, community support |

## Development Workflow

### 1. Creating Issues

- Use the appropriate issue template (Bug Report, Feature Request, or General)
- Fill out all required fields
- Add relevant labels (bug, enhancement, priority levels)
- Assign to yourself if you plan to work on it

### 2. Working on Code

```bash
# Create a new branch for your work
git checkout -b feature/your-feature-name

# Make your changes
# ... code ...

# Commit with descriptive messages
git commit -m "Add feature: description of what you did"

# Push to the repository
git push origin feature/your-feature-name
```

### 3. Creating Pull Requests

- Use the PR template that appears automatically
- Fill out the complete checklist
- Link related issues using "Closes #issue-number"
- Request reviews (CODEOWNERS will auto-assign appropriate reviewers)
- Ensure all checks pass
- Get at least 1 approval before merging

### 4. Code Review

- Be constructive and respectful in reviews
- Explain the "why" behind suggestions
- Approve PRs only when you've thoroughly reviewed the code
- Address all feedback before requesting re-review

### 5. Merging

- **Squash and merge** (recommended) - Creates clean history
- **Merge commit** - Preserves all commits if needed
- Branches auto-delete after merge

## Code Standards

### General Guidelines

- Write clear, self-documenting code
- Add comments for complex logic
- Follow the existing code style in each project
- Keep functions small and focused
- Use meaningful variable and function names

### Project-Specific Standards

#### SAI (Electron/JavaScript)
- Use ES6+ features
- Follow async/await patterns
- Test UI changes across platforms

#### SwuabsOptimizations (TypeScript/Monorepo)
- Strict TypeScript types
- Run `pnpm db:generate` after schema changes
- Test changes locally before pushing

#### ProxyV4 (Python)
- Follow PEP 8 style guide
- Use type hints where applicable
- Test with actual Minecraft connections

### Testing

- Test your changes locally before creating a PR
- Add tests for new features
- Ensure existing tests still pass
- Document test procedures in PR

## Security

- **NEVER** commit sensitive data (API keys, passwords, tokens, .env files)
- Use environment variables for configuration
- Review the [SECURITY.md](SECURITY.md) policy
- Report security issues privately to swuabsoptimizations@gmail.com

## Communication

- **GitHub Issues** - Bug reports, feature requests, technical discussions
- **GitHub Discussions** - General conversations, questions, announcements
- **Pull Request Comments** - Code-specific discussions
- **Discord** - Real-time chat (for non-code topics)

## Questions?

If you have questions about contributing:
- Check project README files
- Ask in GitHub Discussions
- Reach out to your team lead
- Contact swuabsoptimizations@gmail.com

## Recognition

We value all contributions! Contributors will be:
- Listed in project contributors
- Credited in release notes
- Recognized in team discussions

Thank you for being part of Swuabs Organization!

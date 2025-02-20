# Contributing to Roadster

Welcome to the Roadster community! We're excited that you're interested in contributing. This guide will help you get started, whether you're fixing bugs, proposing features, or improving documentation.

## Getting Started

Before contributing, please familiarize yourself with:
- Basic [Git](https://git-scm.com/) workflows if you're new to open source
- Our [issue tracker](https://github.com/mansoorbarri/roadster/issues) for bug reports and feature requests
- The contribution guidelines below

## Creating Issues

We use issues to track bugs and feature requests. Here's how you can help us process them efficiently:

### General Guidelines

- Write issues in English
- Create separate issues for different problems or features
- Include clear titles and helpful descriptions
- Search existing issues first to avoid duplicates
- Use [GitHub's reactions](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments) to show support for ideas instead of "+1" comments

### Bug Reports

When reporting a bug, please include:

```markdown
**Hugo version**
[Output of `hugo version`]

**Theme status**
Is the theme up to date? Yes/No

**Expected behavior**
[What you expected to happen]

**Current behavior**
[What actually happened, including screenshots if relevant]

**Steps to reproduce**
[Clear steps to trigger the bug, or a link to a demo project]

**Additional context**
[Any relevant environment details or deployment information]
```

**Note:** If you find a closed issue similar to your bug, please open a new issue and reference the original one.

### Feature Requests

When proposing new features:
- Explain the feature's purpose and benefits
- Describe how it would work
- Consider including mockups or examples
- Be open to discussion and feedback

## Making Pull Requests

We love receiving contributions! To ensure a smooth process:

### Before You Start

1. **Ask First**: For significant changes (new features, refactoring), please open an issue to discuss your ideas first
2. **Prerequisites**:
   - Hugo v0.128.0+
   - Basic Git knowledge

### Best Practices

1. **Keep Changes Focused**
   - One PR per feature/fix
   - Make changes as small and focused as possible
   - Submit separate PRs for formatting/style changes

2. **Branch Management**
   - Create a descriptive branch name (not "patch-1" or "update")
   - Work from a feature branch, not master
   - Keep your branch up to date with master

3. **Quality Standards**
   - Include clear PR titles and descriptions
   - Add screenshots for UI changes
   - Ensure CI checks pass
   - Write meaningful commit messages
   - Update documentation if needed
   - For SVG changes:
     - Keep files under 2048 bytes
     - Minify to a single line
     - Ensure GPLv2 License compatibility

### Submission Process

1. Fork the repository
2. Clone your fork locally
3. Create a new feature branch
4. Make your changes
5. Push to your fork
6. Submit a Pull Request

We'll review your PR and might request changes. Please be responsive to feedback - PRs without activity for 2-4 weeks may be closed.

## Licensing

By contributing to Roadster, you agree that your contributions will be licensed under the [GPLv2 License](LICENSE.md).

---

Thank you for contributing to Roadster! Your efforts help make this project better for everyone. While we can't guarantee all contributions will be merged, we appreciate your time and effort.
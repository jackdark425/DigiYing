<div align="center">
<sub>

<b>English</b> • [Català](locales/ca/CONTRIBUTING.md) • [Deutsch](locales/de/CONTRIBUTING.md) • [Español](locales/es/CONTRIBUTING.md) • [Français](locales/fr/CONTRIBUTING.md) • [हिंदी](locales/hi/CONTRIBUTING.md) • [Bahasa Indonesia](locales/id/CONTRIBUTING.md) • [Italiano](locales/it/CONTRIBUTING.md) • [日本語](locales/ja/CONTRIBUTING.md)

</sub>
<sub>

[한국어](locales/ko/CONTRIBUTING.md) • [Nederlands](locales/nl/CONTRIBUTING.md) • [Polski](locales/pl/CONTRIBUTING.md) • [Português (BR)](locales/pt-BR/CONTRIBUTING.md) • [Русский](locales/ru/CONTRIBUTING.md) • [Türkçe](locales/tr/CONTRIBUTING.md) • [Tiếng Việt](locales/vi/CONTRIBUTING.md) • [简体中文](locales/zh-CN/CONTRIBUTING.md) • [繁體中文](locales/zh-TW/CONTRIBUTING.md)

</sub>
</div>

# Contributing to Roo Code

This is a fork project, and we welcome all contributions. You can contribute through direct commits or Pull Requests. Please review this guide carefully.

## Table of Contents

- [Before You Contribute](#before-you-contribute)
- [Finding & Planning Your Contribution](#finding--planning-your-contribution)
- [Development & Submission Process](#development--submission-process)
- [Legal](#legal)

## Before You Contribute

### 1. Code of Conduct

All contributors must adhere to our [Code of Conduct](./CODE_OF_CONDUCT.md).

### 2. Project Roadmap

Our roadmap guides the project's direction. Align your contributions with these key goals:

### Reliability First

- Ensure diff editing and command execution are consistently reliable.
- Reduce friction points that deter regular usage.
- Guarantee smooth operation across all locales and platforms.
- Expand robust support for a wide variety of AI providers and models.

### Enhanced User Experience

- Streamline the UI/UX for clarity and intuitiveness.
- Continuously improve the workflow to meet the high expectations developers have for daily-use tools.

### Leading on Agent Performance

- Establish comprehensive evaluation benchmarks (evals) to measure real-world productivity.
- Make it easy for everyone to easily run and interpret these evals.
- Ship improvements that demonstrate clear increases in eval scores.

Mention alignment with these areas in your PRs.

### 3. Join the Roo Code Community

- **Primary:** Join our [Discord](https://discord.gg/roocode) and DM **Hannes Rudolph (`hrudolph`)**.
- **Alternative:** Experienced contributors can engage directly via [GitHub Projects](https://github.com/orgs/RooCodeInc/projects/1).

## Finding & Planning Your Contribution

### Types of Contributions

- **Bug Fixes:** Addressing code issues.
- **New Features:** Adding functionality.
- **Documentation:** Improving guides and clarity.

### Contribution Approaches

You can contribute in the following ways:

- **Direct Commits**: Push changes directly to the main branch for quick fixes and improvements.
- **Pull Requests**: Create PRs for larger changes or when you want feedback.
- **Issues**: Optionally create issues to track bugs or feature requests.

**All contribution methods are welcome.**

### Deciding What to Work On

- Check the [GitHub Project](https://github.com/orgs/RooCodeInc/projects/1) for unassigned "Good First Issues."
- For docs, visit [Roo Code Docs](https://github.com/RooCodeInc/Roo-Code-Docs).

### Reporting Bugs

- Check for existing reports first.
- Create new bugs using the ["Bug Report" template](https://github.com/RooCodeInc/Roo-Code/issues/new/choose).
- **Security issues**: Report privately via [security advisories](https://github.com/RooCodeInc/Roo-Code/security/advisories/new).

## Development & Submission Process

### Development Setup

1. **Fork & Clone:**

```
git clone https://github.com/YOUR_USERNAME/Roo-Code.git
```

2. **Install Dependencies:**

```
pnpm install
```

3. **Debugging:** Open with VS Code (`F5`).

### Writing Code Guidelines

- One focused PR per feature or fix.
- Follow ESLint and TypeScript best practices.
- Write clear, descriptive commits referencing issues (e.g., `Fixes #123`).
- Provide thorough testing (`npm test`).
- Rebase onto the latest `main` branch before submission.

### Submitting a Pull Request

- Begin as a **Draft PR** if seeking early feedback.
- Clearly describe your changes following the Pull Request Template.
- Provide screenshots/videos for UI changes.
- Indicate if documentation updates are necessary.

### Pull Request Guidelines

- PRs should ideally pass CI tests when available.
- Clear documentation of changes is recommended.
- For larger changes, consider creating a draft PR for early feedback.

### Review Process

- For Pull Requests: Review by maintainers when available.
- For direct commits: Self-review and testing recommended.
- Feedback and iterations are welcome.

## Legal

By contributing, you agree your contributions will be licensed under the Apache 2.0 License, consistent with Roo Code's licensing.

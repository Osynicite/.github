# .github

[English](./README.md) | [Русский](./README_RU.md) | [日本語](./README_JP.md) | [中文](./README_ZH.md)

This repository contains organization-wide configurations and templates for Osynicite - an open-source team developing tools for osu!, including beatmap synchronization, MIDI keyboard mapping, and skin editing utilities.

## 📂 Repository Structure
```plaintext
.github/
├── actions/                # Custom Actions
│   ├── rust-bench/        # Rust benchmarking
│   ├── rust-doc/          # Rust documentation generation
│   ├── rust-lint/         # Rust code linting
│   ├── rust-setup/        # Rust environment setup
│   └── rust-test/         # Rust test runner
├── ISSUE_TEMPLATE/        # Issue templates
│   ├── bug_report.md      # Bug report template
│   ├── config.yml         # Issue configuration
│   └── feature_request.md # Feature request template
├── PULL_REQUEST_TEMPLATE/ # PR templates
│   └── pull_request.md    # PR template
├── profile/              # Organization profile
│   └── README.md         # Public organization profile
├── SECURITY/             # Security policies
│   ├── policy.md         # Security policy (English)
│   ├── policy-cn.md      # Security policy (Chinese)
│   └── policy-ru.md      # Security policy (Russian)
├── workflow-templates/   # Workflow templates
│   ├── rust-project.properties.json
│   └── rust-project.yml
└── workflows/           # Organization workflows
    ├── benchmark.yml    # Benchmarking
    ├── ci.yml          # Continuous Integration
    └── release.yml     # Release process
```

## 🔍 What's Inside
### Community Health Files
Default files used across all repositories in the organization:
- Contributing Guidelines (Multiple languages)
- Code of Conduct (Multiple languages)
- Workflows
- Funding Configuration
- Code Owners

### Workflow Templates
Ready-to-use GitHub Actions workflows for Rust projects:
- Continuous Integration
- Benchmark Testing
- Release Process

### Custom Actions
Reusable actions for common tasks:
- Rust Environment Setup
  ```yaml
  - uses: ./.github/actions/rust-setup
  ```
- Code Linting
  ```yaml
  - uses: ./.github/actions/rust-lint
  ```
- Test Running
  ```yaml
  - uses: ./.github/actions/rust-test
  ```
- Documentation Generation
  ```yaml
  - uses: ./.github/actions/rust-doc
  ```
- Benchmarking
  ```yaml
  - uses: ./.github/actions/rust-bench
  ```

## 🛠️ Usage
### For Repository Maintainers
1. When creating new workflows, check the workflow templates in Actions tab
2. Reference custom actions in your workflows using the examples above
3. Follow the contributing guidelines for consistency
4. Help us improve these configurations by opening issues or PRs

### For Contributors
1. Read through CONTRIBUTING.md before making contributions
2. Use provided issue and PR templates
3. Check workflow templates when setting up new projects
4. Ensure all code follows Rust best practices

## 📝 Notes
- These configurations serve as defaults and can be overridden by individual repositories
- Workflow templates are available in the "Actions" tab when creating new workflows
- Custom actions can be referenced from any repository in the organization
- All documentation is available in multiple languages

## 🔄 Maintenance
This repository is maintained by the Osynicite team. If you have suggestions for improvements:
1. Open an issue to discuss the proposed changes
2. Submit a PR with updates
3. Ensure documentation is updated in all languages
4. Update relevant templates if needed

## 📮 Contact
- [Team Discussions](https://github.com/orgs/Osynicite/discussions)
- Discord: [Join our Discord](https://discord.gg/osynicite)
- Email: [contact@osynicite.org](mailto:contact@osynicite.org)

## 📄 License
This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
# Universal Dev Productivity Pack (Stable, Stack-Agnostic)

[![GitHub package.json version](https://img.shields.io/github/package-json/v/ManuelGil/vscode-universal-productivity-pack?style=for-the-badge&logo=github)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-universal-productivity-pack)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-universal-productivity-pack?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-universal-productivity-pack)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-universal-productivity-pack?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-universal-productivity-pack/blob/main/LICENSE)

A lightweight, stack-agnostic Visual Studio Code extension pack focused on productivity, code quality, debugging workflows, development context, structured data visualization, AI-assisted development, and team collaboration.

Designed for developers and teams who want a clean, stable, and maintainable VS Code setup without unnecessary complexity.

## Why This Pack Exists

Most VS Code extension packs are built around:

- specific languages
- framework ecosystems
- large collections of loosely related tools

This pack takes a different approach.

It provides a carefully selected set of widely adopted extensions that improve everyday development workflows across any technology stack while keeping the environment lightweight, maintainable, and focused.

Beyond productivity tooling, this pack also improves:

- debugging workflows
- contextual understanding of codebases
- visibility into structured data
- collaboration and code quality practices

## Core Principles

- Stack agnostic
- Minimal and focused
- Stable over time
- Low maintenance
- Team-friendly
- No redundant tooling

This pack intentionally avoids:

- framework-specific dependencies
- duplicate functionality
- opinionated UI customizations
- heavy or experimental extensions

## Included Extensions

| Category            | Extension            | Purpose                                                                                            |
| ------------------- | -------------------- | -------------------------------------------------------------------------------------------------- |
| Git & Productivity  | GitLens              | Advanced Git insights, annotations, and history                                                    |
| Git & Productivity  | Error Lens           | Inline visibility for errors and warnings                                                          |
| Debugging           | CodeLog+             | Streamlines debugging by automating console log insertion and management across languages          |
| Knowledge & Context | CodeContext+         | Connects documentation and code references to navigate development context directly from your code |
| Data Visualization  | JSON Flow            | Interactive graph explorer for JSON, YAML, XML, CSV, and other structured data formats             |
| Code Consistency    | EditorConfig         | Standardized editor behavior across teams                                                          |
| Collaboration       | GitHub Pull Requests | Review and manage pull requests inside VS Code                                                     |
| AI Assistance       | GitHub Copilot       | Context-aware AI code suggestions                                                                  |
| AI Assistance       | GitHub Copilot Chat  | Interactive AI coding assistance                                                                   |
| AI Assistance       | IntelliCode          | AI-assisted IntelliSense improvements                                                              |
| Code Quality        | SonarLint            | Real-time bug and code smell detection                                                             |
| Code Quality        | Code Spell Checker   | Improves naming and documentation consistency                                                      |

## What Makes This Pack Different

Unlike large extension bundles, this pack focuses on a small number of high-value tools that work well together.

It is designed to provide:

- a professional baseline development environment
- better onboarding consistency for teams
- improved debugging and development workflows
- better visibility into code structure and data
- AI-assisted productivity without excessive tooling
- long-term maintainability with minimal overhead

No themes, visual packs, or framework-specific assumptions included.

## Who Is This For

This pack is ideal for:

- Full-stack developers
- Multi-stack engineering teams
- Consultants working across multiple technologies
- Developers working with large or evolving codebases
- Organizations standardizing VS Code environments
- Teams that value stability over constantly changing tooling
- Developers who prefer clean and focused editor setups

## Lightweight and Maintainable

This extension pack is intentionally small.

Each extension was selected based on:

- ecosystem maturity
- long-term maintenance quality
- practical day-to-day value
- low overlap with other tools
- cross-stack compatibility

The goal is to provide a setup that remains useful over time without requiring constant changes or maintenance.

## What This Pack Intentionally Excludes

Some commonly used extensions are intentionally not included.

Project-specific tooling such as:

- Prettier
- ESLint
- language servers
- framework tooling

should be configured according to the needs of each project or team.

This keeps the pack flexible and avoids imposing unnecessary opinions across different stacks and workflows.

## Optional Additions

You can extend this pack depending on your workflow and technology stack.

### Language-Specific Tooling

- JavaScript / TypeScript
- Python
- Java
- Go
- Rust
- C#

### DevOps and Infrastructure

- Docker
- Kubernetes
- Terraform

### API and Testing Tools

- REST clients
- GraphQL tooling
- Test runners

## Installation

### From the VS Code Marketplace

1. Open the Extensions view in VS Code
2. Search for:

    ```text
    <vscode-universal-productivity-pack>
    ```

3. Click **Install**

### Command Line

```bash
code --install-extension <imgildev>.<vscode-universal-productivity-pack>
```

## Recommended Usage

This pack works best as:

- a baseline development environment
- a starting point for onboarding
- a foundation for multi-language workflows
- a clean setup for AI-assisted development
- a productivity-focused environment for modern software teams

## Contributing

Contributions to the Universal Dev Productivity Pack are welcome and appreciated. To contribute:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-universal-productivity-pack).
2. Create a new branch for your feature or fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request targeting the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-universal-productivity-pack/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. If you encounter a bug or wish to request a new feature, please open an Issue.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-universal-productivity-pack/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

For a complete list of contributors, please refer to the [contributors](https://github.com/ManuelGil/vscode-universal-productivity-pack/contributors) page.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-universal-productivity-pack/blob/main/LICENSE) file for full details.

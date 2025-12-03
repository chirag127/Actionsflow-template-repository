# Contributing to ActionsFlow-Event-Driven-Automation-GitHub-Template

We welcome and appreciate your contributions to this repository! By contributing, you help us maintain a robust, zero-defect, and future-proof template for event-driven automation with Actionsflow and GitHub Actions. Please take a moment to review this document to understand our contribution guidelines.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Our Guiding Principles](#our-guiding-principles)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
  - [Setting Up Your Development Environment](#setting-up-your-development-environment)
- [Making Changes](#making-changes)
  - [Branching Strategy](#branching-strategy)
  - [Commit Messages](#commit-messages)
  - [Testing](#testing)
  - [Style Guidelines](#style-guidelines)
- [Submitting Your Contribution](#submitting-your-contribution)
  - [Issue Reporting](#issue-reporting)
  - [Pull Request Guidelines](#pull-request-guidelines)
- [Security Vulnerabilities](#security-vulnerabilities)
- [License](#license)

## Code of Conduct

This project adheres to a [Code of Conduct](https://github.com/chirag127/ActionsFlow-Event-Driven-Automation-GitHub-Template/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [chirag.s.patel.dev@gmail.com](mailto:chirag.s.patel.dev@gmail.com).

## Our Guiding Principles

As outlined in our [Agent Directives (AGENTS.md)](https://github.com/chirag127/ActionsFlow-Event-Driven-Automation-GitHub-Template/blob/main/AGENTS.md), we operate with absolute precision and uphold the following:

*   **Zero-Defect:** Strive for perfection in every commit, workflow, and action.
*   **High-Velocity:** Deliver impactful changes efficiently without compromising quality.
*   **Future-Proof:** Design with scalability, maintainability, and adaptability in mind.
*   **SOLID Principles:** Apply Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion where applicable in our modular designs.
*   **DRY (Don't Repeat Yourself):** Avoid redundant configurations and logic.
*   **YAGNI (You Ain't Gonna Need It):** Implement only features that are immediately necessary.

## How Can I Contribute?

There are many ways to contribute:

*   **Documentation:** Improve our `README.md`, comments, or any accompanying documentation.
*   **Bug Reports:** Identify and report issues to make the template more stable.
*   **Feature Requests:** Suggest new automations, integrations, or improvements.
*   **Code Contributions:** Fix bugs, add new Actionsflow sources/triggers, or enhance existing workflows.
*   **Refactoring:** Improve code clarity, performance, and adherence to best practices.

## Getting Started

### Setting Up Your Development Environment

This template primarily involves YAML-based workflow definitions and potentially JavaScript/TypeScript for custom Actionsflow components or GitHub Actions. No complex local environment setup is strictly required for *modifying* the YAML, but for local testing of Actionsflow or custom actions, you might need specific tools.

1.  **Fork the Repository:** Click the 'Fork' button at the top right of the [repository page](https://github.com/chirag127/ActionsFlow-Event-Driven-Automation-GitHub-Template).
2.  **Clone Your Fork:**
    bash
    git clone https://github.com/<YOUR_USERNAME>/ActionsFlow-Event-Driven-Automation-GitHub-Template.git
    cd ActionsFlow-Event-Driven-Automation-GitHub-Template
    
3.  **Install Actionsflow (Optional, for local testing):**
    If you plan to test Actionsflow workflows locally, install it globally:
    bash
    npm install -g @actionsflow/cli
    
    Refer to the [Actionsflow documentation](https://actionsflow.github.io/actionsflow/) for detailed setup and local execution instructions.
4.  **Install Node.js/npm (If contributing to JavaScript/TypeScript Actions/Components):**
    Ensure you have Node.js (LTS version) and npm installed if you intend to work on custom JavaScript or TypeScript-based GitHub Actions or Actionsflow sources. We recommend using `nvm` (Node Version Manager).

## Making Changes

### Branching Strategy

We use a `main` branch for stable releases. All new features and bug fixes should be developed in dedicated topic branches.

*   **Feature Branches:** `feature/<descriptive-name>`
*   **Bugfix Branches:** `bugfix/<descriptive-name>`
*   **Documentation Branches:** `docs/<descriptive-name>`

### Commit Messages

We adhere to the [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/). This helps us generate release notes and understand the purpose of each commit.

**Format:**


<type>(<scope>): <short description>

[optional body]
[optional footer(s)]


**Examples:**

*   `feat(workflow): Add new daily summary workflow`
*   `fix(ci): Resolve failing build on main branch`
*   `docs(readme): Update contribution guidelines`
*   `chore(deps): Bump actionsflow to v1.2.3`

### Testing

All contributions should include appropriate testing. For Actionsflow and GitHub Actions, this often means:

*   **Manual Verification:** Run the workflow against test data or in a dedicated test repository.
*   **Automated Tests:** For custom JavaScript/TypeScript components, include unit tests using `Vitest` or similar frameworks.
*   **Linting:** Ensure all YAML, Markdown, and JavaScript/TypeScript files adhere to formatting and style standards (e.g., `prettier`, `eslint`, YAML linters).

Before submitting, ensure your changes pass all local linting and any relevant tests.

### Style Guidelines

*   **YAML:** Follow a consistent indentation (2 spaces), logical grouping of properties, and clear, concise naming for all workflow elements.
*   **JavaScript/TypeScript:** Adhere to the `Biome` standards for linting and formatting. Ensure strict type checking is enabled and all types are correctly defined.
*   **Markdown:** Use clear headings, bullet points, and code blocks for readability. Ensure all documentation is accurate and up-to-date.

## Submitting Your Contribution

### Issue Reporting

*   Before opening a new issue, please search existing issues to see if it has already been reported.
*   For bug reports, use our [Bug Report Template](https://github.com/chirag127/ActionsFlow-Event-Driven-Automation-GitHub-Template/blob/main/.github/ISSUE_TEMPLATE/bug_report.md) and provide as much detail as possible.
*   For feature requests or enhancements, provide a clear description of the desired functionality and its potential benefits.

### Pull Request Guidelines

1.  **Open an Issue:** It's often helpful to open an issue first to discuss the proposed changes.
2.  **Create a New Branch:** Base your branch off the latest `main` branch.
3.  **Make Your Changes:** Implement your feature or fix.
4.  **Test Your Changes:** Ensure everything works as expected and passes all checks.
5.  **Write Clear Commit Messages:** Follow the Conventional Commits specification.
6.  **Push Your Branch:** `git push origin <your-branch-name>`
7.  **Open a Pull Request:**
    *   Use our [Pull Request Template](https://github.com/chirag127/ActionsFlow-Event-Driven-Automation-GitHub-Template/blob/main/.github/PULL_REQUEST_TEMPLATE.md).
    *   Provide a clear, concise description of your changes.
    *   Reference any related issues (e.g., `Fixes #123`, `Closes #456`).
    *   Ensure all CI/CD checks pass.

We will review your pull request promptly and may request changes or clarifications.

## Security Vulnerabilities

If you discover a security vulnerability, please report it responsibly following our [Security Policy](https://github.com/chirag127/ActionsFlow-Event-Driven-Automation-GitHub-Template/blob/main/.github/SECURITY.md). Do **NOT** open a public issue. We appreciate your efforts to keep this project secure.

## License

By contributing to ActionsFlow-Event-Driven-Automation-GitHub-Template, you agree that your contributions will be licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License](https://github.com/chirag127/ActionsFlow-Event-Driven-Automation-GitHub-Template/blob/main/LICENSE).
# Contributing to Actionsflow-Workflow-Automation-GitHub-Actions-Starter-Kit

Thank you for considering contributing to `Actionsflow-Workflow-Automation-GitHub-Actions-Starter-Kit`! We welcome your input to make this starter kit the best it can be.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. By participating, you are expected to uphold this code. Please report any unacceptable behavior to [CODE_OF_CONDUCT_REPORTING_EMAIL](mailto:your-reporting-email@example.com).

## 2. How to Contribute

We accept contributions in the form of bug reports, feature requests, documentation improvements, and code contributions.

### 2.1. Reporting Bugs

If you find a bug, please check if it has already been reported. If not, open a new issue with a clear and descriptive title. Include as much information as possible, such as:

*   The version of the starter kit you are using.
*   The operating system and environment details.
*   Steps to reproduce the behavior.
*   Any relevant error messages or logs.

Use the provided issue template for bug reports.

### 2.2. Suggesting Enhancements or Features

We appreciate new ideas! If you have a suggestion for an enhancement or a new feature, please open an issue. Provide a clear description of the proposed change and why it would be beneficial.

### 2.3. Submitting Code Contributions

We are excited to review your code! To ensure a smooth process, please follow these steps:

1.  **Fork the Repository:** Create a fork of this repository on GitHub.
2.  **Clone Your Fork:** Clone your forked repository to your local machine:
    bash
    git clone https://github.com/chirag127/Actionsflow-Workflow-Automation-GitHub-Actions-Starter-Kit.git
    cd Actionsflow-Workflow-Automation-GitHub-Actions-Starter-Kit
    
3.  **Create a New Branch:** Branch out from the `main` branch for your feature or bug fix:
    bash
    git checkout -b feature/your-feature-name
    # or
    git checkout -b fix/your-bug-fix
    
4.  **Make Your Changes:** Implement your changes. Ensure your code adheres to the project's coding standards (see Section 3).
5.  **Test Your Changes:** Run the tests to ensure everything is working as expected:
    bash
    # Example command based on typical Node.js/TypeScript setup
    npm run test
    # Or if using other tools, refer to the README for specific commands.
    
6.  **Commit Your Changes:** Commit your changes with clear and concise messages.
    bash
    git commit -am "Add your commit message here"
    
7.  **Push to Your Fork:** Push your changes to your fork on GitHub:
    bash
    git push origin feature/your-feature-name
    
8.  **Open a Pull Request:** Navigate to the original repository on GitHub and open a pull request from your branch. Provide a detailed description of your changes.

## 3. Development Standards & Guidelines

This project adheres to the Apex Technical Authority standards, emphasizing Zero-Defect, High-Velocity, and Future-Proof development.

*   **Linter & Formatter:** We use **Biome** for linting and formatting to maintain code quality and consistency. Ensure your code passes all checks before submitting a pull request.
    bash
    # Example: Run linter and formatter
    npx @biomejs/biome check --apply-unsafe . 
    npx @biomejs/biome format --write . 
    
*   **Testing:** All contributions must include relevant tests. We use **Vitest** for unit testing and **Playwright** for end-to-end testing.
    bash
    # Example: Run unit tests
    npm run test:unit
    # Example: Run end-to-end tests
    npm run test:e2e
    
*   **TypeScript:** We use **TypeScript 6.x (Strict)** for robust type safety.
*   **Build Tool:** **Vite 7 (Rolldown)** is used for efficient bundling and development.
*   **Architecture:** We follow **Feature-Sliced Design (FSD)** principles for maintainable and scalable code organization.
*   **Dependency Management:** **npm** (or **yarn/pnpm**) is the standard.

Refer to the `AGENTS.md` file for detailed technical directives and approved tools.

## 4. Pull Request Process

*   **Clarity:** Ensure your pull request has a clear title and description explaining the changes.
*   **Tests:** All tests must pass.
*   **Review:** Your pull request will be reviewed by the project maintainers.
*   **CI/CD:** Automated checks will run on your PR via GitHub Actions.

## 5. Questions?

If you have any questions about contributing, please open an issue.

---**

**Repository:** `Actionsflow-Workflow-Automation-GitHub-Actions-Starter-Kit`
**URL:** `https://github.com/chirag127/Actionsflow-Workflow-Automation-GitHub-Actions-Starter-Kit`
**Username:** `chirag127`

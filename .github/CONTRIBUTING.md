# Contributing to Console Whisperer

Thank you for your interest in contributing to Console Whisperer! We welcome contributions of all kinds, including code, documentation, bug reports, and feature requests. To ensure a smooth and collaborative experience, please review the following guidelines.

## 1. Code of Conduct

We are committed to providing a welcoming and inclusive community. All contributors are expected to adhere to our [Code of Conduct](.github/CODE_OF_CONDUCT.md).

## 2. Getting Started

1.  **Fork the repository:** Click the "Fork" button on the top right of the repository page.
2.  **Clone the repository:** `git clone <your-fork-url>`
3.  **Create a branch:** `git checkout -b <your-branch-name>` (Use descriptive names like `fix-bug-x` or `feat-add-feature`) 
4.  **Install dependencies:** Follow the installation instructions in the [README.md](README.md).

## 3. Making Changes

1.  **Make your changes:**  Write your code, add tests, and update documentation as necessary.
2.  **Commit your changes:** Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commit messages.
    *   `feat`:  A new feature
    *   `fix`:  A bug fix
    *   `docs`: Documentation changes
    *   `style`:  Code formatting, etc. (no functional changes)
    *   `refactor`:  Code changes that improve structure but don't change behavior
    *   `perf`:  Performance improvements
    *   `test`:  Adding or modifying tests
    *   `chore`:  Build process or auxiliary tool changes
3.  **Run tests:** Ensure all tests pass before submitting a pull request.  Use `npm run test` or the appropriate command for the project's testing framework.
4.  **Lint your code:**  Ensure your code adheres to our linting rules.  Use `npm run lint` or the appropriate command.
5.  **Format your code:** Ensure your code is formatted correctly. This project uses Biome for formatting.

## 4. Submitting a Pull Request

1.  **Push your changes:** `git push origin <your-branch-name>`
2.  **Create a pull request:** Go to the original repository and click "Compare & pull request."  Provide a clear and concise description of your changes.
3.  **Review:**  Be prepared to address any feedback or suggestions from the maintainers.

## 5. Branching Model

We use a branching model that is designed to be simple and effective:

*   `main`: The main branch represents the current stable release. Pull requests should be merged into this branch.
*   `develop`: The develop branch represents the in-development state. Feature branches should be based off of and merged into develop branch.

## 6. Project Structure

Refer to the [README.md](README.md) for details about the project's architecture and file structure.

## 7. Reporting Bugs

If you find a bug, please [open an issue](.github/ISSUE_TEMPLATE/bug_report.md) and provide as much detail as possible, including:

*   A clear and concise description of the bug.
*   Steps to reproduce the bug.
*   Expected behavior.
*   Actual behavior.
*   Your environment (browser, operating system, etc.).

## 8. Feature Requests

If you have a feature request, please [open an issue](.github/ISSUE_TEMPLATE/feature_request.md) and provide a clear and concise description of the feature, including:

*   A clear and concise description of the feature.
*   Why the feature is useful.
*   Potential implementation details (optional).

## 9. Security

If you discover a security vulnerability, please refer to our [Security Policy](.github/SECURITY.md).

## 10. Contact

For any questions or concerns, please contact us via GitHub issues.

---
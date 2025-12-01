# Contributing to ScanFlow-Mobile-QR-Barcode-App

Thank you for your interest in contributing to ScanFlow! We welcome contributions of all kinds, including code, documentation, and bug reports. To ensure a smooth and collaborative experience, please review the guidelines below.

## Code of Conduct

We are committed to providing a welcoming and inclusive environment for all contributors. Please adhere to our [Code of Conduct](.github/CODE_OF_CONDUCT.md) in all interactions.

## Getting Started

1.  **Fork the Repository:** Create your own fork of the repository.
2.  **Create a Branch:** Create a new branch for your contribution. The branch name should be descriptive of the changes you are making (e.g., `feature/improved-scanning`, `fix/barcode-decode-error`).
3.  **Make Your Changes:** Implement your changes, following the coding standards and guidelines outlined below.
4.  **Test Your Changes:** Ensure your changes are thoroughly tested and do not introduce any regressions. Run all tests to verify that your changes are working as expected.
5.  **Commit Your Changes:** Commit your changes with clear and concise commit messages. Use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format.  (e.g., `feat: Add support for PDF417 barcodes`).
6.  **Submit a Pull Request:** Open a pull request against the `main` branch of the original repository.

## Coding Standards

*   **Language:** JavaScript, TypeScript
*   **Style Guide:** Follow the [ESLint](https://eslint.org/) rules with Biome. Use `biome check --apply` to automatically format your code.
*   **Code Formatting:** Use Biome for automatic code formatting.
*   **Commit Messages:** Use the Conventional Commits format for all commit messages.
*   **Comments:** Write clear and concise comments to explain complex logic or the *why* behind a piece of code.  Avoid commenting the *what*.

## Development Environment

*   **Node.js & npm/Yarn/pnpm:** Make sure you have Node.js and a package manager (npm, Yarn, or pnpm) installed on your system.
*   **IDE/Editor:** We recommend using an IDE or editor with support for TypeScript and React Native, such as VS Code with the necessary extensions (e.g., ESLint, Prettier, TypeScript Language Features).

## Testing

*   **Testing Framework:** Unit tests using Vitest, end-to-end tests using Playwright.
*   **Test Coverage:** Ensure your code changes are covered by tests. Aim for high test coverage to prevent regressions.
*   **Running Tests:** Use the scripts provided in `package.json` to run tests.

## Pull Request Guidelines

*   **Descriptive Title:** Provide a clear and concise title for your pull request.
*   **Detailed Description:** Describe the changes you have made, the problem you are solving, and any relevant context.
*   **Testing:** Include information about how you tested your changes and the results.
*   **Reviewers:** Request a review from the maintainers of the repository.
*   **Address Feedback:** Be responsive to feedback from reviewers and make necessary changes.

## Issue Guidelines

*   Before opening a new issue, search existing issues to see if the problem has already been reported.
*   Provide a clear and concise description of the problem.
*   Include steps to reproduce the problem.
*   Provide any relevant information, such as error messages, screenshots, or code snippets.

## Thank You

Thank you for contributing to ScanFlow! Your efforts help us make this project better for everyone.

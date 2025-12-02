# Security Policy for ScanFlow-HighPerformance-QRBarcode-MobileScanner-App

As an Apex-engineered project adhering to the **Zero-Defect, High-Velocity, Future-Proof** philosophy, security is integrated from inception.

## 1. Overview

This repository follows the principles outlined in the **AGENTS.md** directive, prioritizing secure coding practices (SOLID, DRY) and verifiable component integrity.

## 2. Supported Versions

We actively support and maintain the latest production-ready versions of our core stack:

*   **React Native / Expo:** Currently targeting the latest stable release channel (as of December 2025).
*   **TypeScript:** Strict mode is enforced on all code.
*   **Scanning Library:** Dependencies related to computer vision and hardware interfacing are subject to rigorous security audits.

## 3. Reporting a Vulnerability

We welcome responsible disclosure of security vulnerabilities.

If you discover a security issue, please follow these steps immediately. **DO NOT** create a public issue or pull request that discloses the vulnerability details.

1.  **Private Disclosure:** Email the security team directly at `security@chirag127.dev` (Substitute with actual contact if applicable, otherwise use a placeholder/private channel directive).
2.  **Include Details:** In your email, provide a detailed description of the vulnerability, the affected component(s), and steps to reproduce it.
3.  **Wait for Acknowledgment:** Wait for an acknowledgment from the security team before disclosing the issue publicly.

## 4. Disclosure Timeline

We commit to the following timeline upon receiving a valid vulnerability report:

| Action | Timeframe |
| :--- | :--- |
| Acknowledgment of Report | Within 48 hours |
| Vulnerability Triage & Fix Development | Up to 14 days |
| Release Candidate Preparation | Up to 21 days |
| Public Disclosure (Post-Patch) | Coordinated release, typically 7 days after patch release. |

## 5. Automated Security Scanning

This repository utilizes GitHub Actions for continuous security monitoring:

*   **Dependency Scanning:** Enabled via workflows to check for known vulnerabilities in `package.json` dependencies.
*   **Static Analysis:** Enforced via linting tools (Biome/Ruff equivalents for JavaScript/TypeScript) integrated into the CI pipeline (`.github/workflows/ci.yml`). Code failing security checks will halt the build.

## 6. Secure Development Practices

All contributions must adhere to the following:

*   **Input Validation:** All data received from the mobile environment or external sources must be aggressively validated, especially when dealing with camera feeds or system APIs.
*   **Secrets Management:** No secrets, API keys, or credentials are to be committed. All necessary keys must be injected via environment variables during the build/runtime process, managed securely through GitHub Secrets or appropriate mobile secure storage mechanisms.
*   **Dependency Review:** All new dependencies must be reviewed for known CVEs before merging. Use `npm audit` checks within the CI pipeline.
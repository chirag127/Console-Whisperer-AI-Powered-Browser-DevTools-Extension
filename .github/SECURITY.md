# Security Policy

## Supported Versions

We are committed to maintaining a secure development environment. The following versions are actively maintained and receive regular security updates:

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |

Security vulnerabilities in `ConsoleAI-DevTools-Copilot-Browser-Extension` should be reported according to the instructions below to ensure prompt attention and remediation.

## Reporting a Vulnerability

We appreciate your efforts to responsibly disclose security vulnerabilities. Please follow these steps:

1.  **Do NOT** file a public issue or pull request for security vulnerabilities.
2.  Send a detailed email to our dedicated security team at: `security@example.com` (Please replace with a real security contact email if available).
3.  In your email, please include:
    *   A clear description of the vulnerability.
    *   Steps to reproduce the vulnerability.
    *   The affected version(s) of the software.
    *   Any relevant system information or environment details.
    *   (Optional) A proof-of-concept exploit.
4.  We will acknowledge receipt of your vulnerability report within **48 hours**.
5.  We will investigate and, if necessary, release a fix as quickly as possible. We will also provide updates on the progress of the fix.
6.  We may choose to publicly disclose the vulnerability once a fix is available, crediting the reporter.

## Security Best Practices

As a browser extension and developer tool, security is paramount. We aim to adhere to the following best practices:

*   **Principle of Least Privilege:** The extension only requests the permissions it absolutely needs to function.
*   **Input Validation:** All external inputs are validated to prevent injection attacks.
*   **Secure Data Handling:** Sensitive data, if any, is handled with encryption and stored securely.
*   **Dependency Management:** We regularly audit and update our dependencies using `uv` and `Ruff` to incorporate the latest security patches.
*   **Code Audits:** Regular code reviews and automated security checks are part of our development lifecycle.

Thank you for helping us keep `ConsoleAI-DevTools-Copilot-Browser-Extension` secure!

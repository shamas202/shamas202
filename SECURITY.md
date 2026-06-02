# Security Policy

## Supported Versions

We provide security updates for the latest version of this project.

## Reporting a Vulnerability

If you discover a security vulnerability within this project, please send an email to shamszia@example.com with details. We will review your report and respond promptly.

Please do not disclose security vulnerabilities publicly until we have had an opportunity to address them.

## Security Best Practices Implemented

This project follows several security best practices:

1. **Minimal Permissions**: GitHub Actions workflows use the principle of least privilege for permissions
2. **Updated Dependencies**: We regularly update GitHub Actions to latest secure versions
3. **Dependency Monitoring**: Dependabot is configured to alert us of outdated actions
4. **Code Scanning**: Regular CodeQL analysis to identify potential security issues
5. **Secure Checkout**: Using `persist-credentials: false` with actions/checkout to prevent credential leakage
6. **Workflow Security**: Timeout limits and careful review of third-party actions

## Dependabot

This repository uses Dependabot to automatically monitor and update GitHub Actions dependencies to their latest secure versions.

## Contact

For security-related inquiries, please contact: shamszia@example.com
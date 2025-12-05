# Security Policy for MindBloom-Digital-Wellbeing-Mindfulness-Mobile-App

**Effective Date:** December 2025 (Reflecting Late 2025 Standards)

**Security is Paramount:** At `chirag127/MindBloom-Digital-Wellbeing-Mindfulness-Mobile-App`, we are committed to providing a secure and trustworthy experience for our users. This document outlines our security policy and procedures.

## 1. Reporting a Vulnerability

We encourage responsible disclosure of security vulnerabilities. If you discover any security issues, please report them to us responsibly.

*   **Preferred Method:** Please submit a **Security Advisory** directly through GitHub. Navigate to the `Security` tab of the repository (`https://github.com/chirag127/MindBloom-Digital-Wellbeing-Mindfulness-Mobile-App/security/advisories`) and click "New advisory". This allows for private discussion and coordinated disclosure.
*   **Alternative Method:** If you are unable to use GitHub's advisory system, please send an encrypted email to `[Your Security Contact Email Address]` (Replace with an actual, secure email if available, otherwise state that GitHub is preferred).

**When reporting a vulnerability, please include:**

*   A clear and concise description of the vulnerability.
*   Steps to reproduce the vulnerability.
*   The affected version(s) or component(s) of the application.
*   Any proof-of-concept code or exploit details.
*   Your contact information for follow-up.

## 2. Vulnerability Handling Process

We are committed to a prompt and thorough response to all reported security vulnerabilities. Our process includes:

1.  **Acknowledgement:** We will acknowledge receipt of your report within **48 hours**. If using GitHub advisories, this will be immediate.
2.  **Triage & Investigation:** Our security team will investigate the reported issue promptly to confirm its validity and assess its impact.
3.  **Resolution:** Once a vulnerability is confirmed, we will work diligently to develop and deploy a fix. For a React Native mobile app, this typically involves updating dependencies, patching code, and releasing a new version.
4.  **Disclosure:** We aim for coordinated disclosure. After a fix is available and deployed, we will publicly disclose the vulnerability (often in collaboration with the reporter) via GitHub Security Advisories and release notes. The target timeline for public disclosure after a fix is deployed is typically **7 days**, unless otherwise agreed upon.

## 3. Supported Versions & Security Updates

We actively maintain and update the following versions of the MindBloom application:

*   **Latest Release Branch:** We provide security updates for the most recent stable release. Users are strongly encouraged to update to the latest version to benefit from the latest security patches.
*   **Previous Minor Version:** We may provide critical security updates for the immediately preceding minor version for a limited time, based on impact and resource availability.

Older versions are not actively supported and may contain unpatched vulnerabilities. Users are advised to upgrade.

## 4. Supported Technologies & Dependencies

This project is built using **React Native** and **Expo**, leveraging JavaScript/TypeScript. We adhere to the following principles:

*   **Dependency Management:** We regularly audit and update third-party dependencies using tools like `npm` or `yarn` and security scanners integrated into our CI/CD pipeline (`https://github.com/chirag127/MindBloom-Digital-Wellbeing-Mindfulness-Mobile-App/actions`).
*   **Expo Security Updates:** We follow Expo's security guidelines and apply updates to the Expo SDK as recommended.
*   **React Native Security:** We monitor React Native security advisories and apply necessary patches.

## 5. Code Security Practices

Our development practices include:

*   **Linting & Formatting:** Strict linting rules enforced by tools like ESLint/Prettier (or Biome as per Apex standards if adapted) to catch potential security anti-patterns.
*   **Static Analysis:** Utilizing security-focused static analysis tools within our CI pipeline.
*   **Secure Coding Guidelines:** Developers are expected to follow secure coding best practices for mobile applications, including input validation, secure handling of sensitive data, and avoiding common vulnerabilities (e.g., XSS, insecure data storage).
*   **Secrets Management:** Sensitive information (API keys, credentials) is managed securely using environment variables and not committed directly into the codebase. We utilize Expo's secure configuration capabilities.

## 6. Contact Information

For security-related inquiries, please use the reporting channels outlined in Section 1. For general inquiries, please refer to the repository's main page (`https://github.com/chirag127/MindBloom-Digital-Wellbeing-Mindfulness-Mobile-App`).

---
**Thank you for helping keep the MindBloom application secure!**

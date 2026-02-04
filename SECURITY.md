# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Currently supported versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take the security of our project seriously. If you have discovered a security vulnerability, we appreciate your help in disclosing it to us in a responsible manner.

### How to Report a Security Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them using one of the following methods:

1. **GitHub Security Advisories** (Recommended)
   - Navigate to the Security tab of this repository
   - Click "Report a vulnerability"
   - Fill out the form with details about the vulnerability

2. **Email**
   - Send an email to the repository maintainers with details about the vulnerability

### What to Include in Your Report

Please include the following information to help us better understand the nature and scope of the issue:

- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### What to Expect

After you submit a report, we will:

1. **Acknowledge receipt** of your vulnerability report within 48 hours
2. **Confirm the issue** and determine its severity within 7 days
3. **Work on a fix** and keep you informed of our progress
4. **Release a security patch** as soon as possible
5. **Credit you** (if desired) in the security advisory when we disclose the vulnerability

## Security Update Policy

Security updates will be released as soon as possible after a vulnerability is confirmed and a fix is developed. We will:

- Release security patches for supported versions
- Publish a security advisory on GitHub
- Update this SECURITY.md file if needed

## Security Best Practices

When using this project, we recommend:

- Keep your dependencies up to date
- Review Dependabot alerts and apply suggested updates
- Enable vulnerability scanning in your environment
- Follow secure coding practices
- Use the latest supported version

## Scope

The following are **in scope** for security reports:

- Security vulnerabilities in the application code
- Dependency vulnerabilities that affect this project
- Configuration issues that could lead to security problems

The following are **out of scope**:

- Issues in dependencies that don't affect this project
- Social engineering attacks
- Physical attacks

## Legal

By reporting security vulnerabilities to us, you agree that:

- You will not exploit the vulnerability beyond what is necessary to demonstrate it
- You will keep the vulnerability confidential until we have addressed it
- You will not harm the project, its users, or its data

We commit to not taking legal action against security researchers who:

- Act in good faith
- Follow this policy
- Report vulnerabilities responsibly

## Contact

For questions about this security policy, please open a discussion in the repository.

---

Thank you for helping keep our project and our users safe!

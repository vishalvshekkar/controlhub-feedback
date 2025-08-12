# Security Policy

## Reporting Security Vulnerabilities

The security of ControlHub and its users is extremely important to me. If you discover a security vulnerability, I appreciate your help in disclosing it responsibly.

### How to Report

**Please do NOT report security vulnerabilities through public GitHub issues.**

Instead, please send an email to: **controlhub@vishalvshekkar.com**

### What to Include

When reporting a security vulnerability, please include:

- **Description** - A clear description of the vulnerability
- **Steps to Reproduce** - Detailed steps to reproduce the issue
- **Impact Assessment** - Your assessment of the potential impact
- **Affected Versions** - Which versions of ControlHub are affected
- **Suggested Fix** - If you have suggestions for fixing the issue

## Security Best Practices

ControlHub follows these security practices:

### Data Protection
- **Local Storage** - Sensitive data like API Key is stored locally using encrypted Keychain
- **API Security** - All API communications use HTTPS with proper authentication
- **No Data Collection** - I don't collect or store personal data on my servers
- **Minimal Permissions** - The app requests only necessary permissions

### Authentication
- **Biometric Authentication** - Support for Face ID/Touch ID for app access through iOS feature
- **API Key Security** - Control D API keys are stored securely in Keychain

### Code Security
- **Regular Updates** - Dependencies are regularly updated
- **Secure Coding** - Following iOS security best practices
- **Code Review** - All code changes are reviewed for security issues

## Security Contact

For security-related questions or concerns:
- **Email**: controlhub@vishalvshekkar.com

## Responsible Disclosure

I believe in responsible disclosure and ask that you:

- Give me reasonable time to fix the issue before public disclosure
- Don't perform actions that could harm the app or its users
- Don't publicly disclose the vulnerability until I've had a chance to fix it

## Recognition

I appreciate security researchers who help keep ControlHub secure. With your permission, I'll acknowledge your contribution in the release notes.

---

Thank you for helping keep ControlHub secure! 🔒
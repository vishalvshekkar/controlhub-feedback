# Security Policy

## Reporting Security Vulnerabilities

The security of ControlHub and its users is extremely important to us. If you discover a security vulnerability, we appreciate your help in disclosing it responsibly.

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

### Response Timeline

- **Initial Response**: Within 48 hours of your report
- **Status Update**: Within 7 days with our assessment
- **Resolution**: Security fixes will be prioritized and released as soon as possible

### What to Expect

1. **Acknowledgment** - We'll confirm receipt of your report
2. **Investigation** - We'll investigate and assess the vulnerability
3. **Fix Development** - We'll develop and test a fix
4. **Release** - We'll release the fix via App Store update
5. **Disclosure** - We'll coordinate public disclosure if appropriate

## Security Best Practices

ControlHub follows these security practices:

### Data Protection
- **Local Storage** - Sensitive data is stored locally using iOS Keychain
- **API Security** - All API communications use HTTPS with proper authentication
- **No Data Collection** - We don't collect or store personal data on our servers
- **Minimal Permissions** - The app requests only necessary permissions

### Authentication
- **Biometric Authentication** - Support for Face ID/Touch ID for app access
- **API Key Security** - Control D API keys are stored securely in Keychain
- **Session Management** - Secure session handling with automatic token refresh

### Code Security
- **Regular Updates** - Dependencies are regularly updated
- **Secure Coding** - Following iOS security best practices
- **Code Review** - All code changes are reviewed for security issues

## Supported Versions

Security updates are provided for:

| Version | Supported |
|---------|-----------|
| Latest Release | ✅ Yes |
| Previous Release | ✅ Yes |
| Older Versions | ❌ No |

## Security Contact

For security-related questions or concerns:
- **Email**: controlhub@vishalvshekkar.com
- **Response Time**: Within 48 hours

## Responsible Disclosure

We believe in responsible disclosure and ask that you:

- Give us reasonable time to fix the issue before public disclosure
- Avoid accessing, modifying, or deleting data that doesn't belong to you
- Don't perform actions that could harm the app or its users
- Don't publicly disclose the vulnerability until we've had a chance to fix it

## Recognition

We appreciate security researchers who help keep ControlHub secure. With your permission, we'll acknowledge your contribution in our release notes.

---

Thank you for helping keep ControlHub secure! 🔒
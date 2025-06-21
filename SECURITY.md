# Security Policy

## 🛡️ Supported Versions

We release patches for security vulnerabilities. Which versions are eligible for receiving such patches depend on the CVSS v3.0 Rating:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | ✅ |
| < 1.0   | ❌ |

## 🔒 Security Focus Areas

### 1. System Safety
- **File System Access**: Safe file operations without system damage
- **Registry Changes**: Minimal and reversible Windows registry modifications
- **Process Isolation**: Secure execution without affecting other applications
- **User Permissions**: Proper UAC handling and permission requests

### 2. Data Protection
- **No Online Communication**: Purely offline operation (no data transmission)
- **Local Storage**: Secure handling of configuration files
- **User Privacy**: No personal data collection or storage
- **Temporary Files**: Secure cleanup of temporary files

### 3. Game Integrity
- **Read-Only Operations**: No modification of core game files
- **Configuration Safety**: Safe configuration file handling
- **Backup Systems**: Automatic backup of important settings
- **Rollback Capability**: Easy restoration of original settings

## 🚨 Reporting a Vulnerability

If you discover a security vulnerability, please follow these steps:

### 📧 Private Reporting
**DO NOT** open a public GitHub issue for security vulnerabilities.

Instead, please email us at: **security@sea-of-thieves-assistant.com**

Include the following information:
- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact and exploitation scenarios
- Your contact information for follow-up
- Any suggested fixes or mitigations

### 🕒 Response Timeline
- **24 hours**: Acknowledgment of your report
- **72 hours**: Initial assessment and severity classification
- **7 days**: Detailed investigation and fix development
- **14 days**: Fix testing and release preparation
- **30 days**: Public disclosure (after fix is released)

### 🏆 Recognition
We appreciate security researchers who help improve our project:

- **Hall of Fame**: Recognition in our security acknowledgments
- **Contributor Status**: Special contributor badge
- **Early Access**: Preview of security improvements
- **Community Thanks**: Public recognition for responsible disclosure

## 🔐 Security Best Practices

### For Users
- **Download Only from Official Sources**: GitHub releases only
- **Verify File Integrity**: Check file hashes when provided
- **Run with Standard Permissions**: Avoid running as administrator unless required
- **Keep Updated**: Use the latest version for security fixes
- **Backup Configurations**: Save your settings before major changes

### For Contributors
- **Code Review**: All security-related changes require multiple reviews
- **Input Validation**: Validate all user inputs and file paths
- **Error Handling**: Secure error messages without information disclosure
- **Dependencies**: Keep all dependencies updated and secure
- **Static Analysis**: Use security scanning tools on code changes

## 🛠️ Security Architecture

### Isolation Principles
- **Process Sandboxing**: Limited system access
- **File System Boundaries**: Restricted to game directories
- **Network Isolation**: No network access required
- **User Space Operation**: No kernel-level modifications

### Safe Defaults
- **Conservative Permissions**: Minimal required access
- **Fail-Safe Operations**: Safe failure modes
- **Reversible Changes**: All modifications can be undone
- **Configuration Validation**: Input sanitization and validation

## 📋 Security Checklist

Before each release, we verify:

- [ ] All user inputs are properly validated
- [ ] File operations are bounded to safe directories
- [ ] No hardcoded credentials or sensitive data
- [ ] Error messages don't leak sensitive information
- [ ] All dependencies are up-to-date and secure
- [ ] Code has been reviewed for security issues
- [ ] Installation/uninstallation is clean and complete
- [ ] No permanent system modifications

## 🚫 Out of Scope

The following are considered out of scope for security reports:

- **Game Exploits**: Issues within Sea of Thieves itself
- **System Configuration**: User's Windows security settings
- **Network Security**: Router/firewall configurations
- **Physical Security**: Access to user's computer
- **Social Engineering**: Attacks targeting users directly

## 📞 Security Resources

- **Security Email**: security@sea-of-thieves-assistant.com
- **PGP Key**: Available upon request
- **Security Updates**: Watch our releases for security patches
- **Best Practices**: Check our documentation for security guidelines

## 🔄 Policy Updates

This security policy may be updated periodically to reflect:

- Changes in threat landscape
- Updates to supported versions
- Improvements in security processes
- Community feedback and suggestions

---

**Remember**: Security is a shared responsibility. Help us keep Sea of Thieves Offline Setup Assistant safe for everyone! 🏴‍☠️🛡️ 
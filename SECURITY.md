# Security Policy

## 🛡️ Supported Versions

We actively support and provide security updates for the following versions of MelonLoader:

| Version | Supported          |
| ------- | ------------------ |
| 0.7.0   | ✅ Fully supported |
| 0.6.x   | ✅ Security fixes  |
| 0.5.x   | ❌ End of life     |
| < 0.5   | ❌ Not supported   |

## 🚨 Reporting a Vulnerability

### Quick Contact
For **urgent security issues**, contact us immediately:
- 📧 **Email**: [security@lavagang.org](mailto:security@lavagang.org)
- 💬 **Discord**: Direct message to `@LavaGang Team`

### What to Include
When reporting security vulnerabilities, please provide:

```
Subject: [SECURITY] Brief description

**Vulnerability Type:** [e.g., Code injection, memory corruption]
**Affected Versions:** [e.g., 0.7.0, 0.6.5]
**Severity:** [Critical/High/Medium/Low]

**Description:**
Clear explanation of the vulnerability

**Steps to Reproduce:**
1. Step one
2. Step two
3. Step three

**Potential Impact:**
What could an attacker achieve?

**Suggested Fix:**
If you have ideas for a solution
```

### Our Response Process

#### Within 24 Hours
- ✅ Acknowledge receipt
- 🔍 Begin initial assessment
- 🤝 Establish communication channel

#### Within 7 Days
- 📊 Complete vulnerability assessment
- 📋 Determine severity and impact
- 🗓️ Provide timeline for fix

#### Resolution
- 🔧 Develop and test fix
- 📦 Release security update
- 📢 Public disclosure (if appropriate)

## 🔒 Security Best Practices

### For Users
- ✅ **Keep Updated**: Always use the latest version
- ✅ **Verify Downloads**: Only download from official sources
- ✅ **Scan Mods**: Use antivirus on downloaded mod files
- ✅ **Backup Saves**: Keep game saves backed up
- ⚠️ **Avoid Untrusted Mods**: Only use mods from reputable sources

### For Mod Developers
- ✅ **Input Validation**: Sanitize all user inputs
- ✅ **Safe APIs**: Use MelonLoader's safe API methods
- ✅ **Memory Management**: Properly dispose of resources
- ✅ **Permissions**: Request minimal necessary permissions
- ⚠️ **Avoid Unsafe Code**: Minimize use of unsafe code blocks

### For Game Developers
- ✅ **Regular Updates**: Keep Unity and dependencies updated
- ✅ **Code Obfuscation**: Consider obfuscating sensitive game logic
- ✅ **Server Validation**: Don't trust client-side data
- ✅ **Anti-Cheat**: Implement server-side validation

## 🚫 Known Security Considerations

### Inherent Risks
MelonLoader operates by injecting code into Unity applications. This inherently:
- Requires elevated privileges on some systems
- Can be flagged by antivirus software
- Allows mods to access game memory
- May bypass some game security measures

### Mitigation Strategies
- 🔍 **Sandboxing**: Mods run in controlled environment
- 🛡️ **API Restrictions**: Limited access to system functions
- 📝 **Logging**: All mod actions are logged
- ⚡ **Quick Updates**: Fast response to security issues

## 🎯 Scope

### In Scope
✅ MelonLoader core library vulnerabilities  
✅ Official MelonLoader tools and utilities  
✅ Documentation security issues  
✅ Build/distribution security  

### Out of Scope
❌ Third-party mod vulnerabilities  
❌ Game-specific security issues  
❌ Unity Engine vulnerabilities  
❌ Operating system security issues  

## 🏆 Security Hall of Fame

We thank these security researchers for responsibly disclosing vulnerabilities:

| Researcher | Date | Issue |
|------------|------|-------|
| *Your name here* | *Date* | *Brief description* |

*Want to be listed? Report a valid security issue!*

## 📞 Contact Information

### Security Team
- **Primary Contact**: [security@lavagang.org](mailto:security@lavagang.org)
- **PGP Key**: Available upon request
- **Response Time**: Within 24 hours

### General Security Questions
For non-urgent security questions:
- 💬 [Discord #security channel](https://discord.gg/2Wn3N2P)
- 🗨️ [GitHub Discussions](https://github.com/Lava-Gang/melonloader/discussions)

---

**Remember**: Security is everyone's responsibility. When in doubt, report it! 
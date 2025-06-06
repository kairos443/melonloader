# Changelog

All notable changes to MelonLoader will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.7.0] - 2024-01-15

### 🎉 Added
- **Unity 2023 Support** - Full compatibility with Unity 2023.x LTS
- **Enhanced Mod Security** - New sandboxing system for safer mod execution
- **Plugin API v2** - Redesigned plugin architecture with better performance
- **Auto-Update System** - Automatic updates for critical security fixes
- **Offline Installation** - Complete offline setup assistant for airgapped environments
- **Multi-Language Support** - Interface now available in 12 languages

### 🔧 Changed
- **Performance Boost** - 40% faster mod loading times
- **Memory Optimization** - Reduced memory footprint by 25%
- **Error Messages** - More descriptive and actionable error reporting
- **Documentation** - Complete rewrite of modding guides

### 🐛 Fixed
- Fixed crash with certain Unity 2022.3 builds
- Resolved mod loading order inconsistencies
- Fixed memory leaks in plugin unloading
- Corrected compatibility issues with IL2CPP stripped builds

### 🗑️ Removed
- Deprecated legacy API v1 methods (use Plugin API v2)
- Removed support for Unity versions below 2019.4

## [0.6.5] - 2023-11-20

### 🔒 Security
- **CVE-2023-XXXX**: Fixed remote code execution vulnerability
- Enhanced input validation for mod parameters
- Improved file system access controls

### 🐛 Fixed
- Stability improvements for Unity 2022.2
- Fixed mod dependency resolution edge cases
- Corrected console output encoding on non-English systems

## [0.6.0] - 2023-08-10

### 🎉 Added
- **Unity 2022 Support** - Beta support for Unity 2022.x versions
- **Mod Manager UI** - Built-in graphical mod management interface
- **Dependency System** - Automatic mod dependency resolution
- **Hot Reload** - Reload mods without restarting the application

### 🔧 Changed
- Restructured mod loading pipeline for better reliability
- Updated logging system with configurable verbosity levels
- Improved compatibility detection for Unity versions

### 🐛 Fixed
- Fixed crashes on applications with custom splash screens
- Resolved threading issues in mod initialization
- Corrected path handling for non-ASCII characters

## [0.5.7] - 2023-06-15

### 🔒 Security
- Patched mod loader privilege escalation issue
- Enhanced validation of mod signatures

### 🐛 Fixed
- Fixed compatibility with Unity 2021.3.26f1+
- Resolved console spam from certain mod configurations
- Fixed mod unloading memory leaks

## [0.5.0] - 2023-03-01

### 🎉 Added
- **IL2CPP Support** - Full support for IL2CPP compiled games
- **Unity 2021 Support** - Compatibility with Unity 2021.x LTS
- **Harmony Integration** - Built-in Harmony patching support
- **Console Commands** - Interactive console for debugging

### 🔧 Changed
- Major refactor of core injection system
- Improved error handling and reporting
- Updated documentation with video tutorials

### 🗑️ Removed
- Dropped support for Unity 2018.x and below

## [0.4.3] - 2022-12-10

### 🐛 Fixed
- Critical fix for Unity 2020.3.40f1+ compatibility
- Fixed mod initialization race conditions
- Resolved issues with certain antivirus false positives

## [0.4.0] - 2022-09-15

### 🎉 Added
- **Unity 2020 Support** - Full compatibility with Unity 2020.x
- **Mod Configuration** - JSON-based mod configuration system
- **Performance Profiler** - Built-in mod performance monitoring
- **Auto-Backup** - Automatic backup of game files before modding

### 🔧 Changed
- Redesigned mod loading architecture for better stability
- Enhanced compatibility with obfuscated games
- Improved startup performance by 30%

## [0.3.0] - 2022-06-01

### 🎉 Added
- **Unity 2019 Support** - Compatibility with Unity 2019.4 LTS
- **Plugin System** - Extensible plugin architecture
- **Logging Framework** - Comprehensive logging for debugging
- **Mod Verification** - Basic mod integrity checking

### 🔧 Changed
- Complete rewrite of injection mechanism
- Improved cross-platform compatibility
- Enhanced documentation with examples

## [0.2.0] - 2022-02-01

### 🎉 Added
- **Basic Mod Loading** - Load and execute .NET assemblies
- **Unity Integration** - Hook into Unity's component system
- **Simple Configuration** - Basic configuration file support

### 🐛 Fixed
- Various stability improvements
- Memory management enhancements

## [0.1.0] - 2021-10-15

### 🎉 Added
- **Initial Release** - Basic proof of concept
- **Unity 2018 Support** - Limited compatibility
- **Simple Injection** - Basic DLL injection capability

---

## 🔗 Links

- **[Download Latest](https://github.com/Lava-Gang/melonloader/releases/latest)**
- **[Installation Guide](docs/installation.md)**
- **[Modding Tutorial](docs/modding-guide.md)**
- **[Migration Guide](docs/migration.md)**

## 📝 Version Support

| Version | Unity Support | Status | End of Life |
|---------|---------------|--------|-------------|
| 0.7.x | 2019.4 - 2023.x | ✅ Active | TBD |
| 0.6.x | 2019.4 - 2022.x | 🔒 Security Only | 2024-12-31 |
| 0.5.x | 2019.4 - 2021.x | ❌ Unsupported | 2023-12-31 |

---

**Note**: For security vulnerabilities, please see our [Security Policy](SECURITY.md). 
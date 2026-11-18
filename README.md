# ProjectVault

**Free Developer Project Backup & Packaging Tool for Windows**

ProjectVault helps developers create clean, organized, and reliable backups of their software projects. Select exactly which files and folders to include, identify unnecessary files, review recommendations, and generate verified ZIP archives.

ProjectVault is free to use. No subscription, registration, or payment is required.

## 🚀 Features

### Smart Project Backup
- Scan and explore software project folders.
- Select or deselect individual files and folders.
- Include or exclude entire directories.
- View file sizes, folder sizes, total selected size, and estimated ZIP size.
- Expand and collapse project directories.

### Intelligent File Classification
ProjectVault analyzes files based on their location and project context, not just their extensions.

It identifies:
- Build and generated files.
- Dependencies and libraries.
- Downloaded artifacts.
- Temporary files and caches.
- Version control and IDE files.
- Configuration files and potential secrets.

Every recommendation includes an explanation and guidance on whether the item should be included, excluded, or reviewed.

### Project Packaging Guidance
- Understand why a file or folder is flagged.
- See recommendations for keeping or excluding files.
- Identify files that can be downloaded again.
- Access official download links when reliably identifiable.
- View restore commands when confirmed by project configuration files.

### Flexible Backup Profiles

Choose from three backup profiles:

| Profile | Description |
|---|---|
| Full | Includes everything by default while displaying recommendations. |
| Source Only | Applies recommended exclusions while keeping important project files. |
| Custom | Lets you decide exactly what to include or exclude. |

Save and reload your backup configurations whenever needed.

### Custom Rules
- Exclude specific folder names.
- Exclude file extensions and patterns.
- Create exceptions for files that must always be included.
- Apply rules to specific folders or project types.

### Supported Project Types

ProjectVault recognizes a wide range of development environments:

- .NET (WPF, WinForms, ASP.NET, MAUI)
- Android
- Java / Kotlin
- PHP / Laravel
- Node.js / React
- Python
- Flutter
- Rust
- Go
- C / C++
- Unity
- Xcode

### Backup Verification & Safety

Your original project files are never modified.

ProjectVault:
- Creates ZIP archives using a temporary file.
- Reopens and verifies the generated archive.
- Checks that selected files are present exactly once.
- Verifies file sizes and folder structures.
- Preserves empty directories and timestamps.
- Supports cancellation without leaving incomplete archives.
- Does not follow directory links or junctions.

### Backup Documentation

Optionally generate a `BACKUP_README.md` inside your ZIP archive containing:
- Project information.
- Version and backup date.
- Backup type.
- Excluded files and reasons.
- Dependencies that need to be downloaded.
- Restoration instructions and relevant links.

Your existing project README is never overwritten.

## 📥 Download & Installation

Download the latest version:

**[Download ProjectVault – Latest Release](../../releases/latest)**

1. Download the latest ProjectVault installer or ZIP package.
2. Run the installer or extract the ZIP.
3. Launch `ProjectVault.exe`.
4. Select your project folder.
5. Review the suggested files and folders.
6. Choose your backup profile or customize your selection.
7. Create your verified ZIP backup.

### System Requirements

- Windows operating system.
- No separate .NET installation is required for the self-contained installer.

## ❤️ Support ProjectVault

ProjectVault is free software, developed and maintained independently.

If you find it useful and want to help us continue improving it, consider making an optional donation.

Your support helps us:
- Maintain and improve the application.
- Develop new features.
- Fix bugs and improve performance.
- Support future development.
- Keep ProjectVault free for everyone.

**Donations are completely voluntary. They do not unlock features or provide additional functionality.**

## 🔄 Updates & Feedback

Check this repository for new releases and improvements.

If you encounter a problem or have a suggestion:
- Open an issue in the GitHub repository.
- Describe the problem and how to reproduce it.
- Include relevant screenshots or error messages.

## 📄 License & Copyright

Copyright © 2026 ProjectVault. All rights reserved.

ProjectVault is distributed as free, closed-source software under a proprietary freeware license.

You may use the application for personal and commercial purposes, subject to the terms of the included `LICENSE.txt`.

Redistribution, modification, and unauthorized distribution of the application are not permitted.

See [LICENSE.txt](LICENSE.txt) for the complete terms.

---

**ProjectVault – Back up your projects. Keep what matters.**

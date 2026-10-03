# Kaptal Releases

Official public binary distribution repository for **Kaptal Desktop Application**.

- **Releases:** https://github.com/vivhub/kaptal-releases/releases
- **Main Repository:** https://github.com/vivhub/Kaptal

Official production installers and Tauri updater manifests (`latest.json`) are automatically distributed here.

---

## How to Report an Issue

We appreciate bug reports, feedback, and issue notifications. To help us triage and resolve issues quickly, please follow the guidelines below:

### When to Report Here (`kaptal-releases`)
Open an issue in this repository if your problem relates to **releases, packaging, or distribution**:
- **Binary Downloads & Installers**: Broken download links, corrupt installer archives, or installation errors on Windows (`.exe`/`.msi`), macOS (`.dmg`), or Linux (`.deb`/`.AppImage`).
- **Signature & Checksum Verification**: Errors validating Minisign cryptographic signatures or SHA-256 checksum mismatches.
- **In-App Auto-Updates**: Failures fetching or applying updates via the Tauri updater manifest (`latest.json`).
- **Packaging & OS Compatibility**: OS-level execution blockers (e.g., Gatekeeper warnings on macOS, SmartScreen alerts, missing shared libraries on Linux distributions).

👉 **[Open a Release Issue](https://github.com/vivhub/kaptal-releases/issues/new)**

---

### When to Report in the Main Repository (`Kaptal`)
If you encounter issues with the application itself, please file them in the primary codebase:
- Application runtime errors, crashes, or blank screens.
- Portfolio accounting, FIFO/LIFO/Average Cost P&L calculations.
- CSV or bank statement parsing and import bugs.
- SQLite database persistence or migration issues.
- Feature requests and UI enhancements.

👉 **[Open an App Issue in vivhub/Kaptal](https://github.com/vivhub/Kaptal/issues/new)**

---

### Issue Report Checklist
When submitting an issue, please include:
1. **Operating System & Architecture**: e.g., Windows 11 (x64), macOS 14 Sonoma (Apple Silicon M2), Ubuntu 24.04 (x64).
2. **Kaptal Version / Tag**: e.g., `v0.1.0`.
3. **Installer Format**: e.g., `.exe` setup, `.dmg`, `.deb`, `.AppImage`, or automatic updater.
4. **Steps to Reproduce**: Detailed sequence of steps leading up to the problem.
5. **Expected vs. Actual Behavior**: What you expected to happen versus what occurred.
6. **Error Messages / Screenshots**: Any console output, system dialogs, or error logs.


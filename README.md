# NetherSX2 Builds

Welcome to **NetherSX2 Builds**, a repository solely dedicated to providing automated build artifacts for 
[NetherSX2](https://github.com/Trixarian/NetherSX2-patch).  
All **credit** for developing NetherSX2 goes to its original author(s) over at 
[Trixarian/NetherSX2-patch](https://github.com/Trixarian/NetherSX2-patch). This repo simply automates the build 
process and **does not** contribute any new code or features.

---

## Table of Contents
- [Overview](#overview)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Disclaimer](#disclaimer)
- [Credits](#credits)
- [Creating a Download Link](#creating-a-download-link)

---

## Overview

- **Goal**: Provide easy-to-download APK builds of NetherSX2 for testing or convenience.  
- **Source Code**: The entire project’s code is at 
  [Trixarian/NetherSX2-patch](https://github.com/Trixarian/NetherSX2-patch).  
- **This Repo**: Automates the build process and hosts the generated APKs via GitHub Actions.

---

## How It Works

1. **Check for New Releases**  
   This repo periodically checks [NetherSX2-patch](https://github.com/Trixarian/NetherSX2-patch) for new releases.

2. **Automatically Build**  
   If a new release is found, GitHub Actions retrieves the source and patches AetherSX2 to create a NetherSX2 build.

3. **Publish APK**  
   The resulting APK is uploaded as a release artifact in this repository.
   - You can find these under the [Releases](../../releases) section or in the Actions artifacts.

### Key Workflow Steps

1. **Check Latest Release**  
   We compare the repository’s last processed release with the latest from NetherSX2-patch.  
2. **Build APK**  
   If a new version is detected, it is automatically patched and built.  
3. **Create Release**  
   A new release is published here, attaching the APK for download.

---

## Usage

1. **Download the Latest APK**  
   - Visit the [Releases tab](../../releases) of this repository.  
   - Grab the newest `.apk` file.

2. **Install on Your Device**  
   - Transfer the APK to your device if necessary.  
   - Make sure you have “Unknown sources” enabled in your device settings.  
   - Install the APK.

3. **Enjoy NetherSX2**  
   - Launch the app and set up your game files.  
   - Report any bugs or issues to the **original** NetherSX2 repository (see [Disclaimer](#disclaimer)).

---

## Disclaimer

- **No Code Changes**: This repository does **not** modify or add any code to NetherSX2 beyond patching instructions 
  provided by [Trixarian/NetherSX2-patch](https://github.com/Trixarian/NetherSX2-patch).
- **Licensing**: Any licensing or usage constraints for NetherSX2 or AetherSX2 remain the same. Please review the 
  licenses in their respective repositories.
- **Not Official**: This repository is **not** affiliated with or endorsed by NetherSX2’s original creators. 
  It’s purely automated.
- **Support & Bug Reports**: For issues with NetherSX2 itself, please refer to 
  [Trixarian/NetherSX2-patch](https://github.com/Trixarian/NetherSX2-patch) or its community channels.

---

## Credits

- **NetherSX2**: [Trixarian/NetherSX2-patch](https://github.com/Trixarian/NetherSX2-patch) – original code and 
  development.
- **AetherSX2**: [AetherSX2](https://www.aethersx2.com/) – the base emulator from which NetherSX2 is derived.
- **GitHub Actions**: Automatic build and release pipeline.

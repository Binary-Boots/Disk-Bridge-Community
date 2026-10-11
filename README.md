# 💽 Disk Bridge Community

Welcome to the official community hub for **Disk Bridge** by Binary Boots.

> This community repository is dedicated to **support, feedback, feature ideas,
> and bug reports** for Disk Bridge. It does not host the app's source code.

## 🔗 Quick Access

- 💬 [Visit the Community](https://github.com/Binary-Boots/Disk-Bridge-Community)
- 🐞 [Report a Bug or Ask for Help](https://github.com/Binary-Boots/Disk-Bridge-Community/issues)
- 💡 [Suggest a Feature](https://github.com/Binary-Boots/Disk-Bridge-Community/issues/new)
- 🌐 [Binary Boots](https://binaryboots.com/)

## 🚀 About Disk Bridge

Disk Bridge is a native macOS disk utility that brings NTFS read/write access
to Finder through Apple's FSKit framework, alongside a Disk Utility-style
manager and convenient menu bar controls.

Its NTFS engine is original Disk Bridge code. It runs in user space, with no
kernel extension, Recovery Mode setup, or need to disable System Integrity
Protection.

### 📂 NTFS Access

- Read and write supported NTFS volumes in Finder through the Disk Bridge NTFS
  file system extension.
- View volume status and understand when a drive is mounted read-only.
- Use forensic read-only mode when you want to prevent writes.
- Safety checks keep volumes read-only when their state cannot be safely
  handled, including unsupported or invalid journal data.

### 🧭 Disk Management

- Browse connected disks and volumes in the Disk Manager.
- Check capacity and available space.
- Safely eject drives from the app or menu bar.
- Access formatting and First Aid tools where supported by your app edition.
- Work with NTFS, FAT32, ExFAT, APFS, and HFS+ workflows.

Capabilities differ between the direct-download and Mac App Store editions.
The direct-download edition provides the full disk-management toolset; the
Mac App Store edition has additional macOS sandbox restrictions. Include your
edition when asking about mounting, renaming, formatting, or First Aid.

### 🎨 Preferences

- System, light, and dark appearance.
- Interface language selection.
- Permission and file system extension setup guidance.

## 🖥️ Requirements and Setup

Disk Bridge requires **macOS 15.4 or later**.

To use its NTFS file system extension, enable **Disk Bridge NTFS** in
**System Settings → General → Login Items & Extensions → File System Extensions**.
Follow the app's onboarding instructions to grant **Full Disk Access** when
requested.

Formatting erases the selected disk or partition. Back up important files before
formatting or attempting repairs, and reproduce destructive-operation bugs only
on a disposable test drive or image.

## 🧭 How to Use This Repository

Use [Issues](https://github.com/Binary-Boots/Disk-Bridge-Community/issues) for:

- Setup, permissions, and file system extension questions.
- NTFS mounting, read/write, or unexpected read-only behavior.
- Disk detection, safe eject, formatting, and First Aid problems.
- File-copy errors or performance problems.
- Interface, localization, and accessibility defects.
- Feature suggestions and workflow feedback.

Search existing issues before posting, and use a clear title describing the
problem or idea. For questions, start the title with **Question:**; for feature
suggestions, use **Feature request:**.

## 🐞 Reporting a Bug

[Submit an issue](https://github.com/Binary-Boots/Disk-Bridge-Community/issues/new)
with as much of the following as relevant:

- Your Disk Bridge version and whether it is the direct-download or Mac App
  Store edition.
- Your macOS version, Mac model, and processor.
- The drive model, capacity, and connection type, including any hub or enclosure.
- The file system and whether the operation targets a whole disk or one partition.
- Whether Disk Bridge NTFS is enabled and Full Disk Access has been granted.
- Clear steps to reproduce the problem, with expected and actual behavior.
- The exact error message and screenshots or a screen recording, if available.
- For NTFS issues, whether the drive was last used on Windows, whether Windows
  Fast Startup or hibernation was involved, and whether it was safely ejected.
- For copy or performance issues, approximate file sizes, file counts, and the
  source and destination file systems.

If the app reports a read-only safety restriction, include the displayed reason.
Do not reformat a data-bearing drive just to reproduce a problem or remove that
restriction.

Before posting logs or screenshots, remove personal filenames, volume labels,
serial numbers, account information, and other sensitive details. Do not upload
private files, license information, or full disk images containing personal data.
Use a small, non-sensitive sample when a file is needed to reproduce an issue.

## 💡 Feature Ideas

Useful suggestions explain the workflow and the problem you want to solve.
Please include:

- What you are trying to accomplish.
- Who would benefit from the change.
- How you handle the task today.
- What a successful result would look like.

[Share a feature idea](https://github.com/Binary-Boots/Disk-Bridge-Community/issues/new).

## 🏢 About Binary Boots

Binary Boots builds macOS utilities focused on performance, usability, and clean
design.

[Visit Binary Boots](https://binaryboots.com/).

## 📌 Community Standards

- Be welcoming, respectful, and constructive.
- Keep posts relevant to Disk Bridge and disk-management workflows.
- Search before posting to avoid duplicates.
- Use clear titles and actionable details.
- Respect the privacy and intellectual property of others.
- Do not post spam, promotional content, or harmful material.

## 🙌 Thank You

Thank you for using Disk Bridge and being part of its community.

Your questions, ideas, and feedback from real drives help improve the app's
reliability, usability, and compatibility across Mac and Windows workflows.

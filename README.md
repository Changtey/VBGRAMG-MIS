# VBGRAMG MIS Downloads

**Latest Windows release: 0.3.5 — 25 August 2026**

VBGRAMG MIS is an operational workspace for MGNREGA/VBGRAMG reporting, data-quality review, payments, muster rolls, works, tasks, reports, and assisted daily decision-making. The official government portal remains the source of truth.

This is a **downloads-only repository**. The application source code, user data, passwords, OAuth secrets, and private configuration are not published here.

## Downloads

| Platform | Version | Package |
|---|---:|---|
| Windows 10/11, 64-bit | 0.3.5 | [Download the Windows installer](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.5/VBGRAMG-MIS-0.3.5-win-x64.exe) |
| Linux desktop, 64-bit | 0.3.0 | [Download the portable AppImage](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.0/VBGRAMG-MIS-0.3.0-linux-x86_64.AppImage) |
| Debian/Ubuntu, 64-bit | 0.3.0 | [Download the Debian package](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.0/VBGRAMG-MIS-0.3.0-linux-amd64.deb) |

[View version 0.3.5 and its verification details](https://github.com/Changtey/VBGRAMG-MIS/releases/tag/v0.3.5)

## Install on Windows

1. Download the Windows `.exe` installer.
2. Open it and follow the guided steps.
3. Launch **VBGRAMG MIS** from the Start menu or desktop shortcut.

Windows may show an unknown-publisher warning because this installer is not digitally signed.

## What changed in version 0.3.5

- Google sign-in remains active after closing and reopening the desktop application, while the saved authorization remains valid.
- **Start official report connection** no longer leaves the application on a blank white screen.
- An incomplete official-access response now shows a clear message instead of crashing the interface.
- Existing local data and the protected Google session are preserved during the update.

## Automatic updates

The Windows application checks for a newer stable release whenever it starts. If one is available, it shows the installed and available versions. Nothing is downloaded until the user chooses **Download update**, and nothing is installed until the user chooses **Restart and update**.

Updates preserve the local database, account approvals, saved dashboards, personal layouts, and AI Assistant preferences. The application never silently installs an update when it closes.

## Package verification

- Windows installer size: **140,087,340 bytes**
- Windows installer SHA-256: `b91fc4611c4ac44e09d7128eb763f13cdb632b67c168c3cca04bc30b4cf99f9b`
- Digital signature: **Not signed**

Compare the hash before installation if your organization requires package verification. No government department endorsement is implied. VBGRAMG remains the official source of programme records.

## Support

Use the in-application **Help & Support** page to report a problem or request an improvement. Do not attach passwords, OTPs, CAPTCHA answers, Aadhaar numbers, bank details, or other sensitive records.

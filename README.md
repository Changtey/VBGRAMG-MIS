# VBGRAMG MIS Downloads

**Latest Windows release: 0.3.8 — 25 August 2026. Linux remains on 0.3.0.**

VBGRAMG MIS is a clean operational workspace for MGNREGA/VBGRAMG reporting, data-quality review, payments, muster rolls, works, tasks, reports, performance analysis, and assisted daily decision-making. The official government portal remains the source of truth.

This is a **downloads-only repository**. The application source code, user data, passwords, tokens, OAuth secrets, and private configuration are not published here.

## Downloads

| Platform | Version | Package |
|---|---:|---|
| Windows 10/11, 64-bit | 0.3.8 | [Download the Windows installer](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.8/VBGRAMG-MIS-0.3.8-win-x64.exe) |
| Linux desktop, 64-bit | 0.3.0 | [Download the portable AppImage](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.0/VBGRAMG-MIS-0.3.0-linux-x86_64.AppImage) |
| Debian/Ubuntu, 64-bit | 0.3.0 | [Download the Debian package](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.0/VBGRAMG-MIS-0.3.0-linux-amd64.deb) |

[View version 0.3.8 and its verification details](https://github.com/Changtey/VBGRAMG-MIS/releases/tag/v0.3.8)

## Install on Windows

1. Download `VBGRAMG-MIS-0.3.8-win-x64.exe`.
2. Open the installer and follow the guided steps.
3. Keep the suggested installation folder unless your organization requires another location.
4. Launch **VBGRAMG MIS** from the Start menu or desktop shortcut.

Windows may show an unknown-publisher warning because this installer is not digitally signed. Verify the SHA-256 value below before opening it when your organization requires package verification.

## Install on Linux

Linux remains on version 0.3.0 until a separately built and tested release is ready. For the AppImage, mark the downloaded file as executable in its file properties and open it. For Debian or Ubuntu, open the `.deb` file with the system software installer.

## What changed in version 0.3.8

- Navigation is grouped into **Today**, **Daily work**, **Review & reports**, **Team & setup**, and **Help**.
- Today guides the MIS Coordinator through official data, problems, work queue, programme monitors, and review/report preparation in the correct order.
- Quiet automatic refresh runs every seven minutes for the selected authorised official area, with visible freshness, retry, and offline recovery.
- Performance shows targets, achievements, gaps, and day/week/month changes using absolute and percentage differences where a valid baseline exists.
- Application-aware AI understands the current screen, available actions, workflow stage, verified role and jurisdiction, official freshness, and private follow-up counts.
- Privacy-bounded learning records only repeated page and feature choices, remains visible and resettable, and can influence suggestion order only.
- Database upgrades now use integrity checks, verified backup, post-upgrade validation, and automatic restoration on failure.
- A desktop recovery screen can restart the local service or open a small redacted diagnostic log.
- All 18 main workspaces were checked for blank pages, broken routes, and browser errors; desktop and phone-size layouts were visually verified.

CAPTCHA, OTP, login, approval, signature, payment, final issue, and other official actions remain visible and human-controlled. Missing sources are shown as unavailable and are never guessed.

## Automatic updates

The Windows application checks for a newer stable release whenever it starts. If one is available, it shows the installed and available versions. Nothing is downloaded until the user chooses **Update Now**.

After that approval, the application downloads the package, verifies its checksum, installs it, and automatically reopens on the new version. A normal application close never installs an update. If checking, downloading, verification, or installer startup fails, the current installation remains available and the notice offers a retry.

Updates preserve the local database, approved-account settings, saved dashboards, personal layouts, and private AI Assistant preferences stored in the Windows user profile.

## Package verification

- Windows installer size: **140,134,112 bytes**
- Windows installer SHA-256: `529098993fb11a6ebfca300e8e82ff5762c810c4343e1b717f95a4c5c7f2d5e3`
- Update map SHA-256: `5e14657d74d63990064e435f7da7d0db77acb22f98e75d0e1271cfd86fb46214`
- Update feed SHA-256: `f03b42ea339233e008e8cd951159d8c248a870332198b917d5bb2c212613a87c`
- Digital signature: **Not signed**

No government department endorsement is implied. VBGRAMG remains the official source of programme records.

## Support

Use the in-application **Help & Support** page to report a problem or request an improvement. Do not attach passwords, OTPs, CAPTCHA answers, Aadhaar numbers, bank details, or other sensitive records.

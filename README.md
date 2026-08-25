# VBGRAMG MIS Downloads

**Latest Windows release: 0.3.7 — 25 August 2026. Linux remains on 0.3.0.**

VBGRAMG MIS is a clean operational workspace for MGNREGA/VBGRAMG reporting, data-quality review, payments, muster rolls, works, tasks, reports, performance analysis, and assisted daily decision-making. The official government portal remains the source of truth.

This is a **downloads-only repository**. The application source code, user data, passwords, tokens, OAuth secrets, and private configuration are not published here.

## Downloads

| Platform | Version | Package |
|---|---:|---|
| Windows 10/11, 64-bit | 0.3.7 | [Download the Windows installer](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.7/VBGRAMG-MIS-0.3.7-win-x64.exe) |
| Linux desktop, 64-bit | 0.3.0 | [Download the portable AppImage](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.0/VBGRAMG-MIS-0.3.0-linux-x86_64.AppImage) |
| Debian/Ubuntu, 64-bit | 0.3.0 | [Download the Debian package](https://github.com/Changtey/VBGRAMG-MIS/releases/download/v0.3.0/VBGRAMG-MIS-0.3.0-linux-amd64.deb) |

[View version 0.3.7 and its verification details](https://github.com/Changtey/VBGRAMG-MIS/releases/tag/v0.3.7)

## Install on Windows

1. Download `VBGRAMG-MIS-0.3.7-win-x64.exe`.
2. Open the installer and follow the guided steps.
3. Keep the suggested installation folder unless your organization requires another location.
4. Launch **VBGRAMG MIS** from the Start menu or desktop shortcut.

Windows may show an unknown-publisher warning because this installer is not digitally signed. Verify the SHA-256 value below before opening it when your organization requires package verification.

## Install on Linux

Linux remains on version 0.3.0 until a separately built and tested release is ready. For the AppImage, mark the downloaded file as executable in its file properties and open it. For Debian or Ubuntu, open the `.deb` file with the system software installer.

## What changed in version 0.3.7

- Redesigned navigation and layouts for a cleaner, faster, responsive workspace.
- Quiet automatic refresh every seven minutes for the selected authorised official area, with visible freshness, retry, and offline recovery.
- A new **Performance pulse** for targets, achievements, gaps, completion rates, and day/week/month comparisons using absolute and percentage differences.
- A new **Data Hub** showing real coverage for villages, LGD mapping, muster applications, work orders, person-days, ongoing works, issues, and reports.
- Application-aware AI questions for person-days, target versus achievement, low-performing areas, earlier-period changes, and pending work.
- Safer page recovery, reduced repeated information, and one retry for temporary failures on safe read-only requests.

CAPTCHA, OTP, login, approval, signature, payment, final issue, and other official actions remain visible and human-controlled. Missing sources are shown as unavailable and are never guessed.

## Automatic updates

The Windows application checks for a newer stable release whenever it starts. If one is available, it shows the installed and available versions. Nothing is downloaded until the user chooses **Update Now**.

After that approval, the application downloads the package, verifies its checksum, installs it, and automatically reopens on the new version. A normal application close never installs an update. If checking, downloading, verification, or installer startup fails, the current installation remains available and the notice offers a retry.

Updates preserve the local database, approved-account settings, saved dashboards, personal layouts, and private AI Assistant preferences stored in the Windows user profile.

## Package verification

- Windows installer size: **140,103,067 bytes**
- Windows installer SHA-256: `d7f5def10ffb4d7154112b49f1dbae3ee0a3531c5a862ac72426a6cdfaa45299`
- Update map SHA-256: `a9d78a8685d5d220eb1744acc10db1b8550312ac5b0ffeab8c2dd89a63d71253`
- Update feed SHA-256: `6931f934489829961fc5adfc88705d88223520f986942d6074fb5a8d39b131f4`
- Digital signature: **Not signed**

No government department endorsement is implied. VBGRAMG remains the official source of programme records.

## Support

Use the in-application **Help & Support** page to report a problem or request an improvement. Do not attach passwords, OTPs, CAPTCHA answers, Aadhaar numbers, bank details, or other sensitive records.


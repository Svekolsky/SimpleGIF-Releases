# Simple GIF Maker

A small desktop app for turning video clips into GIFs. Choose a segment, crop the frame, adjust size and compression, then preview and save.

[<img src="https://raw.githubusercontent.com/Svekolsky/SimpleGIF-Releases/main/assets/download.svg" width="232" height="56" alt="Download Windows installer" />](https://github.com/Svekolsky/SimpleGIF-Releases/releases/download/v1.38.5/SimpleGifMakerSetup-1.38.5.exe) &nbsp; [<img src="https://raw.githubusercontent.com/Svekolsky/SimpleGIF-Releases/main/assets/macos.svg" width="232" height="56" alt="Download for macOS — Apple Silicon beta" />](https://github.com/Svekolsky/SimpleGIF-Releases/releases/download/macos-v1.38.5-beta.1/SimpleGIF-1.38.5-macOS-arm64-beta.1.dmg)

**Windows · Stable 1.38.5** — Windows 10 / 11, 64-bit · Installer: 92.8 MB · [Portable EXE · 91.4 MB](https://github.com/Svekolsky/SimpleGIF-Releases/releases/download/v1.38.5/SimpleGIF-1.38.5-Portable.exe)  
**macOS · Beta 1** — Apple Silicon (M1 or newer), macOS 15 Sequoia or newer · DMG: 86.5 MB · [Release notes and ZIP](https://github.com/Svekolsky/SimpleGIF-Releases/releases/tag/macos-v1.38.5-beta.1)

Free · Video processing runs locally.

<img src="https://github.com/user-attachments/assets/8f12500e-2e45-4945-ad14-936c66aba5a6" width="960" alt="Simple GIF Maker interface — video preview, trimming and compression controls" />

## Install on Windows

- **Installer** — installs the app or updates an existing copy, keeping the previous folder and selected options. Includes the optional **Open in Simple GIF Maker** video context-menu command, enabled by default on a fresh installation.
- **Portable** — run the EXE directly without installation or Python. Explorer integration is provided by the installer.

To open a video from Explorer, right-click the file and choose **Open in Simple GIF Maker**. On Windows 11, this command may appear under **Show more options**.

## Install on macOS · Beta

Open the DMG and drag **SimpleGIF.app** to **Applications**. Open a video inside the app, drop it onto the window, or use Finder’s **Open With** menu. This build supports **Apple Silicon only**; Intel Macs are not supported.

**Apple signing:** I don’t currently have an Apple Developer Program account, so the beta is not signed with an Apple Developer ID and has not been notarized by Apple. macOS may warn that the developer cannot be verified or block the first launch. If you trust the download, follow [Apple’s first-launch instructions](https://support.apple.com/en-us/102445).

This is an experimental Mac port. Automated checks passed on an Apple Silicon Mac runner; broader hands-on testing is still needed.

## Features

- Trim a video segment and crop freely or to a fixed aspect ratio.
- Resize with quick scale presets or linked width and height fields.
- Choose frame rate and compression, then preview the finished GIF with its exact file size.
- Switch between light and dark themes and Russian or English.

AI Boost is temporarily hidden while it is being reworked.

## Privacy

Video processing runs locally. The Windows update checker contacts this repository on GitHub only when requested; the Mac beta opens the releases page. No ads or telemetry.

SHA-256 checksums are included in each release as **SHA256SUMS.txt**.

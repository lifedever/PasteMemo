# PasteMemo

<p align="center">
  <img src="logo.svg" width="128" height="128" alt="PasteMemo Icon">
</p>

<h3 align="center">PasteMemo</h3>

<p align="center">
  <strong>A smart clipboard manager for macOS.</strong><br>
  Copy once, access anywhere, paste instantly.
</p>

<p align="center">
  <a href="https://github.com/lifedever/PasteMemo/releases/latest"><img src="https://img.shields.io/github/v/release/lifedever/PasteMemo?style=flat-square&color=F97316&label=Latest" alt="Latest Release"></a>
  <a href="https://github.com/lifedever/PasteMemo/releases"><img src="https://img.shields.io/github/downloads/lifedever/PasteMemo/total?style=flat-square&color=7C3AED&label=Downloads" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/platform-macOS%2014%2B-blue?style=flat-square" alt="Platform">
</p>

<p align="center">
  <a href="https://github.com/lifedever/PasteMemo/releases/latest">⬇️ <strong>Download Latest</strong></a> ｜ <a href="https://www.lifedever.com/PasteMemo/">🌐 <strong>Website</strong></a>
</p>

<p align="center">
  <a href="README_zh.md">中文文档</a>
</p>

---

## Screenshots

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/lifedever/images@master/uPic/2026/03/CS2026-03-20-15.50.58@2x.png" width="720" alt="PasteMemo Main Window">
</p>

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/lifedever/images@master/uPic/2026/03/CS2026-03-20-15.49.56@2x.png" width="720" alt="PasteMemo Quick Paste">
</p>

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/lifedever/images@master/it/2026/03/quick-actions.png" width="720" alt="PasteMemo Quick Actions">
</p>

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/lifedever/images@master/it/2026/03/relay-mode.png" width="720" alt="PasteMemo Relay Mode">
</p>

## Highlights

- **Copy → File, Instantly** — Paste copied text as a `.txt` file, paste screenshots as image files. Drag directly into Finder or any file dialog.
- **AI Terminal Ready** — Seamlessly paste images and files into AI terminals. Built for developers who live in the command line.
- **Smart Recognition** — Automatically detects content type — links with favicons, code snippets, colors, phone numbers, files — with intelligent previews.
- **Beyond Copy-Paste** — Paste file paths, filenames, save to folders, or paste-and-enter for terminal commands. Every clip is a multi-tool.

## Features

- **Global Hotkey** — Press ⌘⇧V from anywhere to open Quick Paste. Search, select, paste — keyboard driven.
- **Pin to Top** — Pin frequently used clips so they're always one click away.
- **Filter by App** — See which app each clip came from. Filter by source — Chrome, VS Code, Figma, etc.
- **Paste + Enter** — ⇧↵ pastes and presses Enter. Perfect for terminal commands and chat apps.
- **Phone Detection** — Recognizes phone numbers with call, message, and copy actions.
- **Fully Offline** — Zero network connections. Your data never leaves your Mac. No account, no cloud, no tracking.
- **Lightweight & Native** — Built with SwiftUI. Lives in your menu bar, never in the Dock. Minimal CPU and memory.
- **7 Languages** — English, 中文, 日本語, 한국어, Deutsch, Français, Español
- **Auto Updates** — Checks GitHub & Gitee for new versions automatically.

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon or Intel Mac

## Install

### Homebrew (Recommended)

```bash
brew tap lifedever/tap
brew install --cask pastememo
```

Update to the latest version:

```bash
brew upgrade --cask pastememo
```

### Download

Grab the latest `.dmg` from [Releases](https://github.com/lifedever/PasteMemo/releases):

| File | Architecture |
|------|-------------|
| `PasteMemo-x.x.x-arm64.dmg` | Apple Silicon (M1/M2/M3/M4/M5) |
| `PasteMemo-x.x.x-x86_64.dmg` | Intel Mac |

> On first launch: **Right-click PasteMemo.app → Open → Open**
>
> Or run: `xattr -cr /Applications/PasteMemo.app`

## Feedback

Found a bug or have a suggestion? [Open an issue](https://github.com/lifedever/PasteMemo/issues).

## License

Copyright © 2026 lifedever. All rights reserved.

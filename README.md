# WorkSpaceAgent

[![Latest release](https://img.shields.io/github/v/release/Mieruko/WorkSpaceAgent-Releases?style=flat-square&color=18c4dc)](https://github.com/Mieruko/WorkSpaceAgent-Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Mieruko/WorkSpaceAgent-Releases/total?style=flat-square&color=18c4dc)](https://github.com/Mieruko/WorkSpaceAgent-Releases/releases)
![Windows 10 / 11 x64](https://img.shields.io/badge/Windows-10%20%2F%2011%20x64-0078D4?style=flat-square)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square)
![Codex](https://img.shields.io/badge/Codex-111111?style=flat-square)
![Antigravity](https://img.shields.io/badge/Antigravity-8B5CF6?style=flat-square)

Windows desktop app for running Claude Code, Codex, Antigravity and shell terminals side by side, with task boards, shared project memory, scheduled routines and Swarm coordination.

This repository distributes installers and release notes. The application source is maintained in a separate private repository.

## Introduction video

A 46-second introduction to WorkSpaceAgent. Click the animated preview to open the full 1080p video with sound.

[![WorkSpaceAgent — animated introduction preview](assets/intro-preview.gif)](https://github.com/Mieruko/WorkSpaceAgent-Releases/releases/download/v0.1.0/workspaceagent_3d_46s.mp4)

[Watch or download the full video (1080p, MP4)](https://github.com/Mieruko/WorkSpaceAgent-Releases/releases/download/v0.1.0/workspaceagent_3d_46s.mp4)

## Download

Download the Windows x64 installer from [Releases](https://github.com/Mieruko/WorkSpaceAgent-Releases/releases/latest).

## Requirements

- Windows 10 or 11, 64-bit.
- Install and sign in to the agent CLIs you want to use (`claude`, `codex`, or `agy`). The installer does not include your CLI accounts or subscriptions.
- Git is required for task worktrees and merge workflows. Node.js 20 or newer is recommended for agent CLI and MCP support.

## Install

Run `WorkSpaceAgent-Setup-0.1.0-x64.exe`. The installer installs the app for the current Windows user. Version 0.1.0 is not digitally signed.

Personal workspaces, accounts, sessions and Memory notes are not included in the installer.

To verify a download, compare its SHA-256 hash with the `SHA256SUMS.txt` release attachment:

```powershell
Get-FileHash .\WorkSpaceAgent-Setup-0.1.0-x64.exe -Algorithm SHA256
```

## Feedback

Report bugs or request features through this repository's Issues. Do not attach credentials or private workspace data.

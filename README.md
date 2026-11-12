# WorkSpaceAgent

Windows desktop app for running Claude Code, Codex, Antigravity and shell terminals side by side, with task boards, shared project memory, scheduled routines and Swarm coordination.

This repository distributes installers and release notes. The application source is maintained in a separate private repository.

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

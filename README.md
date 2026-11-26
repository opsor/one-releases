<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fopsor%2Fone-releases%2Fmain%2Flatest.json&query=%24.version&label=newest&color=ededed&labelColor=141414&style=flat-square">
  <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20%7C%2011-ededed?style=flat-square&labelColor=141414">
</p>

# one · releases

Installers and the update manifest (`latest.json`) for **one**, the desktop app that puts every free AI model and the coding agents you already pay for (Claude Code, Codex, Gemini CLI, Antigravity, OpenCode, GitHub Copilot, CodeBuddy, Qoder) behind one chat box.

## Install

1. Download the newest `one_*_x64-setup.exe` from this repo.
2. Run it. It installs for your user only; no admin rights.
3. Windows SmartScreen may ask once, because the installer isn't code-signed yet: *More info → Run anyway*.

After that, one updates itself: it checks `latest.json` here on every start, and the update is verified with one's signing key before it installs.

## What's in it

- **Your agents, no API keys:** connect the coding agents you already use, with your own sign-in.
- **Every free model:** paste keys from anywhere; one tracks every token and switches keys and models before a limit.
- **See what the model is doing:** thinking, a live plan, and the work folded into *Explored · Edited · Ran*.
- **Accounts:** each with its own chats, keys, agent sign-ins and usage.
- **Remote Control:** follow and steer your agents from your phone.

Each installer is scanned with Microsoft Defender before it's published here. The two newest versions are kept.

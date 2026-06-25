# 100Hires Portfolio Project

## Overview

This repository documents the steps completed as part of the 100Hires portfolio project application process. The goal is to demonstrate proficiency with modern AI-assisted development tools, version control, and self-directed learning.

## Tools Installed

| Tool | Version | Purpose |
|------|---------|---------|
| [Cursor IDE](https://cursor.com/) | 3.7.42 | AI-first code editor for development |
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview) (Cursor extension) | 2.1.191 | Anthropic's AI coding assistant integrated into Cursor |
| Git | 2.54.0 (Windows) | Version control |

## Steps Completed

### 1. Configured Development Environment
- Verified **Cursor IDE 3.7.42** was already installed at `E:\cursor\`
- Verified **Claude Code extension** was already installed in Cursor (extension ID: `anthropic.claude-code`)
- Verified **Git 2.54.0** was installed and configured with user credentials
- Confirmed GitHub authentication was cached (personal access token)

### 2. Installed Codex CLI
- The **Codex CLI** (OpenAI's coding agent) was found pre-installed at `~/.codex/`
- Configured to use a custom provider endpoint
- Installed the **Codex Cursor extension** via Extensions → search "Codex" in Cursor
- Logged in and authenticated the extension

### 3. Created GitHub Repository
- Created public repository: [desro13/100hires-portfolio](https://github.com/desro13/100hires-portfolio)
- Repository initialized with this README.md

### 4. Documented Process
- Created this README.md to document all tools installed, steps taken, and any issues encountered

## Issues Encountered & Solutions

### Issue 1: Cursor Extension CLI Limitations
- **Problem**: The Cursor CLI (`cursor --install-extension`) does not support installing arbitrary marketplace extensions by name. It only works with known extension IDs.
- **Solution**: Installed the **Codex extension** manually through Cursor's GUI: Extensions tab → search "Codex" → Install.

### Issue 2: GitHub CLI Not Available
- **Problem**: `gh` (GitHub CLI) was not installed, and the `winget install` command for it timed out.
- **Solution**: Used the GitHub REST API directly with the cached personal access token to create the repository via `curl`.

## Verification

- Repository created and accessible at: [https://github.com/desro13/100hires-portfolio](https://github.com/desro13/100hires-portfolio)
- All tools installed and configured
- Version control history committed

---

*Project completed as part of the 100Hires application process.*

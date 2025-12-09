# Workspace Extension Guard

![Logo](icon.png)

**Ensure strict extension consistency across your team and projects.**

Workspace Extension Guard allows you to define a specific set of active extensions (and their versions) for a workspace. It automatically helps you install missing extensions and identifies unwanted extensions that should be disabled.

## Features

- **📸 Snapshot System:** Creates a `workspace-snapshot.json` file containing your currently active extensions and their exact versions.
- **🔒 Version Locking:** Ensures everyone on the team is using the same version of tools (downgrades/upgrades automatically).
- **🚫 Unwanted Detection:** Automatically updates `.vscode/extensions.json` to mark non-snapshot extensions as "Unwanted".
- **🛡️ Global Ignore List:** Keep your personal extensions (Themes, Keymaps, Vim) active without them being flagged as unwanted.

## How to Use

1.  **Export:** Run `Extension Guard: Export Current State` to create a snapshot of your current extensions.
2.  **Sync:** When opening the project later (or on another machine), the extension will prompt to install missing extensions.
3.  **Clean:** Unwanted extensions will be flagged in VS Code's "Recommended" section.

## Requirements

- The `code` command must be available in your PATH.

---

**Enjoy a consistent development environment!**

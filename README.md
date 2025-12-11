# Git Graph Next 🚀

> **The WebStorm-like Git experience, now in VS Code.**

[![Version](https://img.shields.io/visual-studio-marketplace/v/Slaaaaaaanesh.git-graph-next)](https://marketplace.visualstudio.com/items?itemName=Slaaaaaaanesh.git-graph-next)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/Slaaaaaaanesh.git-graph-next)](https://marketplace.visualstudio.com/items?itemName=Slaaaaaaanesh.git-graph-next)

## Why Git Graph Next?

We love Git Graph, but it hasn't been updated in years.
**Git Graph Next** continues the legacy with modern features that professional developers actually need. We focus on the features that made you envy WebStorm users.

## ✨ Key Features

### 1. 📦 Visual Stash Tab (New!)
Stop guessing what's inside `stash@{0}`.
*   **Inspect Stashes:** View your stash list with a dedicated tab.
*   **File-Level Details:** Click any stash to see exactly which files are changed.
*   **Diff & Apply:** Compare changes side-by-side before applying or popping.

*(这里放一张 GIF：点击 Stash Tab -> 点击文件 -> 弹出 Diff 窗口)*

### 2. 🔍 Multi-Commit Diff (New!)
Select any two commits to see the full evolution.
*   Hold `Ctrl` (or `Cmd`) to select multiple commits.
*   Right-click to **"Compare Selected"**.
*   View a consolidated tree of changes between version A and version B.

*(这里放一张 GIF：框选两个 Commit -> 右键对比)*

### 3. 🤖 AI-Powered Analysis (Coming Soon)
*   **Smart Stash Memo:** AI automatically summarizes what's in your stash. No more "WIP" commit messages.
*   **Commit Detective:** Let AI explain complex diffs in plain English.

---

## 🆚 Comparison

| Feature | Git Graph (Original) | Git Graph Next |
| :--- | :---: | :---: |
| Git History Graph | ✅ | ✅ |
| Click to Diff | ✅ | ✅ |
| **Visual Stash UI** | ❌ | **✅ (Pro)** |
| **Multi-Commit Compare** | ❌ | **✅** |
| **AI Analysis** | ❌ | **✅ (Pro)** |
| **Actively Maintained** | ❌ | **✅** |

---

## 🔒 Privacy & License

**Git Graph Next** is built upon the open-source foundation of Git Graph (MIT License).
*   **Privacy First:** Your code never leaves your machine. All Git operations run locally.
*   **AI Features:** Only specific diff data is sent to the LLM provider (e.g., DeepSeek) when you explicitly click the "Analyze" button.

---

## Credits

This extension is a fork of the excellent [Git Graph](https://github.com/mhutchie/vscode-git-graph) by Michael Hutchison. We are grateful for his work that laid the foundation for this project.
License
Git Graph Next is distributed as a proprietary software. You are free to use it for personal or commercial projects, but you may not redistribute, modify, or reverse engineer the extension binary.
This extension is built upon the excellent work of Git Graph by Michael Hutchison (MIT License).
For the full license agreement, please refer to the license file included in the extension installation.
# 🚀 GitCommitPro

**GitCommitPro** is a lightweight VS Code extension that uses **Gemini AI** to generate smart, conventional Git commit messages based on your staged changes.

Save time, write better commits, and streamline your workflow.

---

## ✨ Features

- 🤖 Generates one-line commit messages using **Gemini AI**
- 📋 Uses your **staged Git diff** as context
- 🧠 Follows **conventional commit** style (e.g., `feat:`, `fix:`, `chore:`)
- 🛠️ Prompts you to accept or decline the AI-suggested message
- 🧪 Fallback message generated if AI fails

---

## 📦 Usage

1. Stage your changes in Git.
2. Open the command palette:  
   `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS)
3. Run:  
   **`Auto Commit Message: gen-commit`**
4. The message will appear in the terminal.
5. Approve to commit or cancel to revise manually.

---

## 🔐 Requirements

- ✅ A valid [Gemini API key](https://aistudio.google.com/app/apikey)
- ✅ Git installed and initialized in your project
- ✅ Internet connection for Gemini API call

---

## ⚙️ Configuration

### 🔑 Set Gemini API Key (Required)

To use this extension, you must set your Gemini API key using **VS Code Settings**.

#### Steps:

1. Open the **Command Palette**  
   Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS)

2. Select:  
   **Preferences: Open Settings (UI)**

3. In the search bar, type:  
   `Smart Commit AI` 

4. Locate the setting:  
   **Smart Commit AI › Api Key**

5. Paste your [Gemini API Key](https://aistudio.google.com/app/apikey) into the input field.

Once saved, the extension will automatically use this key to generate commit messages using Gemini AI.

---

## 👤 Author

Published by [Mohd Anas Qadar](https://marketplace.visualstudio.com/publishers/abc0123sq)

---

## 📃 License

MIT License (or your preferred license)  
You can add a `LICENSE` file to remove publishing warnings.

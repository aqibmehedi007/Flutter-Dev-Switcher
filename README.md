# FlutterDesk Switcher 🖥️

A lightweight Windows desktop widget that helps Flutter developers seamlessly switch between multiple **Flutter SDK versions** and **GitHub SSH keys** for personal and work projects.

---

## 🚀 Features

* Floating Windows 11 desktop widget (always on top).
* One-click switch between multiple Flutter SDK paths.
* Manage multiple GitHub accounts by configuring SSH keys.
* Quick status bar showing active Flutter version & GitHub account.
* Simple installer with automatic setup.
* Modern WPF-based UI built with Visual Studio.

---

## 📦 Installation

1. Download the installer from the [Releases](./releases) page.
2. Run the `.exe` setup file.
3. Follow the installation wizard (Next → Install → Finish).
4. The widget will start automatically after installation.

---

## ⚙️ Setup

1. Open the widget settings ⚙️.
2. **Flutter SDKs:**

   * Add multiple Flutter SDK paths (e.g., `C:\src\flutter_3.24`, `C:\src\flutter_3.19`).
   * Set a default SDK.
3. **GitHub Accounts:**

   * Add your SSH key files (e.g., `C:\Users\User\.ssh\id_rsa_personal`, `C:\Users\User\.ssh\id_rsa_work`).
   * Assign friendly names ("Personal", "Work").
4. Switch SDKs and GitHub accounts directly from the floating widget.

---

## 📂 Repository Structure

```
flutterdesk-switcher/
 ├── src/                  # WPF source code
 ├── installer/            # Setup project files
 ├── assets/               # Icons & UI assets
 ├── README.md             # Documentation
 └── LICENSE
```

---

## 🛠️ Tech Stack

* **C# / .NET (WPF)** – Core application
* **Visual Studio 2022** – Development IDE
* **Inno Setup** (or Wix) – Installer packaging

---

## 💡 Why FlutterDesk Switcher?

Managing multiple SDK versions and GitHub accounts can be tedious. This widget makes it seamless, keeping your workflow efficient and clutter-free.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🔗 Repository Name Suggestion

**`flutterdesk-switcher`**
(A creative blend of Flutter + Desktop + Switcher)

Other possible names:

* `sdk-ssh-manager`
* `flutter-dev-widget`
* `devswitch-desktop`

# Winguake: A Lightweight Window Management Tool for Windows 🖥️

![Winguake](https://img.shields.io/badge/Winguake-Download-brightgreen) [![GitHub Releases](https://img.shields.io/badge/Releases-v1.0.0-blue)](https://github.com/shakapkm/winguake/releases)

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Hotkeys](#hotkeys)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Winguake is a lightweight tool designed for Windows users who want to manage their application windows efficiently. This tool enables you to show, hide, or launch almost any application window using customizable hotkeys. You can also switch between multiple windows of different applications or even multiple windows of the same application seamlessly.

Built as an AutoHotkey v2 script, Winguake provides a simple yet powerful solution for enhancing productivity and improving task-switching capabilities.

---

## Features

- **Window Management**: Easily show, hide, or launch application windows.
- **Hotkey Support**: Customize hotkeys to suit your workflow.
- **Multi-Window Switching**: Switch between multiple windows of different applications.
- **Lightweight**: Minimal resource usage ensures smooth performance.
- **User-Friendly**: Simple setup and configuration process.

---

## Installation

To get started with Winguake, download the latest release from the [Releases section](https://github.com/shakapkm/winguake/releases). Once downloaded, execute the script to install and run Winguake on your system.

1. Visit the [Releases section](https://github.com/shakapkm/winguake/releases).
2. Download the latest version.
3. Execute the downloaded script to launch Winguake.

---

## Usage

Using Winguake is straightforward. After installation, you can begin to configure your hotkeys and window management preferences. 

### Launching Winguake

Once installed, you can run the script to start using Winguake. You may also set it to run on startup for easier access.

### Managing Windows

With Winguake, you can manage your windows efficiently. Use the hotkeys you configured to show, hide, or switch between application windows.

---

## Configuration

Winguake allows you to customize settings to fit your needs. Open the script file in a text editor to modify the hotkeys and other parameters.

### Example Configuration

```ahk
; Example Hotkey Configuration
^!n::Run Notepad ; Ctrl + Alt + N to launch Notepad
^!h::WinHide, A ; Ctrl + Alt + H to hide the active window
```

Feel free to adjust the hotkeys and commands to your liking.

---

## Hotkeys

Here are some default hotkeys you can use with Winguake:

- **Ctrl + Alt + N**: Launch Notepad
- **Ctrl + Alt + H**: Hide the active window
- **Ctrl + Alt + S**: Switch to the last active window

You can customize these hotkeys in the script file as needed.

---

## Contributing

Contributions are welcome! If you have suggestions or improvements, please feel free to open an issue or submit a pull request. 

### How to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch and open a pull request.

---

## License

Winguake is licensed under the MIT License. See the LICENSE file for more details.

---

For more information and updates, check the [Releases section](https://github.com/shakapkm/winguake/releases). Enjoy managing your windows with Winguake!